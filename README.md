# 🎮 Análisis del Mercado de Steam: ¿Cómo Diseñar un Videojuego Exitoso?

## 📊 Descripción del Proyecto

Este proyecto analiza datos históricos de videojuegos publicados en **Steam** con el objetivo de identificar qué características están más asociadas al éxito de un juego.

El análisis se centra en tres indicadores principales:

- **Owners (propietarios)** → indicador de éxito comercial  
- **Concurrent Users (usuarios concurrentes)** → indicador de engagement y retención de jugadores  
- **Approval Rate (tasa de aprobación)** → indicador de satisfacción del jugador  

El objetivo final es obtener **insights basados en datos** que permitan definir una estrategia para desarrollar un videojuego con mayores probabilidades de éxito en el mercado.

---

## 📁 Dataset

Los datos utilizados en este proyecto provienen de datasets públicos del mercado de Steam.

---

## 📈 Visualizaciones

El proyecto incluye distintos gráficos para analizar:

- distribución de ventas
- engagement de jugadores
- impacto del precio
- comparación entre géneros

---

## 🧹 Limpieza y Preparación de los Datos

Antes de realizar el análisis exploratorio, se aplicaron varios pasos de preparación de los datos:

- Conversión de los **rangos de propietarios (owners)** en una variable numérica (`owners_mean`)
- Eliminación de **registros duplicados y valores nulos**
- Aplicación de un **mínimo de reseñas** para mejorar la fiabilidad de la tasa de aprobación
- Creación de **rangos de precios** para facilitar el análisis comparativo

El análisis inicial mostró que el mercado presenta una **distribución muy desigual**, donde un número reducido de juegos concentra la mayor parte de las ventas.

---

## 📊 Análisis Exploratorio

### 🔹 Éxito Comercial (Owners)

El mercado de Steam presenta una **alta concentración de ventas**.

Principales observaciones:

- Un pequeño porcentaje de juegos acumula la mayor parte de los propietarios
- La distribución está **fuertemente sesgada hacia la derecha**
- Un alto volumen de ventas **no siempre se traduce en mayor retención de jugadores**

---

### 🔹 Engagement de Jugadores (Concurrent Users)

Algunos juegos consiguen muchas ventas iniciales pero mantienen **bajos niveles de actividad posterior**.

Principales conclusiones:

- Los juegos **multijugador o cooperativos** tienden a mantener más usuarios activos simultáneamente
- El **engagement** se muestra como un factor clave más allá del número de ventas

---

### 🔹 Satisfacción de los Jugadores (Approval Rate)

Para mejorar la fiabilidad del análisis se estableció un **umbral mínimo de reseñas**.

Observaciones principales:

- Géneros como **Accounting, Casual e Indie** presentan mayores niveles de aprobación
- La satisfacción del jugador **no siempre está directamente relacionada con el volumen de ventas**

---

## 🎮 Análisis por Género

Se analizaron los géneros considerando el promedio de:

- Número de propietarios
- Usuarios concurrentes
- Tasa de aprobación

### Resultados principales

- **Photo Editing** y **Massively Multiplayer** destacan en términos de éxito comercial y engagement
- **Accounting, Casual e Indie** sobresalen en satisfacción de los jugadores
- Los juegos con **componentes online** tienden a mostrar mayores niveles de retención

---

## 💰 Análisis por Precio

Para estudiar el impacto del precio en el rendimiento de los videojuegos, se agruparon los títulos en distintos **rangos de precio**.

### Conclusiones principales

El rango de **51 € a 100 €** presenta:

- Mayor número promedio de propietarios
- Mayor número promedio de usuarios concurrentes

Los precios extremadamente altos aparecen como **casos aislados** y no representan una estrategia generalizable.

El posicionamiento del precio influye de forma significativa en el desempeño comercial.

---

## 🚀 Recomendación Estratégica

### 🎮 Género Recomendado

**Massively Multiplayer** o juegos con fuerte componente **online**, orientados a la retención de jugadores.

### 💰 Rango de Precio Recomendado

**Entre 51 € y 100 €**

Esta combinación parece maximizar:

- Éxito comercial
- Engagement de jugadores
- Sostenibilidad a largo plazo

---

## 📐 Metodología

El proyecto incluye diferentes técnicas de análisis:

- Estadística descriptiva
- Análisis de distribuciones (incluyendo transformaciones logarítmicas)
- Rankings y comparaciones entre variables
- Agrupación de datos por género y rango de precio
- Visualización de datos mediante histogramas, gráficos de barras y heatmaps
- Comparación cruzada entre ventas, engagement y satisfacción

---

## 🛠 Herramientas Utilizadas

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
