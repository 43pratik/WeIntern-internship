# Week 2 – Text Classification Model (SMS Spam Detection)

## Overview
This project was completed as **Week 2 task** of my internship at **WeIntern**.  
The goal of this task was to build a **Text Classification Model** using basic **Natural Language Processing (NLP)** techniques to classify SMS messages as **Spam** or **Ham (Not Spam)**.

This project focuses on understanding how raw text data is cleaned, converted into numerical features, and used by a machine learning model for classification.


## Dataset
**Dataset Used:** SMS Spam Collection Dataset  

The dataset contains a collection of SMS messages labeled into two categories:
- **Spam** – Unwanted or promotional messages
- **Ham** – Legitimate or normal messages

### Dataset Structure
- `label` → spam / ham  
- `message` → SMS text content  

**Dataset Source:** Kaggle


## Problem Statement
Machine learning models cannot directly understand raw text.  
The challenge is to:
 1. Clean and preprocess text data
 2. Convert text into numerical form
 3. Train a model that can accurately classify messages



## Approach & Methodology

### 1️⃣ Text Preprocessing
To prepare the text for modeling, the following preprocessing steps were applied:
 1. Converted text to lowercase
 2. Tokenized sentences into words
 3. Removed stopwords (common words like *is, the, and*)
 4. Removed special characters and unnecessary symbols

These steps help reduce noise and improve model performance.


### 2️⃣ Text Vectorization
Since machine learning models work on numbers, the cleaned text was converted into numerical features using:
**Bag of Words (Count Vectorization)**

This technique represents text based on word frequency.


### 3️⃣ Model Training
 1. The dataset was split into training and testing sets
 2. A machine learning classification model was trained on the vectorized text
 3. The model learned patterns associated with spam and ham messages


### 4️⃣ Model Evaluation
The trained model was evaluated using:
 1. Accuracy score
 2. Sample predictions on unseen messages

This helps measure how well the model generalizes to new data.


## Technologies & Libraries Used
 1. **Python**
 2. **Pandas** – data handling
 3. **NumPy** – numerical operations
 4. **NLTK** – text preprocessing
 5. **Scikit-learn** – vectorization and model training


## How to Run the Project
 1. Open the notebook `WeIntern_Task_2.ipynb` from the `code` folder.
 2. Run all cells sequentially.
 3. Observe preprocessing steps, model training, and evaluation results.
 4. Check output accuracy and sample predictions.


## Output
 1. Classification accuracy of the text model
 2. Correct predictions for spam and ham messages
 3. Output screenshots are available in the `output` folder


## Key Learnings
 1. Understood the complete NLP pipeline
 2. Learned how text data is cleaned and processed
 3. Gained hands-on experience with text vectorization
 4. Built a real-world text classification model
 5. Improved understanding of supervised learning for NLP tasks


## Conclusion
This task helped strengthen my understanding of **Natural Language Processing fundamentals** and **text classification workflows**.  
It provided practical experience in handling text data and building machine learning models for real-world applications.
