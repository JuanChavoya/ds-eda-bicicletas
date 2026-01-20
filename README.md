# Análisis Exploratorio de Viajes en Bicicleta (EDA)

## Descripción
Este proyecto presenta un análisis exploratorio de datos de viajes en bicicleta con el objetivo de identificar patrones de uso, comportamiento temporal y variables relevantes para la preparación de modelos predictivos. El enfoque está en comprender la estructura del dataset, evaluar la calidad de los datos y generar insights accionables a partir de visualizaciones y estadísticas descriptivas.

---

## Objetivo
- Analizar el comportamiento de los viajes en bicicleta a lo largo del tiempo.
- Identificar patrones por hora, día y tipo de usuario.
- Evaluar el balance de la variable objetivo y posibles implicaciones para modelado.
- Preparar el dataset para etapas posteriores de aprendizaje automático.

---

## Dataset
El análisis utiliza el archivo:

- `train_full_clean.csv`

Debido a su tamaño (~200 MB), el dataset **no se incluye en el repositorio**.

### Cómo reproducir el análisis
- Coloca `train_full_clean.csv` en la carpeta `data/`, **o**
- Ajusta la ruta en el notebook para cargar el archivo desde Google Drive.

El notebook está preparado para manejar ambas opciones.

---

## Metodología
1. Carga y validación del dataset.
2. Análisis exploratorio de variables numéricas y categóricas.
3. Visualización de patrones temporales (hora, día, fin de semana).
4. Análisis del balance de clases de la variable objetivo.
5. Identificación de variables relevantes para modelado posterior.

---

## Resultados principales
- Se identifican patrones claros de uso por hora y día de la semana.
- Existe desbalance en la variable objetivo, lo cual sugiere la necesidad de técnicas de estratificación o ponderación en modelos posteriores.
- Algunas variables muestran alta correlación con el comportamiento de los viajes y son candidatas clave para modelado predictivo.

---

## Estructura del repositorio
ds-eda-bicicletas/
├── README.md
├── notebooks/
│ └── EDA_viajes_en_bicicleta_portfolio.ipynb
└── data/
└── README.md


---

## Tecnologías utilizadas
- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

---

## Notas
Este proyecto tiene fines demostrativos y forma parte de un portafolio académico-profesional. El análisis se centra en la exploración y comprensión de los datos, no en la construcción final de modelos.

