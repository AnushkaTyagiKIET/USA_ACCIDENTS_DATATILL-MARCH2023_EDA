# US Accidents Exploratory Data Analysis (EDA)

## Overview
This project performs an **Exploratory Data Analysis (EDA)** on the US Accidents dataset, covering multiple years. The dataset includes details about accidents across the United States, collected through various sources such as traffic sensors, law enforcement reports, and weather conditions. The dataset contain approximately 7.7 Million accident Records. The data is collected from Feb 2016 to March 2023

## Data Preparation and Cleaning

1. Load the file using Pandas
2. Look at some information about the data & the columns
3. Fix any missing or incorrect values
4. the handling of missing values were done by replacing it with the mode value or the most frequent value 

## Objectives
- Understand the distribution and frequency of accidents.
- Analyze accident trends based on time (year, month, day, hour).
- Study the impact of weather conditions on accident severity.
- Identify accident-prone locations and hotspots.
- Visualize patterns using different data visualization techniques.
- Using Folium which is a Python library used for visualizing geospatial data

## Dataset
The dataset contains accident records from multiple states and includes:
- **Time-related features**: Year, month, day, hour
- **Location information**: Latitude, longitude, city, state
- **Weather conditions**: Temperature, precipitation, visibility, wind speed
- **Accident severity levels**

## Tools & Technologies Used
- **Python**: For data analysis and preprocessing
- **Pandas & NumPy**: Data handling and manipulation
- **Matplotlib & Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive analysis environment

## Key Findings
- Most accidents occur during peak traffic hours (morning and evening rush hours). Highest Number of Accidents were seen in morning at 7 am in morning and then in even at about 4 to 5 pm
- High accident frequencies are reported in major cities like Los Angeles and states such as California and Texas.
- Weather conditions, such as low visibility and heavy precipitation, significantly impact accident frequency. Highest accidents is in the winters probably due to snow and less visibility.
- with Montly percentage of case are December     10.964024, November      9.836002, January       9.729654
- Highest number of Accidents in Year of 2022( 22.804893%) and 2021(20.233867) and Highest Number of ACCIDENTS on Friday and Thursday
- Certain cities and states report higher accident occurrences due to road infrastructure and traffic density.
- Accidents are more frequent on weekdays compared to weekends.
- **Weekend vs. Weekdays Contrast**: Accidents on weekends tend to occur more frequently in the afternoon, whereas weekday accidents peak during rush hours (morning and evening). This suggests that work-related travel is a major factor in weekday accidents, while weekend accidents may be influenced by leisure activities and different driving patterns.
- Severity 2 (almsot 80%) - most cases fall under this category means most cases are moderate in nature.
- 17% cases fall under severity level 3 they are smaller percentage as comapred to severity 2 but still reflect a significant number of serious inciddents.
-  less than 1% cases fall under the severity -1 means very few cases are there that are very mild in nature.
- 65% of the cases are very critical in nature which are rare but still require significant attention and more insights can be found with further analysis
- The dataset maybe biased towards severity 2 but it is also possible that most cases fall under this category,and preventing such cases is possible with improving safety plans and infrastrcuture. Severity 1 maybe rare and may not be reported as often.
- US/Eastern has the most number of cases with alone more than 3.5 million.
  
## Observations
- Areas lacking key road features such as bumps, crossings, give-ways, and traffic signals show higher accident rates.
- High accident frequencies are reported in major cities like Los Angeles and states such as California and Texas.

## Final Observations

1. The plots of the data shows that many accidents happened in areas where important road features like bumps, crossings, give- ways, junctions, exits, traffic calming, and traffic signals were missing.

2. This could be a major reason for the high number of incidents, especially in cities like Los Angeles and states like California and Texas, which report a lot of accidents. 

3. The lack of these safety features, such as traffic signals and traffic calming, might be making the roads more dangerous. 

4. To reduce accidents, it’s important for authorities to improve road infrastructure by adding these missing elements. This could help lower the number of accidents and make the roads safer for everyone.

5. Most incidents happen on weekdays and during busy commute hours: A large number of accidents are occurring on working days, especially during peak hours when people are traveling to and from work. This suggests that heavy traffic and congestion during these times are likely contributing to the higher number of incidents. Improving traffic management and road safety during these rush hours could help reduce accidents.

6. The number of incidents is rising each year: We can see an increase in incidents over the years, which is concerning. This points to the fact that despite efforts to improve road safety, the core issues might not be getting addressed properly. This upward trend suggests that either infrastructure improvements are lacking, or existing measures aren’t being enforced effectively. As I pointed out eariler that infrastructure absence had higher number cases. We can now confidently say that this is the root issue.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/us-accidents-eda.git
   cd us-accidents-eda
   ```
2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

## Results & Visualizations
- Bar charts, line graphs, and heatmaps for accident distribution analysis.
- Scatter plots and geographical maps for accident-prone location identification.
- Correlation analysis between weather factors and accident severity.

## Future Work
- Develop an interactive dashboard for real-time accident monitoring.
- Explore deeper insights on accident prevention strategies.

## Contributing
Contributions are welcome! If you'd like to improve this analysis, feel free to fork the repository and submit a pull request.
