# battery-storage-optimization
🔋 Battery Energy Storage Optimization with cvxpy
This project simulates a simplified Battery Energy Storage System (BESS) optimizer using convex optimization techniques. The goal is to maximize profit by charging the battery when electricity prices are low and discharging when prices are high, while respecting realistic operational constraints.

Project Overview
Objective: Maximize arbitrage profit from electricity price fluctuations using a BESS.

Approach: Use cvxpy to solve a constrained optimization problem for 24 hourly intervals.

Battery Constraints: Capacity, max charge/discharge rate, and round-trip efficiency.

Key Assumptions:

Simulated hourly price data

Battery starts empty and follows charge/discharge limits

Efficiency losses during charge/discharge cycles

⚙️ Tools & Technologies
Python, cvxpy, pandas, matplotlib

Optimization theory, convex problem solving

Data visualization

📈 Key Outputs
Hourly charge/discharge schedule

State of charge over time

Electricity price trends

Interactive plot for visual insight into battery strategy

