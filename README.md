# Γ Proyecto Gamma | Análisis de Hábitos de Consumo Musical

## Descripción

Una plataforma de streaming musical buscaba comprender mejor los hábitos de escucha de sus usuarios en las ciudades de Springfield y Shelbyville. El objetivo consistía en identificar patrones de consumo, diferencias entre ciudades y tendencias de escucha que pudieran apoyar futuras estrategias de recomendación de contenido y personalización de la experiencia del usuario.

## Objetivos

- Evaluar la calidad de los datos disponibles.
- Preparar el conjunto de datos para su análisis.
- Comparar los hábitos de escucha entre Springfield y Shelbyville.
- Identificar diferencias en la actividad de los usuarios según el día de la semana.
- Analizar las preferencias musicales registradas en la plataforma.
- Generar hallazgos que apoyen la toma de decisiones basada en datos.

## Herramientas utilizadas

- Python
- Pandas
- Jupyter Notebook
- Archivos CSV
- Limpieza de datos
- Análisis Exploratorio de Datos (EDA)

## Fuente de datos

El análisis se realizó utilizando un conjunto de datos que registra la actividad de escucha de usuarios en una plataforma de streaming musical.

Variables analizadas:

- `user_id`: identificador único del usuario.
- `track`: canción reproducida.
- `artist`: artista de la canción.
- `genre`: género musical.
- `city`: ciudad del usuario.
- `time`: hora de reproducción.
- `day`: día de la semana.

Archivo utilizado:

- `music_project_en.csv`

## Metodología

- Exploración inicial del conjunto de datos.
- Revisión de la estructura y calidad de la información.
- Identificación y tratamiento de valores ausentes.
- Eliminación de registros duplicados.
- Corrección de inconsistencias en los géneros musicales.
- Comparación de la actividad de escucha entre ciudades.
- Evaluación de patrones de consumo según el día de la semana.
- Validación de hallazgos obtenidos a partir de los datos.

## Principales hallazgos

- Se detectaron y corrigieron registros incompletos en variables relevantes como artista, canción y género musical.
- Se identificaron y eliminaron registros duplicados que podían afectar la precisión de los resultados.
- Springfield presentó un volumen de reproducciones considerablemente superior al de Shelbyville durante los días analizados.
- Ambas ciudades mostraron un ligero incremento en la actividad de escucha los viernes.
- La base de datos contiene una amplia diversidad de géneros musicales, reflejando distintos perfiles de consumo entre los usuarios.
- La estandarización de categorías musicales permitió obtener resultados más consistentes y confiables.

## Archivos principales

- `gamma_music_consumption_analysis.ipynb`
- `music_project_en.csv`

## Conclusión

El análisis permitió obtener una visión más clara de los hábitos de escucha de los usuarios en Springfield y Shelbyville. Tras la limpieza y preparación de los datos, fue posible comparar niveles de actividad, identificar patrones de consumo y explorar diferencias entre ambas ciudades. Los resultados muestran que Springfield mantiene una actividad significativamente superior durante los días analizados, mientras que ambas ciudades presentan un aumento moderado en las reproducciones hacia el final de la semana. Estos hallazgos proporcionan información valiosa para comprender el comportamiento de los usuarios y apoyar futuras estrategias de personalización y recomendación de contenido.
