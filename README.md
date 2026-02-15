Netflix Data Analysis Dashboard 

The objective of this report is to understand how audience engagement with movies and TV shows has evolved from 1958 to 2022. The analysis aims to study changes in viewing preferences, content characteristics, and audience behavior over time, and to identify key trends that explain the growth of the entertainment industry as well as factors that may be limiting its further expansion.

Tech Stack-
•	Power BI (Data visualization & dashboard creation)
•	Power Query( Data cleaning and Transformation)
•	Kaggle (Dataset source)
•	File format- .pbix for develpment and .png for dashboard previews.

Dataset Description-
The analysis uses a Netflix dataset sourced from Kaggle. The dataset includes information related to movies and TV shows available on Netflix across multiple years. Key columns used in this analysis include:
•	Title
•	Type (Movie / TV Show)
•	Runtime / Duration
•	IMDb ID
•	IMDb Score
•	IMDb Votes
•	Age Certification
•	Release Year
•	Overall Popularity
The dataset spans content released between 1958 and 2022.

Methodology-
Data Collection
The dataset was collected from Kaggle and imported into Power BI for further analysis.
Data Understanding
The initial step involved understanding the structure of the dataset and identifying the key questions to be answered, such as audience engagement trends, content popularity, and changes in runtime over time.

Data Cleaning
•	Removed columns that were not relevant to the analysis
•	Handled missing and null values
•	Removed empty or invalid records to ensure data consistency

Feature Engineering
•	Additional calculated measures and transformations were created in the dataset to support better visualization and analysis, such as average metrics, counts, and aggregated popularity values.


Data Visualization
•	The cleaned and transformed data was visualized using various charts in Power BI, selected based on the type of insight required (trend, comparison, distribution, or relationship).

Dashboard Overview
The dashboard presents a consolidated view of Netflix content trends and audience behavior. It includes:
•	KPI cards showing total title count, average runtime, and average IMDb votes
•	Line charts showing trends in average runtime and IMDb votes by release year
•	Bar charts showing overall popularity by title and by age certification
•	Supporting visuals to analyze IMDb scores and voting behavior

 Key Insights:
1. Inception is the highest-rated movie and Breaking Bad the highest-rated TV show over the last 50 years.

2. In the last decade, Stranger Things and Django Unchained emerged as the most popular in their categories, reflecting strong audience preference for complex storytelling and high rewatch value.

3. A noticeable decline in movie releases after 2021 indicates a shift towards TV shows, highlighting the growing dominance of long-form content.

4. Average runtime has increased over time, especially for TV shows, showing that audiences are more engaged with extended narratives.

5. PG-13 movies and TV-MA shows have the highest popularity, balancing wide reach with narrative depth.


Screenshot- ()


