# 🥇 Análisis de Resultados Deportivos con Pandas

Análisis Exploratorio de Datos sobre el medallero olímpico utilizando Python y Pandas.

---

## 📋 Objetivo

Realizar un análisis exploratorio de datos sobre un conjunto de datos de medallas olímpicas utilizando Pandas. Este proyecto busca aplicar los conceptos y conocimientos sobre **Series**, **DataFrames**, **limpieza de datos**, **operaciones básicas**, **filtrado** y **agregación** en Pandas.

---

## 📂 Dataset

El archivo `medallas.csv` contiene información sobre las medallas obtenidas por cada país en los Juegos Olímpicos de Tokio 2020. Incluye las siguientes columnas:

| Columna | Descripción |
|--------|-------------|
| `Pais` | Nombre del país participante |
| `Oro` | Cantidad de medallas de oro obtenidas |
| `Plata` | Cantidad de medallas de plata obtenidas |
| `Bronce` | Cantidad de medallas de bronce obtenidas |
| `Total` | Total de medallas obtenidas |

- **Registros:** 93 países
- **Nota:** Los valores faltantes en las columnas de medallas representan cero medallas.

---

## 🛠️ Tecnologías

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 🗂️ Estructura del proyecto

```
resultados-deportivos/
│
├──📂 data/
   └── medallas.csv                          # Dataset con el medallero olímpico
├──📓 Análisis de Medallas Olímpicas.ipynb  # Notebook principal con el análisis
└──📄 README.md
```

---

## 📊 Tareas del análisis

1. **Cargar los Datos** — Importar los datos desde el archivo CSV a un DataFrame de Pandas.
2. **Exploración Inicial** — Utilizar métodos básicos para explorar el tamaño, las columnas y los tipos de datos del DataFrame.
3. **Limpieza de Datos** — Identificar y manejar valores faltantes, especialmente en las columnas de medallas donde los valores faltantes indican cero medallas.
4. **Análisis de Medallas de Oro por País** — Identificar los 3 países con más medallas de oro en total.
5. **Análisis de Medallas Totales por País** — Obtener un DataFrame con solo los países que ganaron más de 10 medallas en total.

---

## 🔍 Hallazgos principales

- 🥇 El país con más medallas de oro fue **Estados Unidos** con 39 oros.
- 🌍 Se analizaron **93 países** participantes en el medallero.
- 🏅 Solo **20 países** superaron las 10 medallas totales.

---

## 👤 Autor

**Daniel Roman Villegas**  
[GitHub](https://github.com/DanielRomanVillegas)
