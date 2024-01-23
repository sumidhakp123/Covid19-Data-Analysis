# Covid19-Data-Analysis
Data Extraction from JSON, Data Cleaning, and In-Depth Analysis: A COVID-19 Project
Introduction
COVID-19, caused by the SARS-CoV-2 virus, has been a global respiratory pandemic since 2019. It can lead to mild or severe symptoms, impacting every aspect of our lives. To mitigate its spread, preventive measures like vaccination, mask usage, and social distancing are crucial. Research and cooperation are essential in its management.

Problem Aimed to Solve
This project's objective is to conduct an analysis of the COVID-19 pandemic using publicly accessible data. It encompasses a Jupyter notebook containing Python code for the extraction, cleansing, and visualization of COVID-19 data from diverse sources. Moreover, the project offers an interactive dashboard for exploring this data.

# 📈COVID-19_ANALYSIS - 📑Brief Summary
Used Pandas and Json to gather data from API and then data cleaning.

For K.P.I.’s and insights Used SQL to get useful data sets.

Then transferred datasets to Excel for visualization.

For the presentation used M.S. PowerPoint with the help of team members.

# 🪨Challenges and 🧠learnings-
*JSON Data Extraction*: Skillfully navigated nested JSON structures to extract pertinent COVID-19 information.

*Data Cleaning*: Addressed missing values and discrepancies in COVID-19 data to ensure precise analysis.

*Code Optimization*: Enhanced processing efficiency for extensive COVID-19 datasets, improving overall performance.

*Domain Understanding*: Developed insights into public health and epidemiology by analyzing COVID-19 data.

#  Methodology
1. Import the data from API using the requests library.
2. The imported data was in JSON format hence we used JSON library to read the data.
3. 3. We looked for null values and replaced them with zero, looking for duplicates.
4. Stated analyzing the data by using pandas functions like group by, sort_values, etc.
5. Used nested 'for' loops to extract the relevant data from the nested dictionary.
6. 6. Extracted the individual state data from the data frame in CSV format and imported data into MySQL.
7. Aggregated the distribution by month and week wise for each state.
8. Imported the aggregated data into Excel for further Analysis.
 # Conclusions
Focusing on the weekly progression of COVID-19 cases, recoveries, deaths, and tests, the study offers valuable insights into the pandemic's impact across various regions and timeframes.
Observations revealed fluctuations in the number of cases and deaths, emphasizing the dynamic nature of the pandemic's effects in different geographical areas.
Through effective data visualization employing charts and graphs, this work enhances data clarity, facilitating the interpretation of trends and patterns.
The findings have practical importance for public health authorities, equipping them with the means to formulate more targeted and efficient strategies for curbing the virus's spread.
