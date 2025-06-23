# 📚 Book Recommendation System

A web-based book recommendation system that suggests similar books based on user input using collaborative filtering.

## 🚀 Live Demo

👉 [Book Recommendation App on Render](https://book-recommendation-system-xtr1.onrender.com)

---

## 🧠 Project Objective

The goal of this project is to build a machine learning-powered recommendation engine that recommends books based on a given book title. This system uses **similarity scores** and **user preferences** to suggest books that users are likely to enjoy.

---

## 📦 Tech Stack

* **Python 3**
* **Flask** (Web Framework)
* **Pandas, NumPy** (Data Processing)
* **Pickle** (Model Serialization)
* **HTML, CSS, Bootstrap** (Frontend)
* **Render** (Deployment)
* **Git & GitHub** (Version Control)

---

## 📊 Dataset

The dataset used is based on book ratings and metadata such as:

* Book title
* Author name
* Book cover image URL
* Number of votes
* Average rating

*Note:* Data was preprocessed, filtered, and transformed before building the model.

---

## 🔍 Features

* Recommends 4 similar books based on selected input
* Beautiful, responsive UI using Bootstrap
* Auto-complete feature in form input (using HTML datalist)
* Deployed online using Render (free tier)
* Built with proper folder structure and deployment-ready code

---

## 🛠️ How to Run Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/Pragya26-techie/Book-Recommendation-System.git
   cd Book-Recommendation-System
   ```

2. Create virtual environment (optional but recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # on Windows: venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the app:

   ```bash
   python app.py
   ```

5. Open your browser:

   ```
   http://localhost:5000
   ```

---

## 📂 Project Structure

```
├── app.py
├── templates/
│   ├── index.html
│   └── recommend.html
|
├── popular.pkl
├── pt.pkl
├── Books.pkl
├── similarity_scores.pkl
├── requirements.txt
└── README.md
```

---

## 🧪 Sample Input

> 📖 Book Title: *Harry Potter and the Sorcerer's Stone*
> ✅ Output:
>
> * The Hobbit
> * Percy Jackson
> * Eragon
> * Inkheart

---

## 💡 Future Improvements

* Add login/signup using Flask-Login
* Add content-based recommendation using NLP
* Enable user ratings and feedback
* Add search filtering and genre-based suggestions

---

## 👤 Author

Made with ❤️ by **Pragya Bharti**
📬 [LinkedIn](https://www.linkedin.com/in/your-link/) • [GitHub](https://github.com/Pragya26-techie)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
