# 🎬 Movie Recommendation System  

## 📌 Overview  
This repository contains the implementation of a **Movie Recommendation System**, leveraging **Content-Based Filtering (CBF) and Collaborative Filtering (CF)** to provide personalized movie recommendations. The system is built using **multiple machine learning models** and trained on **real-world datasets** from reputable sources.  

---

## 📂 Datasets  

Our recommendation system is built using **four original datasets** downloaded from two reliable sources:  

1. **MovieLens Dataset (GroupLens) 📊**  
   - **Source:** GroupLens Research Lab, University of Minnesota  
   - **Description:** Data collected from real users on the **MovieLens** platform.  
   - **URL:** [MovieLens Dataset](https://grouplens.org/datasets/movielens/latest/)  

2. **TMDB 5000 Movie Dataset (Kaggle) 🎥**  
   - **Source:** Kaggle  
   - **Description:** Metadata on 5000+ movies, including genres, keywords, directors, and cast.  
   - **URL:** [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)  

---

## 🏆 Machine Learning Techniques  

This project explores various **Movie Recommendation Techniques**, categorized as:  

### **📌 1. Content-Based Filtering (CBF)**
- Recommends movies based on their **attributes** (e.g., genres, keywords, directors, and cast).  
- Utilizes **TF-IDF vectorization**, **cosine similarity**, and **machine learning models** to measure movie similarity.  

### **📌 2. Collaborative Filtering (CF)**
- Suggests movies based on **user preferences** and behaviors.  
- Identifies similar users and recommends movies they have rated highly.  
- Implemented using **both Memory-Based (kNN) and Model-Based (SVD) approaches**.  

---

## 🤖 Machine Learning Models  

This project implements the following **ML models** to improve recommendation accuracy:  

| **Model**                    | **Category**               | **Used for**                  |  
|------------------------------|----------------------------|-------------------------------|  
| **k-Nearest Neighbors (kNN)**  | Memory-Based CF            | Finding similar users/movies  |  
| **Linear Regression**         | Model-Based CF (Baseline)  | Predicting user ratings       |  
| **Random Forest**             | Model-Based CF (Advanced)  | Learning user preferences     |  
| **Gradient Boosting**         | Model-Based CF (Advanced)  | Improving prediction accuracy |  
| **Singular Value Decomposition (SVD)** | Matrix Factorization | Predicting missing ratings |  

---

## 🚀 How to Use  

### **🔹 1. Install Dependencies**  
Clone this repository and install the required dependencies:  
```bash
git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
pip install -r requirements.txt
