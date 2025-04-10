# Fraudulent_Claim_Detection_Saravana-kumarR_Sonali-Bisht
Problem Statement
Global Insure, a leading insurance company, processes thousands of claims annually. However, a significant percentage of these claims turn out to be fraudulent, resulting in considerable financial losses. The company’s current process for identifying fraudulent claims involves manual inspections, which is time-consuming and inefficient. Fraudulent claims are often detected too late in the process, after the company has already paid out significant amounts. Global Insure wants to improve its fraud detection process using data-driven insights to classify claims as fraudulent or legitimate early in the approval process. This would minimise financial losses and optimise the overall claims handling process.

Business Objective
Global Insure wants to build a model to classify insurance claims as either fraudulent or legitimate based on historical claim details and customer profiles. By using features like claim amounts, customer profiles and claim types, the company aims to predict which claims are likely to be fraudulent before they are approved.

Based on this assignment, you have to answer the following questions:

● How can we analyse historical claim data to detect patterns that indicate fraudulent claims?
● Which features are most predictive of fraudulent behaviour?
● Can we predict the likelihood of fraud for an incoming claim, based on past data?
● What insights can be drawn from the model that can help in improving the fraud detection process?
Assignment Tasks
You need to perform the following steps for successfully completing this assignment:

Data Preparation
Data Cleaning
Train Validation Split 70-30
EDA on Training Data
EDA on Validation Data (optional)
Feature Engineering
Model Building
Predicting and Model Evaluation
Data Dictionary
The insurance claims data has 40 Columns and 1000 Rows. Following data dictionary provides the description for each column present in dataset:

Column Name	Description
months_as_customer	Represents the duration in months that a customer has been associated with the insurance company.
age	Represents the age of the insured person.
policy_number	Represents a unique identifier for each insurance policy.
policy_bind_date	Represents the date when the insurance policy was initiated.
policy_state	Represents the state where the insurance policy is applicable.
policy_csl	Represents the combined single limit for the insurance policy.
policy_deductable	Represents the amount that the insured person needs to pay before the insurance coverage kicks in.
policy_annual_premium	Represents the yearly cost of the insurance policy.
umbrella_limit	Represents an additional layer of liability coverage provided beyond the limits of the primary insurance policy.
insured_zip	Represents the zip code of the insured person.
insured_sex	Represents the gender of the insured person.
insured_education_level	Represents the highest educational qualification of the insured person.
insured_occupation	Represents the profession or job of the insured person.
insured_hobbies	Represents the hobbies or leisure activities of the insured person.
insured_relationship	Represents the relationship of the insured person to the policyholder.
capital-gains	Represents the profit earned from the sale of assets such as stocks, bonds, or real estate.
capital-loss	Represents the loss incurred from the sale of assets such as stocks, bonds, or real estate.
incident_date	Represents the date when the incident or accident occurred.
incident_type	Represents the category or type of incident that led to the claim.
collision_type	Represents the type of collision that occurred in an accident.
incident_severity	Represents the extent of damage or injury caused by the incident.
authorities_contacted	Represents the authorities or agencies that were contacted after the incident.
incident_state	Represents the state where the incident occurred.
incident_city	Represents the city where the incident occurred.
incident_location	Represents the specific location or address where the incident occurred.
incident_hour_of_the_day	Represents the hour of the day when the incident occurred.
number_of_vehicles_involved	Represents the total number of vehicles involved in the incident.
property_damage	Represents whether there was any damage to property in the incident.
bodily_injuries	Represents the number of bodily injuries resulting from the incident.
witnesses	Represents the number of witnesses present at the scene of the incident.
police_report_available	Represents whether a police report is available for the incident.
total_claim_amount	Represents the total amount claimed by the insured person for the incident.
injury_claim	Represents the amount claimed for injuries sustained in the incident.
property_claim	Represents the amount claimed for property damage in the incident.
vehicle_claim	Represents the amount claimed for vehicle damage in the incident.
auto_make	Represents the manufacturer of the insured vehicle.
auto_model	Represents the specific model of the insured vehicle.
auto_year	Represents the year of manufacture of the insured vehicle.
fraud_reported	Represents whether the claim was reported as fraudulent or not.
_c39	Represents an unknown or unspecified variable.
