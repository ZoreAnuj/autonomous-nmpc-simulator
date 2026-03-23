# Autonomous NMPC Simulator

A modular simulation framework for rapid prototyping of Nonlinear Model Predictive Control (NMPC) in autonomous vehicle motion planning. It enables the development and testing of self-adaptive, stochastic, and robust control strategies in a simulated environment.

## Key Features
*   Modular architecture for easy integration of different vehicle models and controllers.
*   Implements stochastic NMPC to handle system uncertainties and disturbances.
*   Provides visualization tools for analyzing vehicle trajectories and control performance.

## Tech Stack
*   Python
*   CasADi (for symbolic optimization)
*   NumPy, SciPy
*   Matplotlib (for visualization)

## Getting Started
1.  Clone the repository: `git clone https://github.com/zoreanuj/autonomous-nmpc-simulator.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Run a basic example: `python examples/basic_simulation.py`