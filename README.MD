<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario. -->

|       ID      |     marca     |    modello    |      anno     | chilometraggio|       prezzo  |  tipo_cambio  |   descrizione |     immagine  |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
|      int      | Varchar(50)   | Varchar(50)   |      Year     |  Varchar(50)  |DECIMAL(10, 2) |  Varchar(50)  | Varchar(250)  | Varchar(250)  |
|       PRIMARY KEY ,NULLABLE     |     PRIMARY KEY ,NULLABLE    |    PRIMARY KEY,NULLABLE    |      NULL     | default(0)|       NULL  |  NULL  |   NULL |     NULL  |

