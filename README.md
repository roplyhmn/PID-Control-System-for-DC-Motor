# PID Control System for DC Motor

##Overview
This project implements a closed-loop control system using PID (Proportional–Integral–Derivative) to control the position of a ball on a beam by adjusting the angle of a DC motor-driven mechanism.
The system aims to maintain stability by minimizing the error between the desired position (setpoint) and the actual position in real-time.

##Features
- Real-time position control using PID algorithm
- Closed-loop feedback system
- Adjustable PID parameters (Kp, Ki, Kd)
- Stability improvement (reduced overshoot & steady-state error)
- Motor actuation based on feedback control

##Control System Concept
- Proportional (P): Reduces present error
- Integral (I): Eliminates accumulated error
- Derivative (D): Predicts future error for stability
The PID controller continuously adjusts the motor input to maintain system equilibrium.

##Tech Stack
- Embedded C / C++
- Microcontroller (Arduino / STM32 – adjust based on your implementation)
- Control System (PID Algorithm)
- Motor Driver & DC Motor

##Hardware Components
- Microcontroller (Arduino Uno)
- DC Motor
- Sensor ultrasonic

##System Workflow
1. Sensor reads current ball position
2. System compares with desired setpoint
3. PID controller calculates error
4. Control signal sent to motor
5. Motor adjusts board angle
6. Process repeats in real-time
