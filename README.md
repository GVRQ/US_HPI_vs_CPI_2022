# U.S. Home Prices vs. Consumer Price Index in 2022.

The goal of this project is to provide an overview of U.S. Home Prices vs. Consumer Price Index in 2022.

## 1. Business Problem

Housing prices across the country grow and decline at different rates during 2022. As a means of comparison, the S&P Case Shiller U.S. National Home Price Index (HPI) data is combined and graphed with the United States Consumer Price Index (CPI) data. 2022-Q3 & 2022-Q4 values are missing and need to be predicted to provide a complete overview of the U.S. Home Prices vs. Consumer Price Index in 2022.

## 2. Business Assumptions

Will the CPI fall behind the growth or change in HPI during 2022?

## 3. Solution Strategy

My solution is to develop a data science project with machine learning forecasting of the Q3 & Q4 data to compare and analyze CPI & HPI performances during the entire year 2022.

Step 01. Data Description: In this first section the data will be collected and studied. An initial data description will be carried out to know the data. Therefore some calculations of descriptive statistics will be made.

Step 02. Data Prediction: In this section, Timeseries forecasting with machine learning models with linear regression algorithms will be created to assist the EDA. ML models will analyze 75 years of CPI data & 35 years of HPI data. Predictions for Q3 & Q4 2022 will be made.

Step 03. Data Analysis: In this section, we will analyze actual data and predicted data to discover unique insights and trends. The difference between Predicted HPI vs Actual HPI and Predicted CPI vs Actual CPI will be analyzed. Data visualization will provide an accessible way to see and understand trends, outliers, and patterns in data.

Step 04. Conclusion: This is a conclusion stage that provides insights needed to answer business questions and present the applicability of the EDA's results in the business context.

**Insights**:
## The CPI will continue to fall behind the growth of HPI during entire 2022.

Greater growth in home prices compared to the trend in consumer prices is proven by data analysis in this project.
That is, home prices grow faster than inflation.

Growing HPI trend will most probably continue until the end of the year 2022. That is proven by predicted data:
Predicted values for July 2022: HPI (309.06) vs CPI (292.25)
Predicted values for December 2022: HPI (323.56, 4.69% increase) vs CPI (299.16, 2.36% increase)

The Consumer Price Index has been linearly increasing since 1947.
CPI's peak months: February and October.
The Home Price Index has been linearly increasing since 1987.
HPI's peak months: March, April, May and December.

Q: Why is the HPI is skyrocketing? The low supply of houses for sale in 2022 > Investment purchases 2021-2022.
A: The number of houses for sale = (the number of houses put up for sale - the number of houses sold). Investors are buying the houses for many reasons, including the rise of short-term rentals and government incentives (tax breaks).
