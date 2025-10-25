# 🎬 Movie Recommendation System

> A project demonstrating how **mathematics powers recommendation systems** using linear algebra, vector similarity, and data analysis — built as part of the **Maths for Computer Science** course.

---

## 🧠 Overview

This project implements a **Movie Recommendation System** that suggests movies similar to the ones a user has rated highly.  
It applies the **K-Nearest Neighbors (KNN)** algorithm with **cosine similarity** to identify movies with similar user-rating patterns.

The system is built using real-world datasets from the **MovieLens** database (`movies.csv` and `ratings.csv`) and demonstrates how mathematical and statistical concepts can be applied to build intelligent systems.

---

## 🧮 Mathematical Concepts Used

| Concept | Role in Project |
|----------|----------------|
| **Linear Algebra** | Represents user–movie relationships as a sparse matrix (CSR format). |
| **Cosine Similarity** | Measures the closeness between movie vectors in high-dimensional space. |
| **Discrete Mathematics** | Maps unique users and movies using integer mappings (bijection). |
| **Statistics** | Calculates averages, distributions, and frequency of ratings. |
| **Algorithmic Thinking** | Implements K-Nearest Neighbors to find similar movies efficiently. |

---

## 🧰 Tech Stack

- **Programming Language:** Python 3  
- **Libraries Used:**
  - `NumPy` — numerical computation  
  - `Pandas` — data manipulation  
  - `SciPy` — sparse matrix representation  
  - `Scikit-learn` — KNN algorithm  
  - `Matplotlib` & `Seaborn` — data visualization

---

## 🚀 How It Works

1. **Data Loading**  
   Load movie and rating data from CSV files.

2. **Matrix Construction**  
   Create a **User–Item Matrix** using a **Compressed Sparse Row (CSR)** structure to efficiently store large rating data.

3. **Movie Similarity Calculation**  
   Apply **KNN with cosine similarity** to find movies that have similar user rating patterns.

4. **Recommendation Generation**  
   For a given user:
   - Find their highest-rated movie.
   - Recommend top *k* movies most similar to it.

5. **Visualization**  
   - Bar chart of the **most active users**.  
   - Line chart showing **average rating trends over years**.

---
