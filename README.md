# Rail Delays Analysis 

## Task Summary

Perform exploratory data analysis to understand patterns and trends influencing rail delays in the context of transporting products from multiple mine sites to local and international customers via rail.

## Question

Are there identifiable patterns or factors influencing rail delays that can enhance rail planning accuracy and enable predictions of potential rail service deviations?

## Background

The dataset comprises rail planning and execution data from multiple mine sites, encompassing transportation of products to local and international customers. Rail capacity and service levels occasionally face negative impacts, necessitating accurate comprehension of rail delays. Delays are often associated with rail entities and occasionally influenced by ore production speeds, as well as external factors like weather and seasonal events.

## Data

Two datasets exist for rail planning and execution data:

1. **Historical Database (2009 - 2020):** Contains 42,000+ entries of planned and/or actual trains. 
2. **Active Database (2010 - Present):** Encompasses 32,000+ individual records of planned and actual train movements.

Both datasets are structured and relatively clean, although some records may require validation or correction. They provide details about loading sites, dispatched products, train schedules, and cancellations.

Additional data, such as load sharing information and publicly available weather data, can be incorporated to support the analysis.

## Objective

The primary objective is to enhance rail planning accuracy and predict potential rail service deviations. The analysis aims to identify patterns and influencing factors within the rail planning and execution datasets. Complex patterns involving multiple features contributing to delay likelihood are of particular interest. The goal is to evaluate the feasibility of building a predictive model capable of forecasting delays over a rolling three-week period, up to three months in advance. This advanced timeframe allows for effective delay mitigation strategies.

## Approach

1. **Data Preprocessing:** Clean and validate the datasets, addressing any inconsistencies or errors.
2. **Exploratory Data Analysis (EDA) & Data Visualization:** Explore the datasets to uncover initial insights and trends related to rail delays and influencing factors.
3. **Feature Engineering:** Extract relevant features from the data, including those that could interact to impact delay likelihood.

## Results

The anticipated outcomes of this analysis include:
- Identification of key patterns and factors influencing rail delays.
- Insights into complex interactions between features that contribute to delay likelihood.
- Evaluation of the feasibility of building predictive models for delay forecasting.
- Recommendations for improving rail planning accuracy and implementing effective delay mitigation strategies.

## Conclusion

By thoroughly exploring the rail planning and execution datasets and incorporating relevant external data, this analysis aims to contribute to the enhancement of rail planning accuracy and the prediction of potential rail service deviations. The identified patterns and factors will empower stakeholders to make informed decisions and implement proactive measures to minimize delays and improve overall rail service.

_For more information, refer to the full [project repository](https://github.com/shro-2002/Rail-Riddle)._
