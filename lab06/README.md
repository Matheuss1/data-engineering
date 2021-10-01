# Aluno

- 241882: Matheus Silva de Deus

# Análise do Artigo `BovDB: A data set of stock quotes for Machine Learning on all companies from B3 between 1995 and 2020`

| campo      | valor                                                                                                                  |
| ---------- | ---------------------------------------------------------------------------------------------------------------------- |
| referência | Fabian Corrêa Cardoso, Juan Malska, Paulo Ramiro, Giancarlo Lucca, Eduardo N. Borges, Viviane de Mattos, Rafael Berri: |
| link       | https://drive.google.com/file/d/1-x_TZMxAeGzfHS7Oq-h5cc1uj1zkWdHy/view                                                 |
| dataset    | https://github.com/Ginfofinance/BovDBrepository                                                                        |
| formato    | Banco de dados SQL                                                                                                     |

## Resumo

O artigo se refere à construção de um banco de dados referentes aos dados diários de ativos da bolsa de valores do Brasil, a B3 (Brasil, Bolsa, Balcão), do ano 1995 ao ano de 2020.

A motivação da coleta destes dados se dá pelo fato de que, embora existam centenas de datasets com as mais variadas informações sobre o mercado financeiro, até a publicação do artigo, não era conhecida a existencia de datasets públicos e gratuitos de dados pré-processados sobre ativos da bolsa brasileira.

Os dados podem ser encontrados de forma bruta no site da própria B3, em formato TXT. Contudo, isso torna difícil a análise destes, e, portanto, tê-los de maneira mais acessível e com um banco de dados já montado, é um grande avanço.

Desta forma, tal banco de dados pode ser utilizado para as mais variadas aplicações, como, por exemplo, com técnicas de <em>Machine Learning</em>, para prever um possível preço futuro para determinada ação. Ou ainda, executar análises estatísticas que possam dar apoio aos investidores que trabalham com análise técnica, oferecendo suporte para suas operações de <em>Day trade</em> e/ou <em>Swing Trade</em>.



## Perguntas de pesquisa/análises

Os dados de ações podem ser utilizados para análises, em pesquisas acadêmicas, comparações, previsões de preços, dentre outras aplicações.

Por exemplo, os dados podem ser utilizados por uma rede neural para a classificação de uma série temporal, determinando ser deve ser efetuada a compra ou venda de um ativo. 
Além disso, podem ser feitas análises estatísticas que determinem periodicidades no comportamento das séries temporais.

## Trabalhos relacionados

O artigo cita como iniciativas, relacionadas ao seu tema, os dados públicos disponibilizados pelos sites InfoMoney, Br Investing e Yahoo Finance, que oferem dados sobre ações, já pré-processados.

Além disso, são citados também artigos acadêmicos sobre o uso de datasets contendo o preço de ações, e a utilização de seus dados para a aplicação em modelos de <em>Machine Learning</em>, como, por exemplo, um relacionado ao mercado de ações de Shanghai, que foi utilizado para análises de <em>Day trade</em> utilizando SVM (Support Vector Machine Regression).