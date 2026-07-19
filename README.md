# 📊 ChatGPT Review Analysis using Python & NLP

## 📌 Project Overview

This project analyzes customer reviews of ChatGPT using **Python** and **Natural Language Processing (NLP)** techniques. The goal is to understand customer sentiment, compare textual feedback with user ratings, and identify the most frequently mentioned positive keywords through data visualization.

The project demonstrates the complete data analytics workflow, including data cleaning, exploratory data analysis (EDA), sentiment analysis, and text analysis.

---

## 🎯 Project Objectives

- Analyze customer reviews of ChatGPT.
- Perform data cleaning and preprocessing.
- Calculate sentiment polarity and subjectivity using NLP.
- Classify reviews as Positive, Neutral, or Negative.
- Compare customer ratings with review sentiment.
- Identify frequently mentioned positive keywords.
- Visualize insights using different charts.

---

## 📂 Dataset

The dataset contains the following columns:

| Column | Description |
|---------|-------------|
| Review ID | Unique identifier for each review |
| Review | Customer review text |
| Ratings | User rating (1–5) |
| Review Date | Date the review was posted |

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TextBlob
- WordCloud

---

## 📋 Project Workflow

### 1. Data Preprocessing

- Loaded the dataset
- Standardized column names
- Checked missing values
- Filled missing reviews using `fillna("")`
- Converted review date to datetime format
- Verified appropriate data types

---

### 2. Exploratory Data Analysis (EDA)

Performed visual analysis to understand customer behavior.

Visualizations include:

- Ratings Distribution
- Sentiment Distribution
- Ratings vs Sentiment
- Polarity Distribution
- Subjectivity Distribution
- Average Polarity by Rating

---

### 3. Sentiment Analysis

Used the **TextBlob** library to calculate:

- Polarity (-1 to +1)
- Subjectivity (0 to 1)

Reviews were classified into:

- Positive
- Neutral
- Negative

based on polarity scores.

---

### 4. Text Analysis

Analyzed only positive reviews to understand customer appreciation.

Steps performed:

- Converted text to lowercase
- Removed stopwords
- Counted word frequencies
- Generated Word Cloud
- Created Frequency Plot of top keywords

---

## 📊 Visualizations

- Count Plot
- Histogram
- Bar Plot
- Word Cloud
- Frequency Plot

These visualizations help understand customer satisfaction, sentiment distribution, and frequently discussed topics.

---

## 🔍 Key Insights

- Most users rated ChatGPT **4 or 5 stars**, indicating high customer satisfaction.
- The majority of reviews were classified as **Positive**.
- Higher ratings were associated with higher polarity scores.
- Frequently occurring keywords highlighted the features users appreciated the most.

---

## 📁 Project Structure

```
ChatGPT-Review-Analysis/
│
├── ChatGPT_Review_Analysis.ipynb
├── chatgpt_reviews.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/yourusername/ChatGPT-Review-Analysis.git
```

2. Navigate to the project folder

```bash
cd ChatGPT-Review-Analysis
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Open the notebook

```bash
jupyter notebook
```

or upload the notebook to **Google Colab**.

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
textblob
wordcloud
```

---

## 📈 Future Improvements

- Analyze review trends over time.
- Apply machine learning models for sentiment classification.
- Perform topic modeling using NLP techniques.
- Build an interactive dashboard using Power BI or Streamlit.

---

<img width="667" height="566" alt="image" src="https://github.com/user-attachments/assets/167bd7b6-63d0-4bda-aad5-ed0faf139b98" />
<img width="668" height="507" alt="image" src="https://github.com/user-attachments/assets/d8b74034-3cd6-4545-b087-72f1ca5a5e06" />
<img width="658" height="510" alt="image" src="https://github.com/user-attachments/assets/c9afb383-d714-4bd6-8d20-86e977ac1eb0" />
<img width="635" height="511" alt="image" src="https://github.com/user-attachments/assets/f52f7648-abd7-4bf2-bd8d-348eef194aee" />
<img width="586" height="330" alt="image" src="https://github.com/user-attachments/assets/dd7e3c74-d19f-4b3a-af1f-4f39ceb33d52" />
<img width="670" height="562" alt="image" src="https://github.com/user-attachments/assets/bdd70383-d449-4086-9565-d5e16b822162" />




