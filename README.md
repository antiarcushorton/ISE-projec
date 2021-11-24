# ISE-project

Link to traveling salesperson example: https://colab.research.google.com/github/Gurobi/modeling-examples/blob/master/traveling_salesman/tsp_gcl.ipynb#scrollTo=0UZuXb1e-9Jb

We need the coordinates of all 60 ballparks. I put the first 15 coordinates in the JSON file. 

Link to Google Sheet with all ballpark addresses and names: https://docs.google.com/spreadsheets/d/1PEf0i9N2Eg6t9OHaZTtersH3YAy5TRUuzCSdCRKQL44/edit?usp=sharing

The Python file works up until the point where we import gurobipy, because I just followed the example exactly (using our own data). I think we need to use cvxpy with a Gurobi solver at this point, which might be tough to figure out. Hopefully this all makes sense.
