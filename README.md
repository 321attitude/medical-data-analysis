# MedStat Lab — Medical Data Analysis Toolkit

A GitHub Pages-ready, browser-based medical statistics dashboard.

## Features
1. Data import — CSV/XLS/XLSX
2. Data dictionary
3. Data cleaning
4. Data validation
5. Descriptive statistics
6. Distribution/normality exploration
7. Categorical analysis
8. Continuous analysis
9. Pearson/Spearman correlation
10. Linear regression
11. Logistic regression
12. Poisson/modified-Poisson guided module
13. Kaplan–Meier survival curves
14. Diagnostic 2×2 + ROC/AUC
15. HTML/CSV/printable report export

## Deploy on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`, `style.css`, `app.js`, and `README.md`.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/root`.
5. Save and open the generated Pages URL.

## Important
This project performs analysis locally in the browser. It is intended as a teaching/prototyping toolkit. For clinical decisions, regulated research, or publication, verify results with validated statistical software (R/Stata/SPSS/SAS) and a qualified statistician. In particular, the normality, regression, Poisson robust-SE, and survival modules should be independently validated before publication use.

## Privacy
No application backend is included. The code does not intentionally upload the selected dataset to a server. Third-party JavaScript libraries are loaded from public CDNs, so for highly sensitive environments you should self-host and pin the libraries.
