# Marine Predictive Modelling: A Supervised Machine Learning Approach

This project presents a supervised machine learning model aimed at predicting the age of abalone from physical measurements.

### Repository Contents
- **EDA Files:**
  - `EDA_abalone.qmd`, `EDA_abalone.html`: The Quarto markdown file and its rendered HTML output containing the exploratory data analysis (EDA) code and narrative.
- **Full Report Files:**
  - `analysis_abalone.qmd`, `analysis_abalone.html`: The Quarto markdown file and its rendered HTML that contains the complete analysis, including data preprocessing, model development, and evaluation.
 
## Discovering Solutions
This project was developed with the aim of addressing several key challenges:
- **Balancing Complexity and Usability:** Creating a predictive model that balances technical sophistication with practical usability, making advanced ecological research accessible to a broader audience.
- **Contributing to Sustainable Marine Resource Management:** By providing a tool for accurate and ethical age determination, this project supports efforts towards the sustainable management of marine resources, ensuring the longevity and health of abalone populations.

## How it's Made
The analysis utilizes **Multiple Linear Regression**, a supervised learning technique, to predict abalone age. The project is structured as follows:
- **Exploratory Data Analysis** 
- **Data Preprocessing:** Before modeling, data cleaning was conducted by checking for missing values and independence among measurements. Variable scaling was applied to address the skewed distribution of the target variable (rings/age).
- **Model Development:**
  - **Original Model:** Includes all predictors, providing a baseline for performance comparison.
  - **Live Abalone Model:** Excludes post-mortem measurements, focusing on predictors obtainable from living abalone.

- **Model Selection via AIC Minimization:** I applied both forward and backward stepwise regression, guided by the AIC, to identify the most informative subset of predictors while avoiding overfitting.

## Testing and Validation
- **Assumption Checks**
- **Performance Metrics:** The models were evaluated based on R² (explained variance), RMSE (Root Mean Square Error), and MAE (Mean Absolute Error), with cross-validation to assess generalizability.

## Lessons Learned
- **Ethical Data Science:** The importance of considering ethical implications in model selection and data collection.
- **Supervised Learning:** Demonstrated the potential of linear regression and AIC minimization in ecological research.
- **Trade-offs in Model Complexity:** Explored the balance between model accuracy and simplicity, emphasizing the value of non-invasive predictors.

## Examples
Here are a few more projects from my portfolio:
- [Moderator Program + Test Framework](https://github.com/christy511/ModeratorProgram-TestFramework)
A chat forum moderation program and a separate testing program designed to evaluate the performance of the moderation program.
- [Personalised Fitness Analytics Program](https://github.com/christy511/Personalised-Fitness-Analytics-Program)
Adaptive workout recommendation engine using conditional logic and user data.
