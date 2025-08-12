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
This project followed a structured approach to analyse Netflix’s content data:

1. **Data Collection:** Downloaded the Netflix dataset from Kaggle.  
2. **Data Cleaning:** Removed missing values, split multiple genres into individual entries, and formatted dates.  
3. **Exploratory Data Analysis:** Investigated trends over time, compared movies vs TV shows, identified top countries and genres.  
4. **Hypothesis Testing:** Tested assumptions about content growth, popular genres, and country contributions.  
5. **Data Visualisation:** Created interactive visualisations using Python libraries (Seaborn, Plotly) and Power BI for an engaging dashboard.  
6. **Summary and Insights:** Highlighted key findings and trends from the data.  
7. **Documentation:** Developed this README and Jupyter Notebook to explain methods and results clearly.

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
The dashboard is designed to be clear, interactive, and visually aligned with Netflix’s brand. It uses Netflix’s signature black and red colour scheme with gradients for an engaging background. Visualisations are arranged to guide the user through the data story logically:
- Trend lines at the top showing content added over time.  
- Side-by-side comparison of movies and TV shows growth.  
- Interactive bar charts highlighting top countries and popular genres.  
- Filters and slicers for months, years, countries, and genres to let users explore specific views.  
- A summary insights section at the bottom to highlight key takeaways.

## Note on Power BI Dashboard Access

Due to limitations with the free version of Power BI, it was not possible to directly link or embed the live Power BI dashboard in this README file or the project repository.
However, the completed Power BI file has been saved and included in the project’s **`data`** folder within the Jupyter Notebook environment. You can open and explore the dashboard locally using Power BI Desktop.
If you have any questions or need assistance accessing the dashboard, please feel free to get in touch.
This structure ensures the dashboard is accessible for both data enthusiasts and casual viewers.

## Tools and Libraries
- Python (Pandas, Matplotlib, Seaborn, Plotly)
- Jupyter Notebook
- Power BI

## Insights from Hypotheses

### 1. Content Added Over Time  
**Insight:**  
The analysis showed that Netflix content uploads vary throughout the year. February consistently has the fewest new titles added, while July and December see the highest numbers, likely influenced by holidays such as Christmas. Over the years, there is a general upward trend in content added, reflecting Netflix’s expanding library.

### 2. Growth of Movies vs TV Programmes  
**Insight:**  
Movies have consistently been added in greater numbers than TV programmes. Between 2016 and 2019, movie additions grew significantly before declining slightly after 2019. TV shows followed a similar trend but with smaller volumes overall. The decline after 2019 could relate to shifts in content strategy or external factors like the pandemic affecting production.

### 3. Countries Adding the Most Content  
**Insight:**  
The United States leads by a large margin in contributing content to Netflix, followed by India, which adds roughly half as much. Other countries have smaller but still meaningful contributions. This highlights Netflix’s focus on major content producers and growing investments in diverse regions.

### 4. Most Popular Genres on Netflix  
**Insight:**  
Certain genres dominate Netflix’s library. Drama and Comedy are the most common, followed by Documentaries and Action. This suggests Netflix prioritises genres with broad appeal to attract a wide audience.

## Reflections
This project provided valuable hands-on experience in data cleaning, analysis, and visualisation using Python and Power BI. Throughout the process, several challenges were encountered that helped deepen understanding and problem-solving skills.
- One major difficulty was working with the genre data, where many entries contained multiple genres in a single cell. Splitting this data to analyse each genre separately caused a dramatic increase in rows, which required finding ways to limit the data size to improve performance—such as filtering to the first 5,000 rows. Balancing data completeness with usability was a key learning point.
- Handling missing or inconsistent dates in the dataset also took considerable effort, especially when extracting month and year information for trend analyses. Ensuring the data was clean and consistent was essential for accurate visualisations.
- Using Power BI was a new experience, and there was a steep learning curve, particularly with interactive features like slicers and filters. For example, it was initially unclear how to add slicers that allowed users to filter by ranges or select multiple categories easily. - Figuring out how to customise the dashboard’s appearance to match Netflix’s brand colours, including creating gradient backgrounds, was also a trial-and-error process.
- Another challenge was designing an intuitive layout that balanced multiple charts without overwhelming the viewer. Deciding what to include, how to label axes clearly, and how to title charts so they communicate key messages effectively took several iterations.
- Despite these challenges, the project enhanced skills in data preparation, visual storytelling, and interactive dashboard design. It highlighted the importance of patience and persistence when working with real-world messy data and unfamiliar tools, and provided confidence in delivering insights for both technical and non-technical audiences.

## Credits
- Dataset: [Netflix Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows/data)
- Analysis guided by Code Institute learning materials
- ChatGPT was used as an interactive assistant to help clarify concepts, provide explanations, write and format text, and guide through complex tasks like data analysis and Power BI steps.
- GitHub Copilot assisted in writing and optimizing Python code, suggesting improvements, and speeding up the coding process.

These AI tools helped streamline the workflow and provided valuable insights throughout the project.

## Acknowledgements
Thanks to:
- Code Institute for the project structure
- Kaggle for providing the dataset
- OPENAI for ChatGPT
- GitHub Copilot for coding support
- Code Institute peers for being supportive along the way