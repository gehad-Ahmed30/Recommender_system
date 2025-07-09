# Udemy Courses Recommender System 🎓🔍

This project is a case study in building a simple **Recommender System** using real-world Udemy course data. The system suggests similar courses based on course titles using **Natural Language Processing (NLP)** and **Cosine Similarity**.

---

## 📁 Dataset
The dataset used contains metadata about Udemy courses such as:
- Course title
- Price
- Number of subscribers
- Level
- Subject
- Published date
- Profit

---

## 🛠️ Technologies & Libraries Used

- Python
- pandas, numpy
- matplotlib, seaborn
- `neattext` for text preprocessing
- `sklearn` for feature extraction and similarity calculation

---

## 🔎 Steps in the Project

1. **Data Import & Exploration**
   - Load and explore the Udemy dataset
2. **Data Preprocessing**
   - Clean course titles by removing stopwords and special characters
3. **Feature Extraction**
   - Use `CountVectorizer` to convert course titles into token vectors
4. **Similarity Calculation**
   - Compute **Cosine Similarity** between all course titles
5. **Recommendation Engine**
   - Build a function to recommend similar courses based on a selected title

---

## 📦 How to Use

You can call the main function:

```python
recommend_course('Beginner to Pro - Financial Analysis in Excel 2017', numrec=5)
