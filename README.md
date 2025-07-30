
# Data Engineering ETL Pipeline

A complete end-to-end ETL pipeline built with Pandas and NumPy.

## 🎯 Goal
Clean raw employee data and generate an analytics-ready dataset.

## 📦 Features
- Data cleaning (missing values, string cleanup)
- Type optimization (`int8`, `category`)
- Feature engineering (`YearsOfService`, `SalaryBucket`)
- Aggregation and reporting
- Export to Parquet (optimized format)

## 🧰 Tools Used
- Python
- Pandas
- NumPy
- Parquet

## 📁 Files
- `raw_employees.csv`: Raw input data
- `cleaned_employees.parquet`: Cleaned output
- `hr_summary_report.csv`: Aggregated report

## 🚀 How to Run
```bash
pip install -r requirements.txt
python etl_pipeline.py

# DE-ETL-PIPELINE-BASIC
End-to-End ETL Pipeline using Pandas &amp; NumPy

