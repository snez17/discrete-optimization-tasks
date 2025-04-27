# BRIEF 

## 1. assignment_problem.py

It`s a problem from a mathematical modeling student Olympiad.
There I use the PuLP library to solve an assignment problem, maximizing the overall score of team players assigned to positions. 
It reads player scores from a CSV, uses linear programming to find the best assignments, and outputs the optimal matching and total score.

## 2. scm_analytics_pulp
   
It`s tasks from datacamp course on supply chain analytics in Python.
There I solved optimization problems using linear programming with the PuLP library:

- **Maximize profit**. We have to determine the optimal number of two types of baked goods (A and B) to produce, given constraints on oven time, baker time, and packer time. I use different ways to structure constraints: dicts, csv, build-in function in pulp.
- **Traveling Salesman Problem (TSP)** It defines the distances between 15 cities, sets up decision variables representing the path between cities, and establishes constraints to ensure each city is visited exactly once. The objective is to minimize the total travel distance. The notebook prints the status and optimal values of the decision variables.
- **Minimize Transportation Costs**. We minimize the cost of shipping goods from two warehouses (New York and Atlanta) to four customer regions (East, South, Midwest, West). It defines warehouse capacities and regional demands, sets up decision variables representing the quantity shipped from each warehouse to each customer, and establishes constraints to meet the demands. The results, showing the optimal shipment quantities from each warehouse to each region, are then written into an output.txt file.
- **Cost-minimizing production scheduling problem** The problem involves two factories (A and B) and a monthly demand to meet. It reads factory parameters (variable costs, fixed costs, minimum capacity, maximum capacity) from a CSV file (factory_variables.csv) and monthly demand data from another CSV file (monthly_demand.csv). It then defines decision variables for production quantity and factory status (on/off), sets up constraints related to demand fulfillment and capacity limits, and formulates the objective function to minimize total costs (production and fixed costs). A specific constraint is added that Factory B is forced to be off in May. Finally, it solves the optimization problem, prints the total minimized cost, and presents the optimal production schedule and factory status for each month. A link to the source (a tutorial on linear programming) is also provided.
