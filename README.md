# IRCTC_Sentiment_Analytics-Text-Web-Social-Media-Analytics
NLP-based Sentiment Analysis Project for IRCTC under Travel and Transportation Industry

```markdown
# IRCTC Sentiment Analytics-Text-Web-Social-Media-Analytics

### Industry: Travel and Transportation  
### Course: Text, Web & Social Media Analytics  
### Institution: School of Management Studies, University of Hyderabad  
### Author: Teesa Sharma  
### Academic Year: 2025  

---

## 📘 Project Overview
This project applies **Natural Language Processing (NLP)** and **Social Media Analytics** to analyze customer feedback related to the **Indian Railway Catering and Tourism Corporation (IRCTC)**.  
The objective is to detect sentiment, discover discussion topics, and visualize insights to improve IRCTC’s service quality.  
It combines multiple text analytics techniques to deliver actionable business insights.

---

## 🎯 Problem Statement
IRCTC receives thousands of reviews and social media posts daily.  
Manually analyzing such large-scale textual data is inefficient and prone to bias.  
This project automates the process using NLP to extract sentiments, identify major issues, and provide real-time visual insights into customer satisfaction.

---

## 🧩 Project Objectives
1. Analyze IRCTC customer reviews and Twitter posts using NLP.  
2. Classify sentiments as **positive**, **negative**, or **neutral**.  
3. Discover major discussion topics using **LDA Topic Modeling**.  
4. Build supervised machine learning models for sentiment prediction.  
5. Create interactive **2D and 3D visualizations** for insights.  
6. Store cleaned data and model results in a **SQLite database**.  

---

## 📊 Project Workflow Pipeline

![IRCTC Pipeline](documentation/IRCTC_Sentiment_Analytics_Pipeline.png)

The project follows a structured NLP-based workflow as shown above.

```

Data Collection → Text Preprocessing → Sentiment Analysis → Topic Modeling →
Text Classification → Social Media Analytics → Visualization & Database Storage

```

---

## 🧠 Methodology

| Stage | Description | Tools/Libraries |
|--------|--------------|----------------|
| **Data Collection** | IRCTC reviews dataset + simulated Twitter data | Pandas |
| **Text Preprocessing** | Tokenization, Stopword removal, Lemmatization | NLTK, Regex |
| **Sentiment Analysis** | Polarity detection using TextBlob & VADER | TextBlob, VaderSentiment |
| **Topic Modeling** | Discovering hidden topics | LDA (Gensim) |
| **Text Classification** | Model training and evaluation | Naive Bayes, Logistic Regression |
| **Social Media Analytics** | Public opinion & trend detection | Pandas, Plotly |
| **Visualization & Storage** | 2D & 3D plots, Database integration | Matplotlib, Plotly, SQLite |

---

## 🧮 Use Cases Implemented

| Use Case | Title | Objective |
|-----------|--------|-----------|
| 1 | Text Preprocessing | Cleaning and preparing textual data for analysis |
| 2 | Sentiment Analysis | Identifying sentiment polarity in reviews |
| 3 | Topic Modeling | Discovering major customer discussion themes |
| 4 | Text Classification | Predicting sentiment using ML algorithms |
| 5 | Social Media Analytics | Analyzing Twitter trends and sentiment variation |

---

## 📈 Results Summary
- **Sentiment Distribution:** 60% Positive, 25% Negative, 15% Neutral  
- **Best Model:** Logistic Regression with **91% Accuracy**  
- **Major Discussion Topics:** Tatkal booking, food quality, app interface, refund process  
- **Visualization Outputs:**  
  - Word Cloud of frequent words  
  - 3D Sentiment Trend Graph  
  - Topic Strength Visualization  
  - Confusion Matrix  

---

## 💡 Key Insights
- Most IRCTC customers express positive opinions regarding refund and reliability.  
- Negative feedback revolves around booking delays and app issues.  
- Combining reviews and social media sentiment provides a complete customer perspective.  
- The analytical framework can be extended to other public transportation systems.

---

## 🚀 Future Scope
- Real-time sentiment dashboard for IRCTC management.  
- Multilingual text analysis (Hindi, Tamil, Telugu, etc.).  
- Chatbot integration for automated customer feedback analysis.  

---

## 🧰 Tools and Technologies
Python, Pandas, NumPy, NLTK, TextBlob, VaderSentiment, Gensim, Scikit-learn, Matplotlib, Seaborn, Plotly, SQLite, Jupyter Notebook


```
