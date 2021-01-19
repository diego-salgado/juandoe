# Busca Sociedades
2021 © Diego Salgado, bajo Licencia MIT.

Este programa es un buscador de publicaciones de extractos de sociedades en el Diario Oficial de Chile.

Consta de los siguientes módulos:

* Un módulo scraper que recopila la publicaciones desde el 17.08.2016 a la fecha en una base de datos (a definir si estará guardada en CSV o en SQLite).
* Un módulo de actualizaciones, que actualiza –valga la redundancia- la base de datos al día en que se abre el programa.
* Un módulo buscador offline, que busca en la base de datos y cuyo output es:
    1. Si existen publicaciones de la sociedad.
    2. Las fechas de las publicaciones.
    3. A qué corresponde: constitución, modificación o disolución.
    4. Link a la descarga del extracto.

Debo decidir si subo el módulo scraper, o la base de datos hecha con el scraper solamente. La razón es no llenar de consultas el servidor del Diario Oficial, y que baneen el programa y/o la IP. 

