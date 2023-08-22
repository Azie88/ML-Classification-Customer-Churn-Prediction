# ML-Classification-Customer-Churn-Prediction 🤖

![1_MyKDLRda6yHGR_8kgVvckg](https://github.com/Azie88/ML-Classification-Customer-Churn-Prediction/assets/101363399/a4ca31a7-db9c-4966-b6ae-59c780bfef9f)


A telecom company (Vodafone) wants to find out the likelihood of a customer leaving the company. This project aims to build a classification model that predicts if a customer will churn or not.

## Project Overview

In this project, we use Supervised Machine Learning (classification) Machine Learning to explore the significance of churn analytics as a strategic tool for telecommunication companies to proactively identify potential risk factors for churn, optimize retention efforts, and cultivate lasting customer relationships. The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework to explore and analyze customer churn within the Vodafone network service.

The churn analytics predictive model is a data-driven solution designed to address the persistent challenge of customer churn in subscription-based industries. This model aims to identify customers at risk of churn, enabling businesses to take proactive measures and implement targeted retention strategies.

## 📑 Table of Contents 🔖
- [Project Overview](#project-overview)
- [Project Links](#Project-Links-🔗)
- [Some Tools Used For The Project](#Some-Tools-Used-For-The-Project-🚀)
- [Dataset](#Dataset-💾)
- [Process](#Process)
- [Conclusion and Recommendation](#Conclusion-and-Recommendation)
- [How to use this repository](#How-to-use-this-repository)
- [Author](#Author)

## Project Links 🔗

| Code | Notebook                                     |             Published Article             |                                                                                                                                                          PowerBI Dashboard |
| ---- | ---------------------------------------- | :---------------------------------------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| LP 2 | [Customer Churn Classification Model](https://github.com/Azie88/ML-Classification-Customer-Churn-Prediction/blob/main/notebook/Project_notebook.ipynb) | [Read Article](https://medium.com/@obandoandrew8/machine-learning-for-classification-problems-customer-churn-prediction-ae46c574e60) | [View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzkyMzE5Y2ItNTdmZi00NTQ0LThjMDEtOGIyOWY5ZDliZDg1IiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9) |

##  Some Tools Used For The Project 🚀
<p align="left">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="vscode" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original-wordmark.svg" alt="pandas" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="numpy" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="45" height="45"/>
</p>


## Dataset 💾

<table>
<thead><tr>
<th><strong>Feature Name</strong></th>
<th><strong>Description</strong></th>
<th><strong>Data Type</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>customerID</td>
<td>Contains customer ID</td>
<td>categorical</td>
</tr>
<tr>
<td>gender</td>
<td>whether the customer female or male</td>
<td>categorical</td>
</tr>
<tr>
<td>SeniorCitizen</td>
<td>Whether the customer is a senior citizen or not (1, 0)</td>
<td>numeric, int</td>
</tr>
<tr>
<td>Partner</td>
<td>Whether the customer has a partner or not (Yes, No)</td>
<td>categorical</td>
</tr>
<tr>
<td>Dependents</td>
<td>Whether the customer has dependents or not (Yes, No)</td>
<td>categorical</td>
</tr>
<tr>
<td>tenure</td>
<td>Number of months the customer has stayed with the company</td>
<td>numeric, int</td>
</tr>
<tr>
<td>PhoneService</td>
<td>Whether the customer has a phone service or not (Yes, No)</td>
<td>categorical</td>
</tr>
<tr>
<td>MultipleLines</td>
<td>Whether the customer has multiple lines r not (Yes, No, No phone service)</td>
<td>categorical</td>
</tr>
<tr>
<td>InternetService</td>
<td>Customer’s internet service provider (DSL, Fiber optic, No)</td>
<td>categorical</td>
</tr>
<tr>
<td>OnlineSecurity</td>
<td>Whether the customer has online security or not (Yes, No, No internet service)</td>
<td>categorical</td>
</tr>
<tr>
<td>OnlineBackup</td>
<td>Whether the customer has online backup or not (Yes, No, No internet service)</td>
<td>categorical</td>
</tr>
<tr>
<td>DeviceProtection</td>
<td>Whether the customer has device protection or not (Yes, No, No internet service)</td>
<td>categorical</td>
</tr>
<tr>
<td>TechSupport</td>
<td>Whether the customer has tech support or not (Yes, No, No internet service)</td>
<td>categorical</td>
</tr>
<tr>
<td>streamingTV</td>
<td>Whether the customer has streaming TV or not (Yes, No, No internet service)</td>
<td>categorical</td>
</tr>
<tr>
<td>streamingMovies</td>
<td>Whether the customer has streaming movies or not (Yes, No, No internet service)</td>
<td>categorical</td>
</tr>
<tr>
<td>Contract</td>
<td>The contract term of the customer (Month-to-month, One year, Two year)</td>
<td>categorical</td>
</tr>
<tr>
<td>PaperlessBilling</td>
<td>Whether the customer has paperless billing or not (Yes, No)</td>
<td>categorical</td>
</tr>
<tr>
<td>PaymentMethod</td>
<td>The customer’s payment method (Electronic check, Mailed check, Bank transfer, Credit card)</td>
<td>categorical</td>
</tr>
<tr>
<td>MonthlyCharges</td>
<td>The amount charged to the customer monthly </td>
<td> numeric , int</td>
</tr>
<tr>
<td>TotalCharges</td>
<td>The total amount charged to the customer </td>
<td>object</td>
</tr>
<tr>
<td>Churn</td>
<td>Whether the customer churned or not (Yes or No)</td>
<td>categorical</td>
</tr>
</tbody>
</table>


## Process :paper

-   Pull data from multiple sources, including remote sql server database

-   Develop the hypothesis and some analytical questions to answer

-   Data Preprocessing and cleaning & EDA(Univariate, Bivariate and multivariate Analysis)

-   Ansewring the analytical questions with visualizations

-   Deploying visualizations with PowerBI

-   Balancing the dataset with SMOTE algorithm for overfitting

-   Feature engineering and scaling

-   Model training and Evaluation

-   Hyperparameter Tuning

-   Prediction test and model improvements

-   Conclusion and article writing


## Conclusion and Recommendation

- Number of months the customer has stayed with the company (tenure) and the contract term of the customer (contract) are the most important features that have strong correlation with churn of the customer

- Vodafone should  enhance Early Customer Experience because in the first 5-10 months,  customer tenure shows a higher churn rate, suggesting that customer experience in the initial stages is vital. Focusing on improving onboarding processes, service quality, and addressing customer concerns during this crucial period with tech support can enhance customer satisfaction and loyalty.

- Vodafone should Promote Long-Term Contracts, since the analysis indicates that customers with month-to-month contracts have a significantly higher churn rate compared to those with one-year or two-year contracts. Encouraging customers to opt for longer-term contracts through incentives, benefits, and increased tech support can potentially reduce churn rates and foster customer commitment.

- Hyperparameter tuning does not always drasitically improve model performance

- With 80/20 train/eval split, the random forest model achieved an accuracy of ~87%

- Gradient Boosting models perform well on classification tasks, compared to other regular ML models

##  How to use this repository :monocle_face:

1. Clone this repository: `git clone https://github.com/Azie88/ML-Classification-Customer-Churn-Prediction`
2. Navigate to the project directory: `ML-Classification-Customer-Churn-Prediction`
3. Explore the Jupyter notebook for detailed steps and code execution.
4. Check out the Power BI dashboard for interactive visualizations.
5. Read the published article for a comprehensive understanding of the project.

## Author✍️

Andrew Obando

Connect with me on LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/andrewobando/)

---
