# Description

- load_transfer_&_actuators.xlsx - Calculates the load transfer at peak conditions. At maximum pitch and heave, the spring rates are extracted. Subtracting them from the target roll stiffness outputs the ARB rates. Critical damping rates are then found, and the damping ratio with the minimum contact patch load variation is obtained through a 7-post rig.
- steering_torque.ipynb - Compares the steering torque required for a lap around a circuit between the LFS23 car and the ChassisSim LFS24 model, to check if the target distribution is met.
- suspenion_loads.xlsx - Uses a free-body diagram of the suspension pick-up points to discover the forces going through each control arm. Reference: https://fswiki.us/Suspension_Forces
