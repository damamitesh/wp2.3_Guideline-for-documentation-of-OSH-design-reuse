# **Behavioral model**

*I would like to enable the makers to understand the analysis of the physical behavior of a product to support the decision made at the latter stages of design.* 

## **What is a behavioral model?**

* An opportunity to describe the behavior a product when it receives a stimulus.
* The behavior model could be the mathematical description of the physical product.
* The behavior model is the physical interactions between the components of a design as well as between the design and its environment. An artifact exhibits certain behaviors not only by the change or maintaining of its physical state but also by several interactions that take place inside the artifact, as well as with its environment.


## **Why should you define behavioral model?**

* The behavioral model identifies the properties for understanding the calculation, simulation, component, and environment of the product.
* Behavior model describes how the artifact implements its function and is managed by engineering principles and physical rules that are included in a behavioral model.  
* The behavioral model could provide the simulation of any given physical phenomenon using numerical techniques.   

## **How to document a behavioral model?**

 ### **1. Simulation models**

- **Definition:** *A simulation model enables the designers to test whether the design specifications are met by performing computer simulations rather than experiments on the physical prototype.It promises a more comprehensive exploration of design alternatives and a better-performing final design.*


 ```
Documentation of simulation model consists:

1. Identify the type of simulation
    - Mechanical simulation 
    - physical simulation
    - Thermo-mechanical simulation
    - Electronical simulations
2.  Model definition consist of 
    - Specification of geometrical model (refer to editable file format in structural model)
    - Material characteristics ( refer to structural model)
    - Initial conditions such as initial stresses, temperatures, velocities, etc. 
    - Boundary conditions can be imposed on individual solution variables such as displacements or rotations.
    - Kinematic constraints that are several of the fundamental solution variables in the model (Linear constraint equations) or multi-point constraints (General  multi-point constraints) can be defined. 
    - Interactions that are contact and other interactions between parts can be defined
3. The name of software
  - Scilab
  - Open Modelica
  - ADINA
 
  ```
 #### *Example of Virtual prototype:* 
 *Analysis of the physical phenomenon of product that allows showing a virtual representation or evaluation of the reality.*
 
 ![Image of Finite element analysis](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Finite%20element%20analysis%20image.gif)
 
 #### *Example of Virtual prototype: [Tensor Mechanics Module](https://mooseframework.inl.gov/modules/tensor_mechanics/index.html)*


  
 ### **2. Kinematic models**
 
 - **Definition:** *The kinematic model studies the motion of a mechanism regardless of forces and torque that cause it.*

- **Comments:**

  - *The "kinematics" generally refers to the study of properties of motion-- position, velocity, acceleration, etc.-- without any consideration of why those quantities have the values they do. "Dynamics" is concerned with the relationship between the forces acting on a mechanism and the accelerations they produce. "Statics" means a study of forces in equilibrium without consideration of changes over time.*
  - *The kinematic model can be represented as a tree structure. The tree describes the kinematic chain, i.e., the connection of links with joints, and the inter-dependencies of these links.* 
  - *In design of robot, kinematic model allows to compute the position and orientation of robot manipulator's end-effector relative to the base of the manipulator as a function of the joint variables.*
  
 #### *Example 1: [Arduino IoT Robotic Arm](https://www.hackster.io/aerdronix/arduino-iot-robotic-arm-5a4401)*

 #### *Example 2: [Compas FAB](https://gramaziokohler.github.io/compas_fab/latest/examples/02_description_models/01_kinematic_model.html)*

```
 
   It includes the description of the kinematic model in dynamic and statics form and representation of the structure of the kinematic model (Refer to example 1 and 2)
  
  - Represenation of kinematic model   
    - Description of dynamic model 
    - Description of static model
  ```

