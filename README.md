# UPI Transactions Interactive Power BI Dashboard

## Project Overview
This project presents an interactive Power BI dashboard built using UPI transaction data sourced from an Excel file.
It focuses on user-driven analysis through dynamic visuals, bookmarks, navigator buttons, and synchronized slicers.

---

## Tools & Technologies
- Power BI Desktop & Power BI Service
- Microsoft Excel (Data Source)
- DAX
- Bookmarks & Navigator Buttons
- Slicer Sync

---

## Data Modeling & DAX

- Created calculated measures for:
  - Total Transaction Amount
  - Monthly Remaining Balance
- Used DAX to enable dynamic filtering across:
  - Time (Month, Year)
  - City, Bank, and Transaction Type
- Implemented bookmark-based visual switching to toggle between:
  - Line and Column charts
  - Transaction Amount and Remaining Balance
- Ensured reusability of measures without duplication

---

## Key Features
- **Interactive Visual Switching**
  - Toggle between line and column charts using bookmarks
  - Switch between transaction amount and remaining balance views

- **Multi-Page Report Navigation**
  - Two-page Power BI report
  - Filter context is maintained across pages

- **Synchronized Slicers**
  - Slicers are synced across all report pages
  - User selections persist during navigation

- **Extensive Filtering Options**
  - Bank (Sent & Received)
  - City
  - Device Type
  - Gender
  - Age Group
  - Merchant Name
  - Payment Method
  - Transaction Type
  - Purpose

---

## Dataset
- Source: Excel file containing UPI transaction data
- Used as a static data source for analysis and visualization

---

## Live Report (Power BI Service)

Public interactive Power BI dashboard :

https://app.powerbi.com/view?r=eyJrIjoiYmJkODhiMmItZDg4Zi00MjA0LTkxNjctYzNkMGViMjJjZTdlIiwidCI6IjIwMDE0NzcwLTM3YWEtNDQ1ZC04MTNkLTVlNjhmMTI3MTgyYyJ9


---

## How to Use This Project

1. Download the `.pbix` file from this repository  
2. Open it using **Power BI Desktop**  
3. Use slicers and navigation buttons to explore insights  
4. For full interactivity, ensure bookmarks and slicers are enabled  

---

## Dashboard Screenshots

### Transaction Amount by Month (Line Chart)
![Transaction Amount by Month - Line](Screenshots/transaction-by-month-line-amount-2024.png)

---

### Transaction Amount by Month (Column Chart)
![Transaction Amount by Month - Column](Screenshots/transaction-by-month-column-amount-2024.png)

---

### Remaining Balance by Month (Line Chart)
![Remaining Balance by Month - Line](Screenshots/balance-by-month-line-2024.png)

---

### Remaining Balance by Month (Column Chart)
![Remaining Balance by Month - Column](Screenshots/balance-by-month-column-2024.png)

---

### City-wise Monthly Transactions (Matrix View)
![City-wise Monthly Transactions](Screenshots/city-wise-monthly-transactions-table.png)

---

## Limitations & Assumptions

- Dataset is static and sourced from an Excel file
- No real-time or incremental refresh is enabled
- Data is used purely for educational and portfolio purposes

---

## Key Insights & Observations

- Transaction volumes peak during **May and October**, indicating seasonal usage spikes.
- Remaining balance remains relatively stable across months, suggesting consistent inflow–outflow behavior.
- Metro cities like **Mumbai and Delhi** contribute the highest transaction amounts.
- Younger age groups dominate UPI usage, especially for merchant payments.
- Mobile devices account for the majority of transactions, highlighting mobile-first adoption.
- Dynamic slicers and synchronized filters allow users to analyze transaction behavior consistently across pages without losing context.

---

## Notes

- This project demonstrates practical Power BI skills including data modeling,
  DAX calculations, bookmarks, and synchronized slicers.
- The dataset is used for educational and portfolio purposes.
- For full interactivity, open the `.pbix` file in Power BI Desktop.
