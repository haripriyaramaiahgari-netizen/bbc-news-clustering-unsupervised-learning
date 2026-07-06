# BBC News Articles Clustering using Unsupervised Learning

## 📌 Project Overview

This project demonstrates the application of **Unsupervised Machine Learning** and **Natural Language Processing (NLP)** to automatically cluster BBC news articles into meaningful groups without using predefined labels.

The project uses three different text vectorization techniques and applies the **K-Means clustering algorithm** to discover hidden patterns within news articles. The clustering performance is evaluated using the **Silhouette Coefficient**, and the results are visualized using bar charts and PCA scatter plots.

---

## 🎯 Objective

- Read BBC news articles from multiple categories.
- Combine all articles into a single dataset.
- Perform advanced text preprocessing.
- Convert text into numerical vectors using three vectorization techniques.
- Cluster articles into five groups using K-Means.
- Compare clustering performance using the Silhouette Score.
- Visualize clustering results using bar plots and PCA.

---

## 📂 Project Structure

```
BBC-News-Clustering/

├── NLP_Project.ipynb
├── BBC_News_Articles/
│   ├── business/
│   ├── entertainment/
│   ├── politics/
│   ├── sport/
│   └── tech/
├── BBCNewsArticles.csv
├── BBCNewsArticlesClustered.csv
├── README.md
```

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- NLTK
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📋 Project Workflow

### 1. Dataset Preparation

- Extract BBC News dataset.
- Read articles from five categories.
- Combine all articles into a single CSV file.
- Shuffle the dataset randomly.

### 2. Text Preprocessing

The following preprocessing techniques were applied:

- Convert text to lowercase
- Remove URLs
- Remove HTML tags
- Remove numbers
- Remove punctuation
- Remove extra spaces
- Tokenization
- Stop-word removal
- Lemmatization
- Duplicate consecutive word removal

### 3. Text Vectorization

Three vectorization methods were used:

- Presence/Absence Vectorization
- Count Vectorization
- TF-IDF Vectorization

### 4. Clustering

The project uses the **K-Means clustering algorithm** with:

- Number of Clusters = 5
- k-means++ initialization
- Multiple initializations (`n_init = 20`)
- Maximum iterations = 500

### 5. Evaluation

The clustering models are evaluated using the **Silhouette Coefficient**.

### 6. Visualization

The project includes:

- Silhouette Score comparison using a Bar Chart
- PCA Scatter Plots for cluster visualization

---

## 📊 Results

The project successfully:

- Generated **BBCNewsArticles.csv**
- Generated **BBCNewsArticlesClustered.csv**
- Compared three vectorization techniques
- Visualized clustering results
- Evaluated clustering quality using the Silhouette Score

---

## ✅ Conclusion

This project demonstrates how **Unsupervised Learning** can automatically discover meaningful groups within textual data.

Among the three vectorization techniques, **TF-IDF** provides a richer representation of documents by considering both word frequency and word importance across the dataset. The enhanced preprocessing pipeline and optimized K-Means configuration improved the quality and stability of clustering.

---



## 👩‍💻 Author

**R. Hari priya**

B.Tech – Computer Science and Engineering (Artificial Intelligence & Machine Learning)

SRM Institute of Science and Technology – Ramapuram



---

## 📚 Dataset

BBC News Summary Dataset (Kaggle)

https://www.kaggle.com/pariza/bbc-news-summary