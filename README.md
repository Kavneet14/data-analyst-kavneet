# data-analyst-kavneet
## Data Analytics Portfolio

### Data Wrangling Project 1
#### Project Title: Implementation of Data Analytics Platform for Enhanced Occupational Health and Safety Procedures at UCW HR Department

**Objective:**
The primary objective of this project was to implement a Data Analytics Platform (DAP) to enhance the Occupational Health and Safety (OHS) procedures at the University Canada West (UCW) HR Department. Leveraging AWS services, the project aimed to improve the efficiency, accuracy, and insights derived from OHS data.

**Background:**
The UCW HR Department has accumulated data on incident reports, employee surveys, and performance safety audits. However, this data was dispersed across different systems, making it challenging to derive meaningful insights. Implementing a DAP aimed to facilitate better decision-making and improve safety procedures.

**Dataset:**
The data wrangling process involved various datasets, including:
- **Incident Reports:** Details of workplace incidents, including date, type, severity, and resolution.
- **Employee Surveys:** Feedback from employees regarding safety measures and working conditions.
- **Performance Safety Audits:** Records of safety audits conducted within the organization, highlighting compliance and areas needing improvement.

**Methodology:**
The project followed a structured Data Analytics Platform implementation process:
1. **Data Analytical Question Formulation**
2. **Data Discovery**
3. **Data Storage Design**
4. **Test Dataset Generation**
5. **Data Ingestion**
6. **Data Storage**
7. **Data Pipeline Design**
8. **Data Cleaning**
9. **Data Structuring**
10. **Data Pipeline Implementation**
11. **Data Analysis**
12. **Data Visualization**
13. **Data Publishing**
14. **Data Enriching**
15. **Data Protection**

<img width="787" alt="port1" src="https://github.com/user-attachments/assets/90cfeed3-805d-4c2c-bb24-4117f6a876ad">

**AWS Architecture and Tools:**
The DAP utilized the following AWS services and components:
- **Amazon S3:** For data storage with multiple buckets for different stages of data processing.
- **AWS Glue:** For data integration and ETL (Extract, Transform, Load) processes.
- **AWS Glue DataBrew:** For data preparation and transformation.
- **Amazon Athena:** For querying data stored in S3.
- **Amazon QuickSight:** For data visualization and dashboard creation.
- **Amazon EC2:** For hosting custom applications or processing tasks.

**Key Metrics:**
The project focused on the following metrics:
- **Descriptive Metric:** Number of Incidents Reported
  - *Data Source:* Incident Reports
- **Diagnostic Metric:** Safety Compliance Rate
  - *Data Source:* Performance Safety Audits
- **Predictive Metric:** Employee Satisfaction Rate
  - *Data Source:* Employee Surveys
- **Prescriptive Metric:** Safety Improvement Action Index
  - *Data Sources:* Incident Reports, Employee Surveys, Performance Safety Audits

**Data Flow:**
1. Raw data was ingested into the "OHS/Landing" S3 bucket.
2. Data was processed and moved to the "OHS/Raw" bucket.
3. Further processing occurred, and data was stored in the "OHS/Trusted" bucket.
4. Finally, curated data was stored in the "OHS/Curated" bucket.
5. The curated data was used for analysis, visualization, and creation of data products.

**Security and Compliance:**
Security measures included data encryption, access controls, and compliance with relevant data protection regulations.

**Deliverables:**
- A fully implemented Data Analytics Platform on AWS.
- Cleaned and transformed datasets ready for analysis.
- Interactive dashboards for visualizing key OHS metrics.
- Documentation of the data wrangling and analysis processes.
- Recommendations for improving OHS procedures based on the insights gained.

**Timeline:**
The project timeline was 9 weeks.

---

### Descriptive Analysis Project 2
#### Project Title: Implementation of Data Analytics Platform for Workforce Pay Rate Analysis in Vancouver

**Objective:**
The primary objective of this project was to design and implement a Data Analytics Platform (DAP) on AWS for the City of Vancouver, focusing on analyzing workforce pay rates. The project aimed to provide insights into pay rate distribution and gender pay disparities to inform policy decisions.

**Dataset:**
The dataset included employee pay rates and gender information, containing the following key features:
- **Employee Pay Rates:** Details of salaries for various positions.
- **Gender Information:** Gender data of employees.

**Methodology:**
1. **Data Collection and Preparation**
2. **Data Storage Design**
3. **Data Ingestion**
4. **Data Processing and ETL**
5. **Data Analysis**
6. **Data Visualization**
7. **Data Access and Distribution**
8. **Automation and Orchestration**
   
<img width="880" alt="port2" src="https://github.com/user-attachments/assets/93f9a703-d98a-454e-a8cb-28ee1585345f">

**Tools and Technologies:**
The DAP utilized AWS services and components including:
- **Amazon S3:** For data storage.
- **AWS Glue:** For ETL processes.
- **AWS Glue DataBrew:** For data preparation.
- **Amazon Athena:** For querying data.
- **Amazon QuickSight:** For data visualization.
- **Amazon EC2:** For custom applications or processing tasks.

**Deliverables:**
- Fully functional AWS-based Data Analytics Platform.
- Automated ETL pipelines for data processing and preparation.
- Interactive QuickSight dashboards presenting key insights on workforce pay rates and gender pay disparities.
- Detailed reports on pay rate distribution and recommendations for addressing gender pay disparities.

**Timeline:**
The project timeline was 7 weeks.

---

### Data Quality Control Project
#### Project Title: Implementation of Data Quality Control Measures in AWS Data Analytic Platform for Vancouver Workforce Pay Rates Analysis

**Objective:**
The primary objective of this project was to establish a comprehensive Data Quality Control (DQC) framework within the AWS Data Analytic Platform for the City of Vancouver. This framework ensures the accuracy, security, consistency, and reliability of data, enhancing the city’s ability to make informed decisions and manage resources efficiently.

**Scope:**
The project focused on the following key areas:
- **Data Protection**
- **Data Governance**
- **Data Monitoring**

**Methodology:**
1. **Current State Assessment**
2. **Data Protection (Step 15)**
3. **Data Governance (Step 16)**
4. **Data Monitoring (Step 17)**
5. **Validation Rules and Procedures**
6. **Training and Best Practices**
7. **Feedback Mechanism**
![last-Cloud Solution W#7](https://github.com/user-attachments/assets/2b49e01e-a7c4-4134-b330-124f0d9d3304)
**Tools and Technologies:**
- **AWS Key Management Service (KMS):** For data encryption.
- **AWS Glue:** For metadata management and data cataloging.
- **Amazon CloudWatch:** For monitoring data quality metrics and generating alerts.
- **AWS Trusted Advisor and AWS CloudTrail:** For security auditing and operational insights.

**Deliverables:**
- A comprehensive Data Quality Control framework, including data protection, governance, and monitoring processes.
- Real-time monitoring dashboards visualizing data quality metrics.

**Timeline:**
The project was completed in 1 week, covering assessment, implementation, validation, training, and continuous monitoring setup.

This Data Quality Control initiative within the AWS Data Analytic Platform ensured the City of Vancouver’s data is secure, well-governed, and reliable, enhancing data-driven decision-making and operational efficiency.
