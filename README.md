# Análise de Resultados Anuais de um E-commerce
## Descrição do Projeto
Este projeto teve como objetivo praticar r revisar habilidades com Python e Power BI, criando uma análise fictícia dos resultados anuais de um e-commerce.

Para isso utilizei Python para gerar uma base de dados personalizada com transações de compras, incluindo informações de clientes, produtos, valores e formas de pagamento. Em seguida, os dado foram analisados e visualizados no Power BI, permitindo insights sobre a vendas ao longo do ano.

## Principais Tecnologias Utilizadas
Python(Faker, Pandas) - Para a criação e manipulação dos dados em nosso dataframe.
Power BI - Para análise e visualização dos resultados.

## Passos do Desenvolvimento
* Fiz a criação de meu próprio database para este projeto, utilizando a biblioteca Faker do Python para a criação de informações aleatórias de clientes, datas, cidades.
  <img src= "https://github.com/FelipeRodrii/Projeto-Ecommerce/blob/main/Template_Imagens/definicao.png", weight= 600px />
* Defini um conjunto de produtos com preços fixos.
* Simulei transações aleatórias, incluindo quantidade de itens e forma de pagamentos.

* [imagem do trecho~]

* Organizei os dados em um dataFrame do Pandas.
* Salvei a base no formato CSV para ser utilizada no Power BI.
[exportação do dataFrame]
* Carreguei os dados no Power BI e os normalizei utilizando o Power Query, automatizando assim todo o processo de extração desta base no futuro.
  [Automatização]
* Realizei a criação de Medidas, para simplificar a identificação dados que se faziam necessários para o Dash alem de criar uma nova coluna calculada que trás o nome extenso do estado utilizando a linguagem DAX.
  [imagens focando as medidas e o dax]
* Por fim, Desenvolvi gráficos para entender o volume de vendas, lucros mensais e anula, depesas mensai e anual, lucros por região do brasil, e dados de comportamento de clientes.
  
