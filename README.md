# Car_insurance_policies_analysis

# 1. Project Overview

This project analyzes car insurance policy data in order to understand claim behavior among policyholders. The objective is to uncover patterns in:
- Claim frequency
-	Claim amount
-	Vehicle usage (private vs commercial)
-	Location and lifestyle factors
The insights from this analysis are intended to support better risk assessment, premium pricing, and policy decisions within the insurance company.

# 2. Data Source

The dataset used for this analysis contains information on 37,542 policyholders of an insurance company for August 2023. The dataset includes variables such as:
-	Car use (Private or Commercial)
-	Gender
-	Kid driving
-	Parent
-	Education level
-	Car make
-	Car model
-	Marital status
-	Car color
-	Car Year
-	Coverage Zone
-	Claim frequency
-	Claim amount
This dataset provides a detailed snapshot of how different groups of customers interact with the insurance system.

# 3. Data Cleaning
To ensure the accuracy and reliability of the analysis, the following data cleaning steps were carried out:
- Removal of Duplicate Records: Duplicate entries were identified and removed so that each policyholder was counted only once.
- Handling Missing Values: Missing values were either filled using appropriate methods or removed where necessary to avoid misleading results.
- Resolving Inconsistencies: Inconsistencies such as
  -  Different spellings for the same category
  -  Incorrect or mixed formats were corrected to standardize the data.
- Removal of Redundant Data: Unnecessary columns and repeated information were removed to improve data clarity and processing efficiency.

# 4. Exploratory Data Analysis (EDA)
Exploratory Data Analysis was used to investigate relationships and trends in the dataset. This included:
-	Comparing claim frequency across vehicle types
-	Examining claims based on education level
-	Analyzing claims by urban vs rural areas
-	Studying the effect of marital status
-	Comparing claim behavior across zones
Graphs, charts, and summary statistics were used to visually and numerically highlight patterns.

# 5. Findings
The analysis revealed the following key insights:
-	Private car owners had a higher claim frequency and higher claim amounts compared to commercial vehicle owners.
This suggests that private vehicle users may engage in more risky driving or use their vehicles more frequently.
-	Individuals with a Bachelor’s degree recorded the highest claim frequency, while those with PhDs had the lowest.
This could be linked to lifestyle, driving habits, or travel frequency.
-	This trend was consistent across different zones, meaning education level influenced claims similarly in all regions.
-	Urban areas had a higher claim frequency than rural areas, likely due to heavier traffic, congestion, and accident exposure.
-	Single policyholders recorded higher claim frequencies than married individuals, which may reflect differences in driving behavior and risk-taking.

**[Dashboard](https://github.com/Emediongcharlie/car_insurance_policies_analysis/blob/main/Car%20Insurance%20Analysis%20Dashboard.png)**

# 5. Recommendations
Based on the insights from the analysis, the following actions are recommended:
-	Install speed-limiting devices, especially in vehicles used by younger or high-risk drivers, to reduce accident rates.
-	Apply stricter claim controls for high-risk groups, particularly policyholders with Bachelor’s degrees who show higher claim frequency, to encourage more cautious driving behavior.
- Promote advanced driver training programs, especially for private vehicle owners, since they show significantly higher claim activity than commercial drivers.
- Introduce location-based premium adjustments, with urban drivers paying slightly higher premiums due to their increased risk exposure.

# 6. Limitations
Despite providing valuable insights, the analysis has some limitations:
- The data covers only one month (August 2023), which limits long-term trend analysis.
- The dataset does not include detailed driver behavior such as speed history or accident cause.
- External factors such as weather conditions, road quality, and traffic volume were not included.

