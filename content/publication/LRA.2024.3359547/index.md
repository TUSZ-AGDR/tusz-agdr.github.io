---
title: "An efficient linear programming‑based time‑optimal feedrate planning considering kinematic and dynamics constraints of robots"

authors:
  - Guanghui Liu
  - Qiang Li
  - Bohan Yang
  - Hualiang Zhang
  - Lijin Fang

author_notes:
  - 'School of Artificial Intelligence, Shenyang University of Technology, Shenyang, China.'
  - 'College of Big Data and Internet, Shenzhen Technology University, Shenzhen, China.'
  - 'State Key Laboratory of Robotics, Shenyang Institute of Automation, Chinese Academy of Sciences, Shenyang, China.'
  - 'State Key Laboratory of Robotics, Shenyang Institute of Automation, Chinese Academy of Sciences, Shenyang, China.'
  - 'Faculty of Robot Science and Engineering, Northeastern University, Shenyang, China.'

date: "2024-01-29T00:00:00Z"
doi: "10.1109/LRA.2024.3359547"
publishdate: "2024-01-29T00:00:00Z"

publication_types: ["article‑journal"]

publication: In *IEEE Robotics and Automation Letters*
publication_short: In *IEEE Robotics Automation Lett.*

abstract:
  This letter investigates the time-optimal trajectory generation for a six-degrees-of-freedom articulated robot moving along a given parametric path. In the generation procedure, besides the velocity, acceleration, and joint torque, the jerk is also constrained to enhance the smoothness of the robot's motion. Meanwhile, the trajectory generation is formulated as a convex optimization problem with a nonlinear objective function and constraints. Then, the problem is solved with a typical linear programming (LP) approach by discretizing the continuous path into many sampling points. Specifically, the time-optimal problem is formulated as maximizing the sum of the velocities at all discrete points instead of minimizing time. Moreover, the time-optimal trajectory generation with nonlinear jerk constraints is decoupled into two sub-LP problems, and the solution of the first sub-LP is employed to scale the nonlinear constraints. Finally, the proposed method is verified through robotic experiments. The results indicate that the smoothness of the generated trajectory improves significantly. Also, the trajectory planning accuracy and computational efficiency are increased by 36% and 62%, respectively.

tags: ["time-optimal-trajectory", "feedrate-planning", "linear-programming", "jerk-constraint", "robot-dynamics"]

url_pdf: "https://ieeexplore.ieee.org/abstract/document/10415470/"
---