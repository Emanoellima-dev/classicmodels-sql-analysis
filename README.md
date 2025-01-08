# classicmodels-sql-analysis

Este projeto utiliza o banco de dados `classicmodels` como exemplo para realizar análises de vendas em uma empresa que comercializa modelos de carros. O banco de dados contém informações sobre clientes, pedidos, produtos e funcionários, sendo ideal para praticar consultas SQL e análise de dados.

## Descrição

O banco de dados `classicmodels` simula uma empresa de venda de carros e peças. Ele possui várias tabelas, incluindo `customers`, `orders`, `products`, `orderdetails`, entre outras, permitindo realizar análises sobre:

- Pedidos realizados por clientes.
- Produtos mais vendidos.
- Desempenho de vendedores.
- Informações financeiras, como receita gerada.

Este repositório contém o arquivo SQL para criar o banco de dados e as consultas SQL realizadas para análise dos dados.

## Tabelas

As principais tabelas no banco de dados `classicmodels` incluem:

- **customers**: Contém informações sobre os clientes, como nome, endereço, e país.
- **orders**: Registra os pedidos feitos pelos clientes, incluindo data e status.
- **orderdetails**: Detalhes dos produtos incluídos em cada pedido.
- **products**: Contém informações sobre os produtos disponíveis para venda, como nome, categoria e preço.
- **employees**: Registra informações sobre os funcionários e seus papéis na empresa.

## Objetivo do Projeto

O principal objetivo deste projeto é realizar análises de vendas utilizando consultas SQL no banco de dados `classicmodels`. O foco está em explorar dados de pedidos, identificar os produtos mais vendidos, analisar a performance dos vendedores e calcular a receita gerada pela empresa.

## Como Usar

### 1. Importando o Banco de Dados

Para começar a usar o banco de dados em seu ambiente local, basta importar o arquivo SQL. Se você está utilizando o **MySQL** ou **MariaDB**, execute os seguintes passos:

1. Baixe o arquivo [mysqlsampledatabase.sql](https://github.com/Emanoellima-dev/classicmodels-sql-analysis/blob/main/mysqlsampledatabase.sql).
2. Abra o terminal e conecte-se ao seu banco de dados MySQL/MariaDB:
   ```bash
   mysql -u root -p
3. importe o arquivo sql
   ```bash
   SOURCE /caminho/para/mysqlsampledatabase.sql
   ```
5. 
