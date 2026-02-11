# Healthcare-Utilization-Analysis

# Healthcare Utilization Analysis

A simple, beginner-friendly Python script to analyze hospital visit data.

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

## Steps

### 1. Install Dependencies
```bash
pip install pandas matplotlib
```

### 2. Add Your Data
Place your `healthcare_dataset.csv` in the same folder as `analyze.py`

### 3. Run It


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

## Files

- `analyze.py` - Main analysis script
- `healthcare_dataset.csv` - Data
- `README.md` 

## Data Requirements

 CSV needs these columns:
- `Date of Admission`
- `Discharge Date`
- `Admission Type`
- `Medical Condition`
- `Medication`
- `Test Results`
- `Billing Amount`

## Example Output

```
Total rows: 55502

TOTAL visits: 55502

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

## Code Structure
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
