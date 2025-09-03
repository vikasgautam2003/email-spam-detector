# Spam Classifier 📧🤖

A simple machine learning model to classify messages as **Spam** or **Not Spam** using **Naïve Bayes** and **Bag of Words (CountVectorizer)**.  

---

## 🚀 Features
- Detects whether a message/email is spam or not.
- Uses **Multinomial Naïve Bayes**, a classic text classification algorithm.
- End-to-end pipeline with **CountVectorizer + Classifier**.
- Easy to train, test, and extend with real datasets.

---

## ⚙️ Installation

1. Clone the repository
2. 2. Create a virtual environment (recommended)
3. Install dependencies


---

## 📊 Example Dataset
The project works on any text dataset with two columns:
- `Message`: The text of the message/email
- `spam`: Label (`1` = Spam, `0` = Not Spam)

Example:

| Message                                      | spam |
|----------------------------------------------|------|
| Win money now!!!                             | 1    |
| Hey, are we still meeting tomorrow?          | 0    |
| Urgent: Your account has been compromised    | 1    |
| Let's catch up over lunch                    | 0    |

---

