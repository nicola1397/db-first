| FIELD        | TYPE        | ATTRIBUTES                                 | INDEXES     |
| ------------ | ----------- | ------------------------------------------ | ----------- |
| id           | INT         | AUTO_INCREMENT (UNIQUE, NOTNULL, UNSIGNED) | PRIMARY KEY |
| marca        | VARCHAR(20) | NOTNULL                                    |             |
| modello      | VARCHAR(30) | NOTNULL                                    |             |
| carrozzeria  | VARCHAR(30) | NOTNULL, DEFAULT("an car")                 |             |
| allestimento | VARCHAR(50) | NOTNULL, DEFAULT("Base")                   |             |
| anno         | YEAR        | NOTNULL                                    |             |
| carburante   | VARCHAR(20) | NOTNULL, DEFAULT("Benzina")                |             |
| cilindrata   | SMALLINT    | NOTNULL, UNSIGNED                          |             |
| cavalli      | SMALLINT    | NOTNULL, UNSIGNED                          |             |
| cambio       | VARCHAR(20) | NOTNULL, DEFAULT("Manuale")                |             |
| marce        | TINYINT     | NOTNULL, UNSIGNED, DEFAULT(5)              |             |
| porte        | TINYINT     | NOTNULL, UNSIGNED, DEFAULT(5)              |             |
| posti        | TINYINT     | NOTNULL, UNSIGNED, DEFAULT(4)              |             |
| condizioni   | VARCHAR(50) | NOTNULL, default("Km 0")                   |             |
| colore       | VARCHAR(20) | NOTNULL                                    |             |
| interni      | VARCHAR(20) | NOTNULL, DEFAULT("Tessuto sintetico")      |             |
| km           | MEDIUMINT   | NOTNULL, UNSIGNED                          |             |
| targa        | CHAR(7)     | NOTNULL, UNIQUE                            |             |
| prezzo       | FLOAT(8,2)  | NOTNULL, UNSIGNED                          |             |
