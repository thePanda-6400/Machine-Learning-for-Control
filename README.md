# Machine-Learning-for-Control

## Project Abstract

PID controllers are extensively used in the industry to maintain set points by measuring errors and performing corrective actions. This project aims to enhance PID controller performance by using machine learning algorithms, specifically genetic algorithms, to tune the proportional, integral, and derivative gains. A self-balancing robot was used as the test system for this project.

## Summary

The project explores the use of genetic algorithms to optimize the gains of a PID controller for a self-balancing robot. It also investigates the implementation of a Fuzzy Logic controller to compare performance improvements.

## System Specifications

### Software:
- **MATLAB**: Used for executing the genetic algorithm.
 
- **Simulink**: Used for modeling, simulating, and analyzing the dynamic system of the self-balancing robot.

## Algorithms
### Genetic Algorithm

A genetic algorithm simulates the process of natural selection to optimize PID gains. The fitness of each population is evaluated, and the best solutions are evolved over generations to achieve optimal tuning.
Fuzzy Logic

### Fuzzy logic provides an approach to handle imprecision and uncertainty in control systems. It uses degrees of truth rather than binary true/false values to maintain system stability.
## System and Algorithm Design

### Self-Balancing Robot

The self-balancing robot consists of:
- **Cart**: The wheel assembly with two wheels and a shaft.
- **Chassis**: The upper body that oscillates and needs to be kept upright.
- **Joints**:
  - Prismatic Joint for actuation.
  - Revolute Joint for measuring angular deviation.
### PID Controller

The PID controller receives feedback from the revolute joint and sends corrective signals to the prismatic joint to balance the robot.
Results and Observations

The genetic algorithm successfully optimized the PID gains, improving the stability and response time of the self-balancing robot. Results were compared between manually tuned and machine-learned PID controllers, showing significant improvements with the latter.

### Fuzzy Logic 

A Fuzzy Logic controller was also implemented and tested. Results demonstrated the effectiveness of fuzzy logic in handling complex control scenarios.
## Future Scope

Potential applications of this research include:

 Robotics, particularly in warehouse automation.
 Industrial automation for more stable control processes.
 Wind tunnel controllers for maintaining proper airflow in chaotic environments.

## Conclusion

The project demonstrates the viability of using machine learning, particularly genetic algorithms and fuzzy logic, to control dynamic systms.
