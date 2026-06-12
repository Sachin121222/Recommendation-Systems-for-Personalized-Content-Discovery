# Recommendation Systems for Personalized Content Discovery

A personalized movie recommendation system built using the Netflix Prize Dataset. This project compares **Item-Based Collaborative Filtering (Item-CF)** and **Singular Value Decomposition (SVD)** to evaluate recommendation quality and rating prediction performance.

## Project Overview

The goal of this project is to build and evaluate recommendation models that can provide personalized movie suggestions to users based on their historical ratings.

### Models Implemented

- **Item-Based Collaborative Filtering (Item-CF)** using cosine similarity
- **Matrix Factorization (SVD)** using the Surprise library

### Evaluation Metrics

- **RMSE (Root Mean Squared Error)** for rating prediction accuracy
- **MAP@10 (Mean Average Precision at 10)** for recommendation ranking quality

---

## Dataset

Netflix Prize Dataset

- **24,053,764 ratings**
- **470,758 users**
- **4,499 movies**
- **Average Rating:** 3.60 / 5
- **Dataset Sparsity:** 98.86%

---

## Results

| Model | RMSE | MAP@10 |
|-------|------|---------|
| Item-Based CF | 0.9596 | 0.2323 |
| SVD | 0.8475 | 0.0213 |

### Key Insights

- **Item-Based CF** performs significantly better in ranking relevant recommendations.
- **SVD** achieves better rating prediction accuracy.
- The preferred model depends on whether recommendation quality or prediction accuracy is the primary objective.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Surprise
- Matplotlib
- Seaborn

## Author

**Sachin Meena**
