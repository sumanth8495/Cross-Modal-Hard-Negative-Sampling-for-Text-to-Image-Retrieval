# Cross-Modal Hard Negative Sampling for Text-to-Image Retrieval

This project adapts **DPR-style bi-encoders** to the **text→image retrieval** domain and integrates **QuRe’s score-drop heuristic** for **hard negative mining**.  
We benchmark against **DPR-inspired strategies (ANCE, ICT)** and compare **CLIP + QuRe** vs **CLIP + Random** sampling.

## Comparison of Hard Negative Sampling Methods

**Note**: 1% Train Set + 25% Test Set

| Metric | CLIP + QuRe | CLIP + Random | Δ (Improvement) |
|:-------|-------------:|--------------:|----------------:|
| **MRR** | 42.6440% | 41.6925% | **+0.95%** |
| **Precision@1 / Recall@1** | 30.7532% | 29.8577% | **+0.90%** |
| **Precision@2 / Recall@2** | 41.6920% | 40.1087% | **+1.58%** |
| **Precision@3 / Recall@3** | 47.4172% | 46.3298% | **+1.09%** |
| **Precision@4 / Recall@4** | 51.6072% | 50.9036% | **+0.70%** |
| **Precision@5 / Recall@5** | 55.4934% | 54.4539% | **+1.04%** |
| **Precision@6 / Recall@6** | 58.3240% | 57.3325% | **+0.99%** |
| **Precision@7 / Recall@7** | 60.7069% | 59.6834% | **+1.02%** |
| **Precision@8 / Recall@8** | 62.4500% | 61.6664% | **+0.78%** |
| **Precision@9 / Recall@9** | 64.4011% | 63.9053% | **+0.50%** |
| **Precision@10 / Recall@10** | 66.2882% | 65.8564% | **+0.43%** |
