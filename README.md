# Análise de Resultados Anuais de um E-commerce
## Descrição do Projeto
Este projeto teve como objetivo praticar e revisar habilidades com Python e Power BI, criando uma análise fictícia dos resultados anuais de um e-commerce.

Para isso utilizei Python para gerar uma base de dados personalizada com transações de compras, incluindo informações de clientes, produtos, valores e formas de pagamento. Em seguida, os dado foram analisados e visualizados no Power BI, permitindo insights sobre a vendas ao longo do ano.

## Principais Tecnologias Utilizadas
Python(Faker, Pandas) - Para a criação e manipulação dos dados em nosso dataframe.
Power BI - Para análise e visualização dos resultados.

## Passos do Desenvolvimento
* Fiz a criação de meu próprio database para este projeto, utilizando a biblioteca Faker do Python para a criação de informações aleatórias de clientes, datas, cidades.
<p align="center"><img src= "https://github.com/FelipeRodrii/Projeto-Ecommerce/blob/main/Template_Imagens/definicao.png" width = "600px"/></p>

* Defini um conjunto de produtos com preços fixos.
<p align="center"><img src= "https://github.com/FelipeRodrii/Projeto-Ecommerce/blob/main/Template_Imagens/Colunas_Produtos.png" width = "600px"/></p>

* Simulei transações aleatórias, incluindo quantidade de itens e forma de pagamentos.
  <p align="center"><img src= "https://github.com/FelipeRodrii/Projeto-Ecommerce/blob/main/Template_Imagens/criacao-dados.png" width = "600px"></p>
  
* Organizei os dados em um dataFrame do Pandas e exportei em formato CSV.
  <p align="center"><img src= "https://github.com/FelipeRodrii/Projeto-Ecommerce/blob/main/Template_Imagens/df%20e%20exportacao.png" width = "600px"/></p>
  
* Carreguei os dados no Power BI e os normalizei utilizando o Power Query, automatizando assim todo o processo de extração desta base no futuro.
  <p align="center"><img src= "https://github.com/FelipeRodrii/Projeto-Ecommerce/blob/main/Template_Imagens/PowerQuery.png" width = "600px"></p>
  
* Realizei a criação de Medidas, para simplificar a identificação dados que se faziam necessários para o Dash alem de criar uma nova coluna calculada que trás o nome extenso do estado utilizando a linguagem DAX.
  <p align="center"><img src= "https://github.com/FelipeRodrii/Projeto-Ecommerce/blob/main/Template_Imagens/medidado-DAX.png" width = "600px"></p>
  
* Por fim, Desenvolvi gráficos para entender o volume de vendas, lucros mensais e anula, depesas mensai e anual, lucros por região do brasil, e dados de comportamento de clientes.
  <p align="center"><img src= "https://github.com/FelipeRodrii/Projeto-Ecommerce/blob/main/Template_Imagens/Dashboard.png" width = "600px"></p>

  ## Tecnologias Usadas
  <p align="left">  
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/New_Power_BI_Logo.svg/630px-New_Power_BI_Logo.svg.png" alt="powerbi" width="40" height="40"/>    
    <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="40"/>
    <img src= "https://upload.wikimedia.org/wikipedia/commons/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg" width="40" height="40"/>
  </p> 
  
