# FUTURE_ML_03
A Machine Learning-based Resume Screening and Candidate Ranking System that automatically analyzes resumes, matches them with selected job roles, ranks candidates using TF-IDF and Cosine Similarity, identifies missing skills, and helps recruiters shortlist applicants efficiently.

# Resume Screening ML System

##  Project Overview

This project is a Machine Learning based **Resume / Candidate Screening System** that automatically analyzes resumes, compares them with job descriptions, ranks candidates based on job-role fit, and identifies missing skills.

It helps recruiters reduce manual effort and shortlist candidates faster using NLP and similarity scoring techniques.

---

##  Objective

To build an intelligent hiring support system that can:

* Read and analyze resumes
* Extract useful keywords and skills
* Compare resumes with job descriptions
* Rank candidates based on relevance
* Identify missing skills
* Export final ranked results

---

##  Datasets Used

### 1. Resume Dataset

Contains resume text and candidate categories.

### 2. Job Description Dataset

Contains job titles and job descriptions.

> Note: Original datasets were sourced from Kaggle.

---

##  Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Jupyter Notebook / VS Code

---

## ⚙️ Machine Learning Workflow

### 1. Data Loading

Loaded resume and job datasets using Pandas.

### 2. Text Preprocessing

Performed:

* Lowercasing
* Removing special characters
* Removing stopwords
* Tokenization

### 3. Feature Extraction

Used **TF-IDF Vectorization** to convert text into numerical features.

### 4. Similarity Matching

Used **Cosine Similarity** to compare resumes with selected job descriptions.

\text{Cosine Similarity} = \frac{A \cdot B}{|A||B|}

### 5. Candidate Ranking

Candidates are ranked based on similarity score.

### 6. Skill Gap Detection

Missing skills such as Python, SQL, Machine Learning, Pandas, etc. were identified.

### 7. Visualization

Generated bar charts for top ranked candidates.

---

## 📈 Output Files

* `resume_screening.ipynb` → Complete project notebook
* `final_ranked_candidates.csv` → Ranked candidate results
* `resume_small.csv` → Sample resume dataset
* `jobs_small.csv` → Sample jobs dataset

---

##  Results

The system successfully:

* Screened resumes automatically
* Ranked candidates based on job fit
* Identified missing skills
* Generated recruiter-friendly outputs

---

##  Future Improvements

* PDF Resume Parsing
* Streamlit Web App Interface
* Advanced Skill Matching
* Real-time Resume Upload
* Deep Learning NLP Models

---

##  Conclusion

This project demonstrates how Machine Learning and NLP can automate the recruitment process and improve hiring efficiency through smart resume screening.

---

##  Author

Developed as part of Future Interns ML Internship Task.
