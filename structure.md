# Cars

## Modello : Car

## Table : Cars

- id:         BIGINT        (PK(NOTNULL, AI ,UNIQUE))
- frame:      VARCHAR(30)   (UNIQUE - NOT NULL)
- equipment:  VARCHAR(255)  (NULL)
- img:        VARCHAR(255)  (NULL)
- version:    VARCHAR(50)   (NULL)
- brand:      VARCHAR(25)   (NOT NULL)
- model:      VARCHAR(60)   (NOT NULL)
- year:       YEAR          (NOT NULL)
- used:       TINYINT       (NOT NULL)
- doors:      TINYINT       (NOT NULL)
- seats:      TINYINT       (NOT NULL) 
- kw:         FLOAT(4, 2)   (NOT NULL)
- km:         FLOAT(9, 2)   (NOT NULL)
- price:      DECIMAL(9,2)  (NOT NULL)
- engine:     VARCHAR(25)   (NOT NULL)
- color:      VARCHAR(20)   (NOT NULL)
- rims:       VARCHAR(50)   (NOT NULL)
- car_type:   VARCHAR(25)   (NOT NULL)
- emissions:  VARCHAR(7)    (NOT NULL)