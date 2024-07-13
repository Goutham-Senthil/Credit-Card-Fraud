# Detection of Credit Card Fraud Using Logistic Regression and AdaBoost Algorithm

## Overview

This project aims to detect fraudulent credit card transactions using two machine learning algorithms: Logistic Regression and AdaBoost. The dataset used for this analysis is sourced from Kaggle and contains a mixture of fraudulent and non-fraudulent transactions.

## Dataset

The dataset used in this project is from Kaggle and can be found [here](https://www.kaggle.com/datasets/kartik2112/fraud-detection). It contains information about credit card transactions, including features such as transaction amount, location, and whether the transaction was fraudulent.

## Requirements

To run this project, download the `requirements.txt` file and install the required libraries:

```bash
pip install -r requirements.txt
```

## Usage

To run the notebook, use the following command:

```bash
jupyter notebook credit_card_fraud.ipynb
```

Follow the steps in the notebook to load the data, preprocess it, and train the models. You can also visualize the results and evaluate the model performance.

## Results

The project achieves an accuracy of approximately 83.85% using the AdaBoost algorithm. The Logistic Regression model also performs well, but with slightly lower accuracy compared to AdaBoost.

## Conclusion

This project demonstrates the use of Logistic Regression and AdaBoost algorithms for detecting fraudulent credit card transactions. The AdaBoost algorithm outperforms Logistic Regression in terms of accuracy. Further improvements can be made by tuning the hyperparameters and exploring other machine learning algorithms.


