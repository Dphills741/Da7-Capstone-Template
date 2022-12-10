
# Analysis of Medicaid Prescription Drug Statistics in Relation to Drug Mortality and Substance Abuse Treatment throughout the United States
Capstone Project for Cohort DA7 at Nashville Software School

### **Contents**  
- [Motivation](#Motivation)
- [Data Sources and Tools](#Data-Sources-and-Tools)
- [Data Analysis](#Data-Analysis)
- [Challenges](#Challenges)
- [Conclusions](#Conclusions)
- [Use Case Scenario 1](#Use-Case-Scenario-1)
- [Use Case Scenario 2](#Use-Case-Scenario-2)

### **Motivation** 
Since 2019 I have worked in multiple retail and hospital pharmacies, and have been in close contact with multiple altercations involving fake prescriptions, fake faxes and all sorts of cons to gain medications illegally. In this project, I will explore the amount of legally acquired drugs and gain insight on how that affects our American population. I hope this may raise awareness of drug addiction, and give possible actionable insights about drug control. 

### **Data Sources and Tools**   
**Data Sources**   
Drug Data : https://catalog.data.gov/dataset/state-drug-utilization-data-2020-3e746
FAQ Drug Questions : https://www.medicaid.gov/medicaid/prescription-drugs/state-drug-utilization-data/state-drug-utilization-data-faq/index.html?search_api_fulltext=91956 
Drug Mortality Data : https://www.cdc.gov/nchs/pressroom/sosmap/drug_poisoning_mortality/drug_poisoning.htm
Substance Abuse Treatment Data : https://www.samhsa.gov/data/data-we-collect/n-ssats-national-survey-substance-abuse-treatment-services

**Tools**

Python/Jupyter Notebooks for analysis of data
Tableau for data visualization   

### **Data Analysis**
To begin my analysis, I obtained five years worth of csv files for both national drug utilization and drug mortality from goverment Medicaid data and data from the CDC respectively. 
I then began to narrow down my search of medications to those that included the most common opioids, and benzodiazepines which are both the most common subsets of drugs that are overdosed on. A brief list of these medications would contain medications such as hydrocodone, fentanyl, morphine, valium, klonopin, and many more.
I further then broke this down by state. This allowed me to gain a total amount of perscriptions sold per state to compare to my mortality statistics. 

### **Challenges**
The first challenge that arose was labeling as many opioid and benzodiazepines as possible within my dataset. I started with medications that were the most commonly abused, but found that there is little standardization within Medicaid data. There were more than five listings of morphine that all had to be accounted for within the code. 
The second challenge I faced using data sets over such a time period was changes in data structure and keys.

### **Conclusions**
[Drug Mortality per Prescription in the U.S. - Tableau Dashboard]
https://public.tableau.com/app/profile/daniel.hills/viz/DrugMortalityperPrescriptionintheU_S_/Dashboard1?publish=yes
!