📊 Simple Sales Dashboard 
🧾 Project Title

Sales Performance Dashboard (Tableau)

🎯 Objective

To create a basic interactive dashboard that shows sales performance by product, region, and month using Tableau.
This dashboard helps identify sales trends, top-performing regions, and high-revenue categories.

🧰 Tools Used

Tableau Desktop / Tableau Public

(Optional) Python + Pandas (for data cleaning)

Dataset: Superstore_Sales.csv or train.csv

📁 Dataset Overview
Column Name	Description
Order Date	Date of order placed
Region	Geographical region (e.g., West, East, Central, South)
Category	Product category (e.g., Furniture, Technology, Office Supplies)
Sales	Total sales amount
Profit	Profit earned on each sale
⚙️ Steps to Recreate in Tableau

Import Data:
Open Tableau → Click “Text File” → Select train.csv.

Prepare Fields:

Ensure Order Date is in Date format.

Create a calculated field for Month-Year:

DATENAME('month', [Order Date]) + " " + STR(YEAR([Order Date]))


Create Visuals:

Line Chart: Sales over Month-Year

Bar Chart: Sales by Region

Donut Chart: Sales by Category

Add Filters:
Add a slicer for Region or Category.

Design Dashboard:

Title: “Sales Performance Dashboard”

Arrange visuals clearly.

Use colors (Blue = Top performer, Orange = Mid, Grey = Low).

Export Output:

Go to File → Export → PDF or take a screenshot for submission.

💡 Key Insights

1️⃣ West region recorded the highest overall sales, especially during mid-year months (Q3).
2️⃣ Technology category contributed the largest share of total sales revenue.
3️⃣ Central and South regions showed lower sales performance, indicating potential for targeted promotions.

📦 Deliverables

Dashboard Screenshot/PDF: Sales_Dashboard.pdf

Insights File: Sales_Insights.txt

README File: README.md

✅ Outcome

You will understand how to:

Build an interactive Tableau dashboard

Visualize trends by time, region, and category

Summarize sales insights for business decision-making
