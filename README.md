# 🧠 Obesity Risk - Multiclass Classification

Este proyecto aborda la predicción del riesgo de obesidad utilizando algoritmos de clasificación multiclase, aplicados a un conjunto de datos relacionados con hábitos alimenticios, actividad física y características demográficas. El objetivo es desarrollar un modelo que clasifique correctamente a los individuos en diferentes niveles de riesgo de obesidad, apoyando así estrategias preventivas en salud pública.

## 📁 Estructura del proyecto

El proyecto está contenido en el notebook:  
`Obesity_risk_MClassification.ipynb`

El flujo de trabajo incluye:

1. **Carga y exploración del dataset**
2. **Preprocesamiento de datos (encoding, normalización)**
3. **Análisis exploratorio (EDA)**
4. **Ingeniería de características**
5. **Entrenamiento de modelos base**
6. **Optimización con hiperparámetros**
7. **Evaluación de desempeño**
8. **Selección del mejor modelo**
9. **Conclusiones**

## 📊 Dataset

- Fuente: [UCI Machine Learning Repository - Obesity Level Estimation](https://archive.ics.uci.edu/ml/datasets/Obesity+Level+Estimation)
- Registros: 2111 instancias
- Variables: Hábitos alimenticios, nivel de actividad física, IMC, género, edad, entre otros
- Target: `NObeyesdad` (categoría multiclase con niveles como: Insufficient Weight, Normal Weight, Obesity Type I, etc.)

## 🛠️ Herramientas y tecnologías

- Python 3.9+
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost
- Pipeline de Scikit-learn
- OneHotEncoding y StandardScaler

## 📈 Modelos utilizados

Se entrenaron y compararon los siguientes modelos:

- Logistic Regression (Multinomial)
- Random Forest
- XGBoost (Optimizado con GridSearchCV)

La métrica principal utilizada para evaluación fue la **accuracy**, junto con matrices de confusión y reportes de clasificación por clase.

## 🚀 Resultados

- El modelo con mejor rendimiento fue **XGBoost**, alcanzando una precisión superior al 90%.
- Se evidenció que características como el IMC, la frecuencia de actividad física y el consumo de comida rápida son variables altamente predictivas.

## 📌 Conclusiones

- El enfoque multiclase es efectivo para este tipo de problema, especialmente utilizando modelos como XGBoost con buen tuning.
- Es crucial un buen preprocesamiento y selección de variables para lograr modelos robustos en contextos de salud pública.

## 💡 Próximos pasos

- Implementar validación cruzada estratificada
- Analizar la importancia de variables en modelos de árbol
- Desplegar el modelo en una API REST para inferencia remota
- Explorar fairness metrics para evaluar posibles sesgos en el modelo

## 📬 Contacto

Marcelo Vidal  
[LinkedIn](https://www.linkedin.com/in/marcelo-vidal-bravo)  
