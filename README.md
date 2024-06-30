## "PREDICCION DE LA CONTAMINACION POR MEDIO DOE AUMENTO DE LAS CANTIDADES DE CO2"

### Construcción de Algoritmos de Rendimiento

#### Introduccion 

Este proyecto se centra en la creación de algoritmos de rendimiento utilizando un conjunto de datos sobre energía sostenible, disponible en Kaggle. El objetivo del análisis es comprender y examinar esta información para identificar cuáles son nuestras variables dependientes e independientes, con un enfoque específico en la predicción de la variable "Value_co2_emissions".

Para iniciar el proyecto, se establecieron varios puntos importantes:

- **Análisis Exploratorio de Datos**: Se realizó un análisis exploratorio para familiarizarnos con todas las variables y su posible impacto.

- **Análisis Visual**: Se utilizaron gráficos de dispersión e histogramas para visualizar los datos.
  
- **Tipos de Variables:** Se identificaron y clasificaron las variables en discretas, categóricas y continuas.

- **Análisis de Variables Categóricas vs. Variable Objetivo:** Se analizó la relación entre las variables categóricas y la variable objetivo.

- **Análisis de Variables Continuas vs. Variable Objetivo**: Se examinó la relación entre las variables continuas y la variable objetivo.

- **Balanceo del Conjunto de Datos**: Se balanceó el conjunto de datos, ya que inicialmente la variable dependiente no estaba adecuadamente equilibrada.

- **Codificación de Variables**: Se codificaron las variables categóricas para el análisis.

- **Tratamiento de Valores Atípicos (Outliers):** Se trataron los valores atípicos presentes en el conjunto de datos.

- **Instalación de Librerías:** Se instalaron las librerías necesarias para desarrollar los algoritmos.

- **Determinación de Variables "X" y "Y":** Se identificaron las variables independientes (X) y dependientes (Y).

- **Creación de Algoritmos**: Se desarrollaron varios algoritmos y se les aplicaron cinco hiperparámetros diferentes.

  Los algoritmos trabajados fueron los siguientes:

- Naive Bayes
- Análisis Discriminante Lineal (LDA)
- Regresión Logística
- Máquinas de Soporte Vectorial (SVM)
- Árboles de Decisión
- Random Forest
- Análisis Discriminante Lineal (LDA)
- Análisis Discriminante Cuadrático
- AdaBoost
- Gradient Boosting
- XGBoost
- LGBM

  #### Conclusión
  Los resultados sugieren que los modelos basados en técnicas de ensamble (Random Forest, AdaBoost y Gradient Boosting) y los Árboles de Decisión puros son muy efectivos para este conjunto de datos y lograron una métrica optima pero sobre ajustada por lo tanto
  consideramos que los modelos adecuos para usar son lo del rango de “calidad predicción” de 0.86 a 0.96 Estos modelos deberían ser considerados para implementaciones futuras debido a su rendimiento consistente y superior.

  









  
