# E2E Data Analysis Project: Olist E-Commerce Dataset

## Overview
This project demonstrates an end-to-end (E2E) data analysis pipeline using the Olist e-commerce dataset, available on Kaggle. The project covers data extraction, transformation, cleaning, and visualization, showcasing the process from raw data to insightful dashboards. Various tools were used to accomplish each step of the workflow, providing a robust solution for analyzing e-commerce trends and performance.

## Technologies Used
- **DuckDB**: To enable SQL execution on Python, for Data transformation and processing
- **Pandas**: Data cleaning and manipulation
- **Tableau**: Data visualization and dashboarding

## Project Workflow
The project is structured around the following steps:

1. **Data Extraction & Transformation**  
   The raw data was loaded and transformed using **DuckDB**. DuckDB was employed to perform fast, in-memory SQL-like operations on large datasets, ensuring efficient and scalable data processing.

2. **Data Cleaning**  
   After transforming the data, **Pandas** was used for further cleaning and preparation. Missing values, duplicates, and outliers were addressed, ensuring a clean and consistent dataset for analysis.

3. **Data Visualization**  
   The final processed dataset was visualized using **Tableau**. Interactive dashboards were created to provide actionable insights into key e-commerce metrics such as sales performance, customer demographics, product ratings, and more.

## Tableau Dashboard
You can explore the interactive Tableau dashboard for visual insights [here](https://public.tableau.com/views/olist-ecommerce-business-insights-dashboard/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).
  
## Recommended Viewing
For optimal experience, it is recommended to view the Tableau dashboards on **laptops or personal computers**. The dashboards are optimized for larger screens, and some interactive elements may not display correctly on mobile devices.

## Limitations
- **Flow Orchestrator & Scheduler**: The project does not include a flow orchestrator or scheduler. In its current state, the workflow is manual, requiring users to execute each step individually.

## Getting Started
1. Clone the repository.
2. Download the Olist e-commerce dataset from Kaggle and put it all to datasets directory.
3. Follow the project structure to run the necessary transformation and cleaning scripts.
4. Open the Tableau dashboard for interactive insights.

## Conclusion
This project serves as a comprehensive demonstration of data analysis using a combination of powerful tools to transform raw e-commerce data into meaningful visualizations. While it doesn't include automation for scheduling, it provides a clear and reproducible workflow for users to follow in their own data analysis tasks.
