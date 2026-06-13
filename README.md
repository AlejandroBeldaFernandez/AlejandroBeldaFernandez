**Alejandro Belda Fernández — Portfolio**

> [Portfolio en Español](https://github.com/AlejandroBeldaFernandez/AlejandroBeldaFernandez/blob/main/README_ES.md)
---

## About me

Computer Science graduate from the University of Murcia with a Master's degree in Artificial Intelligence. I spent one year working as a researcher (PDI) handling complex biological datasets, managing Linux server infrastructure, and collaborating in academic research environments. This gave me a strong foundation in data quality, methodological rigour, and working with noisy real-world data. I am now transitioning into industry roles in data science and data analysis.

I enjoy the full pipeline: understanding the business problem, cleaning and transforming messy data, exploring it with the right questions, building models that actually work in context, and communicating results clearly. I care about honest evaluation, documented decisions, and conclusions that non-technical stakeholders can act on.

**Languages:** Spanish (native) · English (B2)

**Contact:** alejandrobeldafernandez@gmail.com

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alejandro-belda-fern%C3%A1ndez-0677903b0/)

## Skills

### Machine Learning
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-%23113254.svg?style=for-the-badge&logo=Seaborn&logoColor=white)


### MLOps & Deployment
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![MLflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=mlflow&logoColor=blue)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Prefect](https://img.shields.io/badge/Prefect-ffffff?style=for-the-badge&logo=prefect&logoColor=20144d)

### Databases & Tools
![SQL](https://img.shields.io/badge/sql-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
![BI Tools](https://img.shields.io/badge/BI%20Tools-FF6B35?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Spreadsheets](https://img.shields.io/badge/Spreadsheets-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---

## Open source

### calm-data-generator
Python library for synthetic data generation, developed during my time as a researcher. Published on PyPI and maintained independently. Designed to generate realistic tabular datasets for development, testing, and prototyping.
PyPI · GitHub

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Calm-Data-Generator)

---

## Portfolio projects
---

### 01 — Madrid Traffic Accident Injury Prediction

Type: Classification

Stack: Python · pandas · scikit-learn · CatBoost · Optuna · SHAP

Dataset: Open data from the Madrid City Council (2019–2023)

Predicts whether a traffic accident in Madrid will result in at least one injured person, using information available at the time the accident is reported. The project covers person-to-accident aggregation, feature engineering, three models with Optuna tuning, SHAP explainability, and actionable recommendations for emergency resource allocation.

Best model (CatBoost): ROC AUC 0.873 · Balanced Accuracy 0.801 · Macro F1 0.73

What does this mean in practice?
Out of every 10 accidents the model predicts as involving injuries, roughly 8 to 9 are correct. It also correctly identifies most accidents where no one is hurt, which avoids unnecessary resource dispatch. The remaining errors are mostly false alarms rather than missed injuries, which in an emergency context is the safer type of mistake.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/madrid-traffic-accidents)

---
### 02 —  Madrid Real Estate Price Prediction
Type: Regression

Stack: Python · pandas · scikit-learn · XGBoost · Optuna · SHAP

Dataset: Kaggle — Madrid residential property listings

Predicts the sale price of residential properties in Madrid using physical characteristics and location. The project covers data cleaning, feature engineering, TargetEncoder for district encoding, three models with Optuna tuning, confidence intervals via bootstrap and cross-validation, and SHAP explainability.

Best model (XGBoost): RMSE 69.568 € · R² 0.897 · MAPE 15.27%

What does this mean in practice?
On average, the model's predicted price is within 15% of the actual sale price. For a property worth 200.000 €, the expected error is roughly 30.000 €. Built area and district are the dominant drivers — and they amplify each other: a large flat in Chamberí is worth disproportionately more than an equally large flat in Vallecas. The model is most reliable for standard properties in established districts, and less reliable for atypical or luxury properties at the extremes of the distribution.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/madrid-real-estate-prediction.git)
---

### 03 — Customer Personality Analysis
Type: Unsupervised Clustering

Stack: Python · pandas · scikit-learn · umap-learn

Dataset: Kaggle — Customer Personality Analysis (2,240 customers, 29 features)

Segments customers into 3 distinct profiles based on demographic, spending, and campaign response data. The project covers outlier detection with Isolation Forest, feature engineering, One-Hot Encoding, RobustScaler, PCA dimensionality reduction, K-Means with Elbow and Silhouette selection, UMAP visualisation, and actionable business recommendations per segment.

Final model (K-Means K=3 + PCA): Silhouette Score 0.24 · 3 segments identified

What does this mean in practice? Premium customers (high income, no children) spend €1,274 on average and respond to campaigns without needing discounts. Deal Seekers (medium income, ~1 child) buy 3.4x more when promotions are available — that is where discount budgets have the highest ROI. Window Shoppers (lowest income, most children) visit the web 6.4 times per month but spend only €80 — high intent, budget barrier. Applying the same campaign to all three simultaneously is the worst possible allocation of marketing spend.


[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Customer-Personality-Analysis.git)
---
*More projects coming soon.*

*Repositories in progress — publishing progressively throughout 2026.*
