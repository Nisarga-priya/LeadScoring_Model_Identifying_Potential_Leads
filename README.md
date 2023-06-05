# LeadScoring_Model_Identifying_Potential_Leads
X Education has a low lead conversion rate despite acquiring a significant number of leads.The company aims to identify 'Hot Leads' with higher conversion chances to improve the lead conversion process.
Lead Scoring Model: Identifying Potential Leads for Higher Conversion Rates
X Education's Lead Scoring Model is designed to help identify potential leads with higher conversion chances, allowing for a more efficient lead conversion process. This model assigns a lead score between 0 and 100 to each lead, indicating the likelihood of conversion. By focusing efforts on leads with higher scores, X Education can prioritize and target the most valuable leads, leading to improved conversion rates.

## Dataset Overview
The dataset used for building the lead scoring model contains information on leads, including attributes such as lead source, total time spent on the website, total visits, and last activity. The target variable, 'Converted,' indicates whether a lead was converted (1) or not (0).

## Exploratory Data Analysis (EDA)
EDA was performed to gain insights into the dataset. Univariate analysis helped understand the distributions and characteristics of individual variables. Bivariate analysis explored relationships and correlations between variables, while multivariate analysis examined interactions and patterns among multiple variables.

## Data Preparation and Model Building
The dataset underwent cleaning and preprocessing steps to handle duplicates, missing values, and irrelevant columns. Feature selection techniques, such as Recursive Feature Elimination (RFE), were applied to select the most influential variables. The logistic regression model was built using the selected features, and the data was split into training and testing sets.

## Model Evaluation
The logistic regression model was evaluated on the test dataset, and its overall accuracy was determined to be 92%. The model's performance indicates its effectiveness in predicting the conversion likelihood of leads.

## Model Interpretation and Recommendations
Based on the logistic regression coefficients, key features that significantly influence lead conversion were identified. Recommendations based on the analysis include:

1. Focus on individuals who spend a significant amount of time on the website by sending them attractive offers.
2. Target unemployed individuals with programs emphasizing job or interview guarantees.
3. Optimize the search engine presence to ensure X Education appears prominently in relevant searches.
4. Send informative content, such as free courses and master classes, via email to engage potential leads.
5. Launch campaigns targeting housewives to encourage them to pursue education through X Education's courses, highlighting interview guarantee programs.


Repository Structure
data/: Contains the dataset used for analysis.
notebooks/: Jupyter Notebook files containing the code for data preprocessing, EDA, and model building.


