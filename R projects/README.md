# data-analysis
# Exploring Author Success in Amazon Bestselling Books in R

**Table of Contents**
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Data Analysis](#data-analysis)
  - [Loading and Inspecting the Dataset](#loading-and-inspecting-the-dataset)
  - [Data Cleaning](#data-cleaning)
  - [Standardizing Author Names](#standardizing-author-names)
  - [Author Analysis](#author-analysis)
  - [Calculating Success Metrics](#calculating-success-metrics)
  - [Merging Author Data](#merging-author-data)
  - [Removing Unnecessary Columns](#removing-unnecessary-columns)
  - [Data Visualization](#data-visualization)
- [Conclusion](#conclusion)

## Introduction
This R Markdown document explores author success in the context of Amazon's bestselling books. I analyze a dataset containing information about the top 50 bestselling books from 2009 to 2019, including details about the books' authors, user ratings, reviews, prices, publication years, and genres.

## Project Overview
The project involves several key steps:
- Loading and inspecting the dataset.
- Data cleaning to ensure data quality.
- Standardizing author names.
- Author analysis to identify authors with multiple entries.
- Calculating success metrics for each author.
- Merging author data and success metrics.
- Removing unnecessary columns.
- Data visualization to understand the distribution of success metrics.

## Data Analysis
### Loading and Inspecting the Dataset
I begin by loading the dataset and taking a quick look at its structure and the first few rows.

### Data Cleaning
Before proceeding with the analysis, I ensure data quality by checking for missing values and duplicates.

### Standardizing Author Names
Author names are standardized by converting them to lowercase.

### Author Analysis
I identify authors who have multiple entries in the top 50 list, indicating recurring success.

### Calculating Success Metrics
Success metrics for each author, including total appearances, average ratings, and total reviews, are calculated.

### Merging Author Data
Data about authors with multiple entries and their success metrics are merged, and the results are arranged by total reviews.

### Removing Unnecessary Columns
The 'n' column, used for counting, is removed from the merged data.

### Data Visualization
I visualize the distributions of total appearances, average ratings, and total reviews for authors in the dataset.

## Conclusion
This project explored author success in fiction and nonfiction categories using Amazon book data. The findings suggest that there is a high degree of inequality in terms of success among authors in the top 50 list. A small number of authors have consistently high total appearances, average ratings, and total reviews, while the majority of authors have lower levels of success on all three metrics.
