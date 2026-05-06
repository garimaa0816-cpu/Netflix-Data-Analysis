~ Netflix Data Analysis using Pandas & Matplotlib
* Project Description

This project focuses on performing Exploratory Data Analysis (EDA) on the Netflix dataset to understand the structure, distribution, and trends of content available on Netflix. Using Python, along with powerful libraries like Pandas and Matplotlib, the dataset is cleaned, processed, and visualized to extract meaningful insights.

The project mainly analyzes differences between Movies and TV Shows, their growth over time, content ratings, duration patterns, and country-wise production.

* Tools & Libraries Used
Python – Programming language used for analysis
Pandas – For data loading, cleaning, and manipulation
Matplotlib – For creating visualizations and plots
Jupyter Notebook – For running and documenting the analysis

* Dataset Information
Dataset used: netflix_titles.csv
The dataset contains the following features:
Title of the content
Type (Movie / TV Show)
Director & Cast
Country
Release Year
Rating
Duration
Genre (Listed In)

* Data Cleaning & Preprocessing

Before visualization, several preprocessing steps were performed:

Removed or handled missing values
Filtered dataset based on content type (Movies / TV Shows)
Extracted numerical values from the duration column
Converted data into suitable formats for analysis
Grouped and aggregated data where required
*Analysis Performed
1. Content Rating Distribution
Analyzed how Netflix content is distributed across different rating categories
Used a pie chart to represent percentage share of each rating
Helped in understanding which type of audience Netflix targets most
2. Movie Duration Analysis
Focused only on Movies
Converted duration into numeric format (minutes)
Plotted a histogram to observe distribution of movie lengths
Identified common duration ranges for movies
3. Release Year Analysis
Studied how Netflix content has grown over the years
Used a scatter plot to visualize release trends
Showed the increase in content production over time
4. Top 10 Countries Analysis
Identified top 10 countries contributing the most content
Used a bar chart for visualization
Highlighted which countries dominate Netflix production
5.  Movies vs TV Shows Comparison
Compared number of Movies and TV Shows released over time
Used subplots for side-by-side comparison
Helped in understanding content strategy differences

* Key Outcomes / Insights
Netflix content is dominated by certain rating categories
Most movies fall within a specific duration range
Content production has increased significantly in recent years
A small number of countries produce the majority of content
Clear difference in growth patterns between Movies and TV Shows
* Project Workflow
Import dataset using Pandas
Clean and preprocess data
Perform analysis using grouping and filtering
Create visualizations using Matplotlib
Interpret insights from graphs
**Conclusion

This project demonstrates how raw data can be transformed into meaningful insights using data analysis and visualization techniques. It provides a better understanding of Netflix’s content distribution, trends, and patterns.

