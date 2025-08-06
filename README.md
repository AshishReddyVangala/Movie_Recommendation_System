# 🎬 Movie Recommendation System

This is a simple and interactive **Content-Based Movie Recommendation System** built using Python, pandas, scikit-learn, and NLP techniques. It suggests similar movies based on the content of a selected movie using **TF-IDF Vectorization** and **Cosine Similarity**.

---

## 📌 Features

- Recommends **top 10 similar movies** based on your input
- Uses **genres, keywords, tagline, cast, and director** to find similar movies
- Handles spelling mistakes in movie titles using **fuzzy matching**
- Includes **data analysis and visualization**:
  - Top 10 most common movie genres
  - Top 10 IMDb rated movies

---

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- TF-IDF Vectorizer
- Cosine Similarity
- difflib (fuzzy string matching)

---

## 📊 Dataset

- Format: `movies.csv`
- Contains metadata about movies (title, genres, keywords, tagline, cast, director, vote_average, etc.)

> Upload your `movies.csv` file before running the code in Google Colab or Jupyter Notebook.

---

## 🚀 How to Run

1. Clone the repository or upload to Google Colab
2. Make sure your `movies.csv` file is in the same directory
3. Run the notebook or script
4. Type a movie name and get similar recommendations


## 📄 License

This project is open source and available under the [MIT License](LICENSE).