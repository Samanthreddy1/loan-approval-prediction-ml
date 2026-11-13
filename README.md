Loan Approval Prediction Using Machine Learning
An academic mini-project exploring classification of loan applications using applicant information and supervised machine learning.
Overview
The project report describes a workflow to estimate loan approval status from attributes such as income, loan amount, credit history, dependents, education, and other applicant information. It discusses data cleaning, exploratory data analysis, categorical encoding, train/test splitting, and classification.
Models and reported results
The following values are reported in the project PDF (page 25), not independently reproduced here:
Model	Reported accuracy
Random Forest	78.49%
Decision Tree	79.70%
Logistic Regression	68.49%


The report's conclusion favors Random Forest, although the displayed Decision Tree accuracy is higher. This discrepancy has not been resolved or independently validated.
Technologies described
Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, and Jupyter Notebook / Anaconda.
Workflow
1. Load training and test datasets.
2. Handle missing values and preprocess applicant attributes.
3. Explore data distributions and correlations.
4. Encode categorical variables and prepare features.
5. Train classification models.
6. Evaluate predictions and compare model accuracy.
Repository contents
- docs/loan_prediction_report.pdf — original academic report, including screenshots of notebook code and diagrams.
- requirements.txt — libraries described or shown in the report (not a tested environment lockfile).
- .gitignore — standard Python exclusions.
- GITHUB_UPLOAD_GUIDE.md — repository publishing instructions.
Source code and datasets are not included: the supplied PDF contains screenshots of code, but not the original .ipynb, .py, train.csv, or test.csv files. This repository is currently a documentation archive, not a reproducible implementation.
Responsible use
This is an educational project only, not a validated credit-decision system. Loan decisions can create fairness and regulatory risks. The report discusses sensitive applicant features, including gender and marital status; real-world deployment would require lawful feature selection, fairness audits, robust validation, and human oversight.
Academic attribution
License
No license has been assigned to the supplied academic report. All rights remain with their respective holders. Do not reuse or redistribute without appropriate permission.
