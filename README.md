# US Accidents Exploratory Data Analysis (EDA)

## Overview
This project performs an **Exploratory Data Analysis (EDA)** on the US Accidents dataset, covering multiple years. The dataset includes details about accidents across the United States, collected through various sources such as traffic sensors, law enforcement reports, and weather conditions.

## Objectives
- Understand the distribution and frequency of accidents.
- Analyze accident trends based on time (year, month, day, hour).
- Study the impact of weather conditions on accident severity.
- Identify accident-prone locations and hotspots.
- Visualize patterns using different data visualization techniques.

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
- Most accidents occur during peak traffic hours (morning and evening rush hours).
- Weather conditions, such as low visibility and heavy precipitation, significantly impact accident frequency.
- Certain cities and states report higher accident occurrences due to road infrastructure and traffic density.
- Accidents are more frequent on weekdays compared to weekends.
- **Weekend vs. Weekdays Contrast**: Accidents on weekends tend to occur more frequently in the afternoon, whereas weekday accidents peak during rush hours (morning and evening). This suggests that work-related travel is a major factor in weekday accidents, while weekend accidents may be influenced by leisure activities and different driving patterns.

## Observations
- Areas lacking key road features such as bumps, crossings, give-ways, and traffic signals show higher accident rates.
- High accident frequencies are reported in major cities like Los Angeles and states such as California and Texas.
- The lack of traffic control measures contributes to a higher number of incidents in these regions.
- Most accidents occur during working days, particularly in the morning and evening rush hours, indicating that traffic congestion is a major factor.
- There is a rising trend in accidents over the years, suggesting that existing safety measures may not be sufficient or properly enforced.
- Improving road infrastructure and implementing better safety regulations could significantly reduce accidents.

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
