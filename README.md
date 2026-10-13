# Active Suspension Control of a Four-DOF Half-Car Model 🚗📈

This repository contains MATLAB simulations for the active suspension control of a four-degree-of-freedom (4-DOF) half-car model. The project investigates the performance of advanced multivariable control techniques, specifically **LQG (Linear Quadratic Gaussian)** and **LQG/LTR (Loop Transfer Recovery)**, compared to a passive suspension system.

## 🌟 Project Overview
The model incorporates body heave and pitch dynamics, along with front and rear unsprung masses, subjected to a delayed half-sine road-bump input. The goal is to minimize body oscillations and pitch response without requiring excessive control effort.

## 🧠 Control Methodologies Applied
- **State-Space Modeling:** Mathematical representation of the 4-DOF suspension system.
- **LQR (Linear Quadratic Regulator):** Optimal state feedback control design.
- **Kalman Filtering (LQE):** Optimal state estimation in the presence of noise.
- **LQG/LTR Design:** Combining LQR and LQE, followed by Loop Transfer Recovery to enhance robustness.

## 🛠️ Simulation & Tools
- **Software:** `MATLAB`.
- **Solvers:** `ODE45` for continuous-time numerical simulation.
- **Evaluated Metrics:** Body displacement, pitch response, suspension deflection, unsprung-mass motion, and actuator forces.

## 📂 Repository Structure
*   `/src`: MATLAB `.m` files containing the system dynamics, controller design, and `ODE45` simulation scripts.
*   `/results`: Plotted comparisons demonstrating the reduced body and pitch oscillations achieved by the LQG/LTR controller relative to standard LQG and passive cases.

## ⚖️ Academic Context
*This project was developed as a comprehensive study in Multivariable Control Systems, focusing on theoretical robustness and state-estimation techniques in automotive applications.*
