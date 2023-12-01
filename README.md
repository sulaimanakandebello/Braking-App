# Braking-App
This is a project to build a MATLAB based app for modeling braking system of a vehicle. 

The application interface, component selection and input handling into the model is coded in the Appdesigner of MATLAB. The mathematical and contorl simulation and modeling of the braking system is done in the Simulink environment. 

The model contains subcomponents for the pedal, the transmitter, the braking hydraulics, the transmission, the brakes and the vehicle body. The input into the model is the pedal force as function of driver action and the outputs are speed, deceleration, braking torque and force, distance and braking time. 

The model can handle a quick static modeling with a constant pedal force input. There is a second tab for dynamic simulation of the system. the dynamic simlation is driven by a time series input of the pedal force. 
