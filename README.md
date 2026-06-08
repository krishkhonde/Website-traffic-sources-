# Website-traffic-sources-


**Intern ID: CITS1317**

**Name: Krish khonde**

**Organization: Codtech IT Solutions Pvt. Ltd**

**Internship Period: 20 May 2026 - 17 June 2026**

---

This is my third internship project. I analyzed website traffic data from different sources like Google, Facebook, Instagram, Email and Direct visits. The goal was to find which source brings the most traffic and conversions.

---

## Tools and Libraries Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Dataset

I created a dummy dataset with 120 records covering January to June 2024. Data is weekly and has 5 traffic sources.

Columns:
- Date
- Source (Google, Facebook, Direct, Email, Instagram)
- Medium (Organic, Social, None, Email)
- Sessions
- Users
- New_Users
- Bounce_Rate
- Avg_Session_Duration
- Pages_Per_Session
- Conversions

---

## Steps I Followed

**1. Data Loading**
Loaded the CSV and checked shape and columns.

**2. Data Cleaning**
- Converted Date to datetime
- Extracted month and week number
- Checked for null values — none found
- Removed duplicates

**3. Analysis**
- Total sessions, users and conversions for 6 months
- Source wise breakdown for sessions, conversions and bounce rate
- Monthly trend for each traffic source

**4. Visualization**
Made 6 charts:
1. Monthly sessions trend by source (line chart)
2. Total sessions by source (bar chart)
3. Traffic source distribution (pie chart)
4. Bounce rate comparison by source (bar chart)
5. Conversions by source (bar chart)
6. Monthly sessions vs users (grouped bar chart)

**5. Prediction Model**
Used Linear Regression to predict July 2024 total sessions.

---

## Results

- Total sessions in 6 months: 1,05,298
- Total users: 87,319
- Total conversions: 6,033
- Top traffic source: Google
- Best conversion source: Google
- Lowest bounce rate: Email (30.6%)
- Predicted sessions for July 2024: 26,471
- Model R2 Score: 0.9981

---

## Files in this Project

- traffic_data.csv — dataset
- traffic_analysis.py — main python code
- traffic_visualizations.png — all 6 charts
- traffic_prediction.png — prediction chart
- README.md — this file

---

## How to Run

```
pip install pandas matplotlib seaborn scikit-learn
python traffic_analysis.py
```
