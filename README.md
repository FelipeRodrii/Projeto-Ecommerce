# Análise de Resultados Anuais de um E-commerce
## Descrição do Projeto
Este projeto teve como objetivo praticar r revisar habilidades com Python e Power BI, criando uma análise fictícia dos resultados anuais de um e-commerce.

Para isso utilizei Python para gerar uma base de dados personalizada com transações de compras, incluindo informações de clientes, produtos, valores e formas de pagamento. Em seguida, os dado foram analisados e visualizados no Power BI, permitindo insights sobre a vendas ao longo do ano.

## Principais Tecnologias Utilizadas
Python(Faker, Pandas) - Para a criação e manipulação dos dados em nosso dataframe.
Power BI - Para análise e visualização dos resultados.

## Passos do Desenvolvimento
* Fiz a criação de meu próprio database para este projeto, utilizando a biblioteca Faker do Python para a criação de informações aleatórias de clientes, datas, cidades etc... . Para a criação antes tive que definir pré configurações antes, como os nomes das minhas colunas, produtos, formas de pagamento e sexo dos clientes
'''colunas = [
    "Nome", "Sobrenome","Sexo", "CPF","Idade", "ID_Produto", "Produto", "Quantidade",
    "Valor_Unitario", "Total_Compra", "Imposto_Produto", "Cidade",
    "Estado", "Pais", "Data", "Forma_Pagamento"]

produtos = [{"id": "01""nome": "Notebook", "valor": 3500.00},
            {"id": "02", "nome": "Smartphone", "valor": 2000.00},
            {"id": "03", "nome": "Tablet", "valor": 3000.00},
            {"id": "04", "nome": "Impressora", "valor": 800.00},
            {"id": "05", "nome": "Monitor", "valor": 950.00},
            {"id": "06", "nome": "Teclado", "valor": 200.00},
            {"id": "07", "nome": "Mouse", "valor": 80.00},
            {"id": "08", "nome": "HeadSet", "valor": 250.00},
            {"id": "09", "nome": "Cadeira Gamer", "valor": 900.00},
            {"id": "10" "nome": "Suporte Monitor", "valor": 150.00}]

formas_pagamento = ["Debito", "Credito", "PIX", "Especie"]

sexo_opcoes = ["Masculino", "Feminino"]

dados = [] '''



