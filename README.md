# Alejandro Belda Fernández — Portfolio

> [Portfolio en Español](https://github.com/AlejandroBeldaFernandez/AlejandroBeldaFernandez/blob/main/README_ES.md)

---

## About Me

Computer Science graduate from the University of Murcia with a Master's degree in Artificial Intelligence. I spent one year working as a researcher (PDI), handling complex biological datasets, managing Linux server infrastructure, and collaborating in academic research environments. This gave me a strong foundation in data quality, methodological rigour, and working with noisy real-world data. I am now transitioning into industry roles in data science and data analysis.

I enjoy the full pipeline: understanding the business problem, cleaning and transforming messy data, exploring it with the right questions, building models that actually work in context, and communicating results clearly. I care about honest evaluation, documented decisions, and conclusions that non-technical stakeholders can act on.

**Languages:** Spanish (native) · English (B2)

**Contact:** alejandrobeldafernandez@gmail.com

[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alejandro-belda-fern%C3%A1ndez-0677903b0/)

---

## Contents

- [Skills](#skills)
- [Top Projects](#top-projects)
- [Open Source](#open-source)
- [Full Project List](#full-project-list)

---

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
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)

### Databases & Tools
![SQL](https://img.shields.io/badge/sql-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
![BI Tools](https://img.shields.io/badge/BI%20Tools-FF6B35?style=for-the-badge&logo=chartdotjs&logoColor=white)
![Spreadsheets](https://img.shields.io/badge/Spreadsheets-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

---

## Top Projects

A quick way into the portfolio for anyone short on time — the five that best represent range: an end-to-end automated pipeline, a comparative recommender system, a full production MLOps stack, a pure-SQL business analysis, and NLP combining classification with retrieval.

### Automated News Report Generator
Scraping, orchestration, local LLM summarization and self-hosted deployment, verified against the real service at every step rather than its documentation.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Automated-News-Report)
[![Gradio Demo](https://img.shields.io/badge/Live%20Demo-Gradio-FF7C00.svg?style=for-the-badge&logo=gradio&logoColor=white)](https://alex-server.taile13699.ts.net/)

### Movie Recommendation System
Three recommender approaches compared and explained rather than blended into one black-box ranking.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Movies_Recommendations)
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue?style=for-the-badge)](https://huggingface.co/spaces/Alessandrou24/movie__Recommender)

### MLOps Telco Customer Churn
Full production lifecycle: tracking, orchestration, drift monitoring, automated retraining and a deployed API.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/MLOPS-Telco-Customer-Churn-Prediction.git)
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue?style=for-the-badge)](https://huggingface.co/spaces/Alessandrou24/telco-churn-predictor)

### Coffee Shop Sales Analysis
12 business questions answered entirely in SQL, from cleaning to a dashboard and a data storytelling presentation.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Coffee-Shop-Sales.git)

### Amazon Reviews Spanish
Sentiment classification and a RAG system on the same corpus, with a formal A/B comparison between a baseline and a fine-tuned transformer.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Amazon-Reviews-Spanish.git)
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue?style=for-the-badge)](https://huggingface.co/spaces/Alessandrou24/Amazon-Reviews-Spanish)

---

## Open Source

### calm-data-generator
Python library for synthetic tabular data generation, developed during my time as a researcher and published independently on PyPI. It wraps several generation backends (including synthcity) behind a single unified interface, adds a concept drift simulation layer for testing how downstream models degrade under distribution shift, and produces an automated data quality report for every generated dataset — distribution comparisons against the source data, correlation preservation, and basic privacy risk indicators.

Built to solve a real problem in the research group: generating realistic tabular data for development and testing without exposing sensitive source data, while still being able to simulate the kind of drift that production models actually face over time.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Calm-Data-Generator)

---

## Full Project List

### 01 — Madrid Traffic Accident Injury Prediction

**Type:** Classification
**Stack:** Python · pandas · scikit-learn · CatBoost · Optuna · SHAP
**Dataset:** Open data from the Madrid City Council (2019–2023)

Predicts whether a traffic accident in Madrid will result in at least one injured person, using information available at the time the accident is reported. The project covers person-to-accident aggregation, feature engineering, three models with Optuna tuning, SHAP explainability, and actionable recommendations for emergency resource allocation.

**Results (CatBoost):** ROC AUC 0.873 · Balanced Accuracy 0.801 · Macro F1 0.73

**In practice:** out of every 10 accidents the model predicts as involving injuries, roughly 8 to 9 are correct. It also correctly identifies most accidents where no one is hurt, which avoids unnecessary resource dispatch. The remaining errors are mostly false alarms rather than missed injuries, which in an emergency context is the safer type of mistake.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/madrid-traffic-accidents)

---

### 02 — Madrid Real Estate Price Prediction

**Type:** Regression
**Stack:** Python · pandas · scikit-learn · XGBoost · Optuna · SHAP
**Dataset:** Kaggle — Madrid residential property listings

Predicts the sale price of residential properties in Madrid using physical characteristics and location. The project covers data cleaning, feature engineering, TargetEncoder for district encoding, three models with Optuna tuning, confidence intervals via bootstrap and cross-validation, and SHAP explainability.

**Results (XGBoost):** RMSE €69,568 · R² 0.897 · MAPE 15.27%

**In practice:** on average, the model's predicted price is within 15% of the actual sale price. For a property worth €200,000, the expected error is roughly €30,000. Built area and district are the dominant drivers — and they amplify each other: a large flat in Chamberí is worth disproportionately more than an equally large flat in Vallecas. The model is most reliable for standard properties in established districts, and less reliable for atypical or luxury properties at the extremes of the distribution.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/madrid-real-estate-prediction.git)

---

### 03 — Customer Personality Analysis

**Type:** Unsupervised Clustering
**Stack:** Python · pandas · scikit-learn · umap-learn
**Dataset:** Kaggle — Customer Personality Analysis

Segments customers into 3 distinct profiles based on demographic, spending, and campaign response data. The project covers outlier detection with Isolation Forest, feature engineering, One-Hot Encoding, RobustScaler, PCA dimensionality reduction, K-Means with Elbow and Silhouette selection, UMAP visualisation, and actionable business recommendations per segment.

**Results (K-Means K=3 + PCA):** Silhouette Score 0.24 · 3 segments identified

**In practice:** Premium customers (high income, no children) spend €1,274 on average and respond to campaigns without needing discounts. Deal Seekers (medium income, ~1 child) buy 3.4x more when promotions are available — that is where discount budgets have the highest ROI. Window Shoppers (lowest income, most children) visit the web 6.4 times per month but spend only €80 — high intent, budget barrier. Applying the same campaign to all three simultaneously is the worst possible allocation of marketing spend.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Customer-Personality-Analysis.git)

---

### 04 — MLOps Telco Customer Churn

**Type:** MLOps Pipeline · Binary Classification
**Stack:** Python · scikit-learn · Optuna · MLflow · Prefect · FastAPI · Evidently AI · PostgreSQL · Grafana · Docker · Terraform · Streamlit
**Dataset:** Kaggle — IBM Telco Customer Churn

End-to-end MLOps pipeline covering the full production lifecycle: data validation, feature engineering, hyperparameter optimisation with Optuna (150 trials, 5-fold CV), experiment tracking with MLflow, orchestration with Prefect, drift monitoring with Evidently AI, automated retraining, model versioning with @champion promotion, a REST API with FastAPI, and an interactive demo deployed on Hugging Face Spaces.

**Results (Random Forest + Optuna):** ROC-AUC 0.84 · Balanced Accuracy 0.76 · Recall (churn) 0.76

**In practice:** acquiring a new telecom customer costs 5–7× more than retaining an existing one. The model correctly identifies 76% of customers who will cancel — before they do — giving the retention team enough time to act. But the MLOps infrastructure is the actual value here: the pipeline monitors incoming data for distribution shift and retrains automatically when more than 40% of features drift. A new model only replaces the current one if it outperforms it on ROC-AUC. The result is a self-maintaining system that stays aligned with current customer behaviour without any manual intervention.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/MLOPS-Telco-Customer-Churn-Prediction.git)
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue?style=for-the-badge)](https://huggingface.co/spaces/Alessandrou24/telco-churn-predictor)

---

### 05 — Store Sales Forecasting

**Type:** Time Series Forecasting · Panel Data Regression
**Stack:** Python · pandas · statsmodels · linearmodels · scikit-learn · LightGBM · XGBoost · Optuna · SHAP · Plotly
**Dataset:** Kaggle — Corporación Favorita Store Sales (Ecuador)

End-to-end forecasting project on a 3-million-row retail panel (1,782 store × product-family series over 4.5 years). Covers exploratory analysis, classical time series diagnostics (additive decomposition, ACF/PACF, ADF stationarity test), an interpretable econometric baseline (PanelOLS with entity fixed effects), leakage-safe feature engineering (lags, shifted rolling means, calendar features), a naive benchmark, and global gradient-boosting models (LightGBM & XGBoost) tuned with Optuna over a custom time-series cross-validation built for panel data. Model behaviour explained with SHAP.

**Results (XGBoost + Optuna):** RMSLE 0.381 · R² 0.977 · ~28% better than the naive baseline. LightGBM was chosen for production — near-identical accuracy, faster to retrain.

**In practice:** retailers lose money two ways: stockouts (lost sales) and overstock (waste, especially in perishables). This model forecasts daily demand for every store–product-family combination, enabling smarter inventory allocation. But the real insight comes from explainability: predictions are driven overwhelmingly by recent sales momentum (7-day average + previous day), while oil price and holidays barely matter once recent history is known. The one high-impact lever the business actually controls is promotions — so the model doubles as a scenario simulator, estimating the sales lift of a promotion before a single dollar is spent.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Store-Sales.git)

---

### 06 — Coffee Shop Sales Analysis

**Type:** Exploratory Data Analysis · Business Intelligence
**Stack:** PostgreSQL · Google Sheets · Metabase · Google Slides
**Dataset:** Maven Analytics — Coffee Shop Sales (NYC)

End-to-end sales analysis of Maven Roasters, a fictitious coffee shop chain operating across three NYC locations (Astoria, Hell's Kitchen, Lower Manhattan). Covers data cleaning in SQL (type casting, decimal normalisation), 12 business questions answered entirely in SQL (aggregations, date functions, window functions, Pareto analysis), an interactive dashboard built in Metabase, a structured report in Google Sheets, and a data storytelling presentation in Google Slides.

**Key findings:** revenue nearly doubled from January to June across all three locations. Coffee and Tea drive 66% of total revenue. Morning concentrates over 54% of all transactions. Only 11 product types generate 80% of revenue (Pareto rule). The three locations perform remarkably similarly, suggesting balanced chain management.

**In practice:** a coffee shop owner can use this analysis to decide which products to promote or cut, optimise staff shifts based on peak hours, and design targeted marketing campaigns for the weakest months. The SQL code is fully documented and reusable for any similar retail or F&B dataset.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Coffee-Shop-Sales.git)

---

### 07 — Amazon Reviews Spanish

**Type:** NLP · Deep Learning · Information Retrieval
**Stack:** Python · scikit-learn · PyTorch · Hugging Face Transformers · ChromaDB
**Dataset:** Amazon Reviews Multi — Spanish subset (208,899 reviews)

Two systems on the same corpus. A classifier labelling each review's sentiment as negative, neutral or positive, comparing a TF-IDF baseline selected from 144 configurations against a fine-tuned BETO transformer. And a RAG system that answers questions about the corpus in natural language, filtering by the classifier's own labels and grounding every answer in real reviews that it cites. The project also covers exploratory analysis with non-parametric testing and effect sizes, a formal A/B comparison (McNemar, bootstrap, inference timing, agreement analysis), and embedding visualisation with t-SNE.

**Classifier findings:** BETO reaches 0.765 macro F1 against 0.725 for the baseline, and the difference is solid — McNemar returns p = 1.3e-12 and the bootstrap interval excludes zero. It also costs 1,009 times more per prediction: 48 ms against 0.048 ms on the same CPU. On the distinction that matters commercially the model is strong: 0.85 and 0.88 F1 on negative and positive, with the sign inverted in only 1% of cases. The neutral class is the bottleneck, and three independent measurements in the exploratory analysis predicted exactly that, three stages before any model was trained.

**RAG findings:** asked what customers complain about in wireless products, the system returned fifteen reviews of which almost none discussed the product itself: sellers who do not reply, orders that never arrived, refunds that took weeks of messages. In that category, dissatisfaction is predominantly logistical rather than about the product itself — a conclusion with a clear owner, and one no aggregate metric can produce. The classifier can say 46% of those reviews are negative; only retrieval can say the complaints are about shipping.

**In practice:** the two systems are complementary: the classifier says how many customers are unhappy and where, retrieval says why and cites the customers who said it. The cost analysis is not academic, it decides the architecture: labelling the 208,899 reviews that feed the index takes 10 seconds with the baseline against 2.8 hours with BETO, so four points of macro F1 rarely justify a thousandfold increase in cost per prediction.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Amazon-Reviews-Spanish.git)
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue?style=for-the-badge)](https://huggingface.co/spaces/Alessandrou24/Amazon-Reviews-Spanish)

---

### 08 — Movie Recommendation System

**Type:** Recommender Systems · Collaborative Filtering · Matrix Factorization
**Stack:** Python · pandas · scikit-learn · Surprise (SVD) · Gradio
**Dataset:** The Movies Dataset (Kaggle, TMDB + MovieLens) — 7,818 movies, 671 users, ~100,000 ratings

Three independent recommender systems compared on the same catalog: content-based filtering from a movie's own metadata (genre, cast, director, keywords, studio, franchise), item-based collaborative filtering from co-rating behaviour alone, and SVD matrix factorization on those same ratings. All three are evaluated with Precision@5/Recall@5 on a matched held-out split, and the trade-offs between them — cold start, coverage, what "similar" even means — are documented rather than blended away behind a single ranked list.

**Findings:** collaborative filtering wins Precision@5/Recall@5 by 7 to 8 times over content-based and SVD (42.41%/15.16% against 5.93%/1.87% and 6.05%/1.57%), but the gap is explained rather than just reported — it reflects that the metric is exactly the task collaborative filtering was built for (predicting a held-out rating), not a verdict on which model a real user would act on. The real cost of that strength is coverage: the 5-rating cutoff that keeps collaborative similarities trustworthy also drops the catalog from 7,818 movies to 3,357 (43%), so 57% of it can only be recommended through content-based filtering. Two of the three models solve their hardest cold-start case (a new user with no history) — content-based filtering never has that problem to begin with — and none of the three can recommend a brand-new movie with zero ratings, a structural gap rather than something a parameter fixes.

**In practice:** the three models are complements, not competitors: content-based filtering has no cold start and answers "more like this" for any movie ever described, collaborative filtering is the sharpest signal on the 43% of the catalog with a real rating history, and SVD trades interpretability for compression on that same 43%. A product built on this needs all three, plus an explicit fallback for the 57% collaborative and SVD cannot reach — not because they weren't tuned, but because the signal they need was never given to them.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Movies_Recommendations)
[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue?style=for-the-badge)](https://huggingface.co/spaces/Alessandrou24/movie__Recommender)

---

### 09 — Fashion Product Images Classification

**Type:** Computer Vision · Transfer Learning · Image Classification · Explainable AI (Grad-CAM)
**Stack:** Python · PyTorch · torchvision · scikit-learn · Grad-CAM
**Dataset:** Fashion Product Images (Kaggle) — 43,946 products across 4 categories, after removing 3 that had too little data to classify reliably

Two transfer learning architectures, EfficientNetB0 and ResNet50, trained and compared on the same masterCategory classification task: frozen ImageNet backbones with only the final layer retrained, evaluated on real held-out test data rather than validation alone, and interpreted with Grad-CAM rather than left as a black box.

**Findings:** ResNet50 beats EfficientNetB0 on every class and every metric (99% accuracy and balanced accuracy against 97%), a consistent gap across the board, not one lucky epoch. The headline number is explained rather than just reported: 3 of the original 7 categories were dropped before training even started because there wasn't enough data to classify them reliably (Home: 1 image; Sporting Goods: 25, would need roughly ×854 augmentation to match the largest class; Free Items: 105, ×203 and visually incoherent, since a "free gift" can be almost any object). Grad-CAM turned what was left into a specific, explainable failure mode instead of a black box: Accessories and Apparel account for 63% of all test errors between them, and the heatmaps show why — in photos where an accessory is worn as part of an outfit, attention locks onto the accessory (a scarf, dense beadwork) instead of the garment actually labeled.

**In practice:** the model is close to production-ready for Footwear and Personal Care (11 and 1 errors respectively out of thousands of test images), and its one real weak spot is a specific, understood boundary rather than random noise — the kind of failure a business can plan a fallback around, not one it gets blindsided by. A real deployment still needs an explicit plan for the 3 excluded categories, and finer categories than masterCategory alone for most retail search and filtering.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Fashion-Product-Images)

---

### 10 — Automated News Report Generator

**Type:** Web Scraping · Workflow Orchestration · Local LLM Summarization · Self-Hosted Deployment
**Stack:** Python · Playwright · Prefect · SQLite · Transformers (Qwen2.5) · ReportLab · Docker · GitHub Actions · Gradio · Tailscale Funnel
**Source:** RTVE (Radiotelevisión Española) live Google News sitemap — 75–190 articles per fetch across 5 sections (noticias, deportes, catalunya, play, rtve)

An end-to-end pipeline (extraction → filtering → scraping → summarization → PDF) built and verified against the real service at every step rather than its documentation: `robots.txt` was checked live before choosing a data source, HTML selectors were confirmed against real article pages rather than guessed, and every free hosting option considered for the public dashboard was tested against its actual account limits, not its marketing page.

**Findings:** the two plans that looked simplest on paper both turned out to be dead ends once checked live. RTVE's classic RSS feed redirects to a host that's been stale since 2022 and is blocked by its own `robots.txt`; the pipeline uses the Google News sitemap instead — explicitly allowed, but not self-limited to 48h as Google's convention suggests, so entries from 2008 showed up mixed in with today's, and the recency filter had to be enforced in the pipeline itself, not assumed from the source. The planned deployment target, Hugging Face Spaces, couldn't create any Space with compute on the account used (Docker, Gradio+CPU, and ZeroGPU were all blocked, for reasons that stayed undiagnosable from outside); Streamlit Community Cloud (1GB RAM) and Google Colab (session limits) were checked and ruled out concretely before landing on self-hosting via Docker + Tailscale Funnel — the option that actually worked, verified from outside the author's own network.

**In practice:** a working, source-cited daily report: every entry in the PDF carries a title, category, and a link back to the original RTVE article, built in plain code from the database, never generated by the model, since the full article text is never published anywhere downstream by design, to stay inside RTVE's usage terms. The dashboard is only reachable while the self-hosted machine is on (roughly 9:00–23:00 CET), not 24/7 — the honest trade-off of a genuinely free deployment over a cloud platform that, in this case, turned out not to be usable at all.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Automated-News-Report)
[![Gradio Demo](https://img.shields.io/badge/Live%20Demo-Gradio-FF7C00.svg?style=for-the-badge&logo=gradio&logoColor=white)](https://alex-server.taile13699.ts.net/)

---

### Extra — Cloud: Serverless ML Inference on AWS

**Type:** Cloud Deployment · Serverless Architecture
**Stack:** AWS S3 · AWS Lambda · API Gateway · IAM · Python · scikit-learn
**Dataset:** Iris (used as a minimal case study — the focus of this project is the cloud architecture, not the model)

A small, self-contained project built to demonstrate practical AWS skills: a classification model served through a public HTTP endpoint, with no server to manage. The trained pipeline (StandardScaler + DecisionTreeClassifier) is stored in S3, loaded on demand by a Lambda function, and exposed via API Gateway.

**In practice:** this project is not about the model — Iris is deliberately simple so the architecture stays the focus. It demonstrates the full serverless deployment loop end-to-end: packaging dependencies for Lambda, configuring IAM permissions, handling cold starts, and exposing a model as a public API without provisioning any server. The README documents the real issues encountered and resolved along the way (missing dependencies, Lambda package size limits, read-only filesystem errors, cold-start timeouts), since debugging a deployment is as representative of the skill as the deployment itself.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/AWS-Iris-Prediction.git)

---

### Extra — Cloud: Serverless ML Inference on Azure

**Type:** Cloud Deployment · Serverless Architecture
**Stack:** Azure Blob Storage · Azure Functions · Python · scikit-learn
**Dataset:** Diabetes (scikit-learn, used as a minimal case study — the focus of this project is the cloud architecture, not the model)

A small, self-contained project built to demonstrate practical Azure skills: a regression model served through a public HTTP endpoint, with no server to manage. The trained pipeline (StandardScaler + RandomForestRegressor) is stored in Blob Storage, loaded on demand by an Azure Function, and exposed via its native HTTP trigger — no separate API Gateway needed.

**In practice:** this project is not about the model — the diabetes dataset is deliberately simple so the architecture stays the focus. It demonstrates the full serverless deployment loop end-to-end: creating resources via Azure CLI (the portal was insufficient due to plan restrictions with the free subscription), registering resource providers, handling region restrictions, managing npm permissions for the Core Tools, and deploying a model as a public API without provisioning any server. The README documents the real issues encountered and resolved along the way, since debugging a deployment is as representative of the skill as the deployment itself.

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AlejandroBeldaFernandez/Azure-Diabetes-Prediction.git)
