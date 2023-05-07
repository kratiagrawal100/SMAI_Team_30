# SMAI_Team_37
## Project SMAI
# Unsupervised Domain Adaptation by backpropogation
Domain Adaptation provides an attractive option that labelled data similar nature but from a different domain are available.
This paper proposed an approach that can be trained on large amount of labeled data from source domain and large amount of unlabeled data from target domain.

### Codebase:
Submit folder carries python notebooks(.ipynb) corresponding to each experiment:
Domain_adaptation_MNIST_MNISTM :this contains experiment for source as MNIST and target as MNISTM
Domain_adaptation_MNIST_SVHN:this contains experiment for source as MNIST and target as SVHN
Domain_adaptation_SVHN_MNIST:this contains experiment for source as SVHN and target as MNIST
ASL_Experiment:this contains experiment for source as ASL and target as ASLM

All experiments are carried out for three scenarios:
1. source only as training
2. Domain adaptation
3. target data only as training

Model checkpoints: https://drive.google.com/drive/folders/1-0YUodKk9FTDbyCmY9O6U366nsuF5h8z?usp=sharing
ASL data link: https://drive.google.com/file/d/1ZDOnPoBCNLjLHgRl5ZVnSFaG_-9oRO9b/view?usp=share_link

### how to run:
Load notebooks on colab(change runtime to GPU)
load the model using the appropraite saved model
To run the notebook no data loading is required but for ASL_experiment load the data first from the below link.
Run all cells to train the model from scratch.
