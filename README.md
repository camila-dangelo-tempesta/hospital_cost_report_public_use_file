# **Hospital Cost Report Public Use File**

## Financial Analysis with SQL Language and Linear Regression in R Language

The Hospital Cost Report Public Use File (Hospital Cost Report PUF) presents select measures provided by hospitals through their annual cost report, and is organized at the hospital level. 
The Hospital Cost Report PUF is available in an interactive format or a downloadable CSV.  
The PUF does not contain all measures reported in the cost reports, but rather includes a subset of commonly used measures.  
Any hospital that submitted a cost report in a given year will be included in the PUF.  
For a full list of variables included in this PUF and their descriptions, please see the [Data Dictionary](https://data.cms.gov/resources/hospital-provider-cost-report-data-dictionary)

<div align="center">
<p float="left">
    <img src="/images/cms.png" width="400" height="300"/>
</p>
</div>

***
## 1. BUSINESS PROBLEMS

A network of hospitals would like to understand the variables related to spending on hospital admissions of patients.

We will use data from a national hospital cost survey conducted by the US Agency for Healthcare consisting of hospital records of patient samples hospitalized.
The data provided is restricted to the city of Wisconsin and refers to patients in the age group from 0 to 17 years.

The project will be divided into two stages:

 * **Step 1**: Let's explore the data using SQL language and answer 10 business questions.

1. How many races are represented in the dataset?
2. What is the average age of the patients?
3. What is the patient age mode?
4. What is the variance of the age column?
5. What is the total expenditure on hospital admissions by age?
6. Which age generates the highest total expenditure on hospital admissions?
7. What is the total expenditure on hospital admissions by gender?
8. What is the average expense with hospital admissions by patient's race?
9. For patients over 10 years old, what is the average total expense with hospitalizations hospital?
10. Considering the previous item, what age has an average of spending over 3000?

 * **Step 2**: Let's perform analysis statistics with Language R through the ANOVA Test and Linear Regression and answer 7 questions business

1. What is the age distribution of patients attending the hospital?
2. Which age group has the highest total hospital expenditure?
3. Which diagnostic-based group (Aprdrg) has the highest total hospital expenditure?
4. Is the patient's race related to the total spent on hospital admissions?
5. The combination of age and gender of patients influences the total expenditure on hospitalizations at the hospital?
6. As length of stay is the crucial factor for hospitalized patients, we wish to find out whether length of stay can be predicted from age, gender and race.
7. Which variables have the greatest impact on hospital admission costs?

***
## 2. BUSINESS ASSUMPTIONS

To answer the proposed questions, it will first be necessary to understand what each variable in the dataset represents.
Then identify the issues, clean the data, organize it and answer the questions through graphs and statistics.

The dataset was generated from the sources below:

The [Hospital Cost Report Public Use File](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Cost-Report/HospitalCostPUF) and the [Haeth Data](https://healthdata.gov/) dataset can be accessed via the highlight.







***
Made By **Camila D'Angelo**

- 🔭 I’m currently working on [DS Comuity](https://www.comunidadedatascience.com/) and [Data Science Academy](https://www.datascienceacademy.com.br/bundle/formacao-cientista-de-dados)
- 🌱 I’m currently learning Data Science
- 📫 How to reach me:  [LinkeldIn](https://www.linkedin.com/in/camiladangelotempesta/)
***
