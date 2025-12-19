# Resume Classification Project

##  Project Overview
An applied machine learning project demonstrating real-world data analysis and automated resume classification using Natural Language Processing (NLP) techniques.

This project aims to simplify and automate the resume screening process by classifying resumes into predefined job categories.

---

##  Business Objective
- Automate the resume shortlisting process
- Reduce manual effort in HR screening
- Improve efficiency and accuracy in job-role matching

---

##  Dataset Description
- The dataset consists of resumes in **DOCX format**
- Resumes belong to multiple job categories
- Dataset is organized category-wise for training and evaluation

Folder:   
`P608-Dataset/Resumes_Docx`



---

##  Data Preprocessing
The following preprocessing steps were applied:
- Text extraction from DOCX files
- Conversion of text to lowercase
- Removal of punctuation and special characters
- Stopword removal
- Tokenization
- Lemmatization

---

##  Exploratory Data Analysis (EDA)
EDA was performed to understand resume content and category distribution:
- Word count analysis
- Category-wise resume distribution
- Word frequency visualization
- Word cloud generation for insights

---

##  Feature Engineering
- Text data transformed using **TF-IDF Vectorization**
- Converted unstructured resume text into numerical features suitable for ML models

---

##  Machine Learning Models Used
The following models were implemented and compared:
- Naive Bayes
- Logistic Regression
- Support Vector Machine (SVM)

---

##  Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

A comparison was performed to identify the best-performing model for resume classification.

---

##  Deployment
- A basic deployment setup is included
- The deployed application allows users to upload resumes and view predicted job categories
- Demonstrates real-world usability of the model

---

##  Demo
A demo video is included in the repository to showcase:
- Application workflow
- Resume upload
- Category prediction output

File:  
`DEMO VIDEO.mp4`



---

##  Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

---

##  Project Presentation
A detailed project presentation explaining the complete workflow, architecture, and results is included:
`Resume Classification Team 4.pptx.pptm`



---

##  Challenges Faced
- Handling unstructured text data
- Cleaning resumes with varied formats
- Feature extraction from large text documents
- Model selection and optimization

---

##  Conclusion
This project successfully demonstrates the application of machine learning and NLP techniques to solve a real-world HR automation problem. The system efficiently classifies resumes into relevant job categories and can be extended further for enterprise-level applications.

---

##  Team Project
This project was developed as a team-based academic data science project.



