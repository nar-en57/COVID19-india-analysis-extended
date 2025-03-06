# Extended COVID-19 India Analysis

This repository contains an extended analysis of COVID-19 data in India, using the "Coronavirus dataset" from Kaggle, with added conclusions.

## Dataset

* Source: [Coronavirus dataset](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset)
* File: `covid_19_data.csv`

## Project Description

This project performs the following analysis of COVID-19 data in India:

* Visualizes confirmed cases over time.
* Identifies the top 10 provinces/states with the highest confirmed cases.
* Analyzes the progression of cases in a specific province/state (e.g., Maharashtra).
* Creates a scatter plot of deaths vs. confirmed cases.
* Shows the overall progression of confirmed, death and recovered cases in India.
* Provides a conclusion summarizing key findings and suggesting further analysis.

## Libraries Used

* Pandas
* Matplotlib
* Seaborn

## How to Run

1.  Download the `covid_19_data.csv` file from Kaggle and place it in the project directory.
2.  Run the `coronavirus_analysis_extended.py` (or `coronavirus_analysis_extended.ipynb`) script.

## Visualizations

![image](https://github.com/user-attachments/assets/170ef0b0-8c65-4546-81cc-21e6319ce888)
![image](https://github.com/user-attachments/assets/15ead905-b570-4492-b800-bc80db6a265a)
![image](https://github.com/user-attachments/assets/975f603b-aee0-4fab-8c9d-a2be5f7725a4)
![image](https://github.com/user-attachments/assets/6ad45643-8714-4ad6-9a7f-fcc5ecf09f7f)
![image](https://github.com/user-attachments/assets/e7efdfc6-42b0-4940-9dea-dbaa63b9bab1)


## Conclusion

This analysis provided a historical overview of the early stages of the COVID-19 pandemic in India, utilizing the "Coronavirus dataset" from Kaggle.

The analysis revealed a clear upward trend in confirmed COVID-19 cases in India, with distinct peaks indicating multiple waves of infection. Maharashtra consistently reported the highest number of confirmed cases, showcasing the impact on densely populated urban centers. The scatter plot of deaths vs. confirmed cases illustrated a positive correlation, suggesting a link between the number of cases and mortality rates.

The analysis underscored the significant regional disparities in COVID-19 impact, with states like Maharashtra and Kerala experiencing higher case loads compared to other regions.

It's important to note that this analysis is based on early data, and the actual impact of COVID-19 in India evolved significantly over time.

This analysis provides a valuable historical perspective on the early stages of the COVID-19 pandemic in India, highlighting the need for continued vigilance and data-driven decision-making.

## Further Analysis

You can extend this analysis by:

* Comparing the impact of COVID-19 across different states in India.
* Performing time series forecasting for specific states.
* Analyzing the effectiveness of state-level interventions.
* Creating maps of the spread of the virus inside of India.
* Adding daily change graphs.
* Adding recovery rate calculations.
