# 📱 Google Play Store Analysis: Unveiling the Android App Market

## 📌 Project Overview

The **Google Play Store Analysis** project focuses on exploring and understanding the Android application ecosystem using real-world app data and user reviews.

The project involves data cleaning, exploratory data analysis (EDA), visualization, pricing analysis, installation trends, and sentiment analysis to identify important factors influencing app performance and user satisfaction.

This analysis provides meaningful insights for developers to make data-driven decisions while planning and launching new mobile applications.

---

# 🎯 Project Objective

The main objectives of this project are:

* Perform data cleaning on real-world Google Play Store datasets
* Analyze app distribution across different categories
* Understand rating patterns and user satisfaction
* Study the relationship between app size and number of installations
* Analyze free vs paid application trends
* Estimate potential revenue by category
* Perform sentiment analysis on user reviews
* Generate business insights and recommendations for app developers

---

# 📂 Dataset Description

The project uses two publicly available datasets:

## 1. Google Play Store Apps Dataset

Contains application-level information:

| Feature  | Description              |
| -------- | ------------------------ |
| App      | Application name         |
| Category | App category             |
| Rating   | Average user rating      |
| Reviews  | Number of reviews        |
| Size     | Application size         |
| Installs | Number of installations  |
| Type     | Free or Paid application |
| Price    | Application price        |
| Genres   | Application genre        |

## 2. Google Play Store User Reviews Dataset

Contains user feedback information:

| Feature                | Description             |
| ---------------------- | ----------------------- |
| App                    | Application name        |
| Translated Review      | User review text        |
| Sentiment              | Review sentiment        |
| Sentiment Polarity     | Positive/negative score |
| Sentiment Subjectivity | Opinion strength        |

---

# 🛠️ Technology Stack

## Programming Language

* Python

## Libraries Used

* Pandas – Data manipulation and analysis
* NumPy – Numerical computations
* Matplotlib – Data visualization
* Seaborn – Statistical visualization
* Plotly – Interactive visualization
* TextBlob – Sentiment analysis

## Development Environment

* Jupyter Notebook

---

# 🔄 Project Workflow

## 1. Data Loading

* Imported Google Play Store application dataset
* Imported user review dataset
* Checked dataset structure, dimensions, and data types

---

# 2. Data Cleaning & Preprocessing

The following preprocessing steps were performed:

### Handling Missing Values

* Identified missing values in important columns
* Filled missing ratings using statistical methods
* Handled missing app size values

### Removing Duplicate Data

* Removed duplicate application records to improve analysis accuracy

### Data Type Correction

* Converted **Installs** column from string format:

```
10,000+  → 10000
```

* Converted **Price** column:

```
$4.99 → 4.99
```

* Converted application size:

```
19M → 19 MB
500k → 0.5 MB
```

---

# 📊 Exploratory Data Analysis (EDA)

## 1. Category Analysis

Analyzed the distribution of applications across different categories.

### Key Findings:

* Categories such as **Family, Games, and Tools** contain a large number of applications.
* These categories are highly competitive due to market saturation.

---

## 2. Rating Analysis

Performed:

* Rating distribution analysis
* Average rating comparison across categories

### Insights:

* Most applications maintain positive ratings.
* User satisfaction is an important factor for application success.

---

## 3. App Size vs Installation Analysis

Analyzed the relationship between:

* Application size
* Number of installs

### Insights:

* App size alone does not determine popularity.
* Application quality, features, and user experience have a stronger impact on downloads.

---

# 💰 Pricing & Revenue Analysis

Performed:

* Free vs Paid application comparison
* Paid app price distribution
* Revenue estimation by category

Revenue calculation:

```
Estimated Revenue = App Price × Number of Installs
```

### Insights:

* Free applications dominate the Play Store.
* Developers commonly use advertisements and in-app purchases for monetization.

---

# 😊 Sentiment Analysis

User reviews were analyzed using **TextBlob sentiment analysis**.

Reviews were classified into:

* Positive
* Negative
* Neutral

### Analysis Performed:

* Overall sentiment distribution
* Sentiment comparison across categories

### Insights:

* Positive reviews indicate better user satisfaction.
* Negative reviews provide opportunities for improving application quality.

---

# 📈 Interactive Visualization

Created interactive visualizations using Plotly to improve data exploration.

Implemented:

* Interactive category distribution chart
* User-friendly visualization of application trends

---

# 🔍 Key Business Insights

1. The Android application market is highly competitive, with certain categories having significantly higher saturation.

2. Free applications have a dominant presence, suggesting that alternative monetization strategies are important for developers.

3. User ratings and sentiment play a major role in application reputation and long-term success.

4. Developers should focus on user experience, performance optimization, and continuous improvement based on feedback.

---

# 🚀 Recommendations for App Developers

* Target less saturated categories to reduce competition.
* Analyze user reviews regularly to understand customer needs.
* Improve application quality to maintain high ratings.
* Select suitable monetization strategies.
* Focus on features that increase user engagement and retention.

---

# 📁 Project Structure

```
Google-Play-Store-Analysis/

│
├── Google_Play_Store_Analysis.ipynb
│
├── Dataset/
│   ├── googleplaystore.csv
│   └── googleplaystore_user_reviews.csv
│
└── README.md
```

---

# ✅ Conclusion

This project demonstrates an end-to-end data analysis workflow on Google Play Store data, including data preprocessing, exploratory analysis, visualization, pricing analysis, and sentiment analysis.

The insights generated from this project help understand market trends, user preferences, and important factors that influence mobile application success.

---

# 👩‍💻 Author

**Boyapati Sathwika**

B.Tech Artificial Intelligence & Data Science

**Skills:** Python | Data Analytics | Machine Learning | SQL | Data Visualization
