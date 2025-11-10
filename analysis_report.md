# Spam Detection Analysis Report

## How My Model Learns

My spam detector uses a **Decision Tree Classifier** to decide if an email is spam or not. It looks at a few features that usually make emails suspicious.

### Features I Used
1. **Word Count** – Spam emails are often shorter.  
2. **Exclamation Marks** – Spammers use these to grab attention.  
3. **Money Words** – Words like “free,” “cash,” or “win” often appear in spam.  
4. **ALL CAPS** – Spammers use capital letters to make messages look urgent.

---

## Training Results
- **Training Accuracy:** 100%  
- **Testing Accuracy:** 100%

### What This Means
The model correctly identified every email in both training and testing. This means it learned the patterns in the data well.

---

## Preventing Overfitting
I avoided overfitting by:
- Splitting the data into training and test sets.  
- Adding small random changes to make more examples.

---

## Real-World Application
If used in Gmail:
- **Strengths:** Fast, simple, and good at spotting obvious spam.  
- **Weaknesses:** Small dataset and limited features.  
- **Improvements:** Use real email data, add text analysis, and try more advanced models.

---

## What I Learned
I learned how a machine learning model can be trained to recognize patterns and make predictions. I also learned how to prepare data, test a model, and visualize results. This helped me understand how spam filters work in real life.

