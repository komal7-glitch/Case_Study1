# Case_Study1
👓 Campaign Budget Optimization for Eyewear Retailer
📌 Problem Statement
A national eyewear retailer has conducted targeted marketing campaigns leveraging individual-level response probability scores. The CRM Director seeks data-driven recommendations on how to:

Evaluate historical campaign effectiveness.

Identify key drivers of customer responses.

Optimize the $2M marketing budget for maximum ROI across future campaigns.

🎯 Project Objectives
Model Campaign Impact: Quantify the influence of product, month, and milestone on response rates using machine learning.

Prioritize Customers: Leverage response probability scores to rank customers and simulate different campaign scenarios.

Budget Optimization: Design a budget allocation strategy across campaign segments to maximize customer responses and return on investment.

🧰 Tools & Technologies Used
Python: Pandas, Scikit-learn, SHAP, PuLP/Scipy.optimize

Power BI / Excel: For dashboarding and optimization (Excel Solver)

SQL: Data manipulation and transformation

Git & GitHub: Version control and code sharing

🧭 Step-by-Step Approach
📅 Day 1: Exploratory Analysis & Modeling
Loaded and cleaned customer-level and campaign-level data.

Performed EDA to assess impact of product type, month, and milestone on response rate.

Built classification models (Logistic Regression, XGBoost) to determine feature importance.

Interpreted model outputs using SHAP to derive actionable insights.

📅 Day 2: Score-Based Budget Simulation
Ranked customers using probability scores.

Simulated response outcomes at different score thresholds.

Evaluated ROI and campaign efficiency across segments.

Designed dashboard (Power BI/Excel) for strategy comparison.

📅 Day 3: Optimization & Final Recommendation
Formulated budget planning as a constrained optimization problem.

Defined constraints (budget, mailing cost, customer limits).

Solved using Python’s PuLP/Scipy.optimize or Excel Solver.

Compiled final slide deck summarizing insights, approach, and recommendation.

📢 Summary
This project provides a data-driven approach to campaign planning, combining predictive modeling, customer segmentation, scenario analysis, and optimization to drive measurable business value for an eyewear retailer.

If you need help setting up or running this project, feel free to reach out!

📧 Komal Yadav – ky4207479@gmail.com
