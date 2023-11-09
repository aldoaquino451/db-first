Database Used-Car
===

#### Numeri
TINYINT UNSIGNED 250 - SMALLINT UNSIGNED 65k 
MEDIUMINT 16kk - INT - BIGINT 

#### Stringe
CHAR() VARCHAR() max250 - TEXT 65k - MEDIUMTEXT - LONGTEXT

#### Tipo di dato
PRIMARY - AUTO_INCREMENT 
UNIQUE - NULL - NOTNULL - DEFAULT()

## Table

| Syntax           | Description       | Altro         |
| ---------------- | ----------------- | ------------- |
| ID | INT UNSIGNED | PRIMARY - AUTO_INCREMENT |
| type_of_vehicle | VARCHAR(20) | NOTNULL |
| status | VARCHAR(20) | NOTNULL |
| brand | VARCHAR(20) | NOTNULL  |
| model | VARCHAR(20) | NOTNULL  |
| series | VARCHAR(20) | NULL |
| category | VARCHAR(20) | NULL  |
| fuel | VARCHAR(20) | NOTNULL |
| year_registration | YEAR | NOTNULL |
| kilometers  | MEDIUMINT UNSIGNED | NOTNULL |
| price | MEDIUMINT UNSIGNED | NOTNULL |
| color_bodyshell | VARCHAR(20) | NULL |
| seat | TINYINT UNSIGNED | NULL |
| doors | TINYINT UNSIGNED | NULL |
| tank_vol | TINYINT UNSIGNED | NULL |
| trunk_vol | SMALLINT UNSIGNED | NULL |
| height | SMALLINT UNSIGNED | NOTNULL |
| width | SMALLINT UNSIGNED | NOTNULL |
| length | SMALLINT UNSIGNED | NOTNULL |
| weight | MEDIUMINT UNSIGNED | NOTNULL |
| parking_sensor | CHAR(1) | NULL |
| dash_cam | CHAR(1) | NULL |
| start_stop | CHAR(1) | NULL |
| car_radio | CHAR(1) | NOTNULL - DEFAUT('1') |
| power_steering | CHAR(1) | NULL |
| air_conditioner | CHAR(1) | NOTNULL - DEFAUT('1') |
| abs | CHAR(1) | NULL |
| displacement | SMALLINT UNSIGNED | NOTNULL |
| horsepower | SMALLINT UNSIGNED | NULL |
| transmission | VARCHAR(10) | NULL |
| emission | VARCHAR(10) | NULL |
| consumption | TINYINT UNSIGNED | NUL |

