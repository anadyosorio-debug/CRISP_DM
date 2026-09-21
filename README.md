# CRISP_DM
Aplicación de la metodología CRISP-DM para analizar la ventaja de localía en la NBA, utilizando datos históricos de partidos .

# Ventaja de localía en la NBA con CRISP-DM

Este proyecto aplica la metodología **CRISP-DM** para analizar si jugar como local representa una ventaja en los partidos de la NBA. Se estudiaron **26,523 partidos completos y únicos**, disputados entre las temporadas **2003 y 2022**.

## Objetivo

Comparar el rendimiento de los equipos locales y visitantes mediante las siguientes estadísticas:

- Puntos anotados.
- Porcentaje de tiros de campo.
- Porcentaje de tiros libres.
- Porcentaje de triples.
- Asistencias.
- Rebotes.
- Proporción de victorias.

## Metodología

El proyecto se desarrolló siguiendo las seis fases de CRISP-DM:

1. Comprensión del problema.
2. Comprensión de los datos.
3. Preparación de los datos.
4. Modelado y análisis estadístico.
5. Evaluación de los resultados.
6. Despliegue de los resultados.

Para comprobar si existían diferencias entre el desempeño local y visitante, se utilizaron **pruebas t de Student para muestras pareadas** y una **prueba binomial** para analizar la proporción de victorias.

## Preparación de los datos

La base original contenía **26,651 registros**. Durante la limpieza se eliminaron registros con valores faltantes, partidos duplicados y columnas redundantes.

También se crearon variables con las diferencias entre las estadísticas de los equipos locales y visitantes.

Después del proceso de limpieza se conservaron **26,523 partidos**.

## Resultados principales

- Los equipos locales ganaron **15,628 partidos**, equivalentes al **58.92 %** del total.
- Los equipos visitantes ganaron **10,895 partidos**, equivalentes al **41.08 %**.
- Los equipos locales anotaron, en promedio, **2.82 puntos más por partido**.
- Los equipos locales también presentaron mejores resultados en tiros de campo, triples, asistencias y rebotes.
- Las diferencias fueron estadísticamente significativas en casi todas las métricas analizadas.
- La diferencia en tiros libres no fue estadísticamente significativa.

## Integrantes

- Alonso Limón Zurizadat
-Osorio Morales Jeane Anady
