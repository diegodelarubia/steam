Análisis del Mercado de Steam — ¿Cómo Diseñar un Videojuego Exitoso?

Objetivo del Proyecto

Este proyecto analiza datos históricos de Steam para identificar qué características (género y precio) están asociadas a:

Mayor número de propietarios (owners) → éxito comercial

Mayor número de usuarios concurrentes (concurrent_users) → engagement y retención

Mayor tasa de aprobación (approval_rate) → satisfacción del jugador

El objetivo final es proporcionar una recomendación estratégica basada en datos para el desarrollo de un nuevo videojuego con altas probabilidades de éxito.

Limpieza y Preparación de Datos

Antes de realizar el análisis, se llevaron a cabo los siguientes pasos:

Conversión de rangos de propietarios en una métrica numérica (owners_mean).

Eliminación de valores nulos y registros duplicados.

Aplicación de un umbral mínimo de reseñas para evitar sesgos en la métrica de satisfacción.

Creación de rangos de precio para facilitar el análisis comparativo.

La distribución de propietarios mostró una estructura de mercado altamente desigual: un pequeño número de juegos concentra la mayor parte de las ventas.
------------------------------------------------------------------------------------------------------------------

1.Análisis Individual de Variables
🔹 Owners (Éxito Comercial)

El mercado presenta una alta concentración.

Un pequeño porcentaje de juegos acumula la mayoría de propietarios.

La distribución está fuertemente sesgada hacia la derecha.

Tener muchas ventas no garantiza alta retención.

🔹 Concurrent Users (Engagement)

Algunos juegos tienen muchas ventas iniciales pero baja actividad posterior.

Los juegos multijugador o cooperativos tienden a mantener mayores niveles de usuarios concurrentes.

El engagement es un factor clave más allá del volumen de ventas.

🔹 Approval Rate (Satisfacción)

Se aplicó un filtro mínimo de reseñas para reducir distorsiones estadísticas.

Géneros como Accounting, Casual e Indie presentan mayores niveles de satisfacción.

La satisfacción no siempre está directamente correlacionada con el volumen de ventas.
------------------------------------------------------------------------------------------------------------------

Análisis por Género

Se analizaron los géneros combinando el promedio de:

Propietarios

Usuarios concurrentes

Tasa de aprobación

Resultados destacados:

Photo Editing y Massively Multiplayer presentan mayor éxito comercial y mayor engagement.

Accounting, Casual e Indie destacan en satisfacción.

Los géneros con componente online muestran mayor retención de jugadores.
------------------------------------------------------------------------------------------------------------------

Análisis por Precio

Se agruparon los juegos en rangos de precio para evaluar su impacto en el rendimiento.

Conclusiones principales:

El rango de 51–100 € concentra:

Mayor número promedio de propietarios.

Mayor número promedio de usuarios concurrentes.

Los precios extremadamente altos son casos aislados y no representan un patrón de éxito generalizable.

El posicionamiento en precio influye significativamente en el desempeño comercial.

------------------------------------------------------------------------------------------------------------------
 Recomendación Estratégica

Con base en el análisis histórico del mercado de Steam:

- Género Recomendado

	- Massively Multiplayer o géneros con fuerte componente online y enfoque en retención.

- Rango de Precio Recomendado

	- Entre 51 € y 100 €.

------------------------------------------------------------------------------------------------------------------

Metodología

El análisis incluyó:

Estadística descriptiva

Análisis de distribuciones (incluyendo transformación logarítmica)

Rankings y comparaciones

Agrupación por género y precio

Visualizaciones (histogramas, gráficos de barras, heatmaps)

Comparación cruzada entre ventas, engagement y satisfacción

------------------------------------------------------------------------------------------------------------------

Herramientas Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn