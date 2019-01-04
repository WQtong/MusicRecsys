# MusicRecsys

_A clear introduction of the Song2Vec method is at my blog: https://medium.com/@weiqi_tong/from-word2vec-to-song2vec-an-embedding-experimentation-9215279c9d7a_

Based on KKBOX (a music streamining app) data our listening history and user & song information, we used different recommendation algorithms including latent factor model, feature engineering with XGboost and Song2Vec.

The Song2Vec is generalization of Word2Vec in NLP. You can download our trained model at: https://www.dropbox.com/s/t75hkzi8wui5ldp/song2vec.model?dl=0

You can play with our mini song recommmender in our folder `mini_song_recommender`. Just run the notebook which has instructions.

We also average the song2vec of an artist to create Artist2Vec. The figure below is a T-SNE dimension reduction visualization of the Artist2Vec.

![T-SNE 2D Visualization of Artist2Vec](https://github.com/WQtong/MusicRecsys/blob/master/image/art2vec.png)
