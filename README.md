# Extensive-Case-Study-on-Hyper-Parameter-tuning-techniques
Explore different approaches used in the process of Hyper parameter tuning, to bring out the best of your models.

<img width="1800" height="378" alt="dataset-cover" src="https://github.com/user-attachments/assets/ceddf3ee-c03a-465a-961e-580b1f779473" />

## Genetic Algorithm for Hyperparameter Optimization
Evaluating Search Algorithms for Star/Galaxy Classification (Sloan Digital Sky Survey)

<strong>Key Contributions:</strong> Designed and executed the end-to-end study, comparing various search algorithms for a Decision Tree Classifier.

<strong>Pros:</strong> The Genetic Algorithm (GA) demonstrated clear supremacy, outperforming traditional search methods in both computational efficiency and accuracy benchmarks.

<strong>Cons:</strong> The performance of the GA is highly sensitive to its own initial parameters, requiring precise tuning to reach peak efficiency.

## Flow of Project

1) Data preprocessing => Selection of Features and Class labels
2) 2 classes =>  Start and Galaxy(Balanced data)
3) Defining Genetic Algorithm functions
4) Fitness calculation
  1) Train test split accuray
  2) K fold cross validation avg accuracy
5) Comparison between Genetic Algorithm, Grid Search, Random Search and Bayesian Optimization search
6) In both the cases Genetic algorithm demonstrated  supremacy both in time taking and accuracy benchmark
7) Bayesian optimization is also good but it used 80% of CP cores where as all other algos worked with just 20% of cores
8) Time and accuracy logs can be obseved in the jupyter notebook.

## Dataset Link (Sloan-Digital-Sky-Survey)
1) [Official link](https://www.sdss4.org/dr14/data_access/)

2) [Kaggle link](https://www.kaggle.com/datasets/lucidlenn/sloan-digital-sky-survey)

## Notebook Link

1) [Case-Study-on-Hyper-Parameter-tuning-techniques](https://github.com/sriram936/Extensive-Case-Study-on-Hyper-Parameter-tuning-techniques/blob/main/Experiment_on_SVM.ipynb)
