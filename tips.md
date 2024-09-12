# Tips for using Monte Carlo simulation in DADM_UT   

1. Probability functions should each be in their own cell, separate from any other calculations. Formulas in other cells may then reference them. Including a probability function within a larger formula in a single cell can result in unreliable behavior.
2. The entire model you are using with Monte Carlo must be on a single Excel sheet.
3. Simulation settings are tied to the specific sheet with the associated model. When you set up the simulation settings and then run a simulation, you must be on the Excel sheet with the model.
4. You can have multiple Monte Carlo models in separate sheets in a single Excel file. Just make sure that you have the correct model sheet selected when setting up and running a simulation!

------------------------------------------------------------------------

# Tips for working with Decision Trees

1. There can only be one decision tree on an Excel sheet. But you can have multiple decision trees in a single Excel file, as long as they are on separate sheets.
2. You can only copy and paste decision tree elements only within a single sheet. You cannot copy and paste tree elements from one Excel sheet to another.
3. Only change the name of the sheet (the tab name at the bottom of the Excel window) before you build the decision tree or after you are done. DADM_UT relies on the sheet name to record settings and information about the tree, and if it is changed _after_ you started building the tree, some features may not work.
4. If you make a copy of a sheet with a decision tree on it, some features (like adding and deleting nodes) will not work on the copy.

