# Juan DOE 
2021 © Diego Salgado, bajo Licencia MIT.

Este programa es un buscador de publicaciones de extractos de sociedades en el Diario Oficial de Chile.

Consta de los siguientes módulos:

* Un módulo scraper que recopila la publicaciones desde el 17.08.2016 a la fecha en una base de datos (a definir si estará guardada en CSV o en SQLite).

El modulo scraper, que lo llamaremos "sabueso", ingresará al sitio, verificará si hay edición en ese día, y luego, si hay más de una edición en ese día (he llegado a ver hasta 4).

* Un módulo de actualizaciones, que actualiza –valga la redundancia- la base de datos al día en que se abre el programa.
* Un módulo buscador offline, que busca en la base de datos y cuyo output es:
    1. Si existen publicaciones de la sociedad.
    2. Las fechas de las publicaciones.
    3. A qué corresponde: constitución, modificación o disolución.
    4. Link a la descarga del extracto.
