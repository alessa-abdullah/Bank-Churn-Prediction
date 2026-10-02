# Bank Customer Churn Prediction — Learning Project

Single-notebook, beginner-focused ML project.
Goal: predict `Exited` (1 = customer left the bank, 0 = stayed) using a
TensorFlow/Keras neural network — binary classification.

## Structure
```
bank-churn-prediction/
├── data/
│   └── Churn_Modelling.csv     # place the Kaggle dataset here (untouched)
├── bank_churn.ipynb            # the entire pipeline, in order
└── README.md
```

## Notebook pipeline (in order)
1. Import Libraries
2. Load Dataset
3. Understand Dataset
4. Data Cleaning
5. Exploratory Data Analysis
6. Feature Selection
7. Encoding
8. Define X and y
9. Train/Test Split
10. Scaling
11. Build TensorFlow Model
12. Train Model
13. Evaluate Model
14. Test Prediction

## Environment
- Virtual env name: `churn_project`
- Python: 3.12 (not 3.14 — TensorFlow does not support 3.14 yet)
- Libraries: pandas, numpy, matplotlib, scikit-learn, tensorflow, jupyter

## Note
`src/`, `models/`, `api/`, `frontend/`, `requirements.txt` are intentionally
NOT included yet. They come later, once the model is understood end-to-end
inside the notebook.
