Dynamic Financial Model & Business Projection Tool
A standalone, single-file HTML web application that functions as a dynamic financial model and business projection tool. It allows users to modify input variables and see all dependent calculations and dashboards update in real-time.
(A representative image of the application's interface)
Features
Real-Time Calculations: All outputs, KPIs, and charts update instantly as you change any input value.
Dynamic Lists: Easily add or remove line items for Variable Costs, Add-On Products, and Fixed Monthly Expenses.
Interactive Dashboard: Key performance indicators (KPIs) are displayed clearly, alongside pie and bar charts for visual analysis of revenue and cost breakdowns.
Multi-Channel Marketing Analysis: Model and compare the performance (Spend, Conversions, CPA) of Direct Mail, Door Knocking, and PPC advertising campaigns.
Detailed Cost Breakdown: Differentiates between marketing costs, fixed expenses, and various types of variable costs (per-customer, per-subscription, add-ons).
Product Mix & Revenue Modeling: Project revenue based on a mix of different product tiers, each with its own one-time and recurring revenue streams.
Formula Transparency: A dedicated "Data & Formulas" tab shows the exact calculations used, ensuring clarity and trust in the results.
Zero Dependencies: The entire application runs from a single HTML file with no need for a web server, backend, or external installations (besides an internet connection for the Chart.js library).
How to Use
No installation is required.
Save the application code as an .html file (e.g., financial_model.html).
Open that file in any modern web browser (such as Google Chrome, Firefox, Safari, or Microsoft Edge).
The application will load and be ready to use immediately.
Application Structure
The application is organized into two main tabs: Calculator and Data & Formulas.
1. Calculator Tab
This is the main interactive part of the application.
Inputs Section (Left Pane)
This is where you can edit all the assumptions for the model.
A. Marketing Assumptions:
Set the parameters for Direct Mail, Door Knocking, and PPC campaigns.
Calculated outputs like CPA and total conversions for each channel are displayed directly below the inputs for quick reference.
B. Product & Revenue Assumptions:
Define the sales mix percentage across your product tiers.
Set the one-time revenue (setup fees) and Monthly Recurring Revenue (MRR) for each product.
C. Variable Costs:
Set the per-subscription support cost.
Dynamically add or remove other per-customer costs (e.g., site survey, materials).
D. Add-Ons:
Dynamically create a list of add-on products. For each, you can specify its name, price, cost, and the attach rate (the percentage of new customers who purchase it).
E. Fixed Monthly Expenses:
Dynamically manage a list of all fixed overhead costs, such as rent, software subscriptions, and fixed salaries.
Dashboard / Outputs (Right Pane)
This pane is a read-only summary of all calculations, providing a high-level view of the business's projected performance for a single month.
Summary KPIs: The most important top-line metrics, including Total Revenue, Expenses, Profit, Net Margin, and Blended Cost Per Acquisition (CPA).
Revenue Breakdown: A pie chart that visualizes the sources of revenue (Cash Upfront, New MRR, Add-ons).
Cost Breakdown: A bar chart that shows the composition of the total expenses (Marketing, Variable, Fixed).
Marketing Channel Performance: A summary table that directly compares the effectiveness and cost-efficiency of each marketing channel.
2. Data & Formulas Tab
This tab provides a transparent, read-only view of all the formulas used in the application. It is designed to help you understand and verify how every calculated value on the dashboard is derived from the inputs you provide.
Technical Details
Frontend: The entire application is built with vanilla HTML, CSS, and JavaScript (ES6).
Styling: Modern CSS with variables is used for easy theming and maintenance.
Logic: All financial calculations are handled in real-time on the client-side using JavaScript.
Charts: Data visualization is powered by the Chart.js library.
Potential Future Improvements
Time-Series Projection: Extend the model to project performance over multiple months (e.g., 12, 24, 36 months), accounting for cumulative MRR and churn over time.
Data Persistence: Use browser localStorage to save a user's inputs, so they are not lost when the page is refreshed.
Export Functionality: Add buttons to export the dashboard summary or raw data to CSV or PDF formats.
