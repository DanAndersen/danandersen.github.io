---
title: "GPU-Accelerated 3D Ant Colony Simulation and Visualization"
excerpt: "Final project for Purdue CS535<br/><img src='/images/gpu-ant-sim.gif'>"
collection: projects
---

<img src='/images/gpu-ant-sim.gif'>

[Project available on GitHub](https://github.com/DanAndersen/gpu-ant-sim)

This is the final project I did during my first semester of graduate school, for Purdue University’s Fall 2014 [CS535 (Interactive Computer Graphics)](https://www.cs.purdue.edu/homes/aliaga/cs535-14/index.htm) course.

Ant colony optimization algorithms are useful for pathfinding, such as in robotics and distributed networks. In this simulated scenario, a collection of ants can converge on common solutions to finding nearby food, despite each ant only having knowledge of its immediate surroundings. This particular quality makes ant colony simulation suitable for parallelization and GPGPU.

The basic setup of the simulation is that ants wander randomly from a central nest point, laying a pheromone trail behind them. They pick up food when they encounter it and return it to the nest. Other ants will follow existing trails, strengthening them over time.