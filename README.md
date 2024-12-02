# Denver Airport Data Challenge - Hackathon Solution

This repository contains the solution developed during the Hackathon organized by our department in collaboration with **Denver International Airport**. The project focuses on creating interactive dashboards that provide actionable insights for both **clients (customer's perspective)** and **companies (internal perspective)** by cleaning, merging, and analyzing operational datasets.

---

## Project Overview

The challenge was to analyze and integrate data from multiple sources to optimize processes and visualize insights that drive effective decision-making. We used advanced tools and methodologies to develop **two dashboards**:
1. **Customer Dashboard (Client's Perspective):**
   - Focuses on feature requests, user story enhancements, and completion progress.
2. **Internal Dashboard (Company's Perspective):**
   - Provides an internal view of enhancement states, assignments, and completion metrics for tracking efficiency.

---

## Data Cleaning and Integration

We were provided with two primary datasets:
1. **ADO_FeatureUserStorylist_V2.xlsx**  
   - Contains details about feature titles, user stories, states, and priorities.
2. **SN_enhancementlist_v2.xlsx**  
   - Contains details about enhancement numbers, customer names, and related attributes.

### Data Cleaning Process:
- Removed redundant and inconsistent data.
- Standardized column names and data formats.
- Merged the two datasets to form a single CSV for analysis and visualization.

### Tools Used for Data Cleaning:
- **Python:** Pandas, NumPy for data wrangling.
- **Excel:** Data validation and preprocessing.

---

## Dashboards

### 1. Customer Dashboard (Client's Perspective)
![Customer dashboard(Client's Perspective)](https://github.com/user-attachments/assets/e78b8d64-4620-4a91-9977-0d541484ad21)



Key Features:
- **Completion Percentage:** Tracks the overall completion progress.
- **Enhancement Metrics:** Displays counts of feature titles and user stories by enhancement number.
- **State Analysis:** Visualizes the state of tasks (e.g., Draft, Closed, On Hold).
- **Customer Breakdown:** Shows enhancement distribution by customer.

---

### 2. Internal Dashboard (Company's Perspective)
![Internal Dashboard(Comapny's Perspective)](https://github.com/user-attachments/assets/afb4cc7e-9804-4534-889f-e6618ab7327c)




Key Features:
- **Task Status:** Tracks states like Closed, New, Active, and On Hold.
- **Assigned Tasks:** Shows task ownership and prioritization within the company.
- **Enhancement Overview:** Provides a high-level summary of enhancements and their statuses.

---

## Tools and Technologies Used

### Data Processing
- **Python:** For data cleaning, merging, and validation.
- **Excel:** Initial preprocessing.

### Visualization
- **Power BI:** Interactive dashboards for both client and internal perspectives.
- **Power Query:** Data modeling and transformation.

---

## Insights and Results

- **Customer Perspective:**
  - Customers can easily track enhancement progress and user story updates.
  - Clear visibility into feature statuses and completion percentages.

- **Company Perspective:**
  - Internal teams can manage task assignments effectively.
  - Provides actionable insights into process bottlenecks and task priorities.

---

## How to Use

1. Open the Power BI report file (`Hackathon.pbix`) to explore interactive dashboards.
2. Use filters to analyze data from different perspectives (Customer vs. Internal).
3. Examine the processed datasets for further insights.

---

## Challenges and Solutions

1. **Data Inconsistencies:**
   - Addressed by standardizing and cleaning datasets using Python and Excel.

2. **Multiple Data Sources:**
   - Merged datasets to create a unified view for analysis.

3. **Dynamic Insights:**
   - Designed dashboards with interactivity and filters for deeper exploration.

---

## Future Enhancements

- **Real-Time Data Integration:** Connect to live data sources for up-to-date insights.
- **Advanced Analytics:** Implement predictive models for better forecasting.
- **Scalability:** Expand dashboards to cover more operational metrics.

---

## Files Included

1. **Dashboards:**
   - `Customer dashboard(Client's Perspective).png`
   - `Internal Dashboard(Company's Perspective).png`

2. **Datasets:**
   - `ADO_FeatureUserStorylist_V2.xlsx`
   - `SN_enhancementlist_v2.xlsx`

3. **Power BI Report:**
   - `Hackathon.pbix`

---

## Acknowledgments

We thank **Denver International Airport** for providing the problem statement and datasets, and our department for organizing the hackathon. This project demonstrates the power of data-driven insights in optimizing operational efficiency.

---

Feel free to reach out for any questions or contributions!
# Denver-Airport-Dashboard
