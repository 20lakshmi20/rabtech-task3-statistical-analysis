# RabTech Academy — Task 3: Advanced Statistical Analysis & Hypothesis Testing

This project uses the UCI Student Performance mathematics dataset (`student-mat.csv`) to demonstrate normality tests, two-group hypothesis tests, one-way ANOVA, two-way ANOVA, Tukey HSD, confidence intervals, and distribution plots.

## Dataset
Download the official UCI Student Performance dataset:
https://archive.ics.uci.edu/dataset/320/student+performance

Place `student-mat.csv` in `data/raw/student-mat.csv`. Keep the raw file unchanged.

## Setup (Windows / VS Code)
Open this folder in VS Code. In Terminal, create and activate an environment if needed:
```powershell
python -m venv .venv
.venv\Scripts\activate
python -m pip install -r requirements.txt
```

Run the notebook in VS Code. Select the `.venv` Python kernel and run cells from top to bottom.

## Notes
- Statistical tests do not prove causation.
- The dataset is observational; findings apply to this dataset and may not generalize.
- The Kolmogorov–Smirnov test here compares standardized grades to a standard normal distribution. Its p-value is approximate because parameters are estimated from the sample; interpret cautiously.
- Two-way ANOVA uses study-time group (lower/higher) and sex.
- Do not claim results until you run the notebook with the actual dataset.
