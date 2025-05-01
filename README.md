# Movie Recommendation System 🎬

This project is a simple movie recommender system using **Streamlit** and **collaborative filtering**.

It suggests movies similar to the one you select, displaying posters and titles.

---

## 💻 Features

- Recommend top 5 similar movies.
- Display posters using The Movie Database (TMDb) API.
- User-friendly Streamlit web app.

---

## 📂 Project Structure

```
.
├── Movie Recommendation System.ipynb  # Jupyter notebook with development and experiments
├── Movie_Rec.py                      # Streamlit app code
├── movie_list.pkl                    # Pickled movie metadata (not uploaded to GitHub)
├── similarity.pkl                    # Pickled similarity matrix (not uploaded to GitHub)
└── README.md                         # This file
```

---

## ⚙️ Requirements

- Python 3.8+
- `streamlit`
- `pandas`
- `requests`

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1️⃣ Make sure `movie_list.pkl` and `similarity.pkl` are present locally (these are not uploaded to GitHub due to size).

2️⃣ Run the Streamlit app:

```bash
streamlit run Movie_Rec.py
```

3️⃣ Open the local URL shown in the terminal to interact with the app.

---

## 🔑 API Key

The project uses TMDb API:

- Replace the placeholder API key in `Movie_Rec.py` with your own if needed.

Get a free API key from [TMDb](https://www.themoviedb.org/documentation/api).

---

## 🌟 Acknowledgments

- TMDb for movie data and posters.
- Streamlit for the interactive web app framework.

---

## 👥 Contributors

- Manshul Singla (500107077)
- Navjot Singh Sahi (500107729)
- Ishika Sharma (500107855)

_Enjoy recommending movies! 🍿_
