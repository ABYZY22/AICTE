🧾 NSAP Scheme Eligibility Prediction
📌 Overview
This project is focused on building a machine learning model that can automatically classify applicants under the appropriate NSAP (National Social Assistance Programme) scheme. The aim is to streamline the process of identifying and allocating benefits to eligible citizens from Below Poverty Line (BPL) households.

🏛️ About NSAP
The National Social Assistance Programme (NSAP) is a social welfare scheme under the Ministry of Rural Development, Government of India. It provides financial aid to the following vulnerable groups:

Elderly

Widows

Persons with disabilities

📦 Sub-Schemes
IGNOAPS – Indira Gandhi National Old Age Pension Scheme

Age ≥ 60

BPL Category

IGNWPS – Indira Gandhi National Widow Pension Scheme

Widow

Age 40–59

BPL Category

IGNDPS – Indira Gandhi National Disability Pension Scheme

Severely disabled (age 18–59)

BPL Category

🎯 Objective
To build a multi-class classification model that predicts the correct NSAP scheme (SchemeCode) based on an applicant’s:

Age

Gender

Marital status

Disability status

Socio-economic details

Other relevant features

🧠 ML Pipeline
Data Collection: NSAP dataset (nsapallschemes.csv)

Data Preprocessing: Cleaning, encoding, handling missing values

Model Selection: Tried algorithms like Random Forest, Logistic Regression, etc.

Evaluation Metrics: Accuracy, precision, recall, confusion matrix

Deployment: IBM Cloud Lite

📁 Files
nsapallschemes.csv – Raw dataset

notebook.ipynb – Training, preprocessing, and evaluation notebook

model.pkl – Saved trained model

README.md – Project documentation

🚀 How to Use
Upload the dataset and script to IBM Watson Studio or run locally.

Preprocess the dataset.

Train the model using your selected algorithm.

Use the model to predict the correct SchemeCode for new applicants.

📈 Future Scope
Integration with government application portals

Real-time eligibility checking

Adding more regional datasets to improve model accuracy
