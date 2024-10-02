## AtliQ Hardware-Sales-Analysis using Power BI and SQL

### Problem Statement
AtliQ Hardware, a computer hardware and peripheral manufacturer with branches across India, is facing declining sales and difficulties in assessing business performance. The sales director struggles to obtain accurate insights, as regional managers find it challenging to interpret data from Excel files. This lack of clarity hinders their ability to identify trends, understand customer preferences, manage inventory, and optimize marketing efforts, resulting in missed growth opportunities.

To address these issues, AtliQ Hardware needs a solution that clearly visualizes sales patterns, enabling data-driven decision-making. This project aims to enhance sales performance, meet financial goals, and improve overall business operations.


### Tools used:
I used SQL queries in MySQL Workbench to take a look into the data and Power BI for ETL and visualizations to create the insights.

## KPIs
• Revenue: sum of the amount

<img width="274" alt="image" src="https://github.com/adithya-sakthi/AtliQ-Sales-Analysis/assets/105962400/be7ba09a-30d2-4b74-a7db-596ed32ac295">


• Sales Quantity: sum of quantity

<img width="257" alt="image" src="https://github.com/adithya-sakthi/AtliQ-Sales-Analysis/assets/105962400/10fd83fc-76cd-4c67-a881-75b645ac5eeb">


• Total Profit Margin (TPM) = sum(profit margin)

<img width="325" alt="image" src="https://github.com/adithya-sakthi/AtliQ-Sales-Analysis/assets/105962400/fd837b7c-4dc8-4721-bcf0-488335dc2d79">


• Profit Margin % = TPM/Revenue then select "Percentage" data type

<img width="317" alt="image" src="https://github.com/adithya-sakthi/AtliQ-Sales-Analysis/assets/105962400/e22211e5-00af-41c6-ae0a-a4a0a9ea9556">


• Profit Margin Contribution (PMC) = TPM/TPM(All sales products, all sales customers, all markets)

For e.g total of 50 bucks profit and out of it "Delhi" brings 10 bucks profit then PMC will be (10/50)*100= 20% profit

<img width="544" alt="image" src="https://github.com/adithya-sakthi/AtliQ-Sales-Analysis/assets/105962400/1fa65bb6-6e6f-4daa-a156-5ea5e2a66d06">

• Top 5 customers and products

• Revenue trend

###Insights:
* In four years, the company generated total revenue of ₹985M with a profit margin of ₹24.7M (2.5%) and sales quantity of ₹2M.
* In 2020, the revenue was ₹142M from 350K units sold, resulting in a profit of ₹2.1M.
* Delhi NCR is the largest market by revenue, contributing ₹520M (52.8%) but has a low profit margin of 2.3%.
* Bhubaneshwar achieved the highest profit margin of 10.48% in 2020.
* Mumbai contributes 23.89% to total profit, while Bengaluru shows the lowest profit margin at -20.8% and a -0.3% contribution to total profit.
* Among the top five customers, Electricalsara Stores generated ₹413M in revenue over four years.
* The highest-grossing product, Prod318, contributed ₹69M.
* Both distribution and own brand product types generated ₹494M each in total revenue.
* The revenue trend indicates a significant decline in June 2020 compared to the previous year, with the lowest profit margin recorded in April 2020.

I've created three dashboards:
- Key Insights
- Profit analysis
- Performance insights

click here to view my [dashboard](https://www.novypro.com/project/sales-insights-23)

