# 📊 Learner Support Analytics

**Author:** Arundham Jena  
**Tools Used:** Excel, SQL, Power Automate (Concept), Pivot Tables, Conditional Formatting  
**Domain:** Education / Operations Analytics  
**Duration:** November 2025  

---

## 🎯 Project Overview

The **Learner Support Analytics** project focuses on analyzing learner feedback and support ticket data to identify key problem areas, measure operational efficiency, and design a sustainable data-driven monitoring system.

This end-to-end project demonstrates how to transform raw operational data into **actionable insights** through data cleaning, exploratory analysis, KPI tracking, and automation planning.

## 🎥 Project Walkthrough

Watch the full screen recording below for a detailed walkthrough of the **Learner Support Analytics** project —  
covering data cleaning, pivot analysis, trend exploration, and KPI dashboard creation.

<p align="center">
  <a href="https://drive.google.com/file/d/1R3SHaIZNuagT137Sw7aCz_IngCNjTwZ-/view?usp=sharing" target="_blank">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDFsNnMwYWFvZnM3azBoNWxscnlmNzBhN3M3bXZhZjVqaDB5czhkZSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/XdIzM7y9fYKXS4melq/giphy.gif" alt="Watch the Project Walkthrough" width="300"/>
  </a>
</p>

🎬 **Click the thumbnail above** to open the full walkthrough video on Google Drive.

---

## 🧩 Data Quality & Validation

**Objective:**  
Identify and document data issues such as missing fields, duplicates, and logical mismatches.

**Key Actions:**
- Cleaned missing values in **Assigned To**, **Resolved Date**, and **Resolved Time**.  
- Created helper columns:
  - `ResolutionHours`
  - `SLA_Breach`
  - `StatusLogicFlag`
  - `DuplicateRemarksFlag`
- Built an **Audit Summary Sheet** to monitor ticket-level data quality.  
- Suggested **data validation rules** and **standardized entry formats** to maintain consistency.  

**Outcome:**  
Detected and corrected missing values, logical mismatches, and duplicate remarks — ensuring data accuracy for further analysis.

---

## 📈 Issue Analysis & Prioritization

**Goal:** Identify high-impact issue types and highlight the most critical operational gaps.

### 🧮 Top 5 Recurring Issues
- **Career Guidance**  
- **Job Outcomes**  
- **Project/Assignment Concerns**  
- **Sales Promises**  
- **Time Management**  

These five categories account for **over 40% of all learner issues**, making them top priorities for process improvement.

### ⏱️ Resolution Time Insights
- Average Resolution Time: **~162 hours (≈7 days)**  
- Longest resolution in **Instructor Feedback**, **Career Guidance**, and **Mentor Support**.  
- 100% SLA breach rate observed → indicates process delays.

### 🧭 Cross-Program Insights
- Issues appear across all programs (Academy, AIML, DevOps, DSML), showing systemic patterns.  
- **DevOps:** More mentor-related issues  
- **Academy:** More TA-related issues  

### 💡 Recommendation
Focusing on **Career Guidance**, **Mentor Support**, and **Time Management** can deliver the highest overall impact across programs.

---

## 📉 Trend & Performance Analysis

**Weekly / Monthly Ticket Trends**
- Ticket volume peaked during **weeks 34–35**, aligning with learner assignment deadlines.  
- Month-wise comparison showed **August (140 tickets)** > **September (85 tickets)**.

**Issue Distribution Across Programs**
- Academy and DSML programs report the highest number of tickets.  
- AIML has more **project-related** concerns.  
- DevOps shows higher **mentor & job outcome** issues.

**Team Performance**
- Visible gap between fastest and slowest ticket resolvers.  
- Some agents handle tickets **twice as fast** as others.

**Seasonal Patterns**
- Most tickets are raised on **weekends**, especially **Saturday and Sunday**, indicating when learners face the most challenges.

---

## 🧠 Monitoring Framework

### 🪄 Root Cause Analysis (Top 3 Issues)

| **Issue Type** | **Root Cause** | **Preventive Measure** | **Impact** |
|----------------|----------------|-------------------------|-------------|
| Career Guidance | Lack of structured process & unclear ownership | Intake form + Default owner + 48h SLA | Cross-program |
| Sales Promises | Inconsistent communication | Sales Commitment Register + Confirmation workflow | High dissatisfaction |
| Time Management | Unclear deadlines & no reminders | Standard deadlines + Auto-reminders | Improves learner experience |

---

### 📊 KPI Dashboard Design

**KPIs Defined:**

| **KPI** | **Frequency** | **Owner** | **Threshold** |
|----------|----------------|-----------|----------------|
| Weekly Ticket Volume | Weekly | Ops Lead | >20/week |
| Monthly Ticket Volume | Monthly | Program Head | >10% MoM growth |
| Avg Resolution Time | Weekly | Support Lead | >72 hrs |
| SLA Breach Rate | Weekly | Support Lead | >10% |
| Unassigned Tickets | Daily | Shift Lead | >5 |
| Top 5 Issue Share | Weekly | Ops Lead | >40% |
| Repeat Ticket Rate | Monthly | Data Ops | >5% |
| Avg First Response Time | Weekly | Support Lead | >24 hrs |

**Dashboard Layout:**
- **Top Row:** KPI cards (dynamic formulas + conditional formatting)  
- **Middle Section:** Charts for weekly trends and top issues  
- **Bottom Section:** Program distribution and team performance charts  
- **Interactive Slicer:** Filter by program name  

---

### ⚙️ Resource Optimisation & Review Process

**Process Improvements:**
- Structured ticket intake with dropdowns  
- Automated reminders for deadlines  
- SLA-based tracking for TA & Career tickets  

**Review Frequency:**

| **Frequency** | **Stakeholders** | **Purpose** |
|----------------|------------------|--------------|
| Weekly | Ops & Support Leads | SLA breaches, top 5 issues |
| Monthly | Program Heads & Sales Leads | Resource planning, trends |
| Quarterly | Management | Strategic review |

**Automation Suggestions:**
- Power Automate for **auto-assigning tickets**  
- Alert emails for **tickets open >48 hrs**  
- Nightly Power Query refresh + **email summary** to stakeholders  

---

## 💡 Key Insights

- **42%** of total tickets come from just 5 recurring issues.  
- **Career Guidance** and **Sales Promises** cause the longest resolution delays.  
- **Average Resolution Time:** ~7 days.  
- **Weekend ticket spikes** suggest learners raise queries during self-study hours.  
- **Systemic SLA breaches** point to process inefficiencies.  

---

## 🏁 Outcome

✅ Improved visibility into learner issues  
✅ Identified top 5 categories contributing to 42% of tickets  
✅ Designed monitoring dashboard with real-time KPIs  
✅ Recommended automation & review processes for sustainable improvement  

---

## 🧰 Tools & Techniques

| **Category** | **Tools Used** |
|---------------|----------------|
| Data Cleaning | Excel formulas, Data Validation |
| Analysis | Pivot Tables, Conditional Formatting |
| Visualization | Excel Charts (Bar, Line, Stacked Column) |
| Monitoring | KPI Dashboard |
| Automation | Power Automate, Macros |
| SQL | MySQL queries for data quality checks |

---

## 🧾 Author

**👨‍💻 Arundham Jena**    
📧 [arundhamjena04@gmail.com](mailto:arundhamjena04@gmail.com)  
