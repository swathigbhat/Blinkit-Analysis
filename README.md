# Blinkit Sales Performance Analysis

## Objective
Analyze Blinkit’s sales performance, customer satisfaction, and inventory distribution using **Python**, focusing on KPIs and visualizations to identify key insights and optimization opportunities.

## KPIs Calculated
- **Total Sales** – Overall revenue generated from all items sold.
- **Average Sales** – Average revenue per sale.
- **Number of Items** – Total count of different items sold.
- **Average Rating** – Average customer rating for items sold.

## Visualizations Created

1. Total Sales by Fat Content
   - Objective: Analyze how sales are distributed across fat content categories.
   - Chart Type: Pie Chart
   - Libraries: pandas, matplotlib
2. Total Sales by Item Type
   - Objective: Identify which item types contribute the most to total sales and compare their performance.
   - Chart Type: Bar Chart
   - Python Libraries Used: pandas, matplotlib
3. Fat Content by Outlet for Total Sales
   - Objective: Compare fat content sales across outlet location tiers.
   - Chart Type: Grouped Bar Chart
   - Libraries: pandas, matplotlib
4. Total Sales by Outlet Establishment
   - Objective: Evaluate how outlet age/type influences sales.
   - Chart Type: Line Chart
   - Libraries: pandas, matplotlib / seaborn
5. Sales by Outlet Size
   - Objective: Analyze the correlation between outlet size and total sales.
   - Chart Type: Donut/Pie Chart
   - Libraries: matplotlib
6. Sales by Outlet Location
   - Objective: Assess geographic sales distribution.
   - Chart Type: Funnel Map
   - Libraries: plotly.express / folium

Tools & Libraries Used
- Python 3.x
- pandas
- matplotlib
- seaborn
- plotly.express / folium

How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/blinkit-sales-analysis.git
   cd blinkit-sales-analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn plotly folium
   ```
3. Run the script:
   ```bash
   python scripts/sales_analysis.py
   ```
