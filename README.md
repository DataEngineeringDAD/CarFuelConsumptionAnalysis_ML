# Predicción de Eficiencia de Combustible con Random Forest

Este repositorio contiene un proyecto de machine learning que utiliza un modelo de **RandomForestRegressor** para predecir la eficiencia de combustible (combinación de millas por galón o `combination_mpg`) de diferentes tipos de vehículos. El conjunto de datos incluye características importantes del vehículo, como el tipo de combustible, clase del vehículo, número de cilindros y desplazamiento del motor, para proporcionar predicciones precisas.

## Descripción del Proyecto

La predicción de consumo de combustible es un desafío común en machine learning, especialmente útil para la industria automotriz y los estudios de impacto ambiental. En este proyecto, implementamos un modelo de **Random Forest** para capturar las relaciones entre las características mecánicas y de clasificación de los vehículos y su eficiencia de combustible.

### Características Principales
- **Modelo Utilizado**: `RandomForestRegressor`
- **Características Incluidas**: 
  - `fuel_type_encoded`: Tipo de combustible (gasolina, diésel, eléctrico, etc.)
  - `class_encoded`: Clase del vehículo (sedán, SUV, etc.)
  - `cylinders`: Número de cilindros del motor
  - `displacement`: Desplazamiento del motor
- **Métricas de Evaluación**:
  - **MSE (Mean Squared Error)**: 3.84
  - **R² (Coeficiente de Determinación)**: 0.8566

### Estructura del Repositorio

- **notebooks/**: Contiene el notebook Jupyter con el análisis exploratorio, preprocesamiento de datos y entrenamiento del modelo.
- **data/**: Archivos de datos utilizados en el proyecto (asegúrate de mantener la estructura de datos en el formato especificado).
- **src/**: Scripts de Python para preprocesamiento, entrenamiento del modelo y evaluación.
- **README.md**: Explicación detallada del proyecto.

### Resultados

El modelo desarrollado logra un **MSE de 3.84** y un **R² de 0.8566**, lo cual indica un alto nivel de precisión y un buen ajuste a los datos. Este proyecto demuestra la efectividad de los modelos basados en árboles para capturar relaciones complejas entre las características y la eficiencia de combustible.

## Instrucciones de Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/prediccion-eficiencia-combustible.git

# Requisitos
  - Python 3.6 o superior
  - Paquetes:
  - scikit-learn
  - pandas
  - numpy
  - matplotlib
