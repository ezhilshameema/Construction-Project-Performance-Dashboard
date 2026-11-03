# Construction Project Performance Dashboard

Analysed 1,300 construction task records to understand material costs, task duration, labour requirements, equipment usage and risk levels through interactive dashboards.



## Project Overview

This project analyses a task-level construction dataset covering duration, labour, equipment, material cost, and risk classification. The goal is to help project teams quickly identify high-cost, high-risk, and resource-heavy tasks that need closer management attention.

## Objectives

- Track total task volume and material cost.
- Compare cost and duration across risk levels (Low / Medium / High).
- Identify tasks with higher material costs and risk levels.
- Understand labour and equipment requirements.

## System Architecture

- **Data Collection Layer:** Task-level construction dataset (1,300 tasks).
- **Data Processing Layer:** Power Query data type validation.
- **Analysis Layer:** DAX measures for totals, averages, and risk analysis.
- **Visualisation Layer:** Power BI dashboard with two pages.

## Key Features

- KPI cards showing total tasks, total material cost, average duration, average labour, and high-risk task percentage.
- Cost breakdown by risk level using a bar chart.
- Duration versus cost scatter plot, sized by labour requirement and coloured by risk.
- Task-level cost and risk details in a table.
- Interactive slicers for risk level and dependency count.

## Technologies Used

- Microsoft Power BI
- Power Query
- DAX
- Python (Pandas) for initial data validation

## Data Pipeline Workflow

1. Import the construction task dataset.
2. Validate data types in Power Query.
3. Create DAX measures for totals, averages, and risk analysis.
4. Build interactive visualisations across two dashboard pages.

## Use Cases

- Construction task cost monitoring.
- Risk-based task prioritisation.
- Labour and equipment planning.
- Project management reporting.

## Data Limitations

This dataset is task-level and does not include actual project dates, a start/end timeline, or an on-time-versus-delayed flag. It supports cost, duration, and risk analysis, but not calendar-based progress tracking.

A future version could include scheduling data for delay and schedule-variance analysis.

## Screenshots

- Overview Page
- Cost and Risk Analysis Page

## Key Learnings

- Creating DAX measures using COUNTROWS and CALCULATE.
- Analysing cost, duration, labour, and risk using scatter charts.
- Designing dashboards to make data easier to understand.
- Using interactive filters to explore construction task details.

Future Improvements

- Add actual project timeline and date information.
- Include budget-versus-actual cost comparisons if budget data becomes available.
- Add site and location-based analysis.

Author

Ezhil Shameema

Project Note

This project demonstrates how Power BI can turn construction task data into meaningful information about costs, duration, resource requirements, and risk to support better project management decisions.
