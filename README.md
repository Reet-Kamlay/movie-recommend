# 🎬 Movie Recommendation System

This project is a **content-based movie recommender system** built using Python. It helps users discover similar movies based on metadata such as title, genre, keywords, cast, and crew.

---

## 🔍 Project Overview

The system uses cosine similarity and NLP techniques to suggest movies that are similar to the input movie. It processes and merges datasets, extracts relevant features, and builds a similarity matrix for recommendations.

---

## 📁 Project Structure

- `movie_recommend.ipynb` – Jupyter notebook containing the full implementation of the recommender system.
- `tmdb_5000_credits.csv` – Dataset containing cast and crew details for 5000+ movies.
- `tmdb_5000_movies.csv` – Dataset containing movie overviews, genres, and metadata.
- `similarity.pkl` – Precomputed similarity matrix (pickle format) for fast recommendations.
- `movies_dict.pkl` – Pickled dictionary of all processed movie data.

---

## 📌 Features

- 📦 Content-based filtering using movie metadata
- 🧠 NLP techniques for tag generation
- 📈 Cosine similarity for computing recommendations
- 💾 Preprocessed and serialized data for fast runtime
- ✅ Clean, readable Jupyter notebook with comments and explanations

---

## 🧰 Tech Stack

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Jupyter Notebook
- Pickle

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/Reet-Kamlay/movie-recommend.git
   cd movie-recommend
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy scikit-learn nltk
   ```

3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook movie_recommend.ipynb
   ```

4. **Explore**
   - Search for a movie title.
   - The notebook will return top 5 similar movies.

---

## 🗂 Example

> Input: `"Avatar"`  
> Output:  
> - John Carter  
> - Guardians of the Galaxy  
> - Prince of Persia: The Sands of Time  
> - Pirates of the Caribbean: At World's End  
> - Battleship  

---

## 👤 Author

**Reet Kamlay**  
📎 [GitHub](https://github.com/Reet-Kamlay)  
🔗 [LinkedIn](https://www.linkedin.com/in/reetkamlay/)

---

⭐ If you like this project, consider starring the repo!
