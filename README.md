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

## Hypotheses and How I Tested Them

### Hypothesis 1: Content Added Over Time  
*I believed the amount of new content added to Netflix changes over time, showing clear patterns by month and year.*  

**How I checked this:**  
I looked at the dates when shows and movies were added, counted how many were added each month and year, then created line charts to spot trends — like seasonal peaks or steady growth over the years.

---

### Hypothesis 2: Growth of Movies Compared to TV Shows  
*I thought movies and TV shows have been added to Netflix at different rates over the years.*  

**How I checked this:**  
I separated the content into movies and TV shows, counted how many of each were added each year, and then compared their growth using line graphs. This helped me see which type grew faster.

---

### Hypothesis 3: Countries Contributing Most Content  
*I expected that certain countries produce much more content on Netflix than others.*  

**How I checked this:**  
I counted how many shows and movies come from each country, then created interactive charts and maps to highlight the top contributing countries.

---

### Hypothesis 4: Most Popular Genres on Netflix  
*I believed some genres are much more common in the Netflix library than others.*  

**How I checked this:**  
I grouped shows and movies by genre, counted how many titles belong to each genre, and visualised the most popular genres with bar charts to see which ones dominate.

## Project Plan
*(To be updated once Power BI visualisation work is complete)*

## Tools and Libraries
- Python (Pandas, Matplotlib, Seaborn, Plotly)
- Jupyter Notebook
- Power BI *(to be added)*

## Credits
- Dataset: [Netflix Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows/data)
- Analysis guided by Code Institute learning materials

## Acknowledgements
Thanks to those who supported me during this project.