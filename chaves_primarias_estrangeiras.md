# Introdução a banco de dados relacionais (SQL)
## Chaves Primarias e Estrangeiras

### Chave primária

* Garante a exclusividade dos registros da tabela.
* Não pode conter valores nulos
* Pode haver apenas uma chave primária

### Chave Estrangeira

* Estabelece relação entre duas tabelas
* Pode ser nulo (NOT NULL)

#### Create table
* FOREIGN KEY (chave_estrangeira) REFERENCES outra tabela (id)

#### Alter Table
* ADD CONSTRAINT

#### Restrições
* ON DELETE: O que acontece com os registros quando um reg pai é excluído

* ON UPDATE: Define o comportamento dos registros quando o registro pai é atualizado

* CASCADE - Replica a alteração do pai nos filhos

* SET NULL - Remove a integridade referencial

* SET DEFAULT - Define um registro padrão para os registros que ficaram sem pai

* RESTRICT - Rejeita a atualização ou exclusão de um registro da tabela pai se houver registros na tabela filha

