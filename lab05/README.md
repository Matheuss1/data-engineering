# Aluno

- RA: 241882

## Tarefa de Cypher sobre Marcadores e Taxonomia

## Tarefa 1

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, sem considerar as categorias subordinadas.

### Resolução

```cypher
MATCH (m:Marcador)-[r:Pertence]->(:Categoria {id: 'Serviços'}) RETURN m
```

## Tarefa 2

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, considerando as categorias subordinadas.

### Resolução

```cypher
MATCH (marker1:Marcador)-[:Pertence]->(:Categoria)-[:Superior *1..]->(:Categoria {id: 'Serviços'})
RETURN marker1 AS marker
UNION ALL
MATCH (marker2:Marcador)-[:Pertence]->(:Categoria {id: 'Serviços'}) RETURN marker2 AS marker
```
