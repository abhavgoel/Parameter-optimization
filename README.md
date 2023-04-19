# Parameter-optimization-of-SVM

The repository contains the R script for optimizing the parameters of SVM 

Dataset - https://archive.ics.uci.edu/ml/datasets/wine


# Attribute information

Input variables (based on physicochemical tests): 

1 - fixed acidity 

2 - volatile acidity 

3 - citric acid 

4 - residual sugar 

5 - chlorides 

6 - free sulfur dioxide 

7 - total sulfur dioxide 

8 - density 

9 - pH 

10 - sulphates 

11 - alcohol 

Output variable (based on sensory data): 

12 - quality (score between 0 and 10)

# Tasks performed

- Download the dataset

- Pre-process the dataset

- Create ten samples

- Split the samples in 70 : 30 for training and testing

- Optimise SVM using randomisation for every sample and report best accuracy and best parameters

- For the best sample plot the convergence graph


# Results

|sample|best_accuracy    |best_kernel|best_nu           |best_epsilon     |
|------|-----------------|-----------|------------------|-----------------|
|S1    |0.649916247906198|laplacedot |0.600165726849809 |0.958756402833387|
|S2    |0.651591289782245|laplacedot |0.162177571561188 |0.727429841179401|
|S3    |0.62751677852349 |laplacedot |0.939081447897479 |0.813470450695604|
|S4    |0.628140703517588|laplacedot |0.712692788802087 |0.705607258714736|
|S5    |0                |           |0                 |0                |
|S6    |0.638190954773869|laplacedot |0.305205665994436 |0.376962826121598|
|S7    |0.644891122278057|laplacedot |0.619259966304526 |0.90585225680843 |
|S8    |0                |           |0                 |0                |
|S9    |0.629815745393635|laplacedot |0.0905253798700869|0.21171743911691 |
|S10   |0.649328859060403|laplacedot |0.332543317927048 |0.137839282630011|


# Convergence Graph
<img width="466" alt="Screenshot 2023-04-19 at 10 15 58 PM" src="https://user-images.githubusercontent.com/72388884/233145898-0d7db216-5910-4981-8655-d6ad7ddfdafa.png">
