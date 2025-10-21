# Netflix-Movie-Recommendation-System-using-Machine-Learning

# Netflix Movie Recommendation System

I built a **Netflix Movie Recommendation System** using Python and Machine learning.  
The system recommends movies or TV shows based on their **description, cast, director, and genre**.

---

## 🧩 How It Works

1. Load the Netflix dataset (`netflix_titles.csv`) from Kaggle  
2. Combine text features (`director`, `cast`, `listed_in`, `description`) into a single "tags" column  
3. Use **TF-IDF** to convert text into numbers  
4. Compute **Cosine Similarity** between movies  
5. Build a function `recommend(title)` to show top 10 similar movies

---
