# -Robotics2_JMFinalProject_Group__5-6_2025

### Submission date: May 13, 2025

### Instruction: 
- Read and comprehend the expected output for each task then perform them according to your group
designation.

### Objectives: 
- Perform Jacobian Matrix, Electro-Pneumatics and PLC experiment to 3-DOF Cartesian Manipulator.   

### Procedure:
1. Derive the Velocity Equation from Jacobian Matrix.
2. Design the electro-pneumatics in FluidSim of the 3-DOF Cartesian Manipulator with A+B+C+C-B-A- sequence.
3. Program the PLC module to control the electro-pneumatics in FluidSim of the 3-DOF Cartesian Manipulator
with A+B+C+C-B-A- sequence.
4. Provide the following as output of the experiment:
    a. Velocity Equation
    b. Electro-pneumatics Circuit
    c. PLC Program

### Documentation

*VELOCITY EQUATION*

*FLUIDSIM PROGRAM*
![image](https://github.com/user-attachments/assets/88700624-8d75-4264-8563-a0fc68271d76)

Access to PDF file of Fluidsim Program: [Robotics Finals FluidSim.pdf](https://github.com/user-attachments/files/20181231/Robotics.Finals.FluidSim.pdf)


*GXWORKS PROGRAM*
![Robotics Finals PLC-1](https://github.com/user-attachments/assets/86bb8fd9-dde7-4704-98f2-6551fd4974a5)

Acces to PDF file of GX Works: [Robotics Finals PLC.pdf](https://github.com/user-attachments/files/20181219/Robotics.Finals.PLC.pdf)

*PNEUMATIC AND PLC WIRING*
![image](https://github.com/user-attachments/assets/5b0c6570-4153-46c5-b438-db8b642e98de)

![image](https://github.com/user-attachments/assets/3bb03576-33c9-4736-88c2-a6ded8ff26c2)

*OVERALL SYSTEM CONFIGURATION*
![image](https://github.com/user-attachments/assets/40943791-89a4-421f-92b4-88a9b61d54ef)


VIDEO DEMONSTRATION 

https://github.com/user-attachments/assets/842abb0c-2c6d-45be-8c86-ba8efdf22c04



THE TEAM BEHIND THE SCENES 
![image](https://github.com/user-attachments/assets/ccdbf9f5-74b9-40b9-a403-f0e032b3e68a)

![image](https://github.com/user-attachments/assets/77e640ef-bab2-4aee-871a-1f33dfbba0e0)


### Conclusion
In this lab experiment, we controlled a 3-DOF Cartesian manipulator using GX Works code and a PLC board. To analyze the manipulator's motion and understand its velocity in relation to joint movements, we first derived the velocity equation using the Jacobian matrix, which provided a mathematical representation of the manipulator's kinematic behavior. Using FluidSIM, we designed an electro-pneumatics circuit to simulate the manipulator's operation, following the specified movement sequence: A+ (extend actuator A), B+ (extend actuator B), C+ (extend actuator C), C- (retract actuator C), B- (retract actuator B), and A- (retract actuator A). Subsequently, we programmed a PLC module using GX Works to control the electro-pneumatics circuit. The program was successfully uploaded and executed, enabling the manipulator to perform the designated sequence with precision and consistency.

This experiment produced three key outputs: the derived velocity equation, the designed electro-pneumatics circuit, and the implemented PLC program. Through this lab experiment, we enhanced our understanding of kinematics, electro-pneumatics, and PLC programming while developing our ability to integrate these components into a cohesive and functional system. Through this hands-on process, we enhanced our understanding of kinematics, electro-pneumatics, and PLC programming while developing our ability to integrate these components into a cohesive and functional system. Furthermore, the lab reinforced the importance of system modeling, simulation, and iterative design in robotics and industrial automation, laying a strong foundation for more complex control systems in future applications.
