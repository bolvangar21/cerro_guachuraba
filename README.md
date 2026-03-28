Descripción general

Este repositorio reúne el trabajo geoespacial, el procesamiento de datos y los insumos analíticos desarrollados en el marco de una línea de investigación realizada junto a Jesús Lara Coronado. El estudio se centra en la arqueología del paisaje, la ocupación prehispánica y la continuidad territorial en la cuenca del Maipo–Mapocho, articulado con el Proyecto Fondecyt–Conicyt N°1180352 sobre ruinas urbanas en ciudades latinoamericanas.

El foco principal es el cerro Huechuraba y sus contextos territoriales, con especial énfasis en la piedra tacita y su papel dentro de la configuración ocupacional temprana del valle de Santiago. La investigación combina evidencia arqueológica, fuentes documentales, trabajo etnográfico y análisis SIG reproducibles para reconstruir relaciones espaciales y secuencias ocupacionales.

🪨 Piedra tacita y paisajes de Chile Central

Una parte central del estudio corresponde a la documentación y análisis de las piedras tacitas presentes en la Región Metropolitana y Chile Central. Se abordan:

patrones de distribución espacial,
relación con rutas de movilidad, terrazas agrícolas y cursos de agua,
función territorial y ritual,
articulación con conjuntos arqueológicos mayores.

El cerro Huechuraba se considera como un complejo arqueológico, no como un punto aislado: se estudia el cerro completo, sus bordes, cimas, visuales, redes de movilidad y continuidades históricas.

🏞️ Continuidad ocupacional del valle de Santiago

La investigación reconstruye la secuencia ocupacional del cerro integrando:

registro material,
fuentes históricas,
testimonios locales,
análisis espaciales reproducibles (R + QGIS).

El estudio dialoga con propuestas recientes sobre la estructuración prehispánica del valle, incluyendo las tesis de Stehberg y colaboradores sobre asentamientos, arquitectura y articulación territorial en los últimos 15 años.

Objetivo del repositorio

Este repositorio tiene por finalidad entregar una base de trabajo clara, reproducible y documentada para comprender la configuración histórica del valle de Santiago, integrando:

evidencia arqueológica y material,
fuentes históricas y cartografía,
información etnográfica,
análisis territoriales y SIG.

Incluye procedimientos de análisis espacial, documentación y criterios de generalización de sitios sensibles.

📁 Estructura del repositorio
data/       → Capas espaciales (generalizadas y sin coordenadas precisas)
qgis/       → Proyecto QGIS con simbología, estilos y mapas base
scripts/    → Scripts de R para procesamiento y análisis (sf, terra, tidyverse)
maps/       → Mapas exportados en PNG/PDF
docs/       → Metodologías, notas técnicas y referencias

🔐 Notas sobre datos sensibles
Los datos georreferenciados de sitios arqueológicos están generalizados conforme a protocolos de protección patrimonial.
Los datos completos, con precisión de coordenadas, están disponibles solo bajo solicitud formal y con compromisos éticos.

🛠️ Requisitos técnicos
QGIS 3.x o superior
R 4.x con librerías:
sf
tidyverse
terra
ggplot2 (opcional para visualizaciones)

✍️ Autoría
Gabriel Sánchez Antonucci

Tesis: Contribuciones al estudio sobre continuidad ocupacional y valor patrimonial del Cerro Huechuraba (2019) Universidad de Chile. Magister en Arqueología.
Repositorio institucional:
https://repositorio.uchile.cl/handle/2250/187419?utm_source=chatgpt.com
