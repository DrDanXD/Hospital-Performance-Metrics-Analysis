# 🏥 Hospital Performance Metrics Analysis

This repository analyzes hospital performance metrics related to **readmission measures**, **patient experience**, and **timely and effective care**. The data is visualized using bar plots to display the average counts of various metrics across hospitals. 📊
DATASET : https://data.cms.gov/provider-data/dataset/xubh-q36u

## 📁 Files

- `Hospital_General_Information.csv`: Contains general information and performance metrics of hospitals.
- `hospital_performance_analysis.py`: Python script that processes the data and generates visualizations using **matplotlib** and **seaborn**.

## 📊 Analysis

The analysis covers the following categories of hospital performance:

1. **🔄 Readmission Categories**:
   - **Count of READM Measures Better**: Number of hospitals improving readmission measures.
   - **Count of READM Measures No Different**: Number of hospitals with no change in readmission measures.
   - **Count of READM Measures Worse**: Number of hospitals showing worsening performance in readmission measures.

2. **💬 Patient Experience Measures**:
   - **Pt Exp Group Measure Count**: Number of hospitals participating in patient experience groups.
   - **Count of Facility Pt Exp Measures**: Number of patient experience measures tracked by each hospital.

3. **⏱️ Timely and Effective Care Measures**:
   - **TE Group Measure Count**: Number of hospitals involved in timely and effective care measures.
   - **Count of Facility TE Measures**: Number of timely and effective care measures adopted by hospitals.

## 🛠️ Dependencies

To run the analysis, you'll need the following Python libraries:
- `pandas`
- `matplotlib`
- `seaborn`

You can install them using pip:

```bash
pip install pandas matplotlib seaborn
