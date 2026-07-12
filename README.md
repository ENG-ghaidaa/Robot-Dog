# Robot-Dog
This project is a 3D model of a robotic dog with a clean, mechanical design. The model focuses on the body structure, joints, and overall robotic appearance without facial features or eyes, giving it a modern industrial look.
 Body and Chassis Shape
The robot has a simple rectangular chassis that provides space for the battery, controller, and motors. The design is lightweight and easy to manufacture.
<img width="462" height="190" alt="image" src="https://github.com/user-attachments/assets/23c16cde-03dd-4a6c-aebd-51c8cc9f0ccd" />

# Leg Design
Each leg consists of two links (upper and lower leg) connected by revolute joints. The rounded feet help improve ground contact and stability.
# Number of Joints and Degrees of Freedom (DOF)
Each leg has:
1 Hip joint AND 1 Knee joint 
So , The Total Degrees of Freedom is 2*4=8  
# Motor Selection
The MG996R servo motor is selected because it provides sufficient torque, is easy to control, and is suitable for lightweight robotic projects.
Preliminary Torque Calculation
Assume:
Robot mass = 2 kg 
Leg length = 0.10 m 
Weight on one leg:
F=(2×9.81)/4=4.9"  " N

# Torque at the hip joint:
T=F×L
T=4.9×0.10=0.49"  " N⋅m

With a safety factor of 2:
# Required Torque≈1.0"  " N⋅m

Therefore, the MG996R servo motor is suitable for this design.
# Stability and Center of Gravity
The center of gravity is located near the middle of the body. Keeping the battery and heavy components in the center improves balance and stability during standing and walking.
# Proposed Walking Gait
The robot uses a Crawl Gait, where one leg moves at a time while the other three legs remain on the ground. This provides stable and simple movement.
# Expected Mechanical Problems
Insufficient motor torque if the robot is too heavy. 
Joint wear after repeated use. 
Foot slipping on smooth surfaces. 
Balance problems if the weight is unevenly distributed. 

