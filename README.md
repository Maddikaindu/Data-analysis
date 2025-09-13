📊 Netflix Data Analysis Project

📌 Introduction

This project explores the Netflix dataset to analyze the distribution of Movies and TV Shows, country trends, director contributions, rating patterns, and movie durations. 
Analysis focuses on data cleaning, descriptive statistics, and visualization using Pandas and Matplotlib.

🧹 Data Cleaning Steps

Converted date_added column to datetime format.

Handled missing values in cast and country columns.

Extracted and converted numeric durations for movies.

Cleaned rating column to standardize categories.

Filtered content from the last five years for focused analysis.

# Key Analyses Performed

1. Movies vs TV Shows

Counted total Movies and TV Shows.

Visualized with a bar chart.

📌 Insight: Movies dominate Netflix’s library, but TV Shows have grown steadily.


2. Top 10 Countries

Used element-wise splitting on the country column with apply.

Counted occurrences and plotted a bar chart.

📌 Insight: The US contributes the most content, followed by India and the UK.



3. Titles Added in the Last 5 Years

Filtered data based on date_added.

Counted yearly additions.

📌 Insight: Recent years show a spike in content additions, reflecting Netflix’s expansion.


4. Average Movie Duration

Extracted numeric values from duration column.

Calculated mean duration (~99 minutes).

📌 Insight: Most Netflix movies are standard feature-length films.


5. Histogram of Movie Durations

Plotted a histogram to show distribution.

📌 Insight: Most movies fall between 80–120 minutes, with a peak around 90–100 minutes.



6. Release Year Trends

Counted titles by release year.

Visualized with a line plot.

📌 Insight: Netflix content releases accelerated after 2010, peaking around 2018–2020.



7. Top 10 Directors (Excluding Unknown)

Removed “Unknown” values.

Counted contributions and plotted a horizontal bar chart.

📌 Insight: A handful of directors contribute significantly, but overall direction is diverse.



8. Ratings Distribution

Cleaned rating categories.

Plotted distribution using a horizontal bar chart.

📌 Insight: Most content is targeted at teen and adult audiences (TV-MA, TV-14).


📈 Visualizations

📊 Bar Chart → Movies vs TV Shows

📊 Bar Chart → Top 10 Countries

📉 Line Chart → Release Year Trends

📊 Horizontal Bar Chart → Top 10 Directors

📊 Horizontal Bar Chart → Ratings Distribution

📊 Histogram → Movie Durations


# Conclusion

This analysis shows that:

Netflix has a balanced mix of Movies and TV Shows, with recent growth in TV Shows.

The US, India, and UK dominate content production.

Average movie duration is ~99 minutes, aligning with feature-length standards.

Content additions peaked in the last 5 years, highlighting Netflix’s expansion.

Ratings indicate a focus on teen and adult audiences.


🛠 Tools Used

Pandas → Data cleaning and analysis

Matplotlib → Visualizations

Jupyter Notebook → Interactive environment for analysis
