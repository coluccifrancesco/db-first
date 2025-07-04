Modellizzare la struttura di una tabella per memorizzare tutti i 
dati riguardanti delle auto usate messe in vendita da un concessionario

COLONNA                           TIPO       (ESEMPIO) (VALORE)         NOT/NULL    ALTRI
- Id                           |  SMALLINT   UNSIGNED  (1)           |  NOTNULL  |  PRIMARY KEY  |  AUTO_INCREMENT  |  UNIQUE
- Marca                        |  VARCHAR    (Porsche) (5-50)        |  NOTNULL  |
- Modello                      |  VARCHAR    (911 Coupe GT3) (5-50)  |  NOTNULL  |
- Km                           |  MEDIUMINT  (8817)                  |  NOTNULL  |
- Anno                         |  YEAR       (2010)                  |  NOTNULL  |
- Alimentazione                |  VARCHAR    (Benzina) (6-10)        |  NOTNULL  |
- Cilindrata                   |  SMALLINT   (4000)                  |  NOTNULL  |
- Numero cilindri              |  TINYINT    (6)                     |  NOTNULL  |
- Cv                           |  SMALLINT   (510)                   |  NOTNULL  |
- Consumo medio (l/km)         |  DECIMAL    (12,4) (2,1)            |  NULL     |
- Tipo di cambio               |  VARCHAR    (Automatico) (5-15)     |  NOTNULL  |
- Numero marce                 |  TINYINT    (7)                     |  NOTNULL  |
- Carrozzeria                  |  VARCHAR    (Coupè) (5-15)          |  NOTNULL  |
- Colore                       |  VARCHAR    (Blu) (3-20)            |  NOTNULL  |
- Peso a vuoto (kg)            |  SMALLINT   (1510)                  |  NULL     |
- Posti                        |  TINYINT    (2)                     |  NOTNULL  |
- Porte                        |  TINYINT    (2)                     |  NOTNULL  |
- Proprietari precedenti       |  TINYINT    (0)                     |  NOTNULL  |
- Tagliandi certificati        |  TINYINT    (BOOLEAN)               |  NOTNULL  |
- Prezzo (€)                   |  MEDIUMINT  (208900)                |  NOTNULL  |
- Targa                        |  VARCHAR    (AA 000 AA) (9)         |  NOTNULL  |  UNIQUE
- Foto                         |  VARCHAR    (255)                   |  NOTNULL  |  DEFAULT
- Descrizione                  |  TEXT                               |  NULL     |  