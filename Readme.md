## **BBDD NoSQL con MongoDB y Python**

Para el presente trabajo he cogido los archivos CSV de la página del ayuntamiento de
Barcelona, que contiene datos sobre los indicadores demográficos.

Los archivos CSV están publicados por años, así que he creado mi dataset uniendo 5 de estos
archivos, contando así con la información de 2017 - 2021.

Aquí la fuente de datos: https://opendata-ajuntament.barcelona.cat/data/es/dataset/est-densitat

Los campos de mi dataset me aportan información sobre el año, distrito, barrio, población,
superficie general en hectáreas, superficie residencial en hectáreas, la densidad general y la
densidad neta de la ciudad de Barcelona.

He optado por hacer las distintas queries con Python en un notebook de Jupyter para poder
ejecutar cada query por separado, y he usado la librería pandas para poder tener una
visualización más clara de los resultados de las queries.

En Jupyter he ido planteando las queries de menor a mayor dificultad. Y en este documento
las traeré en el orden según sea necesario para las conclusiones.

