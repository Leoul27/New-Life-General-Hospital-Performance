# New-Life-General-Hospital-Performance-Analysis
<img width="1672" height="941" alt="Introductory Picture" src="https://github.com/user-attachments/assets/bb984382-5f6d-4db8-8d08-50cf6b1ee1ec" />

## Table of Content

- [Introduction](#introduction)
- [About the dataset](#about-the-dataset)
- [Problem Statement](#problem-statement)
- [Visualization – Hospital Performance Dashboard](#visualization-–-Hospital-Performance-Dashboard)
- [Insights – Key Findings from the Analysis](#insights–Key-Findings-from-the-Analysis)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
## Introduction
Healthcare institutions generate large amounts of data through patient admissions, medical treatments, departmental activities, billing, and insurance transactions. However, collecting data alone is not enough; it must be properly analyzed to support effective decision-making.
This project analyzes New Life General Hospital's patient and financial records for 2024–2025. Its objective is to transform raw hospital data into meaningful insights through data analysis and visualization. The analysis explores patient demographics, departmental performance, hospital billing, payment status, insurance coverage, and patient length of stay.
The resulting dashboard is intended to provide hospital management with a clear overview of operational and financial performance, helping identify trends, evaluate departmental contributions, and recognize areas that may require improvement.

## About the Dataset
The dataset contains 1,000 patient records covering two consecutive years, from January 2024 to December 2025. The patient-level worksheet contains identification, demographic information, admission and discharge dates, medical departments, diagnoses, billing information, insurance coverage, and payment details.

- Total records_1,000 patient records
- Reporting period_2024–2025
- Departments_6 departments
- Gender categories_Male and Female
- Age range_1–85 years
- Payment categories_Paid, Partially Paid, Pending

### Key variables

- Patient information Patient ID Patient Name, Age, and Gender.
- Medical information: Department and Diagnosis.
- Hospitalization: Admission Date, Discharge Date, and Average Length of Days.
- Financial information: Total Bill Amount, Paid Amounts, and Unpaid.
- Insurance information: Insurance Coverage % and Estimated Insurance Coverage Amount.
- Classification: Payment Status and Age Category.

## Problem Statement
The management of a New Life General Hospital has observed a change in patient admissions, outstanding medical bills, and variations in insurance coverage across its departments. The hospital wants to use patient admission, billing and insurance data to understand its operational performance, monitor payments and improve management decision-making. However, the hospital currently lacks a consolidated report that provides a clear picture of its operational and financial performance. 
This project addresses these challenges by analyzing historical hospital data and developing a dashboard that provides an integrated view of operational and financial performance.
The analysis seeks to answer the following business questions:
1.	How many patient visits has the hospital recorded? 
2.	Which departments receive the highest number of patients? 
3.	Which departments generate the highest total bills? 
4.	What is the average length of stay for patients across different departments? 
5.	What proportion of patient bills has been paid, remains pending, or has been partially paid? 
6.	How much has the hospital billed, and how much remains outstanding? 
7.	How does insurance coverage vary across departments and diagnoses? 
8.	Which age groups account for the highest number of patient visits? 
9.	How do admissions and billing amounts change over time? 
10.	Which areas may require management attention based on the analysis?

The ultimate goal is to provide actionable information that supports better resource allocation, financial monitoring, and operational planning.

## Visualization – Hospital Performance Dashboard

This section is reserved for a screenshot of the completed Excel dashboard. The existing workbook's Dashboard worksheet was blank at the time of analysis, so the image should be inserted after the dashboard has been built.

 <img width="1341" height="801" alt="Dashboard Picture" src="https://github.com/user-attachments/assets/36a54b79-98bf-4b65-be83-70b0fdd61007" />

## Insights – Key Findings from the Analysis

### Overall hospital performance
- Total patients:	1,000
- Total bill amount:	8,053,143.44
- Recorded paid amount:	4,568,527.32
- Average length of stay:	4.81 days
- Average insurance coverage:	74.86%

The hospital recorded 1,000 patient admissions over the two-year period. Total billing amounted to approximately 8.05 million, while recorded payments amounted to approximately 4.57 million. The average hospitalization period was approximately 4.81 days.
### Patient demographics
Gender distribution: Female patients account for 51.2% (512 patients), while male patients account for 48.8% (488 patients). This indicates a relatively balanced gender distribution.
|Age category|	Patients|	Percentage|
|---------|------------|------------|
|Under 18|	153|	15.3%|
|18–35|	170|	17.0%|
|36–50|	199|	19.9%|
|51–65|	246|	24.6%|
|66 and above|	232|	23.2%|

The largest patient group is between 51 and 65 years old, representing 24.6% of all patients. Patients aged 51 and above account for 47.8% of the total patient population.
### Departmental performance
|Department	|Patients	|Total bills|
|-----------|---------|-----------|
|General	|252	|$ 993,026.92|
|Emergency	|190	|$ 622,525.28|
|Orthopedics	|159	|$ 2,553,862.32|
|Pediatrics	|153	|$ 572,987.96|
|Cardiology	|152	|$ 2,095,437.97|
|Neurology	|94	|$ 1,215,302.99|

General Medicine records the highest number of patients, with 252 admissions. However, Orthopedics generates the highest billing revenue, approximately 2.55 million, accounting for 31.7% of total hospital billing. The department with the highest patient volume is therefore not necessarily the department generating the highest revenue.
### Financial performance
Total bill amount: $ 8,053,143.44. Total recorded paid amount: $ 4,568,527.32. The average insurance coverage recorded in the dataset is 74.86%. The recorded paid amount represents approximately 56.7% of total billing.
|Payment status	|Patients	|Percentage|
|---------------|---------|-----------|
|Paid	|564	|56.7%|
|Partially Paid	|179	|17.4%|
|Pending	|257	|25.9%|

More than half of the patient records are classified as fully paid, while 25.9% are classified as pending.
### Average length of hospital stay
|Department	|Average stay|
|-----------|------------|
|Orthopedics	|8.38 days|
|Neurology	|6.91 days|
|Cardiology	|6.49 days|
|General	|3.93 days|
|Pediatrics	|3.04 days|
|Emergency	|2.03 days|

Orthopedics has the longest average patient stay at approximately 8.38 days, followed by Neurology at 6.91 days. Emergency has the shortest average stay at approximately 2.03 days. These differences may help management understand departmental resource utilization and hospitalization patterns.
### Annual performance comparison
|Indicator	|2024	|2025|
|-----------|------|------|
|Patients	|508	|492|
|Total billing	|4,132,465.36	|3,920,678.08|
|Recorded paid amount	|2,227,834.70	|2,340,692.62|
|Paid-to-billed ratio	|53.9%	|59.7%|

-	Patient volume decreased by approximately 3.1% in 2025.
-	Total billing decreased by approximately 5.1%.
-	Recorded paid amounts increased by approximately 5.1%.
-	The paid-to-billed ratio increased from 53.9% to 59.7%.
-	
Despite the reduction in patient numbers and total billing, the hospital recorded a higher payment amount in 2025. This suggests an improvement in recorded payment performance, although the underlying payment records should be validated before drawing conclusions about actual collections.
  ### Most frequent diagnoses
|Diagnosis	|Patients|
|-----------|--------|
|Pneumonia	|43|
|Gastritis	|39|
|Dehydration	|38|
|Anemia	|37|
|Fracture	|37|
|Carpal Tunnel	|37|

Pneumonia is the most frequently recorded diagnosis, with 43 patient records. This information can help the hospital understand the distribution of recorded medical conditions and plan relevant resources.
## Recommendations
1.	Strengthen financial monitoring: Regularly monitor billed amounts, collected payments, pending payments, and partially paid accounts. Distinguish insurance responsibility, patient responsibility, and actual outstanding balances.
2.	Improve departmental resource allocation: Orthopedics and Cardiology contribute approximately 57.7% of total hospital billing. Evaluate whether staffing, medical equipment, and other resources are appropriately allocated to these departments.
3.	Investigate declining patient volume: The reduction in patient admissions from 508 in 2024 to 492 in 2025 should be investigated. Examine patient satisfaction, service availability, referral patterns, and other factors that may influence patient visits.
4.	Monitor long-stay departments: Review patient care processes, discharge planning, and resource utilization in Orthopedics, Neurology, and Cardiology, which have relatively longer average hospitalization periods.
5.	Develop age-specific healthcare planning: Patients aged 51 and above represent 47.8% of the recorded population. Consider appropriate staffing, medical equipment, and healthcare services for this patient group.
6.	Improve insurance and payment management: Strengthen coordination with insurance providers and establish effective payment follow-up procedures to improve financial transparency and collection efficiency.
7.	Establish continuous performance monitoring: Use the dashboard to monitor monthly and annual performance, identify emerging trends, and support evidence-based decisions.
## Conclusion
This project demonstrates how raw hospital records can be transformed into meaningful business intelligence through data analysis and visualization. By examining 1,000 patient records across six hospital departments over two years, the analysis provides valuable insights into patient demographics, departmental performance, financial activities, insurance coverage, and hospitalization patterns.
The findings reveal that General Medicine handles the highest number of patients, while Orthopedics generates the highest billing revenue and has the longest average patient stay. The analysis also highlights changes in annual financial performance and identifies areas requiring further investigation.
Overall, the project demonstrates the importance of data-driven decision-making in healthcare management. A well-designed performance dashboard can help hospital administrators monitor key performance indicators, identify operational challenges, improve financial oversight, and make more informed strategic decisions.
