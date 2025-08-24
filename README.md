# Predicting Eligibility for Social Welfare Schemes using Machine Learning  

## 📌 Project Overview  
The **National Social Assistance Program (NSAP)** is a flagship social welfare scheme by the Government of India. It provides financial support to the elderly, widows, and persons with disabilities belonging to below-poverty-line (BPL) households.  

Manual verification of applications and assigning the correct scheme is **time-consuming, error-prone, and inefficient**. To address this, we built a **multi-class classification Machine Learning model** that predicts the most appropriate welfare scheme for an applicant based on their **demographic and socio-economic attributes**.  

This project was developed as part of the **IBM Hackathon Project** under the guidance of **Deepneel** at **Brainware University, Department of CSE - AI**.  

---

## 🎯 Problem Statement  
- Manual application verification delays **timely aid delivery**.  
- Incorrect allocation prevents deserving beneficiaries from receiving help.  
- Objective: Automate eligibility verification using **Machine Learning**.  

---

## ⚙️ Technologies Used  
- **Python** (Pandas, NumPy, Scikit-learn)  
- **Jupyter Notebook / Google Colab**  
- **Matplotlib, Seaborn** (Data Visualization)  
- **IBM Cloud Services**:  
  - IBM Watson Studio  
  - IBM Cloud Object Storage  
  - IBM Machine Learning Service  

---

## 📊 Dataset  
- Source: NSAP Social Welfare Dataset (Government Schemes)  
- Records: **2,085 entries**  
- Features: Socio-economic & demographic attributes (gender, caste, Aadhaar, etc.)  
- Target: **Scheme Code** (e.g., IGNOAPS, IGNWPS, IGNDPS)  

---

## 🚀 Approach  
1. **Data Preprocessing**  
   - Handled categorical & numerical attributes  
   - Feature scaling and cleaning  

2. **Model Building**  
   - Multi-class classification using ML algorithms:  
     - Logistic Regression  
     - Random Forest Classifier  
     - Decision Tree Classifier  

3. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix visualization  

4. **Deployment (Future Scope)**  
   - IBM Watson Studio + Cloud ML deployment  

---

## 🌟 Key Features (Wow Factor)  
- Automates **eligibility verification** for welfare schemes  
- Reduces **manual errors & delays**  
- Ensures **fair and transparent scheme allocation**  
- Scalable for **real-time government decision-making**  

---

## 👥 End Users  
- Government Social Welfare Departments  
- Policy Makers & NGOs  
- Social Workers & Field Officers  
- Researchers in Public Administration  

---

## 📈 Results  
- Built a robust ML classification model for scheme prediction  
- Achieved **high classification accuracy** (details in notebook)  
- Can assign applicants correctly to schemes like:  
  - **IGNOAPS** → Old Age Pension  
  - **IGNWPS** → Widow Pension  
  - **IGNDPS** → Disability Pension  

---

## 🔮 Future Scope  
- Expand dataset with additional socio-economic features (income, occupation, etc.)  
- Deploy as **web or mobile app** for officers  
- Integrate with **Aadhaar/UIDAI database** for real-time verification  
- Add **Explainable AI (XAI)** for transparent decision-making  

---

## 📂 Repository Structure  
```
├── dataset/                  # NSAP dataset (.csv file)
├── notebooks/                # Jupyter Notebooks (data prep, model training)
├── models/                   # Saved ML models
├── README.md                 # Project documentation
└── requirements.txt          # Required Python libraries
```

---

## 📜 Author  
👩‍💻 **Ruchika Raj**  
- Department of CSE - AI  
- Brainware University  
- Guide: **Deepneel**  

---

## 🔗 GitHub Repository  
[IBM Hackathon Project – Ruchika Raj](https://github.com/Ruchika098/IBM-Project-Ruchika.git)  
