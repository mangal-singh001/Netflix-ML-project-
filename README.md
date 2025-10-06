# 🎬 Netflix ML Project – Exploratory Data Analysis & Clustering

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg" width="200">
</p>

## 📌 Project Overview

Netflix, one of the world’s leading OTT streaming platforms, hosts a vast and diverse collection of **Movies** and **TV Shows** across various countries, genres, and languages.
The goal of this project is to perform **Exploratory Data Analysis (EDA)** and apply **Machine Learning (K-Means Clustering)** to uncover hidden patterns and similarities among Netflix titles.

---

## 🎯 Business Objective

To analyze Netflix’s dataset and identify:

* Trends in content distribution (by **country**, **type**, and **genre**)
* Insights into **ratings**, **release years**, and **durations**
* Clusters of similar content using **unsupervised learning (K-Means)**

This helps Netflix understand:

* Regional and genre-based preferences
* Production and licensing opportunities
* Patterns useful for **recommendation systems**

---

## 🧠 Machine Learning Objective

Implement an **unsupervised learning model** using **K-Means Clustering** to group content based on textual and categorical features such as description, genre, and type.

---

## 📂 Repository Structure

```
Netflix-ML-project-/
│
├── NETFLIX MOVIES AND TV SHOWS CLUSTERING DATA.csv   # Dataset used for EDA & ML
├── Netflix.pptm.pptx                                 # Presentation summarizing the project
├── README.md                                         # Project Documentation
├── Sample_EDA_Submission_Template (1).ipynb          # Notebook for Exploratory Data Analysis
└── Sample_ML_Submission_Template.ipynb               # Notebook for Machine Learning Model
```

---

## 🧹 Data Preprocessing

✔ Removed duplicates and missing values
✔ Cleaned and standardized text data
✔ Extracted numeric duration from text (e.g., “90 min”, “2 Seasons”)
✔ Encoded categorical variables (type, country, genre)
✔ Applied **TF-IDF Vectorization** for textual data (description column)

---

## 📊 Exploratory Data Analysis (EDA)

Key Insights:

* Year-wise trends of movie and TV show releases
* Top countries contributing to Netflix’s catalog
* Most popular genres and ratings
* Average duration analysis
* Text analysis using WordClouds for descriptions

> Tools Used: **Pandas, NumPy, Matplotlib, Seaborn**

---

## 🤖 Machine Learning Model – K-Means Clustering

**Goal:** Identify content clusters based on textual and metadata similarity

**Steps:**

1. Cleaned and preprocessed text (stopwords removal, lowercase conversion, punctuation removal)
2. Transformed text data using **TF-IDF Vectorizer**
3. Determined optimal number of clusters using **Elbow Method**
4. Applied **K-Means Clustering**
5. Visualized clusters using **PCA (Principal Component Analysis)**

**Results:**

* Found 5 major clusters representing categories like:

  * Action / Thriller
  * Drama / Romance
  * Documentaries
  * Kids / Family
  * Comedy / Light Entertainment

---

## 🛠️ Tools & Technologies

| Category                 | Tools / Libraries              |
| ------------------------ | ------------------------------ |
| Language                 | Python                         |
| Data Handling            | Pandas, NumPy                  |
| Visualization            | Matplotlib, Seaborn, WordCloud |
| Machine Learning         | Scikit-learn                   |
| Text Vectorization       | TF-IDF Vectorizer              |
| Dimensionality Reduction | PCA                            |

---

## 🧾 Key Learnings

* Performed **EDA** to extract meaningful insights
* Built an **unsupervised clustering model**
* Understood **text vectorization** and **dimensionality reduction**
* Learned practical end-to-end data science workflow

---

## 🚀 Future Scope

* Enhance clustering using **Word2Vec** or **BERT embeddings**
* Build a **recommendation system** based on content similarity
* Deploy interactive visualization using **Streamlit / Power BI**

---

## 💡 Conclusion

This project highlights how **EDA and unsupervised learning** can reveal valuable insights in media datasets.
By clustering Netflix titles, we can better understand content patterns, viewer preferences, and genre similarities — aiding strategic and recommendation-based improvements.

---

## 🧑‍💻 Author

**Mangal Singh**
🎓 B.Tech CSE | Data Science Enthusiast
📊 Focused on Data Analysis, ML, and Visualization

🌐 [GitHub](https://github.com/mangal-singh001) 
• [LinkedIn](https://www.linkedin.com/in/mangal-singh001)

---

## ⭐ Support

If you found this project useful, don’t forget to ⭐ **star this repository** and share your feedback!

---


