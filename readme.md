#Struttura database concessionario auto online

- id AUTO INCREMENT, BIGINT, NOTNULL
- marca VARCHAR (255), NOTNULL
- modello VARCHAR (255), NOTNULL
- allestimento VARCHAR (255), NULL
- data_immatricolazione DATE, NOTNULL
- cavalli VARCHAR (10), NULL
- cilindrata VARCHAR (15), NULL
- chilometraggio VARCHAR (255), NOTNULL
- carburante VARCHAR (30), NOTNULL
- venditore VARCHAR (30), NULL
- targa VARCHAR (30), UNIQUE
- prezzo DECIMAL(10), NULL
