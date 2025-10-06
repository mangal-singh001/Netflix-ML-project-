# 🎬 Netflix ML Project – Exploratory Data Analysis & Clustering

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Netflix_2015_logo.svg" width="200">
</p>

## 📌 Project Overview

Netflix, one of the world’s leading OTT streaming platforms, hosts a vast and diverse collection of **Movies** and **TV Shows** from multiple countries, genres, and languages.
As the content library continues to expand, understanding **patterns in the catalog** — such as regional trends, content types, audience ratings, and duration preferences — becomes essential for **data-driven decisions** and improving **user engagement**.

The main objective of this project is to perform **Exploratory Data Analysis (EDA)** and apply **Machine Learning (K-Means Clustering)** to uncover hidden patterns in Netflix’s content.

---

## 🎯 Business Objective

To analyze the Netflix dataset and identify patterns related to:

* Content distribution by **country, genre, and type**
* Trends over **years** (movies vs TV shows)
* **Ratings and durations** insights
* Grouping similar content using **unsupervised machine learning (K-Means Clustering)**

This analysis helps Netflix in:

* Improving **content recommendation** and **regional strategies**
* Understanding **audience preferences**
* Making **data-backed production and acquisition decisions**

---

## 🧠 Machine Learning Objective

Build an **unsupervised model** using **K-Means clustering** to:

* Group similar titles based on text-based features (description, cast, genre)
* Understand content similarity patterns
* Support recommendation-related insights

---

## 📂 Dataset Information

* **Source:** Kaggle – [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
* **Rows:** 8,807
* **Columns:** 12
* **Key Features:**

  * `type` – Movie or TV Show
  * `title` – Name of the show/movie
  * `director`, `cast`, `country`
  * `release_year`, `rating`, `duration`
  * `listed_in` – Genre
  * `description` – Short summary

---

## 🧹 Data Preprocessing

✔ Handling **missing values**
✔ Removing **duplicates**
✔ Standardizing text formats
✔ Extracting numerical values from `duration`
✔ Splitting multiple genres & countries
✔ Encoding categorical variables
✔ Text vectorization using **TF-IDF Vectorizer** (for descriptions)

---

## 📊 Exploratory Data Analysis (EDA)

Key Insights Visualized:

* 📅 Year-wise content release trends
* 🌎 Country-wise content production
* 🎭 Top genres and most common ratings
* 🎬 Average movie durations & episode counts
* 🔍 WordClouds for title descriptions

> Tools used for visualization: **Matplotlib**, **Seaborn**, and **WordCloud**

---

## 🤖 Machine Learning Model – K-Means Clustering

* **Algorithm:** K-Means
* **Technique:** Text Vectorization with **TF-IDF**
* **Goal:** Group titles based on description similarity
* **Steps:**

  1. Text cleaning (stopwords, lowercase, punctuation removal)
  2. TF-IDF vectorization of descriptions
  3. Optimal K selection using **Elbow Method**
  4. K-Means clustering
  5. Visualization of clusters using **PCA (2D plot)**

---

## 🧾 Results & Insights

* Successfully grouped titles into **5 clusters** based on text similarity
* Identified themes such as **Crime/Thriller**, **Romance/Drama**, **Documentary**, **Children’s Content**, and **Action/Adventure**
* Helped in understanding **content diversity and type-based grouping**

---

## 🛠️ Tech Stack

| Category                 | Tools / Libraries              |
| ------------------------ | ------------------------------ |
| Programming              | Python                         |
| Data Analysis            | Pandas, NumPy                  |
| Visualization            | Matplotlib, Seaborn, WordCloud |
| Machine Learning         | Scikit-learn                   |
| NLP                      | TF-IDF Vectorizer              |
| Dimensionality Reduction | PCA                            |

---

## 📁 Project Structure

```
Netflix-ML-project/
│
├── Netflix.ipynb                # Main Jupyter Notebook
├── Netflix.csv                  # Dataset
├── README.md                    # Project Documentation
├── requirements.txt             # Dependencies
└── outputs/                     # Visualizations and plots
```

---

## 🧩 Key Learnings

* Improved understanding of **EDA and text preprocessing**
* Practical implementation of **TF-IDF and K-Means clustering**
* Hands-on experience in **unsupervised learning**
* Learned how to extract **insights from large datasets**

---

## 🚀 Future Improvements

* Integrate **content recommendation system**
* Apply **hierarchical or DBSCAN clustering** for comparison
* Use **NLP-based embeddings (Word2Vec, BERT)** for deeper text similarity
* Create an **interactive dashboard** using Power BI or Streamlit

---

## 💡 Conclusion

This project demonstrates how **data analysis + machine learning** can uncover hidden insights from entertainment data.
Through clustering and visualization, we gain a clearer understanding of Netflix’s content strategy and diversity.

---

## 🧑‍💻 Author

**Mangal Singh**
🎓 B.Tech CSE | Data Science Enthusiast
📊 Passionate about Data Analysis, Visualization & Machine Learning
🌐 [GitHub](https://github.com/mangal-singh001) • [LinkedIn](https://www.linkedin.com/in/mangal-singh001)

---

## ⭐ If you like this project

Don’t forget to **star this repository** 🌟 and follow for more data projects!

---

