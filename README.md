# Explainable-news-recommendation

This project implements a personalized news recommendation system using multiple methodologies, including collaborative filtering, word embeddings (Word2Vec), and TF-IDF-based content similarity. The system generates recommendations based on user behavior, article content, and embeddings.

---

## Features

- **Collaborative Filtering**: Recommends articles based on the browsing history of similar users.
- **Content-Based Filtering**: Utilizes Word2Vec and TF-IDF to identify similar articles.
- **Hybrid Approach**: Combines collaborative and content-based methods to enhance recommendation accuracy.
- **Customizable Parameters**: Allows flexible tuning of the recommendation pipeline, including:
  - Number of similar users (`similar_user_k`)
  - Number of recommended articles (`articles_k`)
  - Choice of methodology (`word2vec`, `embeddings`, `tfidf`).

---
