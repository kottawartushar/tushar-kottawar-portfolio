# Project Title
Fraud Operations Dashboard

---

## 1️⃣ Project Context
**Organization / Client:** Turing / Aircall  
**Duration:**   January 2025 - September 2025 
**Role:**   Senior Data Analyst
**Domain / Focus Area:**   Fraud Analytics

---

## 2️⃣ Problem Statement
The rapid increase in fraudulent activities within Aircall since December 2024 has created significant risks, including compliance issues with carriers and authorities, financial losses due to chargebacks and refunds, and reputational harm. Existing mitigation measures across teams are fragmented, making it difficult to monitor fraud comprehensively. There is a pressing need for a unified, data-driven solution that can track fraud metrics, strengthen detection capabilities, and provide actionable insights in real time.

---

## 3️⃣ Objectives
The objectives of my project are as follows:

1. Develop a robust, accurate fraud-data pipeline that consolidates disparate sources into a single, reliable repository to enable consistent reporting and analysis.
   
2. Design and implement an interactive dashboard that tracks key fraud risk indicators and supports real-time as well as periodic reporting for decision-makers.
   
3. Apply advanced analytics and visualization techniques to strengthen fraud detection, reveal patterns and trends.
   
4. Ensure alignment with Aircall’s operational and compliance goals by producing actionable insights that reduce direct fraud costs and regulatory risks.
   
5. Incorporate a continuous improvement mechanism whereby feedback, new threats, and evolving business requirements are used to refine the pipeline, analytics logic, and dashboards over time. 

---

## 4️⃣ Data Sources & Tools
**Data Sources Used:**  
-   
-   

**Tools & Technologies:**  
1. Hex - for writing SQL queries and testing
2. Cursor - for pushing queries and/or modifications to existing queries to production
3. LookML - for Data visualization
4. GitHub - for version control

---

## 5️⃣ Methodology / Approach
This project follows a structured, data analytics and engineering approach:

1. **Requirement Gathering & Context:** Initial requirements and expectations were provided by a Manager from the Strategy & Operations team, who had prior research and documentation. This formed the baseline for the project.

2. **Identification of Fraud Filters & Logic:** Manual reports (daily/weekly/monthly) were reviewed to identify practical filters for detecting fraudulent events. SQL logic was designed and implemented to apply these filters accurately.
   
3. **Data Pipeline Development:** A robust ETL pipeline was developed to consolidate, clean and validate fraud event data from multiple sources for consistent reporting.
   
4. **Dashboard Development:** An interactive LookML dashboard was designed and deployed to track key KPIs in real time and support periodic reporting for decision-makers.
   
5. **Validation & Continuous Improvement:** Each stage was tested before deployment. Feedback from the Fraud Operational Specialist and supervisors was used to refine metrics, visualizations and pipeline logic as fraud patterns evolved.  

---

## 6️⃣ Deliverables

1. **Comprehensive Test Data Pipeline:** Designed, developed, and validated an end-to-end test data pipeline with integrated fraud filters, optimized SQL logic, and robust sanity checks to ensure complete data integrity and accuracy.

2. **Production-Grade Base Data Pipeline:** Engineered and deployed a scalable base data pipeline in the production environment, enabling consolidated fraud-event outputs for real-time monitoring and dashboard integration.

3. **Interactive Fraud Monitoring Dashboard:** Delivered a fully functional dashboard featuring finalized KPIs and dynamic visualizations such as “Total Fraud Events,” providing actionable insights through live integration with production data. 

---

## 7️⃣ Results / Impact

1. Enhanced fraud detection efficiency: Improved real-time visibility into fraudulent activity across key channels, enabling faster identification and resolution of suspicious events.

2. Accelerated operational reporting: Reduced manual data preparation time by ~60% through automated and scalable data pipelines, transitioning fraud monitoring cadence from weekly to daily.

3. Improved fraud investigation turnaround: Streamlined fraud reporting logic and unified data pipelines, cutting investigation time by ~30% and enabling proactive fraud management.

4. Strengthened data-driven decision-making: Empowered leadership and operations teams with a live, interactive dashboard for continuous monitoring and self-service analytics, reducing ad-hoc data requests by ~40%.

5. Established a sustainable data foundation: Delivered production-grade pipelines and validated data quality processes to support long-term scalability, auditability, and integration with future fraud analytics initiatives.  

---

## 8️⃣ Challenges & Learnings

**Challenges & Constraints:**

1. Fragmented Data Sources: Fraud-event data was scattered across Salesforce, Admin Portal, Companies, and Zendesk systems — each with differing field structures, timestamps, and fraud indicators. Consolidating these into a single, accurate fraud data model required extensive validation and SQL-based reconciliation logic.
   
2. Tool Access and Deployment Dependencies: Gaining access to production tools such as Cursor and VPN approvals from Turing initially delayed independent deployments. These constraints demanded proactive coordination with multiple teams across time zones.
   
3. Complex Logic Validation: Ensuring correctness across multiple fraud detection models (Customer BBA, Trial BBA, and ATO) involved detailed sanity checks, testing edge cases, and reconciling inconsistencies between manual reports and automated outputs.

4. Bandwidth and Time-Zone Constraints: Collaborating with Aircall’s Strategy & Ops team across regions required restructuring meeting cadences and refining communication efficiency to avoid bottlenecks.

**Learnings:**

1. Strengthened ability to design end-to-end data solutions — from pipeline architecture and SQL optimization to visualization through LookML — while ensuring business alignment.
   
2. Enhanced expertise in data quality assurance and governance, particularly in defining unified fraud detection logic that maintained accuracy and compliance.
   
3. Improved stakeholder management and cross-functional collaboration skills, effectively bridging technical complexity with business expectations under tight timelines.
   
4. Gained deeper understanding of fraud analytics in SaaS environments, translating operational data into actionable insights that directly supported risk mitigation and strategic decision-making. 

---

## 🔖 Tags / Keywords
SQL | Data Analytics | Data Visualization | LookML | Fraud Analytics | Data-Driven Decision Making | Cross-Functional Collaboration | Data Integration | Analytics Engineering | Operational Efficiency