# 📊 NLP Sentiment Analysis & Interactive Executive Dashboard

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-yellow.svg)](https://powerbi.microsoft.com/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-orange.svg)](https://scikit-learn.org/)
[![NLTK](https://img.shields.io/badge/NLTK-NLP-green.svg)](https://www.nltk.org/)
[![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)

An end-to-end Data Science & Business Intelligence project focusing on **Social Media Sentiment Analysis**, Natural Language Processing (NLP), Machine Learning classification, and an interactive **Power BI Executive Dashboard**.

---

## 📌 Executive Summary

This project analyzes multi-platform social media text data (Twitter, Instagram, Facebook, etc.) to uncover user sentiment patterns, engagement dynamics (Likes & Retweets), and temporal trends. By combining **NLP preprocessing**, **predictive modeling**, and **Business Intelligence (BI) visualization**, stakeholders can derive actionable insights into public opinion, brand perception, and content performance across different demographics.

---

## ✨ Key Features

- **🧹 NLP Text Preprocessing Pipeline**:
  - Automated text cleaning using Regular Expressions (Regex), stop-word removal, tokenization, and lemmatization via NLTK & TextBlob.
  - Calculation of Text Polarity and Subjectivity scores.

- **🤖 Machine Learning & Predictive Modeling**:
  - Multi-class classification using **Logistic Regression**, **Decision Trees**, and **Random Forest Classifiers**.
  - Hyperparameter tuning using `GridSearchCV` for model optimization.
  - Comprehensive model evaluation metrics (Accuracy, Precision, Recall, F1-Score).

- **📈 Advanced Analytics**:
  - **Exploratory Data Analysis (EDA)**: Sentiment distributions by social media platform, country, and time of day.
  - **K-Means Clustering**: Segmentation of user engagement behaviors based on Likes and Retweets.
  - **Time Series Analysis**: Seasonal decomposition of post frequency and sentiment trends.

- **📊 Interactive Power BI Dashboard (`codveda dashboard.pbix`)**:
  - Executive-level dashboard visualizing platform distribution, sentiment breakdowns, top trending hashtags, and cross-platform engagement metrics.

---

## 📁 Repository Structure

```
.
├── Sentiment_Analysis_Codveda_tech.ipynb   # Complete Jupyter Notebook (EDA, Preprocessing, ML Models, Clustering)
├── codveda dashboard.pbix                 # Interactive Power BI Dashboard File
├── .gitignore                             # Git ignore rules for Python & Jupyter
└── README.md                              # Professional project documentation
```

---

## 📊 Dataset Overview

The dataset captures multi-platform social media posts with text content, engagement metrics, user details, and timestamps:

| Feature Column | Description | Data Type |
| :--- | :--- | :--- |
| `Text` | Social media post content | String (Text) |
| `Sentiment` | Target sentiment classification (Positive, Negative, Neutral) | Categorical |
| `Platform` | Social media platform (Twitter, Instagram, Facebook, etc.) | Categorical |
| `Likes` / `Retweets` | User engagement metrics | Numeric |
| `Timestamp` | Date & time of post publication | Datetime |
| `User` / `Country` | User identifier and geographic location | Categorical |
| `Hashtags` | Extracted hashtags associated with the post | String (Text) |

---

## 🛠️ Tech Stack & Dependencies

- **Language**: Python 3.8+
- **Data Processing**: `pandas`, `numpy`
- **Natural Language Processing**: `nltk`, `textblob`, `wordcloud`
- **Machine Learning**: `scikit-learn`, `statsmodels`
- **Visualization & BI**: `matplotlib`, `seaborn`, `Power BI Desktop`

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed, along with Power BI Desktop (for opening the `.pbix` file).

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Ecoplex82/nlp-sentiment-analysis-dashboard.git
   cd nlp-sentiment-analysis-dashboard
   ```

2. **Install Required Python Libraries**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn nltk textblob wordcloud statsmodels
   ```

3. **Download NLTK Corpora** (Run in Python):
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')
   nltk.download('wordnet')
   ```

4. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook Sentiment_Analysis_Codveda_tech.ipynb
   ```

5. **Explore the Power BI Dashboard**:
   Open `codveda dashboard.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to interact with the visual dashboard.

---

## 👨‍💻 Author & Acknowledgments

- **Author**: Emmanuel Bright Chetachi
- **Role**: Data Analysis Intern
- **Internship ID**: CV/A1/87703
- **Organization**: Codveda Technologies

---

## 📜 License

This project is licensed under the MIT License.