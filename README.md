# Data Cleaning with PostgreSQL

Projeto desenvolvido em PostgreSQL para simular um cenário de limpeza e validação de dados de campanhas de marketing.

## Objetivo

Demonstrar técnicas de Data Cleaning e Data Quality utilizando SQL e PL/pgSQL.

O projeto cria uma base de dados simulada, gera registros automaticamente por meio de uma Stored Procedure e executa validações para identificar problemas de qualidade dos dados.

## Tecnologias Utilizadas

* PostgreSQL
* SQL
* PL/pgSQL
* pgAdmin

## Estrutura do Projeto

```text
scripts/
├── 01_create_table_and_procedure.sql
└── 02_data_cleaning_queries.sql
```

## Etapas do Projeto

### 1. Criação da Estrutura

* Criação do schema
* Criação da tabela de campanhas de marketing
* Definição dos tipos de dados

### 2. Geração de Dados

Utilização de uma Stored Procedure para gerar 1000 registros simulados contendo:

* Valores nulos
* Caracteres inválidos
* Dados aleatórios
* Diferentes tipos de campanhas

### 3. Validação da Qualidade dos Dados

Foram implementadas consultas para identificar:

* Valores ausentes (NULL)
* Caracteres inválidos ("?")
* Registros duplicados
* Duplicidades parciais
* Outliers em variáveis numéricas

## Aprendizados

* Criação de tabelas em PostgreSQL
* Desenvolvimento de Stored Procedures
* Manipulação de dados com PL/pgSQL
* Técnicas de Data Cleaning
* Análise de qualidade de dados

## Créditos

Projeto desenvolvido como parte dos estudos do curso SQL Para Análise de Dados e Data Science da Data Science Academy (DSA).
