# Análisis Exploratorio de Datos de Exoplanetas

Este proyecto realiza un análisis exploratorio (EDA) de datos sobre exoplanetas confirmados, usando información del [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/).

## Objetivos

- Explorar las características principales de los exoplanetas.  
- Visualizar la distribución de masas, métodos de descubrimiento y evolución temporal.  
- Limpiar y preparar los datos para análisis futuros.

## Estructura del proyecto

exoplanet_eda/
├── data/ # Datos originales
│ └── exoplanets.csv
├── notebooks/ # Notebook con análisis
│ └── eda_exoplanets.ipynb
├── plots/ # Gráficos generados
├── README.md # Esta documentación
├── requirements.txt # Librerías necesarias
└── LICENSE # Licencia del proyecto

## Uso

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/tu_usuario/exoplanet_eda.git

2. Instalar dependencias:

pip install -r requirements.txt

3. Abrir el notebook y ejecutar celdas:

jupyter notebook notebooks/eda_exoplanets.ipynb

# Resultados

El método de tránsito es el más frecuente para detección.

La masa de planetas varía ampliamente, con mayoría de masas bajas.

El número de descubrimientos ha crecido con el tiempo.

# Próximos pasos

Implementar modelos de clasificación para predecir tipos de planetas.

Añadir visualizaciones interactivas.

Analizar zona habitable y propiedades estelares.

# Autor
Gerard Oliver - gerardoliver38@hotmail.com