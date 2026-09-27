# HR Analytics — Job Change Prediction

A Machine Learning project that predicts whether a candidate is likely to look for a new job, built to support recruitment and candidate screening decisions.

##  Project Overview

Organizations need effective recruitment and screening strategies to identify candidates who are more likely to seek new job opportunities. This project builds a Machine Learning-based candidate screening system that predicts job-change likelihood using candidate data (education, experience, company type, training hours, and more).

##  Objectives

- Prepare and clean the recruitment dataset
- Apply feature engineering and data transformation
- Build two Machine Learning models
- Compare their performance using multiple evaluation metrics
- Identify important factors associated with job-change predictions
- Generate recruitment insights and recommendations
- Develop a recruitment dashboard
- (Bonus) Build a candidate ranking system

##  Dataset

The project uses the **HR Analytics Job Change of Data Scientists** dataset, containing candidate information such as education, experience, company type, training hours, and relevant experience.

##  Models

Two classification models were built and compared:

1. **Logistic Regression** — used as a baseline model
2. **Random Forest** — captures more complex relationships between features and target

### Performance Comparison

| Metric | Logistic Regression | Random Forest |
|---|---|---|
| Accuracy | 76% | 70% |
| Precision | 56% | 39% |
| Recall | 20% | 33% |
| F1 Score | 30% | 36% |

**Key takeaway:** Random Forest achieved higher recall and F1 score for identifying candidates likely to change jobs, making it the preferred screening model when catching more potential job changers is the priority.

##  Business Insights

Training Hours and Experience Years were the most important features in predicting job-change likelihood. Graduate-level candidates had the highest job-change rate (~28%).

##  Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

##  Repository Contents

- `ITI_Project.ipynb` — Full notebook with data cleaning, feature engineering, model building, and evaluation
- `Project_Documentation.pdf` — Detailed project write-up and business insights

##  How to Run

1. Clone this repository
2. Install dependencies: `pip install pandas numpy scikit-learn jupyter`
3. Open `ITI_Project.ipynb` in Jupyter Notebook
4. Run all cells

---

*This project was completed as part of the ITI (Information Technology Institute) Summer Training program.*
