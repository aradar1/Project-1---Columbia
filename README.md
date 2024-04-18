DELAYS & CANCELLATIONS: UNDERSTANDING THE PANDEMIC'S INFLUENCE ON AIR TRAVEL PROJECT 1 | GROUP 2

GitHub Repository & Branches https://github.com/aradar1/Project-1---Columbia

Arzoo Fatima - ArzooF Cruzald Boholst - cruz_branch Derrick Smith - D3Smee Justin Lent - JLent_branch Genesis Ruiz - gjruiz_branch

SUMMARY Our project centered around flight cancellations and delays spanning from 2019 to 2023. Utilizing a dataset obtained from Kaggle, we preprocessed and cleansed the data to focus solely on delays and cancellations, ensuring relevance in our analyses. We also correlated the flight data with Covid-19 statistics from an external API tracking case numbers. We organized our analysis by addressing the top 5 airlines, states, and cities, as well as investigating daily, monthly, and yearly cancellation trends. This allowed us to generate visualizations that revealed trends.

HYPOTHESIS There is a significant increase in the frequency of flight delays and cancellations during the pandemic compared to periods without a pandemic.

CONCLUSION The analysis revealed no significant correlation between cancellations and the number of COVID-19 cases during this period, leading to the conclusion that these variables are not closely related.

DATA FETCHING Primary Dataset: Obtained from Kaggle, the "Flight Delay and Cancellation Dataset (2019-2023)" sourced from the Bureau of Transportation Statistics. Covers January 2019 to August 2023, providing essential variables like origin, destination, cancellation, and delays.

Supplementary Data - COVID API: Utilized the COVID Tracking Project's API for state-specific COVID-19 data, enhancing analysis by examining pandemic impacts on flight schedules.

DATA CLEANING Data Preparation: We employed data slicing techniques to handle the dataset's size, facilitating efficient analysis of flight operation patterns. We also included cancellations in the delay count schedules, recognizing that although not all delays lead to cancellations, from a data standpoint, all cancellations are categorized as delays.

KEY TERMS AIRLINE Airline name ARR_DELAY Difference in minutes between scheduled and actual arrival time. (Early arrivals show negative numbers.) CANCELLED Cancelled Flight Indicator (1=Yes) DEP_DELAY Difference in minutes between scheduled and actual departure time. (Early departures show negative numbers.) DEST_CITY City of destination for the flight FL_DATE Flight date (yyyymmdd) ORIGIN_CITY Origin Airport, City Name  ORIGIN_STATE Origin Airport, state abbreviation

NEXT STEPS Given the unexpected finding, we rejected our initial hypotheses. While fewer flights logically lead to fewer opportunities for delays and cancellations, we learned through our analysis that a deeper familiarity with the dataset enables us to ask more insightful and targeted research questions.

Our next step would be:

Propose better questions for exploration
Revise our hypothesis based on alternative explanations that aligned with the data.
Investigate the number of flights during the COVID-19 period
While we've already examined delays and cancellations collectively, it would be intriguing to pinpoint the timeframe when most cancellations occurred.
