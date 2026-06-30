# 📱 Unveiling the Android App Market: Analyzing Google Play Store Data

## 📌 Project Overview

This project analyzes Google Play Store applications to uncover insights into the Android app market. It involves data cleaning, preprocessing, exploratory data analysis (EDA), sentiment analysis of user reviews, and data visualization to understand app performance, popularity, ratings, pricing, and user feedback.

The objective is to transform raw Google Play Store data into meaningful business insights using Python and data visualization techniques.

---

## 🎯 Objectives

- Clean and preprocess the Google Play Store dataset.
- Correct inconsistent data types.
- Analyze app distribution across different categories.
- Study ratings, reviews, installs, size, and pricing trends.
- Perform sentiment analysis using user reviews.
- Create insightful visualizations.
- Extract meaningful business insights from the data.

---

## 📂 Dataset

### Dataset Files

- **apps.csv** – Contains information about Google Play Store applications.
- **user_reviews.csv** – Contains user reviews and sentiment analysis.

### Features in apps.csv

- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

### Features in user_reviews.csv

- App
- Translated Review
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Collection

- Load datasets using Pandas.

### 2. Data Cleaning

- Remove duplicate records.
- Handle missing values.
- Convert data types.
- Clean Install counts.
- Clean Price column.
- Handle Rating values.

### 3. Exploratory Data Analysis (EDA)

- App distribution by category
- Rating distribution
- Most installed categories
- Free vs Paid apps
- Pricing analysis
- Popular applications

### 4. Sentiment Analysis

- Positive reviews
- Negative reviews
- Neutral reviews
- Sentiment polarity distribution

### 5. Visualization

- Bar Charts
- Histograms
- Pie Charts
- Count Plots

---

## 📈 Key Insights

- Family and Game categories contain the highest number of applications.
- Most applications have ratings between **4.0 and 4.5**.
- Free apps dominate the Google Play Store.
- Categories like **Game**, **Communication**, and **Tools** receive the highest installs.
- Positive user sentiment is significantly higher than negative sentiment.
- Paid applications form only a small percentage of the total apps.

---

## 📁 Project Structure

```
Android_App_Market_EDA/
│
├── apps.csv
├── user_reviews.csv
├── Google_Play_Store_Analysis.ipynb
├── README.md
└── images/
```

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/yourusername/Android-App-Market-Analysis.git
```

2. Navigate to the project folder

```bash
cd Android-App-Market-Analysis
```

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open

```
Google_Play_Store_Analysis.ipynb
```

Run all cells to reproduce the analysis.

---

## 📌 Results

The project successfully identifies:

- Popular app categories
- Rating trends
- Installation patterns
- Pricing behavior
- User sentiment distribution
- Market insights through interactive visualizations

---

## 🚀 Future Enhancements

- Build an interactive Power BI dashboard.
- Deploy the analysis using Streamlit.
- Develop app recommendation models.
- Apply machine learning for app rating prediction.

---

## 👩‍💻 Author

**Hemavathi Badiginchala**

Data Analytics Intern – Oasis Infobyte

---

## 📜 License

This project is created for educational and internship purposes under the Oasis Infobyte Data Analytics Internship.
