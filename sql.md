# Introdução a banco de dados relacionais (SQL)
## Conceitos Básicos

### Tipos de bancos de dados
 Relacionais/SQL
 Não Relacionais/NoSQL (Not OnlySQL)
 Orientado a Objetos
 Hierárquico

### SGBD (Sistema de Gerenciamento de Banco de dados)

 Postgres - Mysql - SQLite - MariaDB - Mongodb

### CRUD

 Create
 Read
 Update
 Delete

### Características

 Relacionamento entre tabelas
 Linguagem de consulta estruturada (SQL)
 Integridade referencial
 Normalização de dados 
 Segurança
 Flexibilidade e extensibilidade
 Suporte a transações ACID

### ACID

 Protocolo que Garante que as operações de banco de dados sejam executadas de forma segura e confiável
 
 Atomocidade (Ou tudo funciona, ou nada funciona)

 Consistência (Garante que o bd permaneça consistente)

 Isolamento (Cada transação é executada isolada, sem afetar outras)

 Durabilidade (Uma vez que a alteração é commitada, ela é permanente)

### SQL - Structured Query Language

 Linguagem estruturada utilizada para realizar as transações nos bancos relacionais

#### DQL - Linguagem de consulta de dados
 Onde são realizadas consultas no banco
 
 ``` 
 SELECT
 ```
 #### DML - Linguagem de manipulação de dados

 Inserir, alterar e Deletar dados

 ```
 INSERT - UPDATE - DELETE
 ```

 #### DDL - Linguagem de Definição de dados

 Estruturar as tabelas, definir tipos de dados

 ```
 CREATE - ALTER - DROP
 ```

 #### DCL - Linguagem de controle de dados

 Permissões para manipular o banco de dados (DevOps ou SI)

 ```
 GRANT - REVOKE
 ```
 #### DTL - Linguagem de transação de dados

 Garantem as execuções do BD 
 BEGIN - Define o início da execução
 COMMIT - Efetiva as execuções
 ROLLBACK - Retorna a execução

 #### Regras de Sintaxe

 Nomes devem começar com letra ou underline ex: cliente_1 _1cliente

 Nomes podem conter letras, números e underline

 CaseSensitive
 

