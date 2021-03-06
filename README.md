# Data_Analytics_using_Python


LSE_DA_201 Main Assignment COVID-19 data anlysis.


3 files: 'Cases', 'Vaccinated' & 'Tweets'.


'Cases' is a time series recording COVID-19 Deaths, Cases, Recoveries and Hospitalisation in each region of the UK between Jan 2020 & Oct 2021. It contains additional geographical information relating indentifying the region. Each record relates to a day's observation although the primary key is the record number and not the day to which the obersavations relates to. Indexation changed to date to create time series.


'Vaccinated' contains a time series recording total COVID-19 vacinnations in each region of the UK between January 2020 and Oct 2021. The data records the number of first, second and total doses adminstered for each day in each region. Indexation changed to date to create time series & merge the dataset with 'Cases'.


'Tweets' contains Twitter data between 15 May 2020 and 23 May 2020. It looks like these are tweets which contain  trending handles about COVID-19 during this period.


**Did you notice anything interesting about the data?** The data sets whst purpoting to be real world are unlikely to be. Perhaps in the interest of masking the data, the relative scales of the data sets versus actual population in each of the real world locations are vastly out of sync. This is very off putting & prevented the generation of some additional potentially powerful insights using actual population data. However, for the academic purposes of this exercise, the data being mis-scaled didnt impede the display of the analytical techniques which we were taught to deploy. Tweets dataset was simply too small to carry meaningful analysis.


**What are some of the initial insights you've discovered?** No major insights so far from Twitter data asides that COVID-19 is highly trending nearly  yrs after the onset of the pandemic. Dataset is too small esp for string data such as this. Was useful to craft comment on timeliness of launching a marketing campaign. Cases & Vaccination datasets were merged and were the basis for the analytical content. 


All my observations arising from the data analysis are noted in the Jupyter noteblock underneath the corresponding code block.


The overall conclusions + methodology, background & problem statement are outlined in the written report in PDF.


The Jupyter notebook with all the codes, rationale, functions & visualisations is the final output of all the weekly assignments and saved as ipnyb file. All major visualisations within the notebook have been exported and saved as png files.


A short video recording presenting the key insights, trends, patterns & recommendations; compressed and saved as mp4.


