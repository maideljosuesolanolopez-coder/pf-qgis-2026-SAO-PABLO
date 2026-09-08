# Proyecto Final QGIS – São Paulo, Brasil

## Pregunta de investigación

¿Cuánto y hacia dónde se expandió la ciudad de São Paulo, y qué ocurrió con sus áreas de cobertura natural entre 2005 y 2020?

## Área de estudio

Municipio de São Paulo, Brasil.

Código municipal IBGE: 3550308.

Área municipal: 1521,202 km².

## Sistema de referencia

Para los cálculos de superficie se utilizó SIRGAS 2000 / UTM zona 23S (EPSG:31983), un sistema proyectado en metros.

## Datos utilizados

### Expansión urbana

Se utilizó el producto GHS-BUILT-S de GHSL, con resolución espacial de 100 m, para los años 2005 y 2020.

Como criterio operativo se consideró urbano un píxel con al menos 1000 m² de superficie construida.

### Cobertura natural

Se utilizaron mapas anuales de cobertura terrestre de ESA Climate Change Initiative (CCI) Land Cover, con resolución de 300 m, para los años 2005 y 2020.

Para este análisis se definió como cobertura natural la vegetación correspondiente a las clases 40, 50-90, 100, 110 y 120-180 de la leyenda ESA CCI.

## Procesamiento

Los datos fueron reproyectados al sistema SIRGAS 2000 / UTM zona 23S (EPSG:31983) y recortados al límite municipal de São Paulo.

Para la cobertura natural se utilizó remuestreo por vecino más cercano debido a que se trata de datos categóricos.

Las coberturas naturales de 2005 y 2020 fueron alineadas a una resolución común de 300 m para realizar la comparación temporal.

## Resultados preliminares

Entre 2005 y 2020, la superficie urbana pasó de 82 667 ha a 84 865 ha.

Esto representa una expansión urbana de 2 198 ha, equivalente a 21,98 km².

La proporción del municipio ocupada por la superficie urbana pasó aproximadamente de 54,34 % a 55,79 %.

## Limitaciones

La cobertura natural de ESA CCI tiene una resolución espacial de 300 m, menor que la resolución de 100 m utilizada para el análisis de superficie construida.

Por esta razón, los resultados de cobertura natural deben interpretarse considerando esta diferencia de resolución.

## Reproducibilidad

Los datos procesados, capas de análisis y documentación metodológica se organizan dentro de este repositorio.
