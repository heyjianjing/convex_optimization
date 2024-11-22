# Convex optimization

Main reference
* Lectures from Prof. Stephen Boyd (Stanford), Prof. Constantine Caramanis (UT-Austin)

`cvx_01`
* A note on notation
* Convex set definition
* Common convex sets
* Operations that preserve convexity
* Proper cone and generalized inequalities
* Minimum element
* Minimal element
* Inner product for matrices
* Dual norm
* Hölder's inequality as generalization of Cauchy-Schwarz
* Dual cone
* Examples of dual cone
* Separating hyperplane theorem

`cvx_02`
* Convex function definition
* Common convex functions
* Convexity by restricting function to a line
* 1st and 2nd order condition for differentiable functions
* Conditions for nondifferentiable functions
* Convexity and monotone of (sub)gradient
* Epigraph
* Jensen's inequality
* Operations that preserve convexity
* Quasiconvexity
* Log-convexity
* Conjugate function

`cvx_03`
* Optimization in standard form and explicit constraints
* Feasibility of variable
* Feasibility of optimization problem
* Locally optimal points
* Domain of optimization problem and implicit constraints
* Convex optimization in standard form
* Any local optimal is global optimal for convex problem
* Optimality criterion for differentiable objective function
* Common equivalent convex formulations
* Linear program (LP)
* Solutions of simple LPs
* Quadratic program (QP)
* Second-order cone program (SOCP)
* Semidefinite program (SDP)

`cvx_04`
* Lagrangian
* Lagrange dual function
* Domain of dual function
* Lower bound property
* Lagrange dual function and conjugate function
* Dual feasibility indicates a lower bound for original problem
* Lagrange dual problem to find best lower bound
* Implicit and explicit constraints in dual
* Weak and strong duality
* Slater's constraint qualification
* Inequality form of LP/QP and its dual
* Complementary slackness
* Karush-Kuhn-Tucker (KKT) conditions
* KKT as sufficient conditions for convex problem
* Perturbed primal and dual
* Global sensitivity
* Local sensitivity and interpretation of Lagrange multipliers

`cvx_05`
* Smooth function and bounded gradient
* Quadratic upper bound for smooth function
* Strongly convex function and quadratic lower bound

`cvx_06`
* A bound on suboptimality for smooth function
* Stronger monotone condition with co-coercivity
* A bound on suboptimality for strongly convex function
* Stronger monotone condition with coercivity

`cvx_07`
* Unconstrained optimization for differentiable convex function
* General descent method
* Requirement for search direction
* Line search for step size
* Gradient descent and 1st order approximation
* Gradient descent with ill-conditioned problem
* Convergence analysis of gradient descent for smooth and strongly convex functions
* Steepest descent method
* Search direction under arbitrary norm
* Quadratic norm search direction
* Geometric interpretation of quadratic norm search direction
* Newton step from 2nd order approximation
* Newton step as steepest descent direction under quadratic norm induced by local Hessian
* Gradient descent is not affine invariant and is sensitive to condition number
* Newton step is affine invariant
* Optimal affine transformation makes gradient descent as efficient as Newton step
* Newton decrement as a measure of proximity of function to optimal value based on 2nd order approximation
* Newton decrement is affine invariant
* Newton's method and two-phase convergence theorem
* Problem with Lipschitzness of Hessian at boundary in convergence analysis
* Some problematic functions from the persepective self-confordant functions
* Properties and convergence analysis for self-concordant functions
* Log-barrier example with gradient descent and Newton's method

`cvx_08`
* Equality constrained optimization and optimality condition
* Quadratic example and KKT matrix
* Equivalent conditions for nonsingularity of KKT matrix
* Newton step and Newton decrement with equality constraints
* Feasible points with Newton step remain feasible
* Newton's method with equality constraints
* Newton step at infeasible points
* Primal-dual interpretation
* Infeasible start with Newton's method and use of residual for line search
* Use LDLT factorization to solve KKT system of equations

`cvx_09`
* Interior point methods convert inequality constrained problem into a sequence of unconstrained or equality constrained problems
* Log-barrier function to approximate inequality constraints
* Centering problem with log-barrier function
* Central path and analytic center of polyhedron
* Equivalence between optimality condition for centering problem and minimizing Lagrangian of original problem
* Solving centering problem provides dual feasible point and lower bound of solution of original problem
* Duality gap on central path
* Solution on central path satisfies all KKT conditions except complementary slackness
* Barrier method
* Feasibility problem and finding strictly feasible starting point for barrier method
