# 📚 Book Recommendation System

The **Book Recommendation System** provides book suggestions using two main approaches: **popularity-based recommendation** and **collaborative filtering-based recommendation**.

## 🚀 Features
- **Popularity-Based Recommendation:** Suggests books with high ratings and review counts.
- **Collaborative Filtering-Based Recommendation:** Uses user ratings to find books similar to the ones they like.
- **Efficient Data Processing:** Cleans and preprocesses book, user, and rating datasets.
- **Cosine Similarity Calculation:** Measures book similarity for better recommendations.

## 📌 How It Works
### **Popularity-Based Recommendation**
1. Analyzes books based on **number of ratings** and **average rating**.
2. Filters out books with fewer than **250 ratings**.
3. Sorts books in **descending order** of average rating.
4. Displays the **top 50 books** with title, author, image, and rating details.

### **Collaborative Filtering-Based Recommendation**
1. Selects users who have rated at least **200 books**.
2. Filters books rated by at least **50 users**.
3. Creates a **pivot table** (books as rows, users as columns, ratings as values).
4. Uses **cosine similarity** to find books with similar rating patterns.
5. Defines a `recommend()` function that takes a book title as input and suggests the **top 5 similar books**.

## 🛠️ Installation
### Prerequisites
Ensure you have the following installed:
- **Python 3.x**
- **pip**

### Clone the Repository
```bash
git clone https://github.com/niteshkumar956/BOOK-RECOMENDATION-SYSTEM.git
cd BOOK-RECOMENDATION-SYSTEM
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the App
```bash
streamlit run app.py
```

## 📂 Project Structure
```
BOOK-RECOMENDATION-SYSTEM/
│── app.py                  # Streamlit app
│── model.pkl               # Pre-trained recommendation model
│── requirements.txt        # Dependencies
│── README.md               # Project Documentation
```

## 📜 Usage
1. Run the **Streamlit app**.
2. Enter a **book title**.
3. Click **Get Recommendations** to see **top 5 similar books**.

## 💡 Contributing
Want to contribute? Follow these steps:
1. **Fork** the repository.
2. Create a **new branch**.
3. Make your changes and **commit** them.
4. Open a **Pull Request**.

## 📬 Contact
For any queries, feel free to reach out:
- GitHub: [@niteshkumar956](https://github.com/niteshkumar956)
- Email: [Your Email Here]

---
### ⭐ Don't forget to **star** this repo if you found it useful! ⭐

