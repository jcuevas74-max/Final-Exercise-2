# Wine Quality Prediction System

## Problem
A wine producer needs a preliminary screening tool to classify red-wine samples.

## Dataset
UCI Wine Quality Dataset — Red Wine CSV:
https://archive.ics.uci.edu/dataset/186/wine+quality

## Prediction rule
- Quality score >= 6: GOOD QUALITY
- Quality score < 6: NEEDS IMPROVEMENT

The original `quality` column is the target only and is not used as an input feature.

## Technologies
Python, pandas, scikit-learn, Random Forest, Streamlit, joblib, GitHub.

## Install and run
```bash
pip install -r requirements.txt
python train_model.py
streamlit run app.py
```
Open the local URL shown in the terminal (normally http://localhost:8501).

## Limitation
This is a classroom prototype trained on a particular red-wine dataset. Predictions are preliminary and are not a substitute for laboratory testing, sensory evaluation, food-safety procedures, or professional quality-control decisions.
