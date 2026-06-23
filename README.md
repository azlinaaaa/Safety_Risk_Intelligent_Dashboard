# HSE Risk Intelligence System: Construction Safety Analytics Dashboard

## 📌 Project Overview
This Power BI dashboard provides a comprehensive analysis of workplace safety incidents by examining incident frequency, risk levels, injury severity, root causes, and hazard groups. Analyzing over 4,847 workplace incident records, the dashboard aims to help safety managers and decision-makers identify critical safety issues, monitor historical trends, and implement data-driven preventive actions to reduce workplace accidents.

---

## 📊 Dashboard 1: Executive Overview

![Dashboard 1 - Executive Overview](https://github.com/azlinaaaa/Safety_Risk_Intelligent_Dashboard/blob/62c90809f842549d2b253a5f4681d4a6b39cab06/Dashboard/Dashboard.png)

The Executive Dashboard presents a high-level summary of construction safety incidents through key performance indicators and interactive visualizations.

### Key Performance Indicators (KPIs)
- **Total Incidents:** 4,847
- **Fatal Cases:** 2,964
- **High-Risk Incidents:** 486
- **Average Risk Score:** 3.02

*These KPIs provide an overall picture of workplace safety performance and indicate that fatal incidents remain a significant concern.*

### Visual Insights
- **Degree of Injury:** Fatal incidents represent the largest proportion of recorded cases, indicating that workplace accidents often result in severe consequences.
- **Top 3 Incident Types:** The primary safety issues across sites are **Struck By**, **Other**, and **Vehicle** incidents.
- **Monthly Incident Distribution:** The highest number of incidents occurred during **March, February, and January**, suggesting that safety inspections and preventive measures should be strengthened during these peak months.

---

## ⚠️ Dashboard 2: Risk & Safety Analysis

![Dashboard 2 - Risk & Safety Analysis](https://github.com/azlinaaaa/Safety_Risk_Intelligent_Dashboard/blob/62c90809f842549d2b253a5f4681d4a6b39cab06/Dashboard/RISK%20%26%20SAFETY.png)

This section focuses on workplace risk levels, hazard groups, and frequently occurring dangerous situations.

- **Risk Score Distribution:** Most incidents fall within the `0–10` risk score range. Their high frequency indicates that continuous monitoring is required to reduce the overall volume of incidents.
- **Top Hazard Groups:** **Chemical / Fire Hazards** contribute the highest level of risk, followed by *Work at Height*, *Vehicle Hazards*, and *Machine Hazards*.
- **Top 5 Dangerous Keywords:** *Struck By, Struck Against, Crushing, Structural Collapse,* and *Tree Trimming*. 

> **🚨 Risk Alert:** The risk is highly driven by a few spike-based incidents rather than continuous exposure, with Chemical/Fire Hazard being the main contributor to overall risk. Most incidents are caused by struck-by/struck-against events, indicating weak control of site safety, exclusion zones, and operational discipline.

---

## 📈 Dashboard 3: Incident Analysis

![Dashboard 3 - Incident Analysis](https://github.com/azlinaaaa/Safety_Risk_Intelligent_Dashboard/blob/62c90809f842549d2b253a5f4681d4a6b39cab06/Dashboard/INICDENT.png)

This dashboard provides a detailed analysis of incident trends, injury locations, and project distribution.

### Top 5 Injured Body Parts
| Body Part | Percentage |
| :--- | :--- |
| **Head** | 35.22% |
| **Whole Body** | 19.10% |
| **Finger** | 18.93% |
| **Internal Injuries** | 13.87% |
| **Heart** | 12.80% |

*Head injuries account for more than one-third of all reported injuries, highlighting the critical importance of enforcing personal protective equipment (PPE) compliance.*

### Additional Insights
- **Monthly Trend:** March recorded the highest number of incidents, while June recorded the lowest.
- **Project Distribution:** A significant proportion of incidents are recorded under an "Unknown Project (0)", suggesting potential issues with data quality or incomplete incident reporting.

---

## 🔍 Dashboard 4: Root Cause & Investigation

![Dashboard 4 - Root Cause & Investigation](https://github.com/azlinaaaa/Safety_Risk_Intelligent_Dashboard/blob/62c90809f842549d2b253a5f4681d4a6b39cab06/Dashboard/ROOT%20CAUSE%20%26%20INVESTIGATION.png))

This dashboard investigates the underlying causes of workplace incidents by examining human and environmental factors.

> **⚠️ Investigation Alert:** Human error remains the main cause of incidents, especially unsafe decisions and bypassing safety controls. Chemical/Fire Hazards recorded the highest risk scores, while unsafe work conditions continue to increase overall site risk.

- **Human Factors:** Unsafe behavior and poor decision-making (e.g., Misjudgement, Safety Devices Removed) are major contributors.
- **Environmental Factors:** Work Surface, Shear Point Action, Weather, and Temperature significantly influence workplace safety.

### Highest Average Risk Score by Year
| Rank | Year | Hazard Group | Average Risk Score |
| :---: | :---: | :--- | :---: |
| 1 | 2017 | Chemical / Fire Hazard | 9.07 |
| 2 | 2016 | Chemical / Fire Hazard | 9.06 |
| 3 | 2017 | Vehicle Hazard | 9.00 |

*Chemical/Fire Hazards consistently recorded the highest risk scores across multiple years, making them the top priority for future safety improvement initiatives.*

---

## 💡 Key Takeaways
1. A total of **4,847 incidents** were analyzed, with 2,964 fatal cases recorded.
2. **March** consistently recorded the highest number of workplace incidents.
3. **Struck By** incidents are the most frequent accident type.
4. **Chemical/Fire Hazard** is the highest-risk hazard group across multiple years.
5. **Human error**, particularly poor judgment and unsafe decisions, remains the leading root cause.
6. **Head injuries** (35.22%) dominate reported injuries, emphasizing the need for strict PPE enforcement.
7. Unclassified project data highlights opportunities to improve **data quality and reporting accuracy**.

---

## 🛠️ Tools & Technologies Used
- **Microsoft Power BI** (Interactive Dashboard Design)
- **Power Query** (Data Cleaning & ETL)
- **DAX** (Data Analysis Expressions for Measures & KPIs)
- **Business Intelligence & Safety Analytics**
