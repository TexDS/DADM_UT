# Tips for using Monte Carlo simulation in DADM_UT   

1. Probability functions should each be in their own cell, separate from any other calculations. Formulas in other cells may then reference them. Including a probability function within a larger formula in a single cell can result in unreliable behavior.
2. The entire model you are using with Monte Carlo must be on a single Excel sheet.
3. Simulation settings are tied to the specific sheet with the associated model. When you set up the simulation settings and then run a simulation, you must be on the Excel sheet with the model.
4. You can have multiple Monte Carlo models in separate sheets in a single Excel file. Just make sure that you have the correct model sheet selected when setting up and running a simulation!
