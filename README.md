# Physics-in-real-life

 Τhe physics phenomenons are probably gonna be in c++ or Python

The structure of  the first problem will be something on the more simple side.

The depiction will be very pleasant and eyecathcing.




Phase 1: Observation and Basic Kinematics (Introductory Level)
To a beginner, a bouncing ball serves as a perfect introduction to Kinematics—the branch of mechanics concerned with the motion of objects without reference to the forces which cause the motion. In this stage, we focus on tracking state changes over time using two primary vectors: Position ($\vec{s}$) and Velocity ($\vec{v}$).

Understanding Motion: The Language of Physics
Before we can understand a bouncing ball, we must establish a vocabulary. In physics, we describe motion using several fundamental quantities. Position tells us where an object is located in space, typically measured from a reference point called the origin. Displacement describes the change in position—not the path traveled, but the straight-line distance from start to finish. Velocity measures how quickly position changes, combining both speed and direction. Finally, Acceleration describes how velocity itself changes over time.

Consider dropping a ball from your hand. At the moment of release, its position is at hand height, its velocity is zero (it hasn't started moving yet), but its acceleration is already $9.81 m/s^2$ downward due to gravity. This seemingly simple scenario already involves all the fundamental kinematic quantities working together.

The Coordinate System: Choosing Your Frame of Reference
In computer graphics and physics simulations, we typically use a Cartesian coordinate system. The origin (0,0) is usually placed at the top-left corner of the screen, with the x-axis extending rightward and the y-axis extending downward. This differs from traditional mathematics, where y increases upward. Understanding your coordinate system is crucial—a positive velocity in the y-direction means downward motion in most programming environments.

Mathematical vs. Screen Coordinates
In mathematical conventions, the y-axis points upward, making gravity negative ($-9.81 m/s^2$). In screen coordinates where y increases downward, gravity becomes positive. Always verify which system you're using to avoid sign errors in your calculations.
The Geometry of the 'Bounce'
In an idealized world of Uniform Linear Motion (ULM), we assume the ball moves at a constant speed. The 'Physics' here is purely geometric and conditional. We define a boundary (the floor) and monitor the ball's coordinates. When a coordinate exceeds that boundary, we trigger a 'Reflection Event.'

<img width="510" height="512" alt="image" src="https://github.com/user-attachments/assets/006f8ed8-2c81-46a9-9c03-baa00a96b77b" />



