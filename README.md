# ai4smartcities

Transformar las  imágenes de satélite en un sensor para la ciudad.

Buscar variaciones en las cubiertas de las  edificaciones.

Se ha utilizado la cartografía vectorial del Instituto Cartográficoy Geológico de Catalunya (http://icgc.cat)
para extraer perímetros de la capa de edificaciónd generada a partir del vuelo del año 2010

Se elige el modelo de reprentación vectorial para las edificaciones con dos componentes: centroide, y área.

La meta es obtener una correlacióm entre los edificios detectados por un modelo no supervisado
y la representación de valores obtenida de los píxeles tras aplicar un algoritmo no supervisado
sobre la banda con mayor resolución y que ofrece los mejores resultados, descartando vegetaciones
y favoreciendo colores terrosos.
