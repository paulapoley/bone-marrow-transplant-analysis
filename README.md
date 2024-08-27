
## Título: Bone marrow transplant: children Data Set. Análisis Predictivo de Trasplante de Médula Ósea en Pacientes Pediátricos

Este repositorio contiene el proyecto realizado en la asignatura Análisis Avanzado de Datos Clínicos del grado de Ingeniería de la Salud. El proyecto explora un análisis de datos clínicos sobre trasplantes de médula ósea en pacientes pediátricos con enfermedades hematológicas malignas y no malignas. Utilizamos modelos de regresión logística y Random Forest para predecir la recaída post-trasplante en los pacientes.

## 1. Descripción

El trasplante de médula ósea es una intervención clave en el tratamiento de diversas enfermedades hematológicas, tanto malignas como no malignas, en pacientes pediátricos. Este análisis tiene como objetivo identificar factores de riesgo que pueden predecir la recaída post-trasplante, lo cual podría ayudar a mejorar los pronósticos y tratamientos clínicos. El modelo creado también pretende proporcionar una evaluación predictiva que ayude a los médicos a tomar decisiones informadas.

## 2. Características Principales

- **Modelos Utilizados**: 
  - Regresión Logística
  - Random Forest
- **Evaluación del Modelo**:
  - Curvas ROC y AUC (Área Bajo la Curva) para evaluar el rendimiento de los modelos.
  - Métricas como precisión, sensibilidad, especificidad y F1-score.
- **Técnicas de Preprocesamiento**:
  - Imputación de valores faltantes.
  - Normalización de variables continuas para mejorar la efectividad de los modelos.
  - Codificación de variables categóricas.

## 3. Contenidos del Repositorio

El repositorio está organizado en cuatro carpetas principales: /data, /src, /docs, y un archivo adicional. Cada uno de estos elementos contiene diferentes componentes relevantes para el proyecto.

### 3.1. Conjunto de Datos (data)
La carpeta /data incluye los datos utilizados en el análisis:
- **Datos de Médula Ósea:** [datosMedulaOsea.csv](data/datosMedulaOsea.csv) - Conjunto de datos utilizado en el análisis.

### 3.2. Código fuente (src)
La carpeta /src contiene los scripts y proyectos relacionados con el análisis:

- **Código en RMarkdown:** [proyectofinal.Rmd](src/proyectofinal.Rmd) - Archivo en RMarkdown que implementa el análisis completo.
- **Notebook:** [proyectofinal.nb](src/proyectofinal.nb) - Notebook generado durante el análisis.
  
### 3.3. Documentos (docs)
La carpeta /docs incluye documentos y gráficos generados:

-**Presentación del Trabajo:** [Bone-marrow-transplant.pdf](src/Bone-marrow-transplant.pdf) - PDF con la presentación del trabajo.

### 3.4. Archivo Adicional
Además, el repositorio incluye un archivo relevante:

-**Descripción del Proyecto:** [README.md](README.md) - Archivo que ofrece una explicación general del proyecto y sus componentes.

## 4. Dataset

El conjunto de datos utilizado en este análisis proviene del repositorio de [UCI Machine Learning](https://archive.ics.uci.edu/ml/datasets/Bone+marrow+transplant%3A+children), que contiene información clínica sobre niños sometidos a trasplante de médula ósea. Las variables incluyen factores demográficos, clínicos y genéticos, así como el resultado del trasplante.

## 5. Futuras Mejoras

- Implementar otros modelos de machine learning, como SVM y Gradient Boosting, para comparar los resultados y mejorar la precisión del modelo.
- Realizar validación cruzada para refinar los resultados y evitar el sobreajuste.
- Incluir análisis adicionales de la relación entre los factores genéticos y el éxito del trasplante.
- Explorar técnicas más avanzadas de imputación de valores faltantes y selección de características.


## Referencias

[UCI Machine Learning Repository: Bone marrow transplant: children](https://archive.ics.uci.edu/ml/datasets/Bone+marrow+transplant%3A+children)
Marek Sikora (marek.sikora '@' polsl.pl), Å•ukaszWrÃ³bel (lukasz.wrobel '@' polsl.pl), Adam GudyÅ› 
(adam.gudys '@' polsl.pl)
Faculty of Automatic Control, Electronics and Computer Science, Silesian University of Technology, 44-100 
Gliwice, Poland
