# 📊 Customer Analysis Dashboard – Power BI Project

## 🧩 Overview

This Power BI project delivers a comprehensive customer analysis by combining sales and campaign data, designed for non-technical stakeholders such as the Head of Sales. It addresses the real-world challenge of joining customer data from two different Excel sources without a unique key, and visualizes meaningful insights through an interactive dashboard.

---

## 📂 Data Sources

- CUSTOMER_SALES.xlsx – Contains customer-level sales data.
- CUSTOMER_CAMPAIGN.xlsx – Contains customer demographic and marketing campaign data.
- Challenge: No common unique identifier between the datasets.
- Solution: A custom automated join strategy implemented in Power Query using fields such as:
  - Customer Name
  - Gender
  - Date of Birth
  - Country
  - Marital Status
  - Number of Children

---

## 🔧 Tools Used

- Power BI Desktop
- Power Query 
- Excel (as data source)

---

## 📊 Dashboard Highlights

The dashboard answers key business questions through interactive visuals:

### 📅 Registrations Over Time
- Line chart showing new customer sign-ups by month and year.

### 📈 Spend Analysis
- Scatter plot exploring the correlation between weekly grocery spending and total annual household expenditure.

### 🧍 Demographics Overview
- Bar and pie charts showing customer distribution by:
  - Gender
  - Country
  - Age Range
  - Marital Status
  - Property Ownership
  - Annual Expenditure Range


> Designed with slicers to enable dynamic filtering by user segment.

---

## 🖼️ Dashboard Screenshot

Customer Demographics- (images\Customer_Demographics.png)
Expenditures- (images\Expenditures.png)
Geographic Information- (images\Geographic information.png)
Registrations- (images\Registrations.png)
Sales_Demographics- (images\Sales_Demographics.png)

---

## 🚀 How to Use

1. Download or clone the repository:

```bash
git clone https://github.com/nidhisingh3110/customer-analysis-powerbi.git
Open the Power BI report file:

bash
Copy
Edit
/pbix/CustomerAnalysis.pbix
Load the sample data from the /data folder.

Click Refresh to see the data join and updated visuals in action.

📁 Project Structure
File/Folder	Description
/pbix	Power BI report file (.pbix)
/data	Sample Excel data files
/images	Dashboard screenshots
README.md	Project documentation
.gitignore	Files to exclude from Git



🙌 Author
Made with ❤️ by Nidhi Singh
https://www.linkedin.com/in/nidhi-singh-1bba89155/

----------