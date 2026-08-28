# Employee Engagement, Satisfaction & Burnout Analysis at Palo Alto Networks

## 📌 Project Overview

This project analyzes employee engagement, satisfaction, work-life balance, burnout risk, workload stress, and attrition patterns using HR analytics.

The objective is to identify early warning signals related to employee disengagement and burnout before they result in employee attrition. The analysis helps organizations move from reactive attrition management to proactive employee experience improvement.

The project includes data analysis using Python and an interactive dashboard built using Power BI.

---

## 🎯 Problem Statement

Employee attrition is often influenced by factors such as:

- Low employee engagement
- Poor work-life balance
- Overtime workload
- High burnout risk
- Job dissatisfaction
- Career stagnation

The goal of this project is to analyze these factors and identify employee groups that may require early intervention.

---

## 📊 Dataset Information

- Total Employees: **1,470**
- Total Features: **31 original columns**
- Missing Values: **0**
- Duplicate Rows: **0**

The dataset contains information related to:

- Employee demographics
- Department and job roles
- Job satisfaction
- Environment satisfaction
- Relationship satisfaction
- Job involvement
- Work-life balance
- Overtime
- Business travel
- Career progression
- Employee attrition

---

## 📈 Key Performance Indicators (KPIs)

The following KPIs were created during the analysis:

| KPI | Value |
|-----|------:|
| Total Employees | 1,470 |
| Average Engagement Index | 2.72 |
| Average Work-Life Balance | 2.76 |
| High Burnout Employees | 126 |
| High Burnout Rate | 8.57% |
| High Workload Stress Employees | 381 |
| High Workload Stress Rate | 25.92% |
| Overall Attrition Rate | 16.12% |
| Low Engagement Employees | 69 |

---

## 🔍 Analysis Performed

### 1. Employee Engagement Analysis

An **Engagement Index** was created using:

- Job Involvement
- Job Satisfaction
- Environment Satisfaction
- Relationship Satisfaction

Employees were categorized into:

- Low Engagement
- Medium Engagement
- High Engagement

### Engagement Distribution

- Low: **69 employees**
- Medium: **814 employees**
- High: **587 employees**

---

### 2. Burnout Risk Analysis

Burnout risk was calculated using:

- Overtime
- Work-Life Balance

Employees were classified into:

- Low Risk
- Medium Risk
- High Risk

### Burnout Distribution

- Low Risk: **756 employees**
- Medium Risk: **588 employees**
- High Risk: **126 employees**

---

### 3. Workload Stress Analysis

A workload stress indicator was created using:

- Business Travel
- Overtime

Employees were categorized into:

- Low Stress
- Medium Stress
- High Stress

### Workload Stress Distribution

- Low: **863 employees**
- Medium: **226 employees**
- High: **381 employees**

---

### 4. Engagement vs Attrition

The analysis found a strong relationship between employee engagement and attrition.

| Engagement Level | Attrition Rate |
|------------------|---------------:|
| Low | 42.03% |
| Medium | 17.20% |
| High | 11.58% |

Employees with low engagement showed the highest attrition risk.

---

### 5. Burnout Risk vs Attrition

| Burnout Risk Level | Attrition Rate |
|--------------------|---------------:|
| High | 33.33% |
| Medium | 21.43% |
| Low | 9.13% |

Employees with high burnout risk had significantly higher attrition.

---

### 6. Overtime vs Attrition

| Overtime | Attrition Rate |
|----------|---------------:|
| No | 10.44% |
| Yes | 30.53% |

Employees working overtime had almost three times the attrition rate compared to employees not working overtime.

---

### 7. Department Analysis

| Department | Attrition Rate |
|------------|---------------:|
| Sales | 20.63% |
| Human Resources | 19.05% |
| Research & Development | 13.84% |

Sales showed the highest department-level attrition rate.

---

### 8. Job Role Analysis

The highest attrition rates were observed in:

- Sales Representative: **39.76%**
- Laboratory Technician: **23.94%**
- Human Resources: **23.08%**

These roles may require focused retention strategies.

---

## 💡 Key Insights

- Low-engagement employees have an attrition rate of **42.03%**.
- High-burnout employees have an attrition rate of **33.33%**.
- Employees working overtime have a **30.53% attrition rate**, compared to **10.44%** for non-overtime employees.
- Sales has the highest department-level attrition rate at **20.63%**.
- Sales Representatives have the highest job-role attrition rate at **39.76%**.
- High workload stress affects **25.92% of employees**.
- Early identification of engagement and burnout issues can support proactive HR intervention.

---

## 📊 Power BI Dashboard

The interactive Power BI dashboard includes:

### Executive Overview

- Total Employees
- Average Engagement Index
- Average Work-Life Balance
- High Burnout Rate
- Overall Attrition Rate
- High Workload Stress Rate
- Engagement Level Distribution
- Burnout Risk Distribution
- Attrition Analysis

### Detailed Analysis

- Attrition Rate by Overtime
- Workload Stress Distribution
- Engagement by Job Level
- Engagement by Tenure Group
- Attrition Rate by Job Role
- Work-Life Balance by Department
- Burnout Risk by Department

### Interactive Filters

- Department
- Job Role
- Overtime
- Engagement Level

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Google Colab**
- **Power BI**
- **DAX**
- **GitHub**

---

## 📁 Project Structure

```text
Palo-Alto-Networks-Employee-Engagement-Analysis/
│
├── data/
│   └── Palo_Alto_Networks_Employee_Engagement_Final.csv
│
├── dashboard/
│   └── Palo Alto Networks Employee Engagement & Burnout Analysis.pbix
│
├── images/
│   ├── Dashboad.image1.png
│   └── Dashboard.image2.png
│   |__ Dashboard.image3.png
└── README.md
