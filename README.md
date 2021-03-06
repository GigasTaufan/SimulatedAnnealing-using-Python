# Simulated Annealing-using-Python

Simulated annealing is a method for solving unconstrained and bound-constrained optimization problems. The method models the physical process of heating a material and then slowly lowering the temperature to decrease defects, thus minimizing the system energy. At each iteration of the simulated annealing algorithm, a new point is randomly generated. The distance of the new point from the current point, or the extent of the search, is based on a probability distribution with a scale proportional to the temperature. The algorithm accepts all new points that lower the objective, but also, with a certain probability, points that raise the objective. By accepting points that raise the objective, the algorithm avoids being trapped in local minima, and is able to explore globally for more possible solutions. An annealing schedule is selected to systematically decrease the temperature as the algorithm proceeds. As the temperature decreases, the algorithm reduces the extent of its search to converge to a minimum.

Source: [Mathworks](https://www.mathworks.com/help/gads/what-is-simulated-annealing.html)

## The Function
This is the function that I used for this program

![rumus](/img/rumus.png)

With a limit of -10 ≤ x1 ≤ 10 and -10 ≤ x2 ≤ 10
