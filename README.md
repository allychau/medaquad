# MeDaQuad

The COVID-19 pandemic isn’t affecting all communities the same way.  Social inequities have put many people from racial and ethnic minority groups at risk of getting and dying from the disease.   In this report analysis, we want to show the differential impact of COVID-19 on race and ethnicity. We will be concentrating on 6 of the largest racial/ethnic groups: White, Black, Latin/Hispanic, Asian, Native American, Asian Pacific Island.

What is in the Directory Ethnicity_Race_US?

Directory Jupyter Notebooks for cleanup data file and  Analysis:
medaquad/Ethnicity_Race_US/code/ covid_ethnicity_clean.ipynb
medaquad/Ethnicity_Race_US/code/ ethnicity_race.ipynb

Directory for csv files used in Jupyter Notebook for analysis: 
medaquad/Ethnicity_Race_US/data

csv files used for analysis:
covid_race_data_tracker.csv
race_data_tracker.csv

Graphs generated from analysis report:
medaquad/Ethnicity_Race_US/Images

Files in Images:
EthnicityCase_bar.png
EthnicityDeath_bar.png
CasesVsRaceEthnicity_pie.png
CasesDeaths_bar.png
EthnicityTop3StateCase_line.png


Data Cleanup Process:
The file ‘covid_race_data_tracker.csv’ was opened in Excel and a few value cells was reformatted.  The cells had a discrepancy with the number value being formatted with separator(,). The cell was unchecked ‘use separator(,) ‘ for that particular cell.  The csv file was saved  and loaded up into a dataframe for more processing and cleanup in Jupyter Notebook file ‘covid_ethnicity_clean.ipynb.’  The  ‘NaN’ values were replaced with the number ‘0’.  The column number values type was coverted from string to Int.  The csv file was saved to ‘race_data_tracker.csv’ for Jupyter Notebook file ‘ethnicity_race.ipynb’ for analysis reporting

Data Source Link:
https://covidtracking.com/race/about#download-the-data



