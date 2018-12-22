# MusicRecsys

Based on KKBOX (a music streamining app) data our listening history and user & song information, we used different recommendation algorithms including latent factor model, feature engineering with XGboost and Song2Vec.

The Song2Vec is generalization of Word2Vec in NLP. We also average the song2vec of an artist to create Artist2Vec. The figure below is a T-SNE dimension reduction visualization of the Artist2Vec.

![T-SNE 2D Visualization of Artist2Vec](https://github.com/WQtong/MusicRecsys/blob/master/image/art2vec.png)
