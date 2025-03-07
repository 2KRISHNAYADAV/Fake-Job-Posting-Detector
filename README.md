# 🚀 Fake Job Posting Detector

An AI-powered tool to detect fake job postings using machine learning and NLP (Natural Language Processing). Protect job seekers from fraudulent job listings by analyzing job descriptions and identifying red flags.

## 📌 Features

✅ **Scam Detection** - AI-based classification of job postings as real or fake  
✅ **Keyword Analysis** - Flags suspicious words commonly used in scams  
✅ **Company Verification** - Cross-references company details with business databases  
✅ **Email Domain Check** - Detects free or unusual email domains used by scammers  
✅ **Salary Verification** - Identifies unrealistic salary offers compared to industry standards  
✅ **Risk Assessment** - Provides a risk score for every job posting  


---

## 🛠️ Technologies Used

- **Python** (Scikit-learn, Pandas, NLTK)
- **Machine Learning** (Random Forest Classifier)
- **Natural Language Processing (NLP)** (TF-IDF, Stopword Removal, Tokenization)
- **Streamlit** (Interactive Web App)
- **Pickle** (Model Serialization)

---

## 📂 Dataset Used

We use the **[fake_job_postings.csv](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)** dataset, which contains real and fake job postings.  
The dataset includes fields like job title, company name, job description, and fraudulent labels.

---

## ⚡ Installation & Setup

1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your-username/fake-job-detector.git
cd fake-job-detector
```

2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

3️⃣ **Download NLTK Data**
```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```

4️⃣ **Run Model Training**
```bash
python train_model.py
```

5️⃣ **Run Streamlit App**
```bash
streamlit run app.py
```


**some info :**



![Screenshot 2025-03-07 233036](https://github.com/user-attachments/assets/45d6e4ed-957f-4ed0-aaef-5b4e9d4b25da)

---

![Screenshot 2025-03-07 233042](https://github.com/user-attachments/assets/c63d47ad-17ba-47f8-aa55-895ad2e2585c)

---

## 🚀 Usage

### 🎯 **1. Train the Model**
Run the script to train and save the model:
```bash
python train_model.py
```

### 🔍 **2. Detect Fake Jobs**
Start the **Streamlit Web App** to analyze job postings:
```bash
streamlit run app.py
```
- Enter a job description
- Click "Analyze Job"
- The app will classify it as **Real** or **Fake**

---

## 📊 Model Performance

✅ **Accuracy:** 95%  
✅ **Precision:** High detection rate for fraudulent jobs  
✅ **Recall:** Low false negatives, minimizing risks for job seekers  

---

## 🐜 License

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it.

---

## 📩 Contact

👉 **GitHub:** [2KRISHNAYADAV](https://github.com/2KRISHNAYADAV)  
👉 **Email:** darya1786587@gmail.com  

---

🚀 **Stay Safe from Job Scams!** Analyze job postings before applying. 🌝🔍

