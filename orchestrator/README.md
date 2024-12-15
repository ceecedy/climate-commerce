# Orchestrator: Data Processing Workflow

## Introduction

The **Orchestrator** is the central component in our data processing pipeline. It controls the flow of tasks, ensuring that data is read, transformed, and visualized appropriately. Currently, it processes a static CSV file, performs a one-time transformation and data cleaning since there's no need to do an ETL Pipeline for now, and generates a dashboard for visualization.

### Current Functionality

- **Read Data**: The orchestrator reads a static CSV file (`Olist Datasets`) from the `datasets/` directory.
- **Data Transformation**: It applies a set of predefined data cleaning and transformation steps.
- **Dashboarding**: After processing the data, it generates a dashboard (e.g., an HTML report) to visualize the transformed data.

### Future Enhancements

In the future, the orchestrator will evolve to become a fully-fledged **ETL pipeline**, with the following features:
1. **Extract** data from various sources (APIs, databases, cloud storage).
2. **Transform** data with complex operations like aggregation, enrichment, and joins.
3. **Load** processed data into a data warehouse or database for further use.
4. **Error Handling & Logging**: Robust error handling and logging to ensure pipeline reliability.