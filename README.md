# 5CCSAMLF - Coursework 1

**Lucas Perez Reis Lobo** (k23075501)

## Report

The full report is included as a PDF: `k23075501_5CCSAMLF_Coursework_1_Report.pdf`

## Notebooks (step-by-step)

The implementation is split across three notebooks in `labs/`, meant to be followed in order:

1. **`labs/1_EDA.ipynb`** - Exploratory Data Analysis
2. **`labs/2_Model_Selection.ipynb`** - Model comparison and selection
3. **`labs/3_Model_Training.ipynb`** - Final model training, tuning, and submission generation

The submission CSV is at `labs/CW1_submission_k23075501.csv`.

## Drafts

`labs/drafts/` contains earlier, less structured versions of the notebooks above. They are rougher working drafts from which the final organised notebooks were derived (more commented, better structured, unused code removed).

## Running it yourself

```bash
pip install -r requirements.txt
```

Then open the notebooks in `labs/` in order.

## File overview

```
data/CW1_train.csv          # Training set (10,000 samples)
data/CW1_test.csv           # Test set (1,000 samples)
labs/1_EDA.ipynb             # Step 1: EDA
labs/2_Model_Selection.ipynb # Step 2: Model selection
labs/3_Model_Training.ipynb  # Step 3: Training & submission
labs/drafts/                 # Working drafts
CW1_eval_script.py          # Evaluation script
requirements.txt             # Python dependencies
```
