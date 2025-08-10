Blinkit Sales Performance Analysis

Objective
This project analyzes Blinkit’s sales performance, customer satisfaction, and inventory distribution using **Python**. 
The aim is to identify key insights and opportunities for optimization through **KPIs** and visualizations.

KPIs Calculated
1. Total Sales – Overall revenue generated from all items sold.
2. Average Sales – Average revenue per sale.
3. Number of Items – Total count of different items sold.
4. Average Rating – Average customer rating for items sold.

Visualizations Created
1. Total Sales by Fat Content
Objective: Analyze how sales are distributed across different fat content categories (e.g., Low Fat, Regular).
Chart Type: Pie Chart
Python Libraries Used: pandas, matplotlib

2. Fat Content by Outlet for Total Sales
Objective: Compare the total sales of fat content categories across different outlet location tiers.
Chart Type: Grouped Bar Chart
Python Libraries Used: pandas, matplotlib

3. Total Sales by Outlet Establishment
Objective: Evaluate how the age or type of outlet establishment influences total sales.
Chart Type: Line Chart
Python Libraries Used: pandas, matplotlib / seaborn

4. Sales by Outlet Size
Objective: Analyze the correlation between outlet size and total sales.
Chart Type: Donut/Pie Chart
Python Libraries Used: matplotlib

5. Sales by Outlet Location
Objective: Assess the geographic distribution of sales across different locations.
Chart Type: Funnel Map (using Plotly or similar)
Python Libraries Used: plotly.express / folium

Data Preparation Steps
1. Load Data from CSV using `pandas`.
2. Clean Data:
   - Remove missing values where necessary.
   - Correct data types for numerical and categorical columns.
3. Feature Engineering:
   - Calculate outlet establishment age if only the year is given.
4. Aggregate Data to calculate KPIs by category.


Tools & Libraries Used
- Python 3.x
- Pandas – Data loading and transformation
- Matplotlib – Static visualizations
- Seaborn – Statistical plots
