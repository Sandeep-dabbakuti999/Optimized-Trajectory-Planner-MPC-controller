# Optimized-Trajectory-Planner with MPC-controller
Trajectory planning is done for a finite distance using optimization-based trajectory planning. A model predictive controller follows it. 
The change in the trajectory is done through RL(Optional). 
## Optimized trajectory planner(Kinematic)
  A fixed track of coordinates was chosen from Foxglove. Then a trajectory is planned.
  ### Algorithm for Optimization 
   [OSQP/SQP](https://github.com/osqp/osqp)
## MPC controller(Dynamic)
  A control trajectory is formed every four seconds while the vehicle follows the reference optimal trajectory
## Reinforcement learning(RL)
  If the reference trajectory formed does not meet the required conditions. RL should provide a reference trajectory.  
