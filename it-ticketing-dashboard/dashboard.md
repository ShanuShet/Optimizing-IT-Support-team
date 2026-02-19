#  Dashboard Explanation – Supportlytics  
## Optimizing IT Support Team Performance

This document explains the purpose, analytical intent, and exploratory insights (EDA) behind each dashboard in the **Supportlytics** project. The dashboards are designed to guide decision-makers from a high-level overview to operational details and finally to service quality and risk assessment.

---

##  Dashboard 1: Executive Summary

### Purpose
The **Executive Summary dashboard** provides a high-level snapshot of IT support performance. It is designed for leadership and stakeholders who need quick insights into ticket volume, workload, and overall resolution effectiveness.

This dashboard answers the question:  
**“What is the current state of IT support operations?”**

---

### Key KPIs (Cards)
- **Total Tickets**  
  Indicates the overall workload handled by the IT support team within the selected time period.

- **Open Tickets**  
  Represents tickets that are currently unresolved (Open + In Progress + Pending).  
  Helps assess backlog and operational pressure.

- **Closed Tickets**  
  Shows tickets that have been successfully resolved.  
  Reflects team productivity.

- **Closure Rate (%)**  
  Measures efficiency by showing the ratio of closed tickets to total tickets.

---

### Visual Insights & EDA Questions

- **Total Tickets by Status (Donut Chart)**  
  *EDA Question:* How are tickets distributed across different statuses?  
  *Insight:* Highlights workload balance between Open, In Progress, Resolved, and Pending tickets.

- **Open Tickets by Priority (Pie Chart)**  
  *EDA Question:* Which priority levels contribute most to unresolved tickets?  
  *Insight:* Identifies risk areas where high or critical tickets remain open.

- **Total Tickets by Priority (Bar Chart)**  
  *EDA Question:* What priority levels dominate ticket creation?  
  *Insight:* Helps understand urgency distribution and resource allocation needs.

- **Tickets by Category (Bar Chart)**  
  *EDA Question:* Which issue categories generate the most tickets?  
  *Insight:* Reveals common problem areas such as Hardware, Software, or Network.

- **Ticket Trend Over Time (Line Chart)**  
  *EDA Question:* How does ticket volume change over time?  
  *Insight:* Detects spikes, seasonality, or unusual activity.

---

##  Dashboard 2: Operational Analysis

### Purpose
The **Operational Analysis dashboard** focuses on day-to-day support operations. It helps managers understand where tickets originate, how they are handled across departments and devices, and how priorities interact with ticket statuses.

This dashboard answers the question:  
**“Where are operational bottlenecks and workload concentrations?”**

---

### Key KPIs
- **High & Critical Tickets**  
  Indicates urgent workload requiring immediate attention.

- **Pending Tickets**  
  Highlights tickets stuck in waiting states, signaling potential workflow issues.

- **Distinct Users**  
  Measures the number of unique users raising tickets, indicating demand spread.

- **Average Tickets per Day**  
  Helps assess daily workload consistency.

---

### Visual Insights & EDA Questions

- **Total Tickets by Department (Bar Chart / Table)**  
  *EDA Question:* Which departments generate the most tickets?  
  *Insight:* Identifies departments requiring additional support or training.

- **Category vs Priority (Bar Chart)**  
  *EDA Question:* Which categories are associated with higher priorities?  
  *Insight:* Helps align specialized teams to high-impact issue types.

- **Priority vs Status Matrix**  
  *EDA Question:* How does ticket status vary across priorities?  
  *Insight:* Reveals delays or inefficiencies in resolving critical tickets.

- **Tickets by Device Type (Bar Chart)**  
  *EDA Question:* Which devices cause the most issues?  
  *Insight:* Guides hardware standardization or upgrade strategies.

- **Open Tickets Trend by Year and Status (Area / Line Chart)**  
  *EDA Question:* Are open tickets increasing or decreasing over time?  
  *Insight:* Shows operational improvement or backlog growth.

---

##  Dashboard 3: Service Quality & Risk

### Purpose
The **Service Quality & Risk dashboard** evaluates the reliability, fairness, and risk exposure of IT support services. It highlights unresolved critical issues, repeat problems, and user-level ticket concentration.

This dashboard answers the question:  
**“Where are service risks and quality gaps emerging?”**

---

### Key KPIs
- **Critical Open Tickets**  
  Indicates high-risk unresolved issues.

- **Reopened Tickets**  
  Measures quality issues in initial resolutions.

- **Resolution Efficiency**  
  Evaluates how effectively tickets are resolved over time.

- **Unclassified Tickets**  
  Highlights data quality and classification gaps.

---

### Visual Insights & EDA Questions

- **Tickets by User ID (Bar Chart)**  
  *EDA Question:* Are certain users repeatedly raising tickets?  
  *Insight:* Identifies power users, systemic issues, or misuse.

- **Tickets by Department and Status (Stacked Bar Chart)**  
  *EDA Question:* Which departments struggle with unresolved tickets?  
  *Insight:* Pinpoints service gaps at the departmental level.

- **Tickets by Year and Status (Stacked Area Chart)**  
  *EDA Question:* How is resolution quality changing over time?  
  *Insight:* Shows improvement or deterioration in service quality.

- **Tickets by Priority (Horizontal Bar Chart)**  
  *EDA Question:* How evenly are priorities handled?  
  *Insight:* Highlights imbalance in handling critical vs low-priority issues.

---

##  Overall Analytical Value
Together, these three dashboards provide:
- **Strategic visibility** for leadership  
- **Operational clarity** for managers  
- **Risk and quality awareness** for continuous improvement  

The layered approach ensures data-driven decisions that improve IT support efficiency, customer satisfaction, and operational resilience.

---
