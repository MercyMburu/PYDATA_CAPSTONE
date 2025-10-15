# YouTube Global Statistics Analysis
## Project Overview

This project analyzes a Global YouTube Statistics dataset to uncover trends and insights about YouTube channels across different countries and categories.
The analysis focuses on exploring channel performance metrics such as subscriber counts, total views, ranks, and category distributions, aiming to understand what drives visibility and popularity on YouTube.

## Objectives

Clean and prepare the YouTube dataset for analysis.

Explore and visualize patterns in YouTube channel performance.

Identify top-performing categories, countries, and channels.

Understand the relationship between metrics such as views, subscribers, and rankings.

## Tools & Libraries Used

The analysis was performed using Python in a Jupyter Notebook environment.
Key libraries include:

pandas → Data manipulation and cleaning

numpy → Numerical computation

matplotlib → Data visualization

seaborn → Advanced visual analytics

## Data Cleaning Steps

Loaded the dataset using pandas (encoding='windows-1254' due to special characters).

Dropped irrelevant columns such as:
'Gross tertiary education enrollment (%)', 'Population', 
'Unemployment rate', 'Urban_population', 'Latitude', 'Longitude',
'subscribers_for_last_30_days'

Filled missing categorical values with 'Not Available'.

Replaced missing numeric fields (like channel_type_rank, video_views_for_the_last_30_days, and country_rank) using their mode.

Checked and dropped any remaining missing values.

## Exploratory Data Analysis (EDA)
The analysis included:

Viewing dataset structure using .head(), .tail(), .info(), and .describe().

Checking for duplicates and null values.

Examining top and bottom channel records by rank and views.

Exploring the distribution of channel categories and types.

Visualizing key trends and correlations (e.g., between subscribers and video views).

## Insights & Findings

(You can fill these in after reviewing your charts)
Examples might include:

Entertainment and Music categories dominate global viewership.

Channels with frequent uploads or consistent engagement tend to have higher subscriber-to-view ratios.

Certain countries have a significantly higher concentration of high-performing channels.