# **Structural model**

*I would like to enable makers to understand physical structure of the product and their components.* 

## **What is a structural model?**

* A structure is a description of the components (the combination of parts) of a product and their relationships.
* An opportunity to specify the geometric elements, dimensions, topology, and other physical properties of the product.
* The structures are the potential solutions (concepts) as the result of the conceptual design phase.
* The structural model comprises the set of mechanics theories that obey physical laws required to study and predict the behavior of structures.


## **Why should you define structural model?**

* A structural model helps to describe the geometric elements (design feature, dimensions, constraints, etc.), topology (assembly constraint between components, tolerances, components mating conditions, etc.), and characteristics of the product.
* A structural model helps to decide the physical form of the product and its components to ensure that the structure is fit for its intended purpose. 
* Structural model provides users with a physical model of the product, components, and characteristics of the material at the design phase that enable the stakeholder to understand the geometry, material reaction to external factors, etc.
* The structural model ensures that the structures are safe and fulfill the functions for which they were built.

## **How to document a Structural model?**


 ### **1. Architectural structure**

- **Definition:** *Architectural structure is a physical or logical layout of the components of a system design and their internal and external connections.*

- **Comments:**
 - *An architectural structure shall specify the component of product such as mechanical component (motor shaft adapters, stepper motor, etc.), electrical component (DC motor, kit, resistor, etc.)*
 - *An architectural structure can represent in format a treeor graph by SysML or UML, etc.*


  ```
  Metadata:
  
 It includes all of the components and their sub-components. Moreover, documentation of components of design should provide the information to answer the question such as:  
  
    -  how is possible to provide/make them (for example, kit, board, etc.)? 
    -  Is it possible to buy them?  
    -  How is possible to reproduce the device of electrical components? 
    -  etc. 
  ```



#### *Example of architectural structure:* [PSLab](https://pslab.io/) 

![Image of Structural graph of PSLab](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Functional%20tree%20of%20XYZ%20Cargo%20ADD-ONS%20.jpg)

### **2. Implementation of CAD file**

- *Use the original design file format (native file) to facilitate the modification and making the design of OSH reuse such as 3D designs that can be 3D printed (STEP format), 2D drawings, Circuit diagram and PCB of electronic projects.*
- *Use the standard file format to describe the geometry such as CAD files in interchange format (STL format), 2D drawings (SVG, cdr or JPEG), Manufacturing export formats (G-code, STEP-NC), Circuit board design formats (Gerber RS-274X, Excellon file)* 

- **Definition:** 

- **Comments:**

  - 

  ```
  Metadata:
  
  - 
  ```

### **3. Characteristics of the materials **


- **Definition:** *The characteristics of the materials are those that make the materials have different reactions to heat, electricity, light, force, etc.* 


```
  Metadata:
  
  - Mechanical characteristics (plasticity, toughness, etc.)
  - Electrical characteristics (electrical resistivity and conductibility, etc.)
  - Thermal characteristics (melting point, etc.)
  - Etc.
  ```
  
  ### **4. Structural modelling environment**

```
  Metadata:
  
  - OpensCAD
  - Inkscape
  - Tiny CAD
  - KiCAD
  - ADINA
  - Etc.
  ```
