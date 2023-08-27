# Overview
This repository contains the implementation of a Model Predictive Controller (MPC) for a DC/DC Boost Converter. The project aims to achieve desired reference tracking and minimum ripple over the inductor current and output voltage of the converter. The reference tracking is achieved using the Model Predictive Control technique, while overshoot is regulated using a PID controller.
# Features
## Model Predictive Control: 
 Amongst all existing control techniques, the Model Predictive Control 
(MPC) has emerged as a promising solution for power 
converter control. The flexibility in selection of design 
parameters of MPC makes it suitable for different applications 
of boost converter.The voltage 
tracking by MPC controller is 6 times faster than PID 
controller.
## Boost Converter
With the widespread applications of boost converter and 
its non-linear and non-minimum phase behaviour, the 
requirement of its controller is not only to maintain the stable 
output but also to handle the plant disturbances and model 
uncertainty.
# Simulink Implementation:
The simulation work is performed using MPC toolbox in 
MATLAB/Simulink platform. 
# Usage
Open the Simulink model to explore the control system setup.
Observe how the Model Predictive Controller and PID Controller regulates the inductor current ans output voltage with desired tracking and minimum ripple.
Adjust control parameters, reference values.
Run simulations to visualize the control strategies' impact on current and voltage regulation.
