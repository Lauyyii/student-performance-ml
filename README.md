# student-performance-ml
Modelo de clasificación binaria para predecir la aprobación estudiantil en matemáticas // Binary classification model to predict student approval in mathematics

This project was developed as part of the course *Introducción al Aprendizaje Automático* (UNSAM).

## Objective
Predict whether a student will pass Mathematics based on academic history,
lifestyle, and family-related variables.

## Dataset
- Source: Kaggle / OpenML
- Data collected from two Portuguese secondary schools
- 33 features, no missing values

## Approach
- Binary classification problem
- Logistic Regression
- Pipeline with preprocessing (scaling + encoding)
- Hyperparameter tuning with GridSearchCV
- Evaluation using Accuracy and ROC-AUC

## Results
- Accuracy ≈ 0.84
- ROC-AUC ≈ 0.95
- Strong dependence on previous academic performance (G1)

## Technologies
- Python
- pandas, numpy
- scikit-learn
- matplotlib / seaborn

----------------

Este proyecto fue desarrollado en el marco de la materia **Introducción al Aprendizaje Automático**
(Universidad Nacional de San Martín).

## Objetivo
Construir un modelo de **clasificación binaria** que permita predecir si un estudiante aprobará
la materia Matemáticas, a partir de su rendimiento académico previo, variables familiares y
aspectos del estilo de vida.

## Conjunto de datos
- Fuente: Kaggle / OpenML  
- Datos reales de estudiantes de dos escuelas secundarias de Portugal  
- 33 variables y 339 observaciones  
- El dataset no presenta valores faltantes

## Enfoque metodológico
- Planteo como problema de clasificación supervisada  
- Modelo principal: **Regresión Logística**  
- Preprocesamiento mediante *Pipeline* y *ColumnTransformer*  
- Escalado de variables numéricas y codificación de variables categóricas  
- Selección de hiperparámetros con **GridSearchCV**  
- Evaluación con **validación cruzada**

## Métricas de evaluación
- Accuracy  
- ROC-AUC  

## Resultados
- Accuracy ≈ 0.84  
- ROC-AUC ≈ 0.95  
- La variable **G1** (nota del primer período) explica gran parte del poder predictivo del modelo

## Tecnologías utilizadas
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  


## Authors / Autores
- Lautaro Costa
