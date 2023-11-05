# User Engagement Analysis Project

## Overview

This project focuses on the analysis of user engagement data for a platform to identify and understand adopted users. Adopted users are those who regularly engage with the platform, and by identifying them, we aim to gain insights into user behavior and preferences. These insights can inform business decisions and strategies for improving user retention and engagement.

## Key Steps

1. **Data Collection**: We load and examine two datasets, `takehome_users.csv` and `takehome_user_engagement.csv`. The former contains user information, while the latter provides user engagement data.

2. **Data Preprocessing**: Data is prepared for analysis by merging the datasets and extracting timestamp components (e.g., datetime, week, month, and year).

3. **Identifying Adopted Users**: Using engagement data, we define adopted users as those who logged in on at least three separate occasions within a one-week period.

4. **Data Visualization**: Visualizations are created to provide insights into user engagement. These include distributions of user types, yearly visits by adopted users, monthly distribution of visits, and the distribution of creation sources.

## Project Files

- `data_analysis.ipynb`: The Jupyter Notebook containing the data analysis and visualization code.
- `takehome_users.csv`: User information dataset.
- `takehome_user_engagement.csv`: User engagement dataset.

## Dependencies

The project uses Python with libraries like Pandas, NumPy, Matplotlib, Seaborn, and datetime for data analysis and visualization. You can install these dependencies using the following:


