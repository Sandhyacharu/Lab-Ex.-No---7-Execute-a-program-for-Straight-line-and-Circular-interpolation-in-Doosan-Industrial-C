# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.
## Program:
![image](https://user-images.githubusercontent.com/75235167/206196691-372cae70-bac0-4f6c-aee0-9d4874964aeb.png)
![image](https://user-images.githubusercontent.com/75235167/206196760-bca4954a-3b7a-4419-b4a6-e727cc68d113.png)
![image](https://user-images.githubusercontent.com/75235167/206196835-ea000c38-34c4-4111-812d-2d38b5bb70b9.png)
![image](https://user-images.githubusercontent.com/75235167/206196892-4c320441-7727-40b9-b4d2-4085e0135d90.png)
![image](https://user-images.githubusercontent.com/75235167/206196953-ce0069d7-1672-4fcd-a57a-3223f058dffe.png)

### Linear Interpolation
![image](https://user-images.githubusercontent.com/75235167/206197040-c8ffe16b-1e44-45b1-a856-22efd029dba7.png)

### Circular Interpolation
![image](https://user-images.githubusercontent.com/75235167/206197149-dfc83880-3744-434d-97eb-531d495860e5.png)

## output
### Linear Interpolation:
![image](https://user-images.githubusercontent.com/75235167/206197237-92b1f7c7-e929-4bcf-85be-a34dff7eca68.png)

### Circular Interpolation:
![image](https://user-images.githubusercontent.com/75235167/206197402-fa5ee1ea-2169-4ec7-9b9d-edaa1a9cc938.png)

### Results 
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.


 
