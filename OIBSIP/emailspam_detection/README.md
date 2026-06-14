# Email Spam Detection 📧

## Overview

This project focuses on detecting whether an email is Spam or Ham (Not Spam) using Machine Learning and Natural Language Processing (NLP) techniques.

Email spam detection is a real-world classification problem that helps filter unwanted messages and improve email security. The model analyzes email content and predicts whether an email is legitimate or spam.

## Objective

The main objectives of this project are:

* Build a machine learning model to classify emails as Spam or Ham.
* Apply Natural Language Processing (NLP) techniques to text data.
* Perform text preprocessing and feature extraction.
* Evaluate model performance using classification metrics.

## Dataset

The dataset contains email messages labeled as:

* Spam
* Ham (Not Spam)

### Features

* Email Text/Message Content

### Target Variable

* Spam or Ham Classification

## Project Workflow

### 1. Data Collection

* Loaded the email dataset.
* Explored dataset structure and class distribution.

### 2. Data Preprocessing

Performed text cleaning techniques such as:

* Converting text to lowercase
* Removing punctuation
* Removing special characters
* Removing stopwords
* Tokenization

### 3. Feature Extraction

Converted text into numerical features using:

* Count Vectorization
* TF-IDF Vectorization

### 4. Exploratory Data Analysis (EDA)

* Analyzed spam and ham message distributions.
* Visualized important patterns in the dataset.

### 5. Model Building

* Split the dataset into training and testing sets.
* Trained a machine learning classification model.
* Optimized model performance.

### 6. Model Evaluation

Evaluated the model using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* Google Colab / Jupyter Notebook

## Project Structure

```text id="5k9r7n"
Email-Spam-Detection/
│
├── Email_Spam_Detection.ipynb
└── README.md
```

## Results

The trained machine learning model successfully classifies emails into Spam and Ham categories with high accuracy, helping automate email filtering and improve communication security.

## How to Run

### Clone the Repository

```bash id="g5m7q1"
git clone https://github.com/Nikhilth123/OIBSIP
```

### Navigate to Project Directory

```bash id="0j8g4y"
cd Email-Spam-Detection
```

### Install Required Libraries

```bash id="c7h2w9"
pip install pandas numpy matplotlib seaborn scikit-learn nltk
```

### Run the Notebook

Open the notebook in:

* Google Colab
* Jupyter Notebook

and execute all cells.

## Learning Outcomes

Through this project, I gained practical experience in:

* Natural Language Processing (NLP)
* Text Preprocessing
* Feature Extraction
* Machine Learning Classification
* Data Visualization
* Model Evaluation
* Python Data Science Libraries

## Applications

* Email Filtering Systems
* Cybersecurity Solutions
* Spam Detection Services
* Automated Communication Platforms

## Internship Information

This project was completed as part of the **Data Science Internship Program at OASIS INFOBYTE**.

## Author

**Nikhil Thakur**

B.Tech Student, IIEST Shibpur

Aspiring Data Scientist | Machine Learning Enthusiast | Problem Solver
