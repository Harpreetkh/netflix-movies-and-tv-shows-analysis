# Project Netflix Content Analysis

**Project Netflix Content Analysis** is a comprehensive data analysis project focused on exploring the content available on Netflix from 2008 to 2021. Using a Kaggle dataset containing metadata on films and TV shows available on Netflix, this project investigates trends in content distribution by country, content types, release years, and other attributes. The analysis includes data extraction, transformation, exploratory data analysis (EDA), and visualisation to provide actionable insights about Netflix's content catalogue.


# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content  
The dataset is sourced from [Kaggle: Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) and contains detailed metadata on titles added to Netflix between **2008 and 2021**. The original release years of titles vary widely, often predating their Netflix addition.

Key columns include:  
- `show_id`: Unique identifier for each title  
- `type`: Content type (Film or TV Show)  
- `title`: Title of the work  
- `director`: Director(s)  
- `cast`: Leading actors  
- `country`: Country or countries of production  
- `date_added`: Date added to Netflix (2008–2021)  
- `release_year`: Original release year  
- `rating`: Viewer rating (e.g., PG, 15)  
- `duration`: Duration in minutes or number of seasons  
- `listed_in`: Genres or categories  

---
## Business Requirements  
1. Analyse the distribution of Netflix content by country and identify top producing countries.  
2. Compare the proportions of Films versus TV Shows on Netflix.  
3. Explore temporal trends in content additions and release years.  
4. Examine genre and rating distributions to understand audience targeting.  
5. Create impactful visualisations using Python and prepare for Power BI dashboard development.  

## Hypotheses and how they were tested

### Hypotheses and Findings

This project explored four ideas (hypotheses) about Netflix’s content, which were then tested and validated using the dataset.


### 1. Content Added Over Time  
**Idea:** The amount of new content added to Netflix changes over time, showing patterns by month and year.  
**Method:** The month and year each title was added were identified, and the number of titles added each month and year was counted. Charts were then created to highlight trends such as seasonal peaks or steady growth over time.

### 2. Growth of Movies vs TV Programmes  
**Idea:** Movies and TV programmes have been added to Netflix at different rates over the years.  
**Method:** Content was divided into movies and TV shows, with yearly counts for each category. These were compared using line charts to visualise differences in growth rates.

### 3. Countries Adding the Most Content  
**Idea:** Some countries contribute much more to Netflix’s library than others.  
**Method:** The number of titles from each country was counted and visualised with bar charts and maps to show the countries with the largest contributions.

### 4. Most Popular Genres on Netflix  
**Idea:** Some genres are much more common in Netflix’s catalogue than others.  
**Method:** Titles were grouped by genre, and the number in each category was counted. A bar chart was used to highlight the most frequently occurring genres.

## Project Plan
*(To be updated once Power BI visualisation work is complete)*

## Analysis technique used
The following techniques were applied to explore and understand the Netflix dataset:
- **Data Cleaning** – Handled missing values in key columns such as *director*, *cast*, and *country* to ensure the dataset was complete and ready for analysis.
- **Data Transformation** – Converted date information into separate *year* and *month* fields to make time-based trends easier to analyse.
- **Exploratory Data Analysis (EDA)** – Used visualisation tools to identify patterns, trends, and anomalies in the data.
- **Trend Analysis** – Examined how Netflix content additions have changed over time, both monthly and yearly.
- **Comparative Analysis** – Compared growth patterns between *Movies* and *TV Shows*.
- **Geographical Analysis** – Identified the top countries contributing content to Netflix.
- **Genre Analysis** – Determined the most common genres in Netflix’s catalogue.
- **Interactive Visualisation** – Used Plotly to create dynamic charts for deeper exploration of trends.

## Ethical considerations
- **Public and Anonymous Data** – The dataset is publicly available on Kaggle and does not contain any personally identifiable information (PII) about Netflix users or employees. It only includes publicly visible metadata such as title name, release year, country, genre, and date added.
- **Copyright Awareness** – While the dataset lists copyrighted works (Netflix titles), it does not share the actual content. Any use of this data is intended solely for educational and research purposes.
- **Data Accuracy and Bias** – The dataset may not represent all Netflix content globally. Certain countries, genres, or time periods may be underrepresented due to collection limitations, which could introduce bias in the findings.
- **Responsible Interpretation** – Insights from this analysis are based only on the provided dataset. No assumptions are made about Netflix’s internal business decisions, viewership behaviour, or user demographics.

## Dashboard design

## Tools and Libraries
- Python (Pandas, Matplotlib, Seaborn, Plotly)
- Jupyter Notebook
- Power BI *(to be added)*

## Credits
- Dataset: [Netflix Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows/data)
- Analysis guided by Code Institute learning materials

## Acknowledgements
Thanks to those who supported me during this project.