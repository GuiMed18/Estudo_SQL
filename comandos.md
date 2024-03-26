# Introdução a banco de dados relacionais (SQL)
## Comandos

### CREATE TABLE

```
CREATE TABLE {{nome}} 

    ({{coluna}} {{tipo}} {{opções}} COMMENT 

 {{´COMENTARIO´}});
```

### Tipos de dadaos

 * Inteiro (Integer)
 * Decimal/Numérico (Decimal/Numeric)
 * Caractere/varchar (Character/Varchar)
 * Data/Hora (Date/Time)
 * Booleano (Boolean)
 * Texto longo (Text) 

 ### Restrições de valor:

 * NOT NULL - Torna a coluna obrigatória
 * UNIQUE - Torna a coluna restrita a dados únicos
 * DEFAULT - Configura a coluna para criar um dado padrão para cada registro
