# 🎬 Movie Recommendation System

A smart **content-based movie recommendation system** built with **Python, NLP, and Machine Learning**.  
The system helps users discover movies similar to their preferences by analyzing textual data from the IMDB dataset.  

---

## 🚀 Features
- **KNN (k-Nearest Neighbors)** with **cosine similarity** for recommendations.  
- **TF-IDF vectorization** to capture movie plot features.  
- **NLP preprocessing**: tokenization, stopword removal, stemming for clean text analysis.  
- **Interactive Streamlit web app** for user-friendly movie search and recommendations.  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn, NLTK)  
- **Streamlit** for frontend web interface  
- **IMDB dataset** (movies metadata)  

---

## 📂 Project Structure
```

├── app.py               # Streamlit app entry point
├── model.ipynb          # Jupyter Notebook for training & preprocessing
├── requirements.txt     # Dependencies
├── data/                # Dataset (IMDB movies metadata)
└── README.md            # Documentation

````

---

## ⚙️ Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/narasimha-1412/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:

   ```bash
   streamlit run app.py
   ```

---

## 🎯 Real-World Use Case

This project solves the problem of **choice overload** in streaming platforms.
By analyzing movie metadata and user selections, it **guides viewers toward personalized recommendations**, similar to how Netflix or Prime Video suggest content.

---

## 📸 Demo

(Add screenshots or GIFs of your Streamlit app here)

---

## 🙌 Acknowledgements

* [IMDB dataset](https://www.imdb.com/interfaces/)
* [Scikit-learn](https://scikit-learn.org/)
* [Streamlit](https://streamlit.io/)

```

