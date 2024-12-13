# Convex optimization

Main reference
* Lectures from Prof. Stephen Boyd (Stanford)

`cvx_01`
* A note on notation
* Convex set definition
* Examples of convex set
* Operations that preserve convexity
* Proper cone and generalized inequalities
* Minimum and minimal element
* Inner product for matrices
* Dual norm
* Hölder's inequality
* Dual cone
* Examples of dual cone
* Separating hyperplane theorem

`cvx_02`
* Convex function definition
* Examples of convex function
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
* Local optimal is global optimal for convex problem
* Optimality criterion for differentiable objective function
* Equivalent convex formulations
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
* Dual feasibility and lower bound for original problem
* Lagrange dual problem
* Implicit and explicit constraints in dual
* Weak and strong duality
* Slater's constraint qualification
* Inequality form of LP/QP and its dual
* Complementary slackness
* Karush-Kuhn-Tucker (KKT) conditions
* Dual residual
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
* Quadratic norm search direction and geometric interpretation
* Newton step from 2nd order approximation
* Affine invariance
* Newton decrement
* Newton's method and two-phase convergence theorem
* Self-confordant functions
* Properties and convergence analysis for self-concordant functions
* Quadratic, exponential, and log-barrier example

`cvx_08`
* Equality constrained optimization and optimality condition
* KKT equations
* Condition for nonsingularity of KKT matrix
* Newton step and Newton decrement with equality constraints
* Newton's method with equality constraints
* Newton step at infeasible points
* Primal-dual interpretation
* Newton's method with infeasible start
* Solving KKT equations using block elimination
* Equality-constrained analytic centering example (infeasible/feasible start Newton's method)

`cvx_09`
* Log-barrier function to approximate inequality constraints
* Centering problem with log-barrier function
* Central path
* Optimality for centering problem and dual feasible point for original problem
* Duality gap on central path
* Interpretation using KKT conditions
* Barrier method
* Dual feasible points near central path
* Surrogate duality gap
* Inequality-constrained LP example (feasible start Newton's method)
* Inequality- and equality-constrained LP example (feasible start Newton's method)
* Find strictly feasible initial point for LP (Phase I example with feasible start Newton's method)
* Solve LP with this initial point (Phase II example with feasible start Newton's method)
* LP example with infeasible start Newton's method
