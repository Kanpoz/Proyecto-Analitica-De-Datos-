# Predicción de Entregas Tardías en Órdenes de Producción Manufacturera

## Descripción del Proyecto

Este repositorio contiene el desarrollo completo del proyecto de Analítica de Datos Aplicada a la Ingeniería Industrial, enfocado en la predicción del riesgo de entrega tardía de órdenes de producción en una planta manufacturera.

El proyecto fue desarrollado en dos etapas académicas (Segundo y Tercer Corte), siguiendo una metodología progresiva donde inicialmente se construyó una línea base de modelos predictivos y posteriormente se optimizó el desempeño mediante técnicas avanzadas de Machine Learning.

El objetivo principal es identificar de manera anticipada aquellas órdenes de producción con alta probabilidad de incumplir su fecha comprometida de entrega, permitiendo a la organización tomar acciones preventivas y mejorar sus indicadores operativos.

La variable objetivo utilizada durante todo el proyecto fue:

- **entrega_tardia**
  - **1:** La orden fue entregada tarde.
  - **0:** La orden fue entregada a tiempo.

Este problema corresponde a una tarea de clasificación binaria supervisada.

---

## Estructura del Repositorio

### Segundo Corte

#### Archivo: `Cuadernillo_FINAL.ipynb`

Corresponde al cuadernillo final desarrollado para el segundo corte del proyecto.

En este notebook se encuentran las etapas iniciales del proceso analítico:

- Comprensión del problema de negocio.
- Exploración y entendimiento de los datos.
- Preprocesamiento de variables.
- Análisis Exploratorio de Datos (EDA).
- Ingeniería de características.
- Construcción de modelos base:
  - Regresión Logística
  - Perceptrón
  - Adaline
- Evaluación mediante métricas de clasificación.
- Selección del mejor modelo del segundo corte.

El enfoque principal de esta fase fue demostrar cómo una adecuada preparación de los datos y una correcta ingeniería de variables pueden mejorar significativamente el desempeño de modelos relativamente simples.

---

### Tercer Corte

#### Archivo: `proyecto_modelos_final.ipynb`

Corresponde al cuadernillo final desarrollado para el tercer corte del proyecto.

Este notebook toma como punto de partida los resultados obtenidos en el segundo corte y desarrolla una fase de optimización, validación y comparación avanzada de modelos.

Entre las técnicas implementadas se incluyen:

#### Modelos Supervisados

- Regresión Logística
- Perceptrón
- Adaline
- Naive Bayes
- Support Vector Machines (SVM)
- Árboles de Decisión
- K-Nearest Neighbors (KNN)

#### Optimización y Validación

- Regularización L1 y L2.
- Holdout Validation.
- K-Fold Cross Validation.
- Validación Cruzada Estratificada.
- Grid Search para ajuste de hiperparámetros.
- Curvas ROC y AUC.

#### Balanceo de Clases

- Oversampling.
- Undersampling.

#### Reducción de Dimensionalidad

- PCA (Principal Component Analysis).
- LDA (Linear Discriminant Analysis).

#### Métodos de Ensamble

- Bagging.
- Random Forest.
- Gradient Boosting.
- Otros métodos de Boosting evaluados.

#### Modelo Final

Finalmente se realiza una comparación integral de todos los modelos desarrollados para seleccionar la solución con mejor equilibrio entre:

- Recall.
- Precision.
- F1-Score.
- Balanced Accuracy.
- Capacidad de generalización.
- Utilidad para el negocio.

---

## Tecnologías Utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn

---

## Flujo General del Proyecto

```text
Comprensión del problema
          ↓
Carga y limpieza de datos
          ↓
Análisis Exploratorio (EDA)
          ↓
Ingeniería de características
          ↓
Modelos base (Segundo Corte)
          ↓
Optimización y nuevas técnicas
          ↓
Validación y ajuste
          ↓
Métodos de ensamble
          ↓
Selección del modelo final
```

---

## Archivos Principales

| Archivo | Descripción |
|----------|-------------|
| `Cuadernillo_FINAL.ipynb` | Cuadernillo final correspondiente al proyecto del Segundo Corte. |
| `proyecto_modelos_final.ipynb` | Cuadernillo final correspondiente al proyecto del Tercer Corte. |
| `README.md` | Documentación general del proyecto. |

---

## Objetivo Final

Desarrollar un sistema predictivo capaz de identificar órdenes de producción con riesgo de entrega tardía, utilizando técnicas de analítica de datos y aprendizaje automático para apoyar la toma de decisiones en entornos manufactureros.

---

## Autor(es)

Proyecto desarrollado para la asignatura **Analítica de Datos Aplicada a la Ingeniería Industrial**.

**Integrantes del equipo: Corte 2**

- Juan J. Campos
- David Orozco
- David Peralta
- Samuel Robayo

**Integrantes del equipo: Corte 3**

- Juan J. Campos
- David Orozco
- Daniel F. Esquinas
- Juan F. Jaime
