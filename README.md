# aircraft-routing-direct
We will be replicating the work done by M.C. Barthlomew-Biggs, S.C. Parkhurts, and S.P. Wilson in their paper, Using DIRECT to Solve an Aircraft Routing Problem.
Bartholomew-Biggs, M., Parkhurst, S. & Wilson, S. Using DIRECT to Solve an Aircraft Routing Problem. Computational Optimization and Applications 21, 311–323 (2002).
Given an origin and a destination, we need to find the best intermediate waypoints connecting the two destinations.
Consider the problem in two dimensions, i.e. we need to find the ground-plan from the origin to the destination.
The ground plan must avoid no-fly zones called “threats”.
Minimize flight distance
Minimize distance flown within threats
Avoid sharp turns
Maintain minimum “leg” distance between waypoints
