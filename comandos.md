# Introdução a banco de dados relacionais (SQL)
## Comandos

### CREATE TABLE

```
CREATE TABLE {{nome}} 

    ({{coluna}} {{tipo}} {{opções}} COMMENT 

 {{´COMENTARIO´}});
```

### Operações CRUD

#### Create

```
 INSERT INTO 
    
    {{nome-tabela}}

    ([coluna1,coluna2]) 

 VALUES

   ([valor-coluna1,valor-coluna2])

   ```

 * É possível ocultar as colunas, porém tem que colocar na ordem certa pra não ter confusão.

#### Read

``` 

SELECT {{lista_colunas}}

FROM tabela;

WHERE {{condicao}}


```
 * O * Retorna todas as colunas 