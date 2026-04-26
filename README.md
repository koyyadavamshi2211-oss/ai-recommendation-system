# 🎬 AI Movie Recommendation System

An intelligent movie recommendation system built using **Machine Learning** and **Flask** that suggests movies based on user input using **content-based filtering**.

---

## 📌 Project Overview

This project uses **Artificial Intelligence** techniques to recommend movies similar to the one entered by the user.
It analyzes movie features (genres) and calculates similarity using **Cosine Similarity**.

---

## 🚀 Features

* 🎯 Movie recommendations based on user input
* 🤖 Content-based filtering
* ⚡ Fast and efficient results
* 🌐 Simple web interface using Flask
* 🔍 Case-insensitive and partial search support

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Framework:** Flask
* **Libraries:**

  * Pandas
  * Scikit-learn
  * NumPy
* **Frontend:** HTML, CSS

---

## 📂 Project Structure

```
project/
│
├── app.py
├── movies.csv
├── templates/
│   └── index.html
└── static/
    └── style.css
```

---

## ⚙️ How It Works

1. User enters a movie name
2. System searches for the movie in dataset
3. Converts genres into vectors
4. Computes similarity using cosine similarity
5. Displays top recommended movies

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/koyyadavamshi2211-oss/ai-recommendation-system.git
cd ai-recommendation-system
```

### 2️⃣ Install dependencies

```
pip install flask pandas scikit-learn
```

### 3️⃣ Run the application

```
python app.py
```

### 4️⃣ Open in browser

```
http://127.0.0.1:5000/
```

---

## 📊 Example

**Input:**

```
Toy Story
```

**Output:**

* Similar animated/comedy movies

---

## 🧠 Concepts Used

* Content-Based Filtering
* Cosine Similarity
* Text Vectorization (CountVectorizer)
* Machine Learning Basics

---

## 🔮 Future Enhancements

* Hybrid recommendation system
* User login & personalization
* Integration with movie APIs (TMDB)
* Better UI (React/Angular)
* Mobile application

---

## 👨‍💻 Authors

* **K. Vamshi**
* N. Navaneeth
* M. Adithya Prasad
* T. Bhaskar

---

## 📜 License

This project is for educational purposes.

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
