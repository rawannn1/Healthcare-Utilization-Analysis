
# Healthcare Utilization Analysis

A simple, beginner-friendly Python script to analyze hospital visit data using Google Colab.

## What It Does

Answers real healthcare questions:
- Total hospital visits
- Admission types (Urgent, Emergency, Elective)
- Length of stay statistics
- Medical conditions
- Medications used
- Abnormal test results
- Billing analysis
- Cost trends over time

## Quick Start (Google Colab)

### 1. Get the Data
Download from Kaggle: https://www.kaggle.com/datasets/prasad22/healthcare-dataset

### 2. Open Google Colab
Go to: https://colab.research.google.com

### 3. Create New Notebook
Click "New notebook"

### 4. Upload Data
Click folder icon → Upload → Select `healthcare_dataset.csv`

### 5. Paste the Code
Copy the entire code from `analyze.py` and paste it into a Colab cell

### 6. Run It
Press **Shift + Enter**

## Output

The script prints:
- Hospital utilization statistics
- Length of stay analysis
- Medical conditions breakdown
- Medication usage
- Abnormal test result counts
- Billing information
- Monthly cost trends

And creates:
- `healthcare_analysis.png` - Cost trend chart

## Data Source:
**Kaggle Healthcare Dataset**
https://www.kaggle.com/datasets/prasad22/healthcare-dataset

Dataset contains:
- 55,500+ hospital visit records
- Patient demographics
- Admission/discharge dates
- Medical conditions
- Medications
- Billing amounts
- Test results

## Data Requirements

Your CSV needs these columns:
- `Date of Admission`
- `Discharge Date`
- `Admission Type`
- `Medical Condition`
- `Medication`
- `Test Results`
- `Billing Amount`

## Example Output

```
HOSPITAL VISITS
Total visits: 55,502

Visits by admission type:
Urgent       18367
Emergency    18500
Elective     18635

LENGTH OF STAY (days)
Longest stay: 89
Shortest stay: 0
Average stay: 25.45
Median stay: 25

...
```

## Files

- `analyze.py` - Main analysis script
- `README.md` - This file

## Code Structure:
The script follows this simple flow:

1. Load data
2. Convert dates
3. Calculate length of stay
4. Count visit types
5. Analyze length of stay
6. Find top conditions
7. Find top medications
8. Count abnormal cases
9. Analyze billing
10. Show cost trends
11. Create chart
