# bcgx-customer-churn
## job simulation @ BCG X

This repository showcases my completed work from the **BCG X Forage Job Simulation**. This virtual experience provided an immersive opportunity to tackle real-world business challenges, mirroring the work of a consultant at BCG X, the tech build & design unit of Boston Consulting Group. The simulation focused on developing practical skills in strategic problem-solving, data analysis, and machine learning within a digital transformation context.

## Project Overview

This project demonstrates an end-to-end data science workflow applied to a critical business challenge. The core objective was to leverage data to understand and address a specific problem, ultimately providing data-driven recommendations. The workflow is broken down into distinct phases, each documented in a dedicated Jupyter Notebook, reflecting the iterative nature of data-driven problem-solving in a consulting environment.

## Problem Statement (As Addressed in the Simulation)

In the BCG X Forage Data Science simulation, the primary challenge revolved around **customer churn prediction and retention strategies for a telecommunications company**. The company was experiencing a significant rate of customer attrition, impacting revenue and market share. The goal was to:

* **Identify key drivers of churn**: Understand which customer behaviors, service usage patterns, or demographic factors contribute most to customers leaving.

* **Predict future churn**: Develop robust machine learning models capable of accurately predicting which customers are most likely to churn in the near future.

* **Inform retention strategies**: Provide actionable insights and a predictive tool that business teams can use to proactively intervene and retain at-risk customers, thereby minimizing churn and maximizing customer lifetime value.

This project utilized a comprehensive dataset containing customer demographics, service usage, contract details, and churn status to achieve these objectives through a structured data science approach.

## Project Components (BCG X Forage Tasks)

The following Jupyter Notebooks represent the key tasks and analytical phases undertaken during the BCG X Forage job simulation:

### 1. `Task_2_EDA_.ipynb` - Exploratory Data Analysis (EDA)

* **Objective:** To thoroughly understand the provided datasets, identify key trends, distributions, and potential data quality issues relevant to the business problem.

* **Description:** This notebook focuses on initial data inspection, descriptive statistics, and various data visualizations. It's crucial for gaining foundational insights into the data, which informs subsequent feature engineering and modeling decisions within the simulation's context, particularly in understanding customer behavior and potential churn indicators.

* **Key Activities:** Data loading, summary statistics, missing value analysis, distribution plots, correlation matrices, and initial hypothesis generation related to customer churn.

### 2. `Task_3_Feature_Engineering.ipynb` - Feature Engineering

* **Objective:** To transform and prepare the raw data into a format suitable for machine learning models, enhancing their ability to extract valuable patterns and improve predictive performance.

* **Description:** This notebook details the process of creating new, more informative features from existing data, handling categorical variables, scaling numerical features, and other data transformations. This step is critical for building robust models for the simulation's challenges, specifically for improving churn prediction accuracy.

* **Key Activities:** Feature creation, encoding categorical variables, data scaling/normalization, and potentially dimensionality reduction, all tailored to the specific customer data and the churn prediction problem of the BCG X simulation.

### 3. `Task_4_modeling_starter.ipynb` - Modeling

* **Objective:** To implement, train, and evaluate machine learning models to address the predictive or classification tasks presented in the BCG X Forage simulation.

* **Description:** This notebook covers the application of various machine learning algorithms, training them on the engineered data, evaluating their performance using relevant metrics (e.g., accuracy, precision, recall, F1-score, ROC AUC), and potentially fine-tuning hyperparameters to achieve optimal results for the simulation's objectives, with a focus on churn prediction.

* **Key Activities:** Model selection, data splitting (train/test), model training, prediction, and comprehensive performance evaluation, demonstrating practical application of ML in a business context for churn mitigation.


## Key Learnings & Skills Demonstrated

* **Strategic Problem-Solving**: Applied structured thinking to break down complex business problems (e.g., customer churn) and develop data-driven solutions.

* **Data Analysis & Interpretation**: Utilized Python and libraries (Pandas, NumPy) for data manipulation and extracted key insights from datasets to inform business decisions.

* **Feature Engineering**: Transformed raw data into effective features for machine learning models, enhancing predictive power.

* **Machine Learning**: Implemented and evaluated various models for predictive tasks, specifically focusing on classification for churn prediction.

* **Data Visualization**: Used Matplotlib and Seaborn to create insightful plots for understanding data and presenting findings effectively.

* **Jupyter Notebooks**: Documented and presented the entire data science workflow in a clear, reproducible format.

* **Consulting Mindset**: Gained exposure to applying analytical skills to real-world business challenges, mirroring a consulting environment and delivering actionable insights.

## Repository Structure
```
.
├── datasets/
│   ├── clean_data_after_eda.csv
│   ├── client_data.csv
│   ├── data_for_predictions.csv
│   └── price_data.csv
├── README.md
├── Task_2_EDA_.ipynb
├── Task_3_Feature_Engineering_.ipynb
└── Task_4_modeling_starter_.ipynb
```

## License
This project is for educational and portfolio purposes only, showcasing work completed as part of the BCG X Forage Job Simulation. No specific license is applied.
