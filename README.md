# Movie Recommender System

A simple content‑based movie recommendation web app built with Streamlit and Python. Users select a movie title from a dropdown and receive 5 similar movie suggestions based on precomputed similarity scores.

---

## 🚀 Features

- Content‑based filtering using precomputed similarity matrix  
- Interactive web interface via Streamlit  
- Lightweight, easy to deploy  

---

## 📸 Screenshot

![Movie Recommender App Screenshot](https://github.com/user-attachments/assets/19989237-ea39-476c-b721-00239b0f3a4c)

> _Screenshot of the Streamlit UI showing movie selection and recommendations._

---

## 📁 Project Structure

```text
├── .gitattributes           # Git LFS tracking for large files
├── .gitignore               # Ignored files and folders
├── models/                  # (optional) pickled model artifacts
│   └── model.pkl            # (if applicable)
├── movies_dict.pkl          # Pickled dictionary of movie metadata
├── similarity.pkl           # Pickled similarity matrix (tracked with Git LFS)
├── app.py                   # Streamlit application script
├── requirements.txt         # Python dependencies
├── screenshots/             # Folder to store screenshots
│   └── movie_recommender_ui.png
└── README.md                # Project documentation
