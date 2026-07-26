# Alejandro Belda Fernandez — Portfolio

> [View this portfolio in English](https://github.com/AlejandroBeldaFernandez/AlejandroBeldaFernandez/blob/main/README.md)

---

## Sobre mi

Graduado en Informatica por la Universidad de Murcia con Master en Inteligencia Artificial. Durante un año trabaje como investigador (PDI) gestionando datasets biologicos complejos, administrando infraestructura de servidores Linux y colaborando en entornos de investigacion academica. Esta experiencia me dio una base solida en calidad del dato, rigor metodologico y trabajo con datos reales y ruidosos. Actualmente estoy en transicion hacia roles en la industria como Data Scientist o Data Analyst.

Disfruto del pipeline completo: entender el problema de negocio, limpiar y transformar datos desordenados, explorarlos con las preguntas correctas, construir modelos que funcionen en contexto y comunicar los resultados con claridad. Me importa la evaluacion honesta, las decisiones documentadas y las conclusiones que los perfiles no tecnicos puedan llevar a la practica.

**Idiomas:** Español (nativo) · Ingles (B2)

**Contacto:** alejandrobeldafernandez@gmail.com

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alejandro-belda-fern%C3%A1ndez-0677903b0/)

---

## Habilidades

### Machine Learning

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%23113254.svg?style=for-the-badge&logo=Seaborn&logoColor=white)

### MLOps y Despliegue

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![MLflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=mlflow&logoColor=blue)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Prefect](https://img.shields.io/badge/Prefect-ffffff?style=for-the-badge&logo=prefect&logoColor=20144d)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
### Bases de datos y herramientas

![SQL](https://img.shields.io/badge/sql-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
![Herramientas BI](https://img.shields.io/badge/BI%20Tools-FF6B35?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Hojas de calculo](https://img.shields.io/badge/Spreadsheets-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---

## Open source

### calm-data-generator

Libreria Python para generacion de datos sinteticos, desarrollada durante mi etapa como investigador. Publicada en PyPI y mantenida de forma independiente. Disenada para generar datasets tabulares realistas para desarrollo, pruebas y prototipado.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Calm-Data-Generator)

---

## Proyectos

---

### 01 — Predicción heridos accidente de trafico en Madrid

**Tipo:** Clasificacion

**Stack:** Python · pandas · scikit-learn · CatBoost · Optuna · SHAP

**Dataset:** Datos abiertos del Ayuntamiento de Madrid (2019–2023)

Predice si un accidente de trafico en Madrid va a resultar en al menos un herido, usando informacion disponible en el momento en que se registra el incidente. El proyecto cubre la agregacion de personas por accidente, feature engineering, tres modelos con ajuste de hiperparametros mediante Optuna, explicabilidad con SHAP y recomendaciones accionables para la asignacion de recursos de emergencia.

**Mejor modelo (CatBoost):** ROC AUC 0.873 · Balanced Accuracy 0.801 · Macro F1 0.73

**Que significa esto en la practica?**
De cada 10 accidentes que el modelo predice como con heridos, aproximadamente 8 o 9 son correctos. Tambien identifica correctamente la mayoria de accidentes sin heridos, evitando el despacho innecesario de recursos. Los errores restantes son en su mayoria falsas alarmas en lugar de heridos no detectados, que en un contexto de emergencias es el tipo de error menos grave.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/madrid-traffic-accidents)

---

### 02 — Predicción precio de la vivienda en Madrid

Tipo: Regresión

Stack: Python · pandas · scikit-learn · XGBoost · Optuna · SHAP

Dataset: Kaggle — Anuncios de propiedades residenciales en Madrid

Predice el precio de venta de propiedades residenciales en Madrid a partir de sus características físicas y ubicación. El proyecto incluye limpieza de datos, ingeniería de características, TargetEncoder para la codificación del distrito, tres modelos con tuning mediante Optuna, intervalos de confianza via bootstrap y validación cruzada, y explicabilidad con SHAP.

Mejor modelo (XGBoost): RMSE 69.568 € · R² 0.897 · MAPE 15.27%

¿Qué significa esto en la práctica?
De media, el precio predicho por el modelo se encuentra dentro del 15% del precio real. Para una propiedad de 200.000 €, el error esperado es de aproximadamente 30.000 €. La superficie construida y el distrito son los factores dominantes — y se amplifican mutuamente: un piso grande en Chamberí vale desproporcionadamente más que uno igual de grande en Vallecas. El modelo es más fiable para propiedades estándar en distritos bien representados, y menos fiable para propiedades atípicas o de lujo en los extremos de la distribución.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/madrid-real-estate-prediction.git)

---

### 03 — Clustering de perfiles de clientes
Tipo: Clustering No Supervisado

Stack: Python · pandas · scikit-learn · umap-learn

Dataset: Kaggle — Customer Personality Analysis

Segmenta clientes en 3 perfiles diferenciados a partir de datos demograficos, de gasto y de respuesta a campanas. El proyecto incluye deteccion de outliers con Isolation Forest, feature engineering, One-Hot Encoding, RobustScaler, reduccion de dimensionalidad con PCA, K-Means con seleccion de K por codo y silueta, visualizacion con UMAP y recomendaciones de negocio accionables por segmento.

Modelo final (K-Means K=3 + PCA): Silhouette Score 0.24 · 3 segmentos identificados

Que significa esto en la practica? Los clientes Premium (ingresos altos, sin hijos) gastan €1.274 de media y responden a campanas sin necesidad de descuentos. Los Cazadores de Ofertas (ingresos medios, ~1 hijo) compran 3.4 veces mas cuando hay promociones disponibles — ahi es donde el presupuesto en descuentos tiene mayor ROI. Los Escaparatistas (ingresos mas bajos, mas hijos) visitan la web 6.4 veces al mes pero gastan solo €80 — alta intencion, barrera economica. Aplicar la misma campana a los tres grupos simultaneamente es la peor asignacion posible del presupuesto de marketing.


[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Customer-Personality-Analysis.git)

---
### 04 — MLOPS Prediccion de fuga de clientes

Tipo: Pipeline MLOps · Clasificación Binaria

Stack: Python · scikit-learn · Optuna · MLflow · Prefect · FastAPI · Evidently AI · PostgreSQL · Grafana · Docker · Terraform · Streamlit

Dataset: Kaggle — IBM Telco Customer Churn

Pipeline MLOps de extremo a extremo que cubre el ciclo de vida completo en produccion: validacion de datos, ingenieria de features, optimizacion de hiperparametros con Optuna (150 trials, validacion cruzada de 5 folds), seguimiento de experimentos con MLflow, orquestacion con Prefect, monitorizacion de drift con Evidently AI, reentrenamiento automatico, versionado de modelos con promocion a @champion, API REST con FastAPI y demo interactiva desplegada en HuggingFace Spaces.

Modelo final (Random Forest + Optuna): ROC-AUC 0.84 · Balanced Accuracy 0.76 · Recall (churn) 0.76

Que significa esto en la practica? Captar un nuevo cliente de telecomunicaciones cuesta entre 5 y 7 veces mas que retener a uno existente. El modelo identifica correctamente el 76% de los clientes que van a cancelar — antes de que lo hagan — dandole al equipo de retencion tiempo suficiente para actuar. Pero la infraestructura MLOps es el valor real del proyecto: el pipeline monitoriza los datos entrantes en busca de cambios en la distribucion y reentrena automaticamente cuando mas del 40% de las variables muestran drift. Un modelo nuevo solo reemplaza al actual si lo supera en ROC-AUC. El resultado es un sistema que se mantiene alineado con el comportamiento actual de los clientes sin ninguna intervencion manual.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/MLOPS-Telco-Customer-Churn-Prediction.git)

---

### 05 — Predicion de Series Temporales de ventas de tiendas

Tipo: Prediccion de Series Temporales · Regresion de Datos de Panel

Stack: Python · pandas · statsmodels · linearmodels · scikit-learn · LightGBM · XGBoost · Optuna · SHAP · Plotly

Dataset: Kaggle — Corporación Favorita Store Sales (Ecuador)

Proyecto de prevision de principio a fin sobre un panel minorista de 3 millones de filas (1.782 series tienda × familia de producto durante 4,5 años). Abarca analisis exploratorio, diagnostico clasico de series temporales (descomposicion aditiva, ACF/PACF, test de estacionariedad ADF), un baseline econometrico interpretable (PanelOLS con efectos fijos de entidad), ingenieria de variables sin fugas (lags, medias moviles desplazadas, calendario), un benchmark naive y modelos globales de gradient boosting (LightGBM y XGBoost) ajustados con Optuna sobre una validacion cruzada temporal personalizada para datos de panel. Comportamiento del modelo explicado con SHAP.

Modelo final (XGBoost + Optuna): RMSLE 0.381 · R² 0.977 · ~28% mejor que el baseline naive. LightGBM se eligio para produccion: precision casi identica y mas rapido de reentrenar.

Que significa esto en la practica? Una cadena minorista pierde dinero de dos formas: roturas de stock (ventas perdidas) y exceso de inventario (desperdicio, sobre todo en perecederos). Este modelo predice la demanda diaria de cada combinacion tienda–familia, permitiendo una asignacion de inventario mas inteligente. Pero el verdadero valor esta en la explicabilidad: las predicciones se explican sobre todo por la inercia reciente de ventas (media de 7 dias + dia anterior), mientras que el precio del petroleo y los festivos apenas importan una vez conocido el historial reciente. La unica palanca de alto impacto que la empresa realmente controla son las promociones, asi que el modelo funciona ademas como simulador de escenarios, estimando el incremento de ventas de una promocion antes de gastar un solo dolar.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Store-Sales.git)

---

### 06 — Analisis de Ventas de Cafeteria
Tipo: Analisis Exploratorio de Datos · Business Intelligence
Stack: PostgreSQL · Google Sheets · Metabase · Google Slides
Dataset: Maven Analytics — Coffee Shop Sales (Nueva York)
Proyecto de analisis de ventas end-to-end de Maven Roasters, una cadena de cafeterias ficticia con tres locales en Nueva York (Astoria, Hell's Kitchen, Lower Manhattan). Cubre limpieza de datos en SQL (conversion de tipos, normalizacion de decimales), 12 preguntas de negocio respondidas integramente en SQL (agregaciones, funciones de fecha, window functions, analisis de Pareto), un dashboard interactivo en Metabase, un reporte estructurado en Google Sheets y una presentacion de data storytelling en Google Slides.
Hallazgos clave: el revenue casi se duplica de enero a junio en los tres locales. Coffee y Tea generan el 66% del revenue total. La mañana concentra mas del 54% de todas las transacciones. Solo 11 tipos de producto generan el 80% del revenue (regla de Pareto). Los tres locales tienen un rendimiento muy equilibrado, lo que sugiere una gestion homogenea de la cadena.
Que significa esto en la practica? Un propietario de cafeteria puede usar este analisis para decidir que productos potenciar o retirar, optimizar los turnos de personal segun las franjas de mayor actividad y diseñar campañas de marketing en los meses mas debiles. El codigo SQL esta completamente documentado y es reutilizable para cualquier dataset similar de retail o restauracion.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Coffee-Shop-Sales.git)

---

### Extra — Cloud: Inferencia ML Serverless en AWS

Tipo: Despliegue Cloud · Arquitectura Serverless

Stack: AWS S3 · AWS Lambda · API Gateway · IAM · Python · scikit-learn

Dataset: Iris (usado como caso de estudio minimo — el foco de este proyecto es la arquitectura cloud, no el modelo)

Proyecto pequeño y autocontenido construido para demostrar conocimiento practico de AWS: un modelo de clasificacion servido a traves de un endpoint HTTP publico, sin servidor que administrar. El pipeline entrenado (StandardScaler + DecisionTreeClassifier) se almacena en S3, se carga bajo demanda por una funcion Lambda, y se expone mediante API Gateway.
*Mas proyectos proximamente.*
Que significa esto en la practica? Este proyecto no trata sobre el modelo — Iris es deliberadamente simple para que el foco se mantenga en la arquitectura. Demuestra el ciclo completo de despliegue serverless de extremo a extremo: empaquetado de dependencias para Lambda, configuracion de permisos IAM, gestion de cold starts, y exposicion de un modelo como API publica sin aprovisionar ningun servidor. El README documenta los problemas reales encontrados y resueltos por el camino (dependencias faltantes, limites de tamaño del paquete de Lambda, errores de sistema de archivos de solo lectura, timeouts por cold start), ya que depurar un despliegue es tan representativo de la habilidad como el despliegue en si.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/AWS-Iris-Prediction.git)

---

### Extra — Cloud: Inferencia ML Serverless en Azure

Tipo: Despliegue Cloud · Arquitectura Serverless

Stack: Azure Blob Storage · Azure Functions · Python · scikit-learn

Dataset: Diabetes (scikit-learn, usado como caso de estudio minimo — el foco de este proyecto es la arquitectura cloud, no el modelo)

Proyecto pequeño y autocontenido construido para demostrar conocimiento practico de Azure: un modelo de regresion servido a traves de un endpoint HTTP publico, sin servidor que administrar. El pipeline entrenado (StandardScaler + RandomForestRegressor) se almacena en Blob Storage, se carga bajo demanda por una Azure Function, y se expone mediante su trigger HTTP nativo, sin necesidad de un servicio adicional equivalente a API Gateway.

Que significa esto en la practica? Este proyecto no trata sobre el modelo — el dataset de diabetes es deliberadamente simple para que el foco se mantenga en la arquitectura. Demuestra el ciclo completo de despliegue serverless de extremo a extremo: creacion de recursos mediante la Azure CLI (el portal web resulto insuficiente por restricciones de plan con la suscripcion gratuita), registro de proveedores de recursos, gestion de restricciones de region, configuracion de permisos de npm para las Core Tools, y exposicion de un modelo como API publica sin aprovisionar ningun servidor. El README documenta los problemas reales encontrados y resueltos por el camino, ya que depurar un despliegue es tan representativo de la habilidad como el despliegue en si.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Azure-Diabetes-Prediction.git)

---


*Repositorios en progreso — publicacion progresiva a lo largo de 2026.*
