 Movie Recommender System  

This project is a **Content-Based Movie Recommendation System** built with **Python, Scikit-learn, and Streamlit**.  
It recommends movies similar to a selected title using **NLP preprocessing, vectorization, and cosine similarity**.  

The project has two parts:  
1. **Jupyter Notebook (`movie-recommender-sys.ipynb`)** → Data preprocessing, feature engineering, model building.  
2. **Streamlit App (`app.py`)** → Interactive web app for movie recommendations with posters.  

---

## 🚀 Features
- Recommend **top 5 similar movies** based on a chosen movie.  
- Uses **content-based filtering** (genres, cast, crew, keywords, overview).  
- **Cosine Similarity** for finding nearest movies.  
- **Stemming function** for better text matching.  
- Fetches **movie posters** from **TMDB API**.  
- Simple, interactive **Streamlit UI**.  

---

## 🛠️ Tech Stack
- **Python** (pandas, numpy, sklearn, pickle, requests)  
- **NLP**: CountVectorizer, stemming  
- **Similarity**: Cosine Similarity  
- **Frontend**: Streamlit  
- **Dataset**: [TMDB 5000 Movies](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)  

---

## 📂 Project Structure
movie-recommender-system/
│
├── app.py # Streamlit app
├── movie-recommender-sys.ipynb # Notebook for preprocessing & model building
├── model/
│ ├── movie_list.pkl # Pickled movies dataframe
│ ├── similarity.pkl # Pickled similarity matrix
├── requirements.txt # Python dependencies
└── README.md # Project documentation

---

## Setup & Installation

1. **Clone the repository**  
```bash
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system

