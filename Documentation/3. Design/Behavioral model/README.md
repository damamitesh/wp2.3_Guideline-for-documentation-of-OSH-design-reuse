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

*Documentation of a behavioral model depends on each project and there is different type of simulation for analysis of the behavior of a product. For example, finite element analysis( FEA), computational fluid dynamics (CFD),etc.* 
*FEA uses mathematical models to understand and quantify the effects of real-world conditions on a part or assembly. CFD is a branch of fluid mechanics that uses numerical analysis and data structures to analyze  the free-stream flow of the fluid, and the interaction of the fluid (liquids and gases) with surfaces defined by boundary conditions.*
*Analysis of the behavior of a product depends on its components and its environment. So, we can not identify all types of behavioral models in this section. But, we provide a general vision of the simulation models and their implementation.* 

 ### **1. Simulation models**

- **Definition:** *A simulation model enables the designers to test whether the design specifications are met by performing computer simulations rather than experiments on the physical prototype.It promises a more comprehensive exploration of design alternatives and a better-performing final design.*


 ```
1. What minimum documentation should the simulation model provide?

  - Identify the type of simulation
    - Mechanical simulation 
    - physical simulation
    - Thermo-mechanical simulation
    - Electronical simulations
    
  - Model definition consist of 
    - Specification of geometrical model (refer to editable file format in structural model)
    - Material characteristics ( refer to structural model)
    - Initial conditions such as initial stresses, temperatures, velocities, etc. 
    - Boundary conditions can be imposed on individual solution variables such as displacements or rotations.
    - Kinematic constraints that are several of the fundamental solution variables in the model (Linear constraint equations) or multi-point constraints (General  multi-point constraints) can be defined. 
    - Interactions that are contact and other interactions between parts can be defined
    
2. How to implement the simulation model?

  - Use open-source software
    - Open Modelica
    - ADINA
  ```
   #### *Example of simulation models:* 
   
 **Example 1: [FinEtools: Finite Element tools](https://github.com/PetrKryslUCSD/FinEtools.jl)**
 
 **Example 2:** *Image below shows the simulation of the torsion of the fixed part from below and its evaluation of the reality.*
 
 ![Image of Finite element analysis](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Finite%20element%20analysis%20image.gif)
 
  
 

