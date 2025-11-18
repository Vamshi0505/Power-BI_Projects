## 🛍️ E-commerce Sales Performance Dashboard

This project delivers a comprehensive Business Intelligence solution, utilizing Power BI to analyze the sales performance and profitability of an e-commerce platform. It transforms raw transactional data into actionable visualizations, offering key insights into product performance, regional sales, and customer behavior to drive strategic business decisions.

### 🔗 Live Dashboard Access

You can view the interactive, published report live on the Power BI Service:

[**View the E-commerce Sales Dashboard**](https://app.powerbi.com/groups/me/reports/85220834-0ff0-4db4-9b86-97c6fcbbf7a2/f33aedf8ab5770dd5cfb?experience=power-bi)

### ⚙️ Technologies Used

The solution was built using Power BI Desktop for data modeling and visualization, leveraging Power Query for data preparation and DAX for complex calculations. The final report is hosted on the Power BI Service.

### 📂 Project Contents

The repository includes the main project file and the source data files:
* `Ecommerce Sales dashbord.pbix`: The core Power BI file containing the data model, transformations, and all report pages.
* `Orders.csv`: Contains order-level data including `Order Date`, `CustomerName`, `State`, and `City`.
* `Details.csv`: Contains item-level transactional details such as `Amount`, `Profit`, `Quantity`, `Category`, `Sub-Category`, and `PaymentMode`.
* `README.md`: This documentation file.

### 📊 Analysis Highlights

The dashboard focuses on visualizing the following key insights:

* **Financial Performance:** Tracking Total Sales Amount and Total Profit, with detailed analysis of profit margins across all transactions.
* **Product Performance:** Evaluating sales and profitability broken down by `Category` (e.g., Furniture, Electronics, Clothing) and various `Sub-Category` items.
* **Customer Insights:** Analyzing customer trends based on `PaymentMode` (e.g., COD, UPI, Credit Card, EMI) and geographical sales density by `State` and `City`.
* **Time-Series Trends:** Monitoring sales volume and profit trends over time based on the `Order Date`.

### 💻 How to View the Dashboard Locally

To view the underlying data model or make modifications using Power BI Desktop:

1.  **Install Power BI Desktop:** Ensure you have the application installed.
2.  **Clone the Repository:** Download the project files.
3.  **Open the Report:** Double-click the `Ecommerce Sales dashbord.pbix` file.
4.  **Refresh Data:** If necessary, ensure the `.csv` files are in the same directory as the `.pbix` file and use the **Refresh** button in the Home ribbon to connect to the local data sources.
