---
title: Research
---

## 1. Motion Planning

We develop efficient trajectory optimization approaches for autonomous vehicles and robot swarms.

Applications of autonomous robots in dynamic, uncertain environments, such as crowded traffic, overwhelmed workspace, or unexplored wilderness, has posed significant challenges to the design of motion planning algorithms. We develop efficient trajectory optimization approaches for autonomous vehicles to drive in a smooth and safe manner in structured traffic environments, and for robot swarms to efficiently coordinate and safely navigate in unknown environments.

{{< image src="images/research/r1.png" style=""  >}}

## 2. Active Sensing

We develop informative-theoretic trajectory planning approaches for mobile robots to actively search and track moving targets.

Active sensing refers to using autonomous robots to proactively explore an unknown environment or gather information of object states, and it holds great potential for both civil and military applications, such as search and rescue, environmental monitoring, surveillance and reconnaissance. In the active sensing, both motion planning and perception are inherently coupled in that trajectories determine the informativeness of observations, and the observations in turn guide the trajectory generation. The abilitiy to generate informative paths/trajectories is the key factor in successful active sensing.

Among various tasks of active sensing, we focus on target search and tracking using autonomous robots. We develop informative-theoretic trajectory planning approaches for mobile robots to actively search and track moving targets, the motion models of which can be linear, nonlinear, or even unknown a priori.

{{< image src="images/research/r2.png" style=""  >}}

## 3. Distributed Filtering

We propose a measurement dissemination-based distributed Bayesian filter for nonlinear estimation.

**Distributed filtering** using multiple mobile robots has many important applications such as environmental monitoring, SLAM, and target localization. While significant achievements have been made for distributed linear filtering, the counterparts for nonlinear filtering techniques fall short.

We propose a measurement dissemination-based distributed Bayesian filter for nonlinear estimation of target position under either fixed or time-variant communication topologies. Such method has been shown to generate consistent estimation and fast convergence performance.

{{< image src="images/research/r3.png" style=""  >}}

## 4. Human Robot Collaboration

We are interested in enabling robots to collaborate with humans as peers.

**Intention-Aware Robots** Human-robot Interaction (HRI) has been an increasingly popular research area due to the boom in personal and industrial robots. We are especially interested in enabling robots to collaborate as peers with the human. On one hand, we utilize Bayesian inference approach to help robots identify human’s intention and then provide assistance accordingly. On the other hand, we model how human anticipates the collaborative robot’s plan based on the partial actions that the robot has made. These two aspects close the interaction loop between human and robot and can be useful for developing algorithms to improve human-robot collaboration.

**Companion Robot** With robots stepping into daily life of human beings, various applications for improving human life qualify has been envisioned. We are interested in enabling robots to work as companions of humans, walking with a target human while carrying items for the human. Especially, we have developed a trajectory planning algorithm for robots to autonomously follow a target human, using onboard cameras.​​Due to the uncertainty in human’s motion, we proposed a Parallel Interacting Multiple Model-Unscented Kalman Filter (PIMM-UKF) approch for human motion estimation and prediction. Based on the predicted human states, an MPC path planner is developed to produce safe and comfortable following trajectory of the robot.

{{< image src="images/research/r4.png" style=""  >}}
