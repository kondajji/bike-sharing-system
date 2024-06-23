# Project Name - Lending Club Case Study

This repository contains the code and presentation for a case study on identifying patterns of loan default using Exploratory Data Analysis (EDA). The case study is conducted for a consumer finance company specializing in lending various types of loans to urban customers.

## Problem Statement
#@ Bike Sharing Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The objective is to use EDA to understand how consumer and loan attributes influence the tendency of default, aiding in decision-making such as loan approval, amount adjustment, or higher interest rates.
## Data Understanding
The dataset contains loan data from 2007 to 2011, including applicant attributes and loan outcomes. A data dictionary is provided to understand variable meanings.

## Approach
1. **Data Loading and Cleaning**: Load the dataset, handle missing values, and clean the data.
2. **Exploratory Data Analysis (EDA)**: Perform univariate and bivariate analysis to understand the relationship between various attributes and loan default.
3. **Insights and Observations**: Summarize insights and observations from the analysis.
4. **Presentation**: Create a presentation summarizing the problem statement, analysis approach, key findings, and visualizations.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

### Goal
#### Key Driving factors/variables to determine if loan gets default are:
- Annual Income
- Loan Amount
- Interest Rate
- Loan Purpose
- Employment Duration
- Loan/Credit Grade

### Other Findings using EDA: 
- Loans with a **10+ year employment length**, **interest rates in the range of 10%-20%**, **credit grades of B, C, and D**, and **loan values in the range of 5K-20K**, with the purpose of **debt consolidation**, are the riskiest loans.
- Loan amount for defaulters ranges between **20%-35% of annual income** in general.
- The **median interest rate** for defaulters is higher than that of all loans, indicating that interest rate impacts loan payment. Almost **50% of loans** in the higher loan amount category get defaulted. **Higher loan amounts and high interest rates** are risky.
- Most loans that are charged off are held by individuals who either **rent or have a mortgage**. This could suggest that the financial burden of a mortgage or rent, combined with additional loan obligations, might stretch financial capacities, leading to defaults.

The detailed analysis is available in the notebook

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python 3.11.5
- pandas -2.0.3
- numpy -1.24.3
- matplotlib -3.7.2
- seaborn -0.12.2
- jupyter notebook -6.5.4


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This case study was carried out as part of Upgrad-IIITB AI-ML Executive PG Program
- References
    - Upgrad Course - https//learn.upgrad.com
    - YouTube Links - https://www.youtube.com/@codebasics
    

## Contact
- Created by [@kondajji]() & [@Shahtirth19]()


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
