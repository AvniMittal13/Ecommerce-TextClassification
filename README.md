# Ecommerce-TextClassification

Text classification of E-commerce data descriptions to 4 classes of :

    a) Household
    b) Books
    c) Electronics
    d) Clothing & Accessories

## Dataset

Dataset obtained from Kaggle : [link](https://www.kaggle.com/datasets/saurabhshahane/ecommerce-text-classification)

## Deep learning model using PyTorch

Bidirectional Encoder Representations from Transformers (BERT) was used for Text Classification

## Procedure

### 1. Performed Data Analysis and Pre-processing like :

    - Removing Duplicates
    - Removal of URL's custom stopwords (analysed from Word Clouds and data analysis tools), Tokenization and Lemmatization
    - Balancing dataset due to imbalance present in class labels 
    - In depth analysis of dataset using Word Clouds, Bar Graphs and TSNE Visualization to get idea about category distribution, word distribution, most frequent words, average lengths of descriptions etc.
    
### 2. Deep Learning for Classification

  BERT based model was used for classification with an average accuracy of 94% achieved.
  
  Due to less processing power machine learning models like SVM, Decision Trees, K-nearest neighbours, Logistic regression etc could not be run on the dataset.
