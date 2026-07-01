# 📊 Análisis Exploratorio de Datos (EDA): Factores asociados al ingreso anual de clientes

## 📌 Descripción del proyecto

Este proyecto corresponde al **Sprint 8 del Bootcamp de Análisis de Datos de TripleTen** y tiene como objetivo realizar un **Análisis Exploratorio de Datos (EDA)** sobre un conjunto de datos de clientes para identificar las variables que presentan mayor asociación con el **ingreso anual**, variable objetivo del estudio.

A través de técnicas de análisis descriptivo, visualización y estadística inferencial, se exploró la estructura del conjunto de datos, se evaluó la distribución de las variables y se identificaron relaciones entre ellas para generar hallazgos relevantes desde una perspectiva de negocio.

---

## 🎯 Objetivos

- Explorar la calidad y estructura del conjunto de datos.
- Analizar la distribución de variables numéricas, categóricas y binarias.
- Identificar relaciones entre variables mediante diferentes medidas de asociación.
- Interpretar los resultados desde una perspectiva de negocio.
- Documentar hallazgos, limitaciones y posibles líneas de análisis futuras.

---

## 📂 Dataset

El conjunto de datos contiene información de clientes e incluye variables relacionadas con:

- Edad
- Nivel de ingreso
- Número de visitas mensuales
- Número de compras mensuales
- Gasto en publicidad dirigida
- Nivel de satisfacción
- Membresía premium
- Abandono de la plataforma
- Tipo de dispositivo
- Región
- Ingreso anual (variable objetivo)

---

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab

---

## 🔎 Etapas del análisis

### 1. Exploración inicial de los datos

- Revisión de la estructura del dataset.
- Identificación de tipos de datos.
- Estadística descriptiva.
- Exploración de valores únicos.

### 2. Análisis exploratorio (EDA)

- Distribución de variables numéricas.
- Exploración de variables categóricas y binarias.
- Matriz de correlación.
- Visualización mediante scatterplots.

### 3. Análisis estadístico

- Correlación de Pearson.
- Correlación de Spearman.
- Correlación punto-biserial.
- V de Cramer para variables categóricas.

### 4. Interpretación de resultados

- Identificación de las variables con mayor asociación al ingreso anual.
- Hallazgos desde una perspectiva de negocio.
- Limitaciones del análisis.
- Recomendaciones y próximos pasos.

---

## 📈 Principales hallazgos

- **`compras_mes`** presentó la asociación más fuerte con el **ingreso_anual**, mostrando una correlación positiva muy alta.
- **`visitas_mes`** mostró una relación positiva moderada con el ingreso anual.
- La variable **`miembro_premium`** presentó una asociación positiva muy débil con el ingreso anual.
- **`abandono`** no mostró una relación estadísticamente significativa con el ingreso anual.
- No se encontraron asociaciones relevantes entre las variables categóricas analizadas mediante la **V de Cramer**.

> **Nota:** Las relaciones encontradas representan asociaciones estadísticas y **no implican causalidad**.

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar este repositorio:

```bash
git clone https://github.com/tu-usuario/nombre-del-repositorio.git
```

2. Abrir el archivo `.ipynb` utilizando alguna de las siguientes opciones:

- Google Colab
- Jupyter Notebook
- Visual Studio Code (con la extensión de Jupyter)

3. Ejecutar las celdas en orden para reproducir el análisis completo.

---

## 📁 Estructura del repositorio

```
├── data/
│   └── dataset.csv
├── notebooks/
│   └── Sprint8_EDA.ipynb
├── README.md
```

*(La estructura puede variar dependiendo de cómo organices tu repositorio.)*

---

## 🚀 Próximos pasos

- Analizar segmentos específicos de clientes para identificar patrones de comportamiento.
- Desarrollar modelos predictivos para estimar el ingreso anual.
- Incorporar nuevas variables que permitan explicar con mayor precisión el comportamiento de los clientes.

---

## 👩‍💻 Autora

**Michell Azpíroz Carreón**

Proyecto desarrollado como parte del **Bootcamp de Análisis de Datos de TripleTen**.
