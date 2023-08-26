# MPC

# Project Title: Design of Model Predictive Controller for DC-DC Boost Converter.

## Project Description:
- This project involves the design, implementation, and evaluation of a Model Predictive Control (MPC) strategy for a DC-DC boost converter.
- The objective is to regulate the output voltage and inductor current of converter by manipulating the duty cycle of the switching elements while adhering to specified constraints.

 ## Key Components:

#### System Modeling:

- Develop a mathematical model of the DC-DC boost converter that captures its dynamics, including input voltage, inductor current, and output voltage.
- Discretize the continuous-time model to enable prediction and optimization.

#### Prediction Model:

- Implement a prediction model in MATLAB/Simulink that employs Euler's Forward Method or more advanced numerical techniques.
- The model should predict the future behavior of the converter's state variables over a defined prediction horizon.

#### Cost Function and Constraints:

- Define a cost function that quantifies the deviation of the output voltage from the desired reference over the prediction horizon.
- Specify constraints on control inputs (duty cycle), inductor current, output voltage, and possibly other relevant variables.

#### MPC Controller Design:

- Design an MPC controller in MATLAB/Simulink that includes the prediction model, cost function, and constraints.
- Formulate the optimization problem to minimize the cost function subject to system dynamics and constraints.

#### Simulation and Testing:

- Simulate the MPC controller using various load conditions, setpoint changes, and disturbances.
- Evaluate the control performance, stability, and ability to track reference changes while adhering to constraints.

#### Parameter Tuning and Robustness:

- Fine-tune the MPC controller's parameters to achieve desired performance metrics.
- Assess the controller's robustness against uncertainties in the system model and disturbances.
