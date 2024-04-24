<h1 style="font-size: 40px; border-bottom: 7px solid #57c4d0">FDA Adverse Event Reporting System (FAERS) Analysis & Insights</h1>

# **Executive Summary**

## Project Overview: Analyzing Trends in Real World Adverse Healthcare Events


This comprehensive analysis of the FDA Adverse Event Reporting System (FAERS) dataset for the third and fourth quarters of 2023 by Team1 reveals critical trends and insights into reported adverse healthcare events. Our investigation targets enhancing understanding of drug safety and efficacy monitoring, crucial for improving patient care and healthcare outcomes.

## Key Findings

 * Prevalence of Adverse Reactions: The analysis identified the most common adverse reactions reported in the latter half of 2023, with 'dependence', 'drug ineffective', 'off-label use', 'death', and 'overdose' being the most frequent. This highlights areas where healthcare providers and patients must exercise caution.

* Impact of Reporting Sources: The data shows a significant influence of report sources on the reported outcomes. Reports from consumers and health professionals, particularly, indicate hospitalizations as the dominant outcome, underscoring the importance of these reports in identifying potential risks associated with drug use.

* Therapy Duration and Off-Label Drug Usage: Our findings suggest a strong correlation between therapy durations and the frequency of adverse reactions. Notably, adverse reactions peak within the first two days of therapy initiation, emphasizing the need for vigilant monitoring during this period. Additionally, the analysis uncovers significant off-label use of specific drugs, with 'INFLECTRA' leading, indicating a potential area for regulatory review and guidance.

* Demographic Insights: The quarterly variation in the average age of patients and the number of patients provides valuable insights into the demographics most affected by adverse drug events, informing targeted interventions and awareness programs.

## Implications for Healthcare

* The insights call for heightened monitoring and post-marketing surveillance by healthcare professionals, especially during the initial stages of therapy.

* The identification of commonly reported adverse reactions and the significant off-label use of drugs like 'INFLECTRA' underscore the need for ongoing education and communication between healthcare providers and patients about the potential risks of drug therapies.

* The variations in adverse event reporting by source and demographic differences highlight the importance of personalized and demographic-specific healthcare approaches.

## Significance

This analysis underscores the critical role of FAERS data in enhancing drug safety monitoring and healthcare delivery. By identifying key trends and insights into adverse drug reactions, healthcare stakeholders can better understand the risks associated with drug therapies, leading to improved patient safety and care outcomes.

# **Business Context**


## Problem Statement

Our project aims to analyze the FAERS database, hosted by the FDA, which contains reports of adverse drug events from hospitals, reported by both healthcare professionals and consumers. We'll use the data from the last two quarters of 2023, accessed through quarterly snapshots, to identify trends in common and severe adverse drug events. This involves examining drug types, active ingredients, patient demographics, and medical conditions to determine the most frequent and serious drug-related complications.

## Data Source

The [FAERS dataset](https://www.fda.gov/drugs/questions-and-answers-fdas-adverse-event-reporting-system-faers/fda-adverse-event-reporting-system-faers-public-dashboard) comprises reports of adverse events related to drug usage. It includes detailed information about the patient demographics, reported outcomes, drug specifics, and event descriptions, which were meticulously cleaned and structured for this analysis. Due to the large amounts of data present in this data source, we extracted data only for the last two quarts of 2023 and appended them together. If we included any further data in our extraction, we would hit the RAM limit provided in google colab and would not be able to continue forward with our analysis. 

## Motivation

We aim to simplify the complex FAERS data into clear summary statistics, helping doctors spot potential drug risks to enhance patient care and ease their workload. This can be used to produce warnings for prescribers of potential adverse drug events that could occur based on the treatment doctors are proposing for a patient. By doing so, we aim to contribute to the improvement of patient safety and the overall healthcare system's response to drug-related issues.

# Data Visualizations**


## Interactive Dashboards

### Demographics Dashboard


### Medical Dashboard


## Tableau Links

The below links represent the same embedded dashboards as above should you wish to open and interact with them in a new tab. 


* [Demographics Dashboard](https://public.tableau.com/views/FAERS-Tableau-Dashboard-Team1/DemographicResponses?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

* [Medical Dashboard](https://public.tableau.com/views/FAERS-Tableau-Dashboard-Team1/MedicalResponses?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

# **Python Data Analysis**

[Analytics File](https://public.tableau.com/views/FAERS-Tableau-Dashboard-Team1/MedicalResponses?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

# **Challenges**

# **Conclusion**
