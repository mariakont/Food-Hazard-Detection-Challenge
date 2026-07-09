# Food Hazard Detection (SemEval 2025)

> Machine Learning project developed for **SemEval 2025 Task 9 – The Food Hazard Detection Challenge**.

This project applies Natural Language Processing (NLP) and transformer-based deep learning models to automatically identify food hazards from textual incident reports.

The solution addresses both official competition subtasks using transformer-based text classification models built on BERT.

---

## Overview

Food safety agencies process thousands of incident reports every year. Automatically identifying the type of food hazard and the affected product can significantly accelerate food safety monitoring and risk assessment.

This project was developed as part of the **SemEval 2025 Food Hazard Detection Challenge**, focusing on transformer-based NLP models for multi-class classification.

---

## Objectives

The project addresses both official competition tasks:

### ST1 — Food Hazard Prediction

Predict:

- Hazard Category
- Product Category

from food incident reports.

### ST2 — Hazard & Product Detection

Predict the exact:

- Hazard
- Product

mentioned in each food incident report.

---

## Methodology

The overall workflow consists of:

1. Dataset loading and preprocessing
2. Data exploration and quality analysis
3. Text tokenization using the BERT tokenizer
4. Fine-tuning pre-trained BERT models
5. Model evaluation
6. Submission file generation for both SemEval tasks

Separate BERT classification models were trained for the required prediction targets.

---

## Technologies

- Python
- PyTorch
- Hugging Face Transformers
- BERT
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Structure

```
.
├── FoodHazardDetection.ipynb
└── README.md
```

---

## Model Pipeline

- Data preprocessing
- Label encoding
- BERT tokenization
- Fine-tuning pre-trained BERT models
- Classification
- Evaluation
- Competition submission generation

---

## Evaluation

The notebook includes:

- Classification reports
- Confusion matrix visualization
- Weighted F1-score evaluation
- Generation of the official SemEval submission files for both competition subtasks

---

## Learning Outcomes

This project provided hands-on experience with:

- Natural Language Processing (NLP)
- Transformer-based language models
- BERT fine-tuning
- Multi-class text classification
- Deep learning using PyTorch
- Machine learning model evaluation
- End-to-end NLP pipeline development

---

## References

- SemEval 2025 Task 9 – Food Hazard Detection Challenge
- Hugging Face Transformers
- PyTorch

---

## Author

**Maria Kontogiannopoulou**

BSc in Management Science and Technology  
Athens University of Economics and Business

Specialization:
Software and Data Analysis Technologies
