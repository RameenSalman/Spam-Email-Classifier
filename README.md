# Spam Email Classifier (Python)

A machine-learning-based system that classifies emails as spam or not using Logistic Regression. It extracts features from email text (keywords, links, capitalized words) and includes a statistical anomaly check for unusual sender behavior. The dataset is synthetic.

---

**Features**

* ML Classification: Logistic Regression for spam detection
* Feature Extraction: Keywords, links, capitalized words
* Anomaly Detection: Flags unusual patterns in sender behavior

---

**Project Files**

* spam_classifier.py — Main script
* email_dataset.xlsx — Synthetic dataset
* requirements.txt — Python dependencies

---

**Requirements**

Install the required Python libraries using requirements.txt or manually: numpy, pandas, scikit-learn, openpyxl.

---

**Usage**

1. Ensure email_dataset.xlsx is in the same folder as spam_classifier.py.
2. Run the script.
3. Enter the email content when prompted.
4. The script outputs feature counts, spam probability, anomaly check result, and final verdict (Spam / Not Spam / Suspicious).

