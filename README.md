Download Link: https://assignmentchef.com/product/solved-solvedlinear-programming
<br>
For this project, you will model the following problems as linear programs and solve them using a language/linear programming /mathematical software of your choice (problems may be solved using different methods) . Include in your report the solutions to the problems along with any code/files used. This project will only be submitted in Canvas only.

Problem 1: Transshipment Model This is an extension of the transportation model. There are now intermediate transshipment points added between the sources (plants) and destinations (retailers). Items being shipped from a Plant (pi) must be shipped to a Warehouse (wj) before being shipped to the Retailer (rk).

Each Plant will have an associated supply (si) and each Retailer will have a demand (dk). The number of plants is n, number of warehouses is q and the number of retailers is m. The edges (i,j) from plant (pi)to warehouse (wj) have costs associated denoted cp(i,j). The edges (j,k) from a warehouse (wj)to a retailer (rk) have costs associated denoted cw(j,k). The graph below shows the transshipment map for a manufacturer of refrigerators. Refrigerators are produced at four plants and then shipped to a warehouse (weekly) before going to the retailer.

Below are the costs of shipping from a plant to a warehouse and then a warehouse to a retailer. If it is impossible to ship between the two locations an X is placed in the table. cost W1 W2 W3 P1 $10 $15 X P2 $11 $8 X P3 $13 $8 $9 P4 X $14 $8 cost R1 R2 R3 R4 R5 R6 R7 W1 $5 $6 $7 $10 X X X W2 X X $12 $8 $10 $14 X W3 X X X $14 $12 $12 $6 The tables below give the capacity of each plant (supply) and the demand for each retailer (per week). P1 P2 P3 P4 Supply 150 450 250 150 R1 R2 R3 R4 R5 R6 R7 Demand 100 150 100 200 200 150 100

Part A:

Determine the number of refrigerators to be shipped plants to warehouses and then warehouses to retailers to minimize the cost.

i. Formulate the problem as a linear program with an objective function and all constraints.

ii. Determine the optimal solution for the linear program using any software you want. Include a copy of the code/file in the report.

iii. What are the optimal shipping routes and minimum cost.

Part B:

Due to old infrastructure Warehouse 2 is going to close eliminating all of the associated routes. What is the optimal solution for this modified model? Is it feasible to ship all the refrigerators to either warehouse 1 or 3 and then to the retailers without using warehouse 2? Why or why not?

Part C:

Instead of closing Warehouse 2 management has decide to keep a portion of it open but limit shipments to 100 refrigerators per week. Is this feasible? If so what is the optimal solution when warehouse 2 is limited to 100 refrigerators?

Part D:

Formulate a generalized linear programming model for the transshipment problem. Give the objective function and constraints as mathematical formulas.

Problem 2: A mixture problem Veronica the owner of Very Veggie Vegeria is creating a new healthy salad that is low in calories but meets certain nutritional requirements. A salad is any combination of the following ingredients: Tomato, Lettuce, Spinach, Carrot, Smoked Tofu, Sunflower Seeds, Chickpeas, Oil Each salad must contain:  At least 15 grams of protein

 At least 2 and at most 8 grams of fat

 At least 4 grams of carbohydrates

 At most 200 milligrams of sodium

 At least 40% leafy greens by mass. The nutritional contents of these ingredients (per 100 grams) and cost are Ingredient Energy (kcal) Protein (grams) Fat (grams) Carbohydrate (grams) Sodium (mg) Cost (100g) Tomato 21 0.85 0.33 4.64 9.00 $1.00 Lettuce 16 1.62 0.20 2.37 28.00 $0.75 Spinach 40 2.86 0.39 3.63 65.00 $0.50 Carrot 41 0.93 0.24 9.58 69.00 $0.50 Sunflower Seeds 585 23.4 48.7 15.00 3.80 $0.45 Smoked Tofu 120 16.00 5.00 3.00 120.00 $2.15 Chickpeas 164 9.00 2.6 27.0 78.00 $0.95 Oil 884 0 100.00 0 0 $2.00

Part A:

Determine the combination of ingredients that minimizes calories but meets all nutritional requirements.

i. Formulate the problem as a linear program with an objective function and all constraints.

ii. Determine the optimal solution for the linear program using any software you want. Include a copy of the code/file in the report. iii. What is the cost of the low calorie salad?

Part B:

Veronica realizes that it is also important to minimize the cost associated with the new salad. Unfortunately some of the ingredients can be expensive. Determine the combination of ingredients that minimizes cost.

i. Formulate the problem as a linear program with an objective function and all constraints.

ii. Determine the optimal solution for the linear program using any software you want. Include a copy of the code/file in the report. iii. How many calories are in the low cost salad?

Part C:

Compare the results from part A and B. Veronica’s goal is to create a Very Veggie Salad that is both low calorie and low cost. She would like to sell the salad for $5.00 and still have a profit of at least $3.00. However if she can advertise that the salad has under 250 calories then she may be able to sell more.

i. Suggest some possible ways that she select a combination of ingredients that is “near optimal” for both objectives. This is a type of multi-objective optimization.

ii. What combination of ingredient would you suggest and what is the associated cost and calorie. iii. Note: There is not one “right” answer. Discuss how you derived your solution.

Problem 3:

Solving shortest path problems using linear programming. The file Project3Problem3.txt contains a list of the edges and weights in a directed graph. Use linear programming to answer the following questions. Include a copy of the linear program code.

a) What are the lengths of the shortest paths from vertex a to all other vertices.

b) If a vertex z is added to the graph for which there is no path from vertex a to vertex z, what will be the result when you attempt to find the lengths of shortest paths as in part a).

c) What are the lengths of the shortest paths from each vertex to vertex m. How can you solve this problem with just one linear program?

d) Suppose that all paths must pass through vertex i. How can you calculate the length of the shortest path from any vertex x to vertex y that pass through vertex i (for all x,y  V)? Calculate the lengths of these paths for the given graph. (Note for some vertices x and y it may be impossible to pass through vertex i).