# Development of an algorithm for constructing academic disciplines embeddings.

The task objective is to create a model which can transform academic discipline into embedding based on its various available descriptions, including bibliographies of courses, keywords in descriptions, etc.   
The dataset for classification consists of features compiled from the discipline descriptions and dependencies identified using latent semantic indexing.  
A neural network was trained and applied to a dataset to solve the task and was assessed in comparison to the baseline (logistic regression).   
The neural network produced embeddings from compiled dataset similar to which it was trained on.   
The obtained embeddings were reduced using SVD and the optimal hard threshold for singular values. The experimentations with UMAP and autoencoder did not give the desired effects.  
The resulting vector space made it possible to solve applied problems, for example, the search for similar disciplines.  
