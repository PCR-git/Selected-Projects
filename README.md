# Selected-Projects

This repository contains a collection of small-scale technical projects and explorations in dynamical systems, control, reinforcement learning, and simulation.

Many of these originated as coursework and were later extended or refined. They are intended as self-contained implementations and experiments rather than polished research contributions.

```
selected-projects/
│
├── decision-making/
│   ├── tree-q-learning/
│   ├── monte-carlo-rollout-policy/
│   ├── motion-planning-2d
│   └── gridworld-mdp/
│
├── dynamics-and-control/
│   ├── multibody-dynamics-locomotion/
│   ├── optimal-control-rocket/
│   └── simplified-model-of-serpentine-locomotion/
│
├── estimation-and-filtering/
│   ├── continuous-time-kalman-filter/
│   ├── discrete-time-kalman-filter/
│   └── slam-linear-systems/
│
└── graph-and-probabilistic-models/
    ├── graph-inference-and-mcmc/
    ├── dynamic-gnn-ode-expansion/
    └── self-avoiding-walks/

```

## Project Descriptions

### Decision Making
- **Gridworld MDP** — stochastic control environment with value iteration and policy analysis under noise and reward variation  
- **Monte Carlo Rollout Policy (Tic-Tac-Toe)** — simple planning via rollout-based value estimation and empirical policy improvement  
- **2D Motion Planning** — obstacle generation, collision detection, and visibility graph construction for shortest-path planning with A*  
- **Tree Q-Learning** — reinforcement learning with RRT*-style exploration, replacing ε-greedy sampling and enabling backtracking through a learned search tree  

### Dynamics and Control
- **Multibody Dynamics (Locomotion)** — multibody dynamics simulation framework using differential-algebraic equations (DAEs), with applications to robotic locomotion  
- **Optimal Control (Rocket)** — trajectory optimization via steepest descent for a nonlinear rocket model under dynamic constraints  
- **Simplified Model of Serpentine Locomotion** — My 2017 MS thesis: reduced-order modeling of serpentine locomotion; closed-form expression for optimal phase offset to maximize forward speed.

### Estimation and Filtering
- **Kalman Filtering (Continuous & Discrete)** — implementations of linear state estimation with process and observation noise  
- **SLAM (Linear Systems)** — joint state and landmark estimation using Kalman filtering and maximum likelihood updates  

### Graph and Probabilistic Models
- **Graph Inference and MCMC** — probabilistic inference on graph structures using sampling-based methods  
- **Dynamic GNN / ODE Expansion** — exploration of graph neural networks with continuous-time dynamics  
- **Self-Avoiding Walks** — simulation and analysis of constrained random walks with applications to statistical physics  
