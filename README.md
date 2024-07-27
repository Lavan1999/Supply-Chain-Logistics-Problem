# Supply-Chain-Logistics-Problem

Project Workflow: Order Routing Optimization
# 1. Project Overview
This project focuses on optimizing order routing in a supply chain by minimizing total costs. The model considers warehouse capacities, freight costs, and product availability to provide optimal routing strategies.

# 2. Data Preparation
Warehouse Capacities: Data about the daily capacities of each warehouse.
Order List: Information on customer orders including origin and destination ports, products, and quantities.
Freight Rates: Cost of shipping goods between warehouses and customers.
Product Availability: List of available products at each warehouse.
# 3. Model Development
Define LP Model:
Objective Function: Minimize the total cost, which includes warehouse costs and freight costs.
Decision Variables: x[i][j][p] representing the quantity of product p shipped from warehouse i to customer j.
Constraints:
Fulfill Customer Demand: Ensure each customer’s demand is met.
Warehouse Capacity: Adhere to the storage capacities of each warehouse.
Product Availability: Ensure products not available at a warehouse are not shipped.
# 4. Scenario Analysis
Evaluate different scenarios to understand their impact on the total cost:

Increase Capacity by 20%: Assess the effect of increasing warehouse capacities.
Decrease Freight Rates by 10%: Analyze the impact of reduced shipping costs.
Adjust Product Compatibility: Examine changes in product availability and their effects.
# 5. Results Analysis
Cost Calculation: Compute total storage and freight costs under various scenarios.
Status Evaluation: Check the status of the LP problem solution.
# 6. Visualization
Warehouse Capacity Utilization:
Plot a bar chart showing the utilization of warehouse capacities.
Cost Distribution:
Create a pie chart to visualize the distribution of storage vs. freight costs.
Order Distribution:
Generate count plots for orders by various categorical features such as origin port, destination port, and customer.
Warehouse Capacities:
Display a bar chart of daily capacities of warehouses.
Products per Plant:
Plot the number of products available per plant.
# 7. Implementation
Libraries Used:
pulp for linear programming.
pandas for data manipulation.
seaborn and matplotlib for visualization.
# 8. Results
Summarize the total cost and status for each scenario analyzed.
Discuss key insights from visualizations and their implications for supply chain optimization.
