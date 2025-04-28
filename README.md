# Insurance Data Analysis - Power BI Project 2

## Project Overview

This project focuses on analyzing insurance data using **Power BI** for rich and interactive visualizations.  
Data was first imported into a **MySQL Server** database named `InsuranceDB`, and then loaded into **Power BI Desktop** for further transformation and visualization.


## Tools & Technologies Used
- **MySQL Server** (Database creation and management)
- **Power BI Desktop** (Data visualization and analysis)
- **Power BI Service** (Publishing, RLS implementation, scheduled refresh)


## Project Steps

1. **Database Setup**:
   - Created a new database `InsuranceDB` in MySQL Server.
   - Imported the insurance dataset into `InsuranceDB`.
   - Verified and cleaned the imported data.

2. **Data Loading in Power BI**:
   - Connected Power BI Desktop to the `InsuranceDB`.
   - Loaded tables and performed necessary transformations.


## Visualizations and Features

- **Table View and Data Profiling**:
  - Explored and validated the dataset using Power BI's data profiling tools.

- **Slicers and Text Boxes**:
  - Added slicers for `Policy Number`, `Claim Number`, and `Customer ID`.
  - Included a text box displaying `PRISM Insurance Pvt Ltd`.

- **Card Visuals**:
  - Created individual card visuals to show:
    - **Total Premium Amount**
    - **Total Claim Amount**
    - **Total Coverage Amount**

- **Multi-Row Card**:
  - Designed a multi-row card to display the count of **Male** and **Female** customers.

- **Ribbon Chart**:
  - Visualized the **Number of Claims** segmented by **Claim Status**.

- **Bar Chart**:
  - Showed the **Premium Amount** distribution across different **Policy Types**.

- **Line Chart**:
  - Analyzed **Claim Amounts** across different **Age Groups**.

- **Donut Chart**:
  - Illustrated the proportion of **Active** vs **Inactive Policies**.

- **Matrix Visual**:
  - Built a matrix showing:
    - **Pending**
    - **Rejected**
    - **Settled**
    - **Total Claims** by **Policy Type**.


## Advanced Power BI Features Implemented

- **Scheduled Refresh**:
  - Enabled scheduled refresh from MySQL database.

- **Drill-Through Filter**:
  - Added drill-through capabilities for detailed customer/claim analysis.

- **Role-Level Security (RLS)**:
  - Created and tested different roles to restrict data access.
  - Implemented and validated RLS in Power BI Service.

- **Power BI Dashboard**:
  - Published a dashboard with KPIs, trend analysis, and claim statuses.

- **Sentiment Analysis (Power Query)**:
  - Integrated sentiment analysis on customer feedback/comments using Power Query Editor.


## How to Run the Project

1. Clone or download the repository.
2. Import the provided SQL file into your local MySQL Server to create `InsuranceDB`.
3. Open the Power BI report (`.pbix` file).
4. Update the data source settings if necessary (MySQL server credentials).
5. Explore the visuals and insights!


## Screenshots

![Screenshot 2025-04-28 094744](https://github.com/user-attachments/assets/06344046-4d19-43e2-a6b8-f5a330d0ba36)

## Author
**Hasrat Hussain**  
Data Analyst | Power BI Developer
