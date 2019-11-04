# lpSolver

The software needs the following inputs from the user:

Variables:

	Enter all the variables, separated by comma. The variable type is fixed to non-negative variables.
	
Objective Type:

	Select the objective type.
	
Objective Function:

	Enter the objective function using +, -, * symbols.
	
Constraints:

	Enter constraints line by line. The constraints should have all the variables on the LEFT hand side and the constant on the RIGHT hand side. Following symbols can be used for the constraints:
	
	==    for equal to type constraint
	
	<=    for less than or equal to type constraint
	
	>=    for greater than or equal to type constraint



The software gives the following output:

The LP model:

	On the left output panel, you will see the LP that was solved.
	
The LP status:

	Optimal, unbounded, undefined(or infeasible)
	
The LP solution: 

	On the right output panel, you will see the LP solution.

For any doubts or debugging, kindly email mnusyed AT gmail DOT com.


The "lpSolver" is a GUI developed using TKINTER package. The GUI takes input from user (with the help of SYMPY) that is required to solve an LP.
Internally, PULP package is called to develop an LP. Then the LP is solved via GLPK solver. 
All repositories used in this application are open source. You are allowed to modify and reuse the GUI. 
Kindly do not remove this note from the software. 
If you find any legal issues with the software, then kindly let me know. The issues will be resolved ASAP.
