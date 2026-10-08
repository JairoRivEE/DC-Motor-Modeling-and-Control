# DC Motor Modeling and Control Using MATLAB & Simulink

## Project Overview

This project explores the mathematical modeling, experimental characterization, and simulation of a DC servo motor using the Quanser QUBE platform.

Developed as part of ENGR 446 at San Francisco State University, the project demonstrates fundamental control systems engineering concepts through MATLAB programming and Simulink modeling.

## Objectives

- Analyze the dynamic behavior of a DC servo motor.
- Estimate motor gain and time constant using experimental data.
- Calculate physical motor parameters, including equivalent rotational inertia.
- Develop and examine motor models using MATLAB and Simulink.
- Explore the relationship between theoretical models and experimental motor responses.

## Tools and Technologies

- MATLAB
- Simulink
- Quanser QUBE Servo
- Control Systems Modeling
- Experimental Data Analysis

## Technical Approach

### 1. Experimental Motor Characterization

A voltage bump test was used to analyze the motor's speed response.

The MATLAB analysis estimates two important system parameters:

- **Steady-state gain (K):** Relates the change in motor speed to the applied voltage change.
- **Time constant (τ):** Describes how quickly the motor approaches its steady-state response.

### 2. Mathematical Modeling

Physical motor parameters were used to calculate equivalent rotational inertia.

The model includes:

- Motor resistance
- Motor torque constant
- Back-EMF constant
- Rotor inertia
- Hub inertia
- Disc inertia

### 3. Simulink Modeling

A Simulink model was developed as part of the investigation of DC motor dynamics.

The project includes the original Simulink model for further inspection and simulation.

## Project Files

- `Lab_4.1.m` — Experimental motor parameter estimation
- `Lab_4_2.m` — Physical motor parameter calculations
- `lab_4_3.slx` — Simulink model

## Skills Demonstrated

- MATLAB programming
- Dynamic system modeling
- Experimental parameter estimation
- Engineering calculations
- Simulink model development
- Control systems fundamentals

## Author

**Jairo Rivera**  
Electrical Engineering  
San Francisco State University
