# Movie Recommender System

A simple content‑based movie recommendation web app built with Streamlit and Python. Users select a movie title from a dropdown and receive 5 similar movie suggestions based on precomputed similarity scores.

---

## 🚀 Features

- Content‑based filtering using precomputed similarity matrix  
- Interactive web interface via Streamlit  
- Lightweight, easy to deploy  

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
└── README.md                # Project documentation
