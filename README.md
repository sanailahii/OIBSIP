# OIBSIP
**Data Overview:**

Two datasets were provided for this analysis:
1. "Unemployment in India.csv": Contains region-wise unemployment data with corresponding dates.
2. "Unemployment_Rate_upto_11_2020.csv": Contains similar unemployment data, focusing on a different or overlapping time frame.

These datasets were combined, and redundant records were removed to create a comprehensive dataset that spans from 2019 to October 2020.

**Data Cleaning and Preparation:**
1. The datasets were inspected to ensure consistency in column names, formats, and data types.
2. The 'Date' column in both datasets was converted to a uniform datetime format.
3. The data was then concatenated into a single dataset, and duplicates were removed based on the Region and Date columns to maintain unique records.
4. The dataset was then split into two periods: pre-COVID-19 (before March 2020) and post-COVID-19 (from March 2020 onwards).

**Analysis Methodology:**

**1. Monthly Aggregation:**

a. The data was resampled to calculate the mean unemployment rate for each month.

b. The average monthly unemployment rates for both pre-COVID and post-COVID periods were computed to assess the impact of the pandemic.

**2. Visualization:**

a. The analysis was visualized using bar graphs, showing the unemployment rates on a monthly basis for both periods.

b. The graphs highlight the trend in unemployment rates over time, with a vertical red line marking the onset of COVID-19 (March 2020).

**Key Findings:**

**1. Pre-COVID-19 Period:**
The average unemployment rate before March 2020 exhibited some fluctuations but remained relatively stable.

**2. Post-COVID-19 Period:**

a. Following the outbreak of COVID-19, there was a noticeable spike in the unemployment rate, reflecting the adverse effects of the pandemic on employment in India.

b. The unemployment rate showed variability during the post-COVID period, likely due to lockdown measures, economic slowdowns, and gradual recovery efforts.

**3. Comparative Analysis:**

A comparison of the average unemployment rates before and after COVID-19 reveals a significant increase in unemployment during the post-pandemic period, highlighting the pandemic's severe impact on the labor market.

Here's the link to Google Colab which includes all the code and graph:

https://colab.research.google.com/drive/1XAutI-5vwYDrlCyyo8HqVlQByZudSIDr#scrollTo=qLwMt6A2jqq9

**Outcome:**

The analysis clearly demonstrates the economic disruption caused by COVID-19, as evidenced by the sharp rise in unemployment rates post-March 2020. This trend underscores the need for targeted economic policies and interventions to support the recovery of the labor market in India. The visualization of unemployment trends provides a clear picture of the challenges faced during the pandemic and can serve as a basis for future policy-making and economic forecasting.
