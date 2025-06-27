# book-Recommendation
 Book Recommendation System

This is a Flask-based Book Recommendation System that suggests books to users based on similar readers’ preferences. It uses machine learning to find and recommend top books for a given user input.

---

 Features

- 📖 Recommend similar books based on user input
- 🔍 Search by book title
- 🎨 Clean and simple web interface using HTML + CSS (Flask templates)
- 💾 Pre-trained recommendation model
- ⚡ Fast and lightweight – runs locally

---

 Folder Structure

book_recommender_system/
│
├── app.py                  # Main Flask backend  
├── templates/              # HTML files (index.html, recommend.html)  
├── static/                 # CSS, JS, images  
├── model.pkl               # Trained recommendation model  
├── books.csv               # Dataset (metadata)  
├── recommendations.csv     # Similarity matrix / processed data  
├── requirements.txt        # Project dependencies  
└── README.md               # Project documentation

---

 How it Works

- Uses cosine similarity between books read by users  
- When a user enters a book title, it finds the most similar books from the dataset using a precomputed similarity matrix  
- Returns top N recommended books with titles, authors, and images

---

 Requirements

Install dependencies using:

---

 Running the App
 
Then open your browser and go to:
http://127.0.0.1:5000/

---

## 📊 Dataset

The model was trained on the **Book-Crossing dataset**, which includes:
- Book titles
- Authors
- User ratings
- Book image URLs

---

 Tech Stack

- **Frontend:** HTML, CSS (Jinja templates)  
- **Backend:** Flask (Python)  
- **ML:** Cosine similarity, Pandas, Scikit-learn  
- **Deployment ready** – can be hosted on Render, Heroku, or GitHub Pages (via API)

---

 Future Improvements

- Add user login and ratings  
- Use deep learning for better personalization  
- Host it online (Render/Heroku)  
- Add book cover previews dynamically

---

 Author

**Megha Solanki**  
📧 meghasolanki65@gmail.com  
🔗 GitHub: [Megha31Solanki](https://github.com/Megha31Solanki)

---

# Show Your Support

If you liked this project, please ⭐️ the repo to support my work!  
Pull requests and suggestions are always welcome 😊




