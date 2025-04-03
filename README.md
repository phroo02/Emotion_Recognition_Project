# NLP Emotion Recognition Project

## Overview

This repository contains a machine learning project that implements emotion recognition from text data. Developed as part of a guided course on Coursera, the project demonstrates end-to-end natural language processing (NLP) techniques—covering data preprocessing, feature extraction, model building, and evaluation.

## Project Description

The goal of this project is to classify text samples into different emotion categories. The project walks through the following steps:
- **Data Preprocessing:** Cleaning and tokenizing text data, including stop-word removal and normalization.
- **Feature Extraction:** Converting text into numerical features using methods such as TF-IDF or count vectorization.
- **Model Building:** Training and comparing different machine learning classifiers to predict emotions.
- **Evaluation:** Assessing model performance with metrics like accuracy, precision, recall, and F1-score, supported by visualizations (e.g., confusion matrices).

The complete code and analysis can be found in the Jupyter Notebook `main.ipynb`.


## Installation

Follow these steps to set up the project locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/phroo02/Emotion_Recognition_Project.git
   cd emotion-recognition
   
2. **Set Up a Virtual Environment (Recommended):**
   ```bash
    python -m venv env
    source env/bin/activate  # On Windows: env\Scripts\activate


3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt

## Usage
To run the project, open the notebook using Jupyter Notebook or JupyterLab:
  ```bash
  jupyter notebook main.ipynb
```
Follow the instructions in the notebook to execute each cell sequentially and explore the process from data preparation to model evaluation.


## Project Highlights

- **Data Preprocessing:** Involves cleaning, tokenizing, and normalizing text data to make it suitable for feature extraction.

- **Feature Extraction:** Uses vectorization techniques (e.g., TF-IDF, Count Vectorizer) to convert text into features that can be processed by machine learning models.


- **Model Building:** Implements various classifiers and compares their performance on emotion recognition tasks.

- **Evaluation:** Uses a range of evaluation metrics and visual tools such as confusion matrices to analyze model performance.

## Future Enhancements
- **Deep Learning Models:** Explore more advanced models (e.g., LSTM, transformers) for potentially improved performance.

- **Data Augmentation:** Investigate data augmentation techniques to handle limited or imbalanced datasets.

- **Extended Analysis:** Implements various classifiers and compares their performance on emotion recognition tasks.

- **Evaluation:** Enhance the evaluation section with cross-validation and additional performance metrics.

 ## Acknowledgements
- **Coursera:** This project was developed as part of a Coursera guided project on NLP and machine learning.

- **Open-Source Libraries:** Special thanks to the developers of the Python libraries and frameworks used in this project.






















