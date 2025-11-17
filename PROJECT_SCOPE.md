# Project Scope: Next-Gen Session-Based Recommender for Spotify

## Objective
Build a session-aware music recommender prototype focused on Indian-origin tracks, demonstrating measurable improvement over collaborative filtering baselines.

## Deliverables
- Sessionized dataset pipeline
- Baseline CF models (Item-KNN, ALS)
- Transformer-based session model
- Hybrid recommender with re-ranking
- Evaluation (Hit@K, MRR, NDCG, coverage)
- Demo notebook + documentation

## Datasets
- Million Song Dataset
- Kaggle Indian Music datasets
- Custom metadata (language, genre, artist)

## Model Plan
1. Baseline CF
2. Content embeddings from audio+metadata
3. Transformer session model
4. Hybrid fusion + re-ranking
