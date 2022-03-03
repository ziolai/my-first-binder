# Numerical Practicum 2022 - Current Overview

## Section 1/: Common to all Homework Assignments

- Six assignments in total - 1 ECTS per assignment - 28 hours of work for students  
- in Q1: three compulsory assignments (no freedom of choice)
- in Q2: possibly elective assignments (choice assignment corresponding to course)

## Section 2/: HW1: Recap/Intro of Prerequisites in Various Parts

Recap of prerequisites: Assignment in various sections on solving boundary value problem numerically.  

1. Intro into this assignment - explain what the goals are; 
2. State problem to solve. Boundary value problem for the Poisson equation (diffusion with constant coefficient only) on the unit interval with Dirichlet and Neumann boundary conditions;
3. Generate analytical reference solution. Use either by pen-and-paper or using symbolic computations;
4. Generate numerical solution using built-in numerical method (e.g. solve-bvp) 
5. Discretize the problem in space. Introduce into finite difference method for the boundary value problem. Treatment of interior and boundary nodes. Linear system formulation: matrix and right-hand side vector. Make sure to provide sufficient references; 
6. Solve linear system using LU decomposition of the coefficient matrix; compare LU with explicit matrix inverse; 
7. Give physical interpretation of solution obtained (steady state of diffusion of drop of dye in water);  
8. Add linear reaction term. Revisit all previous steps; 
9. Add non-linear reaction term. Revisit previous steps. Recognize the problem this time to be non-linear. Identify problem as a root-finding problem in N dimensions. Compute the Jacobian. Solve non-linear system using Newton-Raphson method. Compare with reference solution. Give physical interpretation. 
10. Extend to partial differential and add transient term. Perform spatial discretization as above. Solve system of ordinary differential equation using a built-in time-stepping method; 
11. Compute average,  derivative and frequency content of the computed solution; 
12. Extend from 1D space (x) to 2D space (x,y) using finite difference method for the Poisson equation. In first step, use manufactured solutions as a reference. Use pulses a point sources or sinks in a subsequent step;  
13. Change problem set-up to meet predefined target using non-linear optimization method. Compute cost function gradient and Hessian. Solve optimization problem using built-in method; 
14. List here possibly other extensions and implementation specific issues; 

Out-of-scope: to be defined; 

References:  
1. [Finite Difference Method in Python](https://pythonnumericalmethods.berkeley.edu/notebooks/chapter23.03-Finite-Difference-Method.html)  

Deadline: September 30th; 

Formative assessment: Discussion of how assignment went after grading of assignments;




