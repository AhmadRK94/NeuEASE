# NeuEASE
Pytorch implementation of the EASE method for collaborative filtering

There are two notebooks in this repo:
  1) EASE.ipynb which is a numpy implementation of a closed-formed version of EASE that proposed in the original paper: https://arxiv.org/abs/1905.03375
  2) NeuEASE.ipynb which is a PyTorch implementation of the neural network version of EASE.

Note: The dataset is movielens 1m and it contain both positive and negative implicit feedbacks. for preprocessing steps look at my other repo: https://github.com/AhmadRK94/RecSys-CF
