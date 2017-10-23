### E.1.5 Modelo de datos

#### E.1.5.1 Modelos relevantes

El único modelo con el que cuenta esta aplicación es Store. 

#### E.1.5.2 Tablas

Cuenta con sólo una tabla llamada Store. Aquí se guardan en formato JSON todas las revisiones de las modificaciones que va teniendo un Pad. Esta tabla sólo cuenta con dos columnas: Key (Clave) y Value (Valor). 

#### E.1.5.3 Gráficos UML

Al contar con una única tabla (store) con dos columnas (key y value) no se agrega gráfico UML. La información relativa a esta tabla y sus columnas es la siguiente:

>  mysql> describe store;
>  +-------+--------------+------+-----+---------+-------+
>  | Field | Type     	| Null | Key | Default | Extra |
>  +-------+--------------+------+-----+---------+-------+
>  | key   | varchar(100) | NO   | PRI | NULL	|   	|
>  | value | longtext 	| NO   | 	| NULL	|   	|
>  +-------+--------------+------+-----+---------+-------+
>  2 rows in set (0.00 sec)

A continuación un ejemplo de los contenidos dentro de esta tabla:

> key: pad:test:revs:1
> value: {"changeset":"Z:6c>1|5=6b*0|1+1$\n","meta":{"author":"a.oQuROhHCepHhKURO","timestamp":1504275170925}}
> 
> key: pad:test:revs:2
> value: {"changeset":"Z:6d>2|6=6c*0|2+2$\n\n","meta":{"author":"a.oQuROhHCepHhKURO","timestamp":1504275171362}}

