# Resume-Ranking-Program  
An AI-powered resume evaluation system using BERT regression to deliver consistent, bias-reduced scoring  

---

## 🤖 AI Resume Ranker  
Team project developed by 3rd-year Computer Science students at **UKZN** as part of *COMP316 Machine Learning & NLP*.  

---

## 📖 About the Project  
**AI Resume Ranker** is an automated resume scoring system built with **Natural Language Processing (NLP)** and **BERT-based regression**.  
It transforms structured resume data (Skills, Experience, Education, Certifications, Projects) into natural language text and predicts a **continuous evaluation score** between **0–100**.  

The goal is to assist recruiters by providing:  
- ⚡ Fast and consistent scoring  
- 🎯 Reduced human bias  
- 📊 Objective evaluation across large applicant pools  

---

## ✨ Features  
- 📝 Resume text preprocessing (skills, experience, education, certifications, projects)  
- 🤗 Fine-tuned **BERT (bert-base-uncased)** model for regression  
- 📈 Evaluation with **RMSE** and **R² score**  
- ⚙️ Hugging Face **Trainer API** integration  
- 📊 Results: **RMSE ≈ 14.1, R² ≈ 0.31**  

---

## ⚙️ Requirements  
- Python 3.8+  
- PyTorch  
- Transformers (Hugging Face)  
- Pandas / NumPy  
- Jupyter Notebook  

---

## ▶️ How to Run the Project  
1. Clone the repository  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

---
## 📊 Results  
- **RMSE:** ~14.13  
- **R² Score:** ~0.31  

The model captures key trends in resume quality but leaves room for improvement (data variability, label noise, domain nuance).  

---
## 👥 Team Members  
- Farha Mustan    (Farry18)
- Reyasen Naicker (Reyasen-Naicker)
- Xander Links    (xanderLinks)
- Zuriel Singh    (zurielsingh)

---
## ⚠️ Disclaimer  
This project was developed **for educational purposes only**.  
We do not claim ownership of datasets or pretrained models used.  
