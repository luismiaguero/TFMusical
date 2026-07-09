# TFMusical

Proyecto de análisis de datos musicales basado en datasets de canciones de Spotify. 

El objetivo es conseguir una comparativa de diferentes sistemas de recomendación musicales basados en similitud en diferentes espacios reducidos.

Estos espacios reducidos se construyen con diferentes técnicas multivariantes (PCA, MCA; CATPCA y UMAP) tras la debida exploración inicial, limpieza y preprocesamiento y análisis de características de audio.

## Contenido del proyecto

El repositorio incluye scripts y notebooks para:.

- Limpieza y preprocesamiento de datos.
- Análisis previo univariante y multivariante para la adecuación de las variables y los datos..
- Comaprador de diferentes modelos candidatos.
- Construcción de los espacios reducidos PCA, MCA, CATPCA y UMAP.
- Clusterización y estudio itnerpretativo de los espacios generados.
- Implementación de los sistemas de recomendación basados en los diferentes modelos.
- Puesta en práctica, uso con ejemplos.
- Comaprativa y evaluación de los diferentes sistemas de recomendación.

Además se incluyen los datasets con los que se trabajan dentro del propio repositorio.

## Requerimientos
Las librerías utilizadas están instaladas e importadas en los propios notebooks.

Es necesario tener instalado python, aconsejablemente con una versión 3.14.*

El trabajo ha sido realizado en Visual Studio code por lo que si se desea clonar para reproducir los resultados, sería aconsejable utilizar el mismo programa.
