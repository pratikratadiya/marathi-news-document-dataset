# Marathi News Documents Dataset for extractive text summarization

A collection of 100 news articles in Marathi language along with their corresponding summaries. The summaries are extractive in nature and have been acknowledged by a language expert.

Results obtained by baseline approaches on this dataset after basic preprocessing steps (stop word removal, suffix stemming) were as follows:

| Approach | ROUGE-1 F1 | ROUGE-2 F1 | ROUGE-L F1 |
| ----- | ------------------ | ---------------- | ---------------- |
| Position based textrank | 0.646 | **0.592** | **0.659** |
| Similarity based textrank | **0.648** | 0.591 | 0.661 |
| SVD | 0.612 | 0.512 | 0.626 |
