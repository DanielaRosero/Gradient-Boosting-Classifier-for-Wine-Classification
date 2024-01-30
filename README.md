# Gradient-Boosting-Classifier-for-Wine-Classification with Weights & Biases

C:\Users\danyr\Downloads\Gold Glasses National Wine Day Social Media Graphic.png

This repository contains an experimentation project from the Data Science class at Upgrade Hub (an educational institution). We utilize Weights & Biases to systematically tune and evaluate the hyperparameters of a Gradient Boosting Classifier. The dataset we are working with is the Wine dataset.

## Results

The experimentation results can be viewed in detail on the Weights & Biases dashboard. This includes various performance metrics such as accuracy, along with the hyperparameters used for each experiment.

🔗 [View Experimentation Results]([https://api.wandb.ai/links/demstalfer/qnqgjsqc](https://wandb.ai/drsoler94/vinitoupgrade/reports/GradientBoosting-Wine-classification-with-Wandb--Vmlldzo2NjgyNTE5))

## Problem Description

Our intention is to predict the category of wine based on several physicochemical attributes. The Wine dataset is a common benchmark dataset in the machine learning community.

## Dataset

The Wine dataset is a publicly available dataset that contains 178 samples of wines with 13 different attributes such as Alcohol content, Malic acid, Ash, etc. There are three classes, representing three different types of wines. The dataset is well-suited for classification experiments.

## Experimentation

For this project, we utilize the Gradient Boosting Classifier, a powerful ensemble machine learning algorithm that builds on decision trees. It is particularly known for its effectiveness in classification problems.

To find the best model, we explore various combinations of hyperparameters such as learning rate, maximum depth of the trees, the number of estimators, etc. Through systematic experimentation, we aim to understand the effect of these hyperparameters on the model's performance and find the combination that yields the best results.

We integrate Weights & Biases into our experimentation pipeline, which allows us to log the hyperparameters and the performance metrics for each experiment. Weights & Biases provides us with an interactive dashboard where we can visualize and analyze the results.

## Hyperparameter Tuning and Best Model

During the experimentation process, we performed an extensive search over the hyperparameter space. A total of **384 different combinations** of hyperparameters were tested to find the model that yields the best performance. The hyperparameters that we tuned include:

- Learning rate
- Maximum depth of the trees
- Number of estimators
- Loss function
- Subsample fraction
- Minimum number of samples required to split an internal node
- Minimum number of samples required to be at a leaf node

This extensive search allowed us to explore a wide range of models and identify the combination of hyperparameters that optimizes the performance for this specific dataset.

The model with the best score achieved an accuracy of **0.9815**. This high level of accuracy indicates that the model is highly effective in classifying the wine samples correctly. The hyperparameters of the best model are as follows:

- Learning rate: 0.53
- Loss function: deviance
- Max depth: 6
- min_samples_leaf: 2
- min_samples_split: 4
- n_estimators: 130
- subsample: 1

This combination of hyperparameters allowed the Gradient Boosting Classifier to capture the underlying patterns in the data efficiently and make highly accurate predictions.

## Running the Code

To run the code, first, ensure you have all the dependencies installed: read requirements

## Contributions

Contributions to this repository are welcome. Please, ensure that the code follows best practices and is well-documented.

## License

This project is licensed under the MIT License.
