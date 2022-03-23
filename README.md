# Tensor applications to RecSys
Here you can find project materials on term of tensor applications to recomendation systems. Mainly it  is related to tensor decompositions, such as Tucker and CPD.

Why it is important.
Recommendation system is very important part of Machine learning. Lot's of companies gain millions of dollars using these systems like Netflix, Google, TikTok etc. The whole business could be done only on the idea of recommendations. 
Tensor - is data structure that provides a huge opportunities of data representation and transforming. Tensor decompositions dive us additional pool of opportunities. We can do matrix factorizations as additional tool to handle with data.

In this repository you can find an approach to use tensors in recomendation system task.
In jupyter notebooks you can find working solutions on 2 datasets.
We use such methods as: random recommendation, Svd, BiVAE, Tucker (HOOI), CoFFee

In our experiments we estimate quality of random recommendation, Svd, BiVAE, CoFFee models using MAP, NDCG, Precision@K, Recall@K. For Tucker and PureSVD models we applied Hit rate, MRR, Coverage quality measures. We provide sensitivity analysis to hyperparameters of Tucker model.
