# MyPossibilities PowerBI Dashboard

This repository showcases the development process of an interactive PowerBI dashboard designed to visualize survey data from the Lifelong Learning, Online, and Clinical programs at MyPossibilities. The dashboard provides insights into HIPster and Caregiver feedback through a structured data model and interactive visualizations.

## Project Overview
The project aimed to create a dynamic and scalable dashboard for analyzing survey responses. Key steps included:

- **Data Integration**: Merging all survey data into a single table with unique identifiers for seamless comparisons.
- **Data Cleaning & Processing**: Standardizing responses and merging similar questions across programs, particularly between Lifelong Learning and Online surveys.
- **Relational Data Model**:
  - `Questions Table`: Contains all unique questions.
  - `Sources Table`: Lists all programs.
  - `Types Table`: Categorizes surveys into HIPster or Caregiver.
  - `Pivoted Data Table`: Enables easy calculation of metrics such as percentage-based responses.
- **Dashboard Features**:
  - Total response counts by gender.
  - Interactive graphs for deeper insights.
  - Aggregated response ratings using a 5-star system.
  - Filtering capabilities to drill down into specific metrics.

## Viewing the Report
For a detailed breakdown of the methodology and findings, please refer to the full report:

📄 [MyPossibilities.pdf](./MyPossibilities.pdf)

This document provides an in-depth explanation of the dashboard's structure, the survey analysis, and key insights derived from the data.

## Future Enhancements
- Implementing additional interactive filters for specific therapy types.
- Expanding the dataset to incorporate new survey responses dynamically.
- Enhancing visual elements for improved user experience.

---
This project was developed to provide MyPossibilities with a scalable and insightful tool for ongoing program evaluation. If you have any questions or suggestions, feel free to reach out!
