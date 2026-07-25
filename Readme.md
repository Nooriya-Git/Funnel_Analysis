# 📊 User Funnel Drop-off Analysis

A data analysis project that evaluates user behavior across a website/app conversion funnel. The objective is to identify where users abandon the onboarding process by calculating stage-wise conversion rates, drop-off rates, and providing business recommendations to improve user retention.

---

## 📌 Project Overview

This project analyzes event-level user data representing a typical product onboarding funnel. Each event records the user, the funnel stage reached, and the corresponding timestamp.

The analysis focuses on:

- Counting unique users at each funnel stage
- Calculating stage-to-stage conversion rates
- Identifying the stage with the highest user drop-off
- Visualizing the funnel using a bar chart
- Providing actionable business recommendations

---

## 📂 Project Structure

```
User-Funnel-Dropoff-Analysis/
│
├── data/
│   └── funnel_events_sample.csv
│
├── notebook/
│   └── Funnel_Analysis.ipynb
│
├── images/
│   └── funnel_chart.png
│
├── output/
│   └── funnel_analysis_results.csv
│
├── README.md
└── requirements.txt
```

---

## 📈 Funnel Stages

1. Visited Site
2. Signup Started
3. Details Filled
4. Email Verified
5. Purchase Completed

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📊 Analysis Performed

- Data loading and preprocessing
- Duplicate event removal
- Unique user count calculation
- Funnel conversion rate analysis
- Funnel drop-off analysis
- Data visualization
- Business insight generation

---

## 📉 Key Findings

| Funnel Stage | Users | Conversion Rate | Drop-off Rate |
|--------------|------:|----------------:|--------------:|
| Visited Site | 200 | 100.00% | 0.00% |
| Signup Started | 150 | 75.00% | 25.00% |
| Details Filled | 96 | 64.00% | 36.00% |
| Email Verified | 52 | 54.17% | 45.83% |
| Purchase Completed | 44 | 84.62% | 15.38% |

### Biggest Drop-off

The highest user abandonment occurs between the **Details Filled** and **Email Verified** stages, where **45.83%** of users leave the funnel before verifying their email.

---

## 💡 Business Recommendation

The email verification stage represents the largest bottleneck in the user journey. Improving email delivery speed, simplifying the verification process, providing a **"Resend Verification Email"** option, and clearly communicating the purpose of verification can reduce friction and improve the overall conversion rate.

---

## 🚀 How to Run

### Clone the repository

```bash
git clone <repository-url>
```

### Navigate to the project

```bash
cd User-Funnel-Dropoff-Analysis
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
notebook/Funnel_Analysis.ipynb
```

Run all cells to reproduce the analysis.

---

## 📁 Output Files

After execution, the notebook generates:

- `images/funnel_chart.png`
- `output/funnel_analysis_results.csv`

---

## 👤 Author

**Nooriya**

Data Science Student | Aspiring Data Analyst

GitHub: https://github.com/Nooriya-Git
