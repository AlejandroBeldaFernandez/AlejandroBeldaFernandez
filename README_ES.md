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

### Bases de datos y herramientas

![SQL](https://img.shields.io/badge/sql-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)

---

## Open source

### calm-data-generator

Libreria Python para generacion de datos sinteticos, desarrollada durante mi etapa como investigador. Publicada en PyPI y mantenida de forma independiente. Disenada para generar datasets tabulares realistas para desarrollo, pruebas y prototipado.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Calm-Data-Generator)

---

## Proyectos

---

### 01 — Madrid Traffic Accident Injury Prediction

**Tipo:** Clasificacion

**Stack:** Python · pandas · scikit-learn · CatBoost · Optuna · SHAP

**Dataset:** Datos abiertos del Ayuntamiento de Madrid (2019–2023)

Predice si un accidente de trafico en Madrid va a resultar en al menos un herido, usando informacion disponible en el momento en que se registra el incidente. El proyecto cubre la agregacion de personas por accidente, feature engineering, tres modelos con ajuste de hiperparametros mediante Optuna, explicabilidad con SHAP y recomendaciones accionables para la asignacion de recursos de emergencia.

**Mejor modelo (CatBoost):** ROC AUC 0.873 · Balanced Accuracy 0.801 · Macro F1 0.73

**Que significa esto en la practica?**
De cada 10 accidentes que el modelo predice como con heridos, aproximadamente 8 o 9 son correctos. Tambien identifica correctamente la mayoria de accidentes sin heridos, evitando el despacho innecesario de recursos. Los errores restantes son en su mayoria falsas alarmas en lugar de heridos no detectados, que en un contexto de emergencias es el tipo de error menos grave.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/madrid-traffic-accidents)

---

*Mas proyectos proximamente.*

*Repositorios en progreso — publicacion progresiva a lo largo de 2026.*
