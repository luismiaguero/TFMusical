# TFMusical

Proyecto de análisis de datos musicales basado en datasets de canciones de Spotify. 
El objetivo es conseguir una comparativa de diferentes sistemas de recomendación musicales basados en similitud en diferentes espacios reducidos.
Estos espacios reducdios se construyen con diferentes técnicas multivariantes (PCA, MCA; CATPCA y UMAP) tras la debida exploración inicial, limpieza y preprocesamiento y análisis de características de audio.

## Contenido del proyecto

El repositorio incluye scripts y notebooks para:.

- Limpiar y preparar los datos.
- Escalar variables numéricas.
- Aplicar PCA, UMAP y análisis factorial.
- Crear agrupaciones con K-Means y otros métodos.
- Evaluar clusters con métricas como Silhouette Score, Davies-Bouldin Score y Calinski-Harabasz Score.
- Generar gráficos y resultados interpretables.

Además se incluyen los datasets con los que se trabajan dentro del propio repositorio.

## Requerimientos
Las librerías utilizadas están instaladas e importadas en los propios notebooks.
Es necesario tener instalado python, aconsejablemente con una versión 3.14.*
El trabajo ha sido realizado en Visual Studio code por lo que si se desea clonar para reproducir los resultados, sería aconsejable utilizar el mismo programa.
