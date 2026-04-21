**Alejandro Belda Fernandez — Data Science Portfolio**

---

### About me

Computer Science graduate from the University of Murcia with a Master's degree in Artificial Intelligence. I spent one year working as a researcher (PDI) handling complex biological datasets, managing Linux server infrastructure, and collaborating in academic research environments. This gave me a strong foundation in data quality, methodological rigour, and working with noisy real-world data. I am now transitioning into industry roles in data science and data analysis.

I enjoy the full pipeline: understanding the business problem, cleaning and transforming messy data, exploring it with the right questions, building models that actually work in context, and communicating results clearly. I care about honest evaluation, documented decisions, and conclusions that non-technical stakeholders can act on.

**Looking for:** Junior Data Scientist or Data Analyst roles in Spain or remote.

**Languages:** Spanish (native) · English (B2)

**Contact:** alejandrobeldafernandez@gmail.com

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alejandro-belda-fern%C3%A1ndez-0677903b0/)

### Skills

**Data Science & Machine Learning**
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%23113254.svg?style=for-the-badge&logo=Seaborn&logoColor=white)


**MLOps & Deployment**
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![MLflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=mlflow&logoColor=blue)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Prefect](https://img.shields.io/badge/Prefect-ffffff?style=for-the-badge&logo=prefect&logoColor=20144d)

**Databases & Tools**
![SQL](https://img.shields.io/badge/sql-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)

---

### Open source

**calm-data-generator**
Python library for synthetic data generation, developed during my time as a researcher. Published on PyPI and maintained independently. Designed to generate realistic tabular datasets for development, testing, and prototyping.
PyPI · GitHub

View repository: https://github.com/AlejandroBeldaFernandez/Calm-Data-Generator.git

---

### Portfolio projects
---

**01 — Madrid Traffic Accident Injury Prediction**

Type: Classification

Stack: Python · pandas · scikit-learn · CatBoost · Optuna · SHAP

Dataset: Open data from the Madrid City Council (2019–2023)

Predicts whether a traffic accident in Madrid will result in at least one injured person, using information available at the time the accident is reported. The project covers person-to-accident aggregation, feature engineering, three models with Optuna tuning, SHAP explainability, and actionable recommendations for emergency resource allocation.

Best model (CatBoost): ROC AUC 0.873 · Balanced Accuracy 0.801 · Macro F1 0.73

What does this mean in practice?
Out of every 10 accidents the model predicts as involving injuries, roughly 8 to 9 are correct. It also correctly identifies most accidents where no one is hurt, which avoids unnecessary resource dispatch. The remaining errors are mostly false alarms rather than missed injuries, which in an emergency context is the safer type of mistake.

View repository: https://github.com/AlejandroBeldaFernandez/madrid-traffic-accidents

---
*More projects coming soon.*

*Repositories in progress — publishing progressively throughout 2026.*
