# Simple ML

<p align="center">
  A growing collection of small, practical Machine Learning projects built in Jupyter Notebook.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/License-MIT-green" alt="MIT License">
</p>

---

## About

**Simple ML** is a personal collection of machine-learning experiments focused on learning by building.

The notebooks cover supervised learning, unsupervised learning, NLP, preprocessing, model evaluation, visualization, and basic model comparison. The goal is to build a strong ML foundation while continuously improving earlier models as new techniques are learned.

Most projects are designed to be explored and run locally through **Jupyter Notebook**.

## Projects

| Notebook | Focus |
|---|---|
| [`Customer_Segmentation.ipynb`](Customer_Segmentation.ipynb) | Customer segmentation using **K-Means clustering** and **PCA** |
| [`Diabetes_Prediction.ipynb`](Diabetes_Prediction.ipynb) | Diabetes classification using **SVM** and feature scaling |
| [`Finance_NLP.ipynb`](Finance_NLP.ipynb) | Financial NLP with **spaCy**, identifying companies, stocks, indexes and exchanges |
| [`Forest_Fire.ipynb`](Forest_Fire.ipynb) | Forest-fire classification with models such as **Logistic Regression** and **SVC** |
| [`Heart_Failure.ipynb`](Heart_Failure.ipynb) | Heart-failure prediction, preprocessing and classification evaluation |
| [`Houses.ipynb`](Houses.ipynb) | House-price prediction using **Linear Regression** |
| [`Songlikes.ipynb`](Songlikes.ipynb) | Song-like classification using **Logistic Regression** |
| [`Spam_sms.ipynb`](Spam_sms.ipynb) | SMS spam detection using **TF-IDF** and multiple classification models |
| [`Spam_sms_sim.ipynb`](Spam_sms_sim.ipynb) | A simpler SMS spam classifier using **CountVectorizer + Multinomial Naive Bayes** |
| [`Stocks.ipynb`](Stocks.ipynb) | Stock-data analysis and regression experiments |
| [`Student_Placements.ipynb`](Student_Placements.ipynb) | Student placement classification using **Logistic Regression** |

## Tech Stack

- Python
- Jupyter Notebook
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn
- spaCy
- NLTK
- XGBoost

## Running Locally

### 1. Clone the repository

```bash
git clone https://github.com/yupitsmegd7/Simple_ML.git
cd Simple_ML
```

### 2. Create a virtual environment

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install the common dependencies

```bash
pip install jupyter numpy pandas matplotlib seaborn scikit-learn spacy nltk xgboost
```

Some notebooks may require additional packages depending on the experiment.

### 4. Start Jupyter

```bash
jupyter notebook
```

Open the notebook you want to explore and run the cells in order.

> **Note:** Some notebooks were originally written with Colab-style paths such as `/content/...`.  
> When running locally, place the required dataset on your machine and update the `read_csv()` / file path in the notebook accordingly.

## Typical Workflow

Most notebooks follow a simple ML workflow:

```text
Dataset
   ↓
Cleaning / Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Train / Test Split
   ↓
Model Training
   ↓
Evaluation
   ↓
Prediction / Experimentation
```

## What This Repository Is For

This repository is primarily a learning space for:

- understanding ML algorithms by implementing them
- comparing different models
- practicing preprocessing and feature engineering
- working with real datasets
- learning evaluation metrics
- experimenting with NLP and clustering
- gradually improving models and notebooks over time

## License

This project is available under the [MIT License](LICENSE).

---

<p align="center">
  Built while learning, experimenting, and getting better at Machine Learning.
</p>
