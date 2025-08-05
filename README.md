# 🧠 NSAP Scheme Eligibility Prediction  
**IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies**  

This repository contains the capstone project completed during the **IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies**. This internship is a joint initiative by **Edunet Foundation**, **AICTE**, and **IBM SkillsBuild** to provide practical experience in Artificial Intelligence and Cloud technologies through real-world projects.

---

## 📝 Table of Contents  
- [👨‍💻 Intern Details](#intern-details)  
- [📖 About the Internship](#about-the-internship)  
- [💡 Project: NSAP Scheme Eligibility Classification](#project-nsap-scheme-eligibility-classification)  
  - [Problem Statement](#problem-statement)  
  - [Solution Overview](#solution-overview)  
- [⚙️ Technology Stack](#️technology-stack)  
- [🚀 Project Workflow](#project-workflow)  
- [📊 Results](#results)  
- [📁 Repository Contents](#repository-contents)  

---

## 👨‍💻 Intern Details  
**Name**: Abi Zeeth  
**Institute**: KLN College of Engineering  
**Duration**: 4 Weeks (15th July 2025 to 7th August 2025)  

---

## 📖 About the Internship  
This 4-week internship aimed to provide students with exposure to **AI and Cloud** using IBM tools and platforms. The internship included weekly live sessions, hands-on labs, mentor interactions, and a capstone project.

### 📆 Internship Structure:
- **Week 1**: Orientation, IBM Cloud Setup, Intro to AI  
- **Week 2**: Data Analytics, Data Preprocessing, IBM Cloud EDA  
- **Week 3 & 4**: AutoAI, Chatbot Building, Final Project Development  

To complete the internship, students had to complete:
- Minimum **2 IBM SkillsBuild courses**  
- A capstone project  
- A final **project presentation**

---

## 💡 Project: NSAP Scheme Eligibility Classification  

### 🎯 Problem Statement  
The **National Social Assistance Programme (NSAP)** provides pensions and financial aid to **Below Poverty Line (BPL)** individuals, including the elderly, widows, and disabled persons.  
Manual classification of applicants into the correct NSAP sub-schemes like **IGNOAPS**, **IGNWPS**, and **IGNDPS** is time-consuming and error-prone.

---

### ✅ Solution Overview  
An AI/ML solution was developed to **predict the eligibility scheme code** using applicant attributes such as age, gender, disability status, marital status, etc.  
The trained model was deployed on IBM Cloud to allow **real-time predictions**.

---

## ⚙️ Technology Stack  
- **Cloud Platform**: IBM Cloud  
- **AI/ML Studio**: IBM watsonx.ai  
- **AutoML Tool**: IBM AutoAI  
- **Languages & Libraries**:  
  - Python  
  - pandas  
  - scikit-learn  
  - xgboost  
  - ibm-watsonx-ai SDK  

---

## 🚀 Project Workflow  
1. **Dataset Upload**: `nsapallschemes.csv` uploaded to IBM Cloud project  
2. **AutoAI Experiment**: Used to preprocess, engineer features, and train classification models  
3. **Model Selection**: Best pipeline (XGBoost/Random Forest) chosen based on accuracy  
4. **Deployment**: Model deployed in Watsonx.ai Deployment Space as a REST API  
5. **Testing**: Endpoint tested with new applicant data for scheme prediction  

---

## 📊 Results  
- The final deployed model accurately classified applicants into appropriate NSAP schemes.  
- Streamlined the eligibility detection process for faster and more efficient government benefit distribution.  
- Demonstrated effective use of **AutoAI** for quick prototyping and deployment.

---

## 📁 Repository Contents  
- `NSAP_Scheme_Classifier.ipynb` – Jupyter notebook for training, EDA, and evaluation  
- `nsapallschemes.csv` – Cleaned input dataset  
- `NSAP_Prediction_Model.pdf` – Final presentation slides  
- `README.md` – Project documentation
