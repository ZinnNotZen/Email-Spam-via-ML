# Email-Spam-via-ML
This project creates a model that filters out spam emails using machine learning, creating a spam filter with 98% accuracy. 

---

# Confusion Matrix using trigram
<img width="521" height="434" alt="Confusion Matrix (using trigram model)" src="https://github.com/user-attachments/assets/f6735678-a14a-4e18-8d2a-8563955c262d" />

---

## Project Objectives
To createa a email filter by useing machine learning
To find out how much the accuracy will change when using unigram vs bigram vs trigram

---

## Key Insights
There was not a significat accuracy increace when using unigrams vs bigrams vs trigrams for this data set.
For this data set, the trigram was the most accurate by only 0.02%
The spam filter is 98% accurate

---

## Tools & Technologies

* Python (Pandas, NumPy, Matplotlib, Scikit-learn)
* Git & GitHub

---

## Repository Structure
```
Email-Spam-via-ML/
│
├── data/
│   Raw CSV datasets
│
├── notebooks/
│   ml_spam.ipynb (EDA and visualization)
│
├── images/
│   Confusion Matrix (using trigram model).png
│   Model Accuracy by N-gram Type.png
│   Top Spam Indicators (for trigram model).png
│   Unigram top spam words.png
│
├── README.md
└── requirements.txt
```

---

## Key Calculations
** Accuracy 
```
print("Accuracy:", accuracy_score(y_test, y_pred))
```
---

## Dataset
This data was found on Kaggle: https://www.kaggle.com/datasets/jackksoncsie/spam-email-dataset

---

## Author
Rowan Zinn
MS Data Science – Western Governors University

GitHub: https://github.com/ZinnNotZen
