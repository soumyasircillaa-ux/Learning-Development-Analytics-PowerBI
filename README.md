# Learning & Development Analytics – Power BI

A Power BI portfolio project analyzing employee training effectiveness, 
performance improvement, training investment, employee engagement, 
completion rates, and training ROI.

The dashboard is designed to help organizations understand how training 
programs and delivery methods relate to employee performance and business 
outcomes.

---

## 📌 Project Overview

Learning and Development teams invest significant resources in employee 
training. However, measuring whether training is effective requires looking 
beyond participation and completion rates.

This project uses Power BI to analyze training data across multiple 
dimensions, including:

- Employee training participation
- Training completion
- Performance improvement
- Training hours
- Employee engagement
- Training investment
- Training ROI
- Training programs
- Delivery modes
- Departments
- Quarterly trends

The dashboard converts the underlying training data into an interactive 
three-page analytical report.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Measure overall training effectiveness.
- Analyze employee performance before and after training.
- Understand training investment and ROI.
- Compare training programs and delivery modes.
- Identify differences in training outcomes across departments.
- Analyze the relationship between training hours, engagement, and 
  performance improvement.
- Identify key business insights and potential areas for improvement.
- Develop recommendations based on the analysis.

---

# 📊 Dashboard Structure

The Power BI dashboard consists of three analytical pages.

---

## Page 1 – Overview

The Overview page provides a high-level summary of the organization's 
training performance.

### Key Performance Indicators

The page includes the following KPIs:

- **Employees Trained**
- **Completion Rate**
- **Training Investment**
- **Average Performance Gain**
- **Average ROI**

These KPIs provide a quick view of the scale, effectiveness, investment, 
and return associated with employee training.

### Visualizations

#### 1. Pre vs Post Performance by Department

Compares employee performance before and after training across departments.

This helps identify differences in performance improvement between 
departments.

#### 2. Monthly Training Investment and Average Performance Gain

Shows the monthly trend of training investment alongside average 
performance gain.

This provides a view of how training spending and performance outcomes 
change over time.

#### 3. Training Completion Distribution by Number of Employees

Shows the distribution of employees based on their training completion 
status.

This helps evaluate overall participation and completion patterns.

#### 4. Average Performance Gain and ROI by Program Name

Compares training programs using performance improvement and ROI metrics.

This provides a program-level view of training outcomes and financial 
return.

---

# Page 2 – Methods & Strategies

The second page focuses on understanding how different training methods, 
delivery modes, departments, and training characteristics relate to 
business outcomes.

This page moves beyond high-level KPIs and provides deeper analytical 
comparisons.

### Visualizations

#### 1. Average Performance Gain by Quarter and Delivery Mode

**Visual:** Line Chart

Shows how average performance gain changes across quarters for different 
training delivery modes.

This helps analyze trends in training effectiveness over time and compare 
different delivery approaches.

#### 2. Average ROI by Program Name and Delivery Mode

**Visual:** Ribbon Chart

Compares average ROI across training programs and delivery modes.

The visualization helps examine how the relative position of programs 
changes across different delivery methods.

#### 3. Performance Lift by Department

**Visual:** Scatter Chart

Analyzes performance lift across departments in relation to training 
characteristics.

The analysis considers factors such as:

- Average Training Hours
- Performance Lift
- Department
- Employees Trained

This helps explore whether differences in training exposure are associated 
with differences in performance outcomes.

#### 4. Average Employee Engagement and Average Training Hours by Department

**Visual:** Clustered Column Chart

Compares employee engagement and training hours across departments.

This provides additional context for understanding differences in training 
participation and employee response.

---

# Page 3 – Conclusions

The Conclusions page summarizes the major findings from the analysis and 
converts the dashboard results into business-oriented actions.

The page is structured around four areas:

### Key Insights

Highlights the major patterns identified from the dashboard analysis, 
including differences in performance improvement, ROI, training methods, 
engagement, and departmental outcomes.

### Recommendations

Provides practical recommendations based on the observed training 
performance and business outcomes.

The recommendations focus on areas such as:

- Improving training effectiveness
- Reviewing delivery methods
- Monitoring program-level ROI
- Improving employee engagement
- Evaluating departmental training needs
- Aligning training investment with measurable outcomes

### Root Cause Analysis (RCA)

The RCA section explores possible reasons behind variations in training 
outcomes.

Factors considered include:

- Training hours
- Employee engagement
- Delivery mode
- Training program
- Department-level differences
- Training completion

The objective is to move from identifying an issue to understanding the 
factors that may contribute to it.

### SWOT Analysis

A SWOT framework is used to summarize:

- **Strengths** – Areas where the training strategy demonstrates positive 
  outcomes.
- **Weaknesses** – Areas where training performance or consistency may need 
  improvement.
- **Opportunities** – Areas where training programs or strategies can be 
  developed further.
- **Threats** – Factors that may affect training effectiveness or return 
  on investment.

---

# 📈 Key Metrics

The dashboard uses several important training and business metrics.

| Metric | Purpose |
|---|---|
| Employees Trained | Measures the scale of training participation |
| Completion Rate | Measures the proportion of training completed |
| Training Investment | Measures resources allocated to training |
| Average Performance Gain | Measures improvement in employee performance |
| Average ROI | Measures the return generated from training |
| Training Hours | Measures employee exposure to training |
| Employee Engagement | Provides an additional indicator of employee response |
| Performance Lift | Measures improvement associated with training |

---

# 🧮 DAX & Data Analysis

The project uses Power BI and DAX to create calculated measures and 
business metrics.

The analysis includes calculations related to:

- Employee counts
- Training completion
- Performance gain
- Performance lift
- Training investment
- ROI
- Average training hours
- Employee engagement
- Time-based analysis

DAX measures are used to transform the raw training data into meaningful 
business KPIs and analytical metrics.

---

# 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **CSV Dataset**
- **Data Cleaning & Transformation**
- **Data Visualization**
- **Business Analytics**

---

# 📂 Project Files

```text
Learning-Development-Analytics-PowerBI/
│
├── README.md
│
├── LearningDevelopment_Dataset.csv
│
└── Learninganddevelopment_dashboard.pbit
