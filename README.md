# Boston-Equity-Dashboard

Project Overview
This project analyzes 311 service request data from Boston (2015–2019) to assess citywide responsiveness, expose operational delays, and enable equitable, data-informed decision-making. It was developed as part of the ALY6015: Intermediate Analytics course at Northeastern University.

Objectives
Evaluate service equity across Boston neighborhoods

Identify departments with the highest delays

Understand factors influencing response times

Promote predictive, data-driven planning

Enable real-time monitoring through dashboards

Tools & Technologies
Power BI: For creating interactive visual dashboards

Python (scikit-learn, pandas, seaborn): For data preparation and regression modeling

Logistic Regression & LASSO: For identifying delay drivers and predicting on-time resolution

Chi-Square Tests: For evaluating reporting channels vs timeliness

Dataset
Source: Boston 311 Public Dataset (2015–2019)

Fields used:

Location, Neighborhood, Request Type

Timestamps (creation, closure)

Source (App, Call, Twitter, etc.)

Department assigned

Key Steps
Data Cleaning & Enrichment

Removed duplicates

Joined with Census population data

Engineered new features (season, requests per 1,000 residents)

Modeling & Analysis

Logistic Regression: To model the probability of on-time closure

LASSO Regression: To pinpoint key predictors of delay

Chi-Square Analysis: To test association between report channels and timeliness

Visualization

Mapped delays by department and neighborhood using Power BI

Tracked rise in app usage vs traditional reporting methods

Highlighted seasonal complaint patterns

Findings
Neighborhoods like Chestnut Hill and Mattapan face the longest delays (up to 70 hours)

Digital reporting (e.g., app use) is correlated with faster responses

Departments like Housing and Schools show the highest delay, suggesting staffing or workflow gaps

Service delivery is inequitable, with outer neighborhoods often underserved

Recommendations
Audit and support high-delay departments

Promote app-based tools in digitally underserved communities

Use seasonal/geographic patterns for proactive resource allocation

Deploy a real-time dashboard to guide operational decisions

Contributors
Harshit Mayank Singh

License
This project was developed as an academic submission and is not intended for commercial use. Please cite appropriately if referenced.
