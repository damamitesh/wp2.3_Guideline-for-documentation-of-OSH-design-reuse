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

- **Definition:** *The architectural structure is a physical or logical layout of the components of a system design and their internal and external connections.*

- **Comments:**

  - *An architectural structure shall specify the component of the product such as mechanical component (motor shaft adapters, stepper motor, etc.), electrical component (DC motor, kit, resistor, etc.), etc.*
  - *An architectural structure can represent in the format a tree or graph by SysML or UML, etc.*  

 ```
  Metadata:
 It includes all of the components and their sub-components. Moreover, documentation of components of design should provide the information to answer the question that include:  
    -  how is possible to provide/make them (for example, kit, board, etc.)? 
    -  Is it possible to buy them?  
    -  How is possible to reproduce the device of electrical components? 
    -  etc. 
  ```

#### *Example of architectural structure:* [PSLab](https://pslab.io/) 

![Image of Structural graph of PSLab](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Structural_graph.png)


### **2. Modelling a design in native or standard file format**

- **Definition:** *A file format is a standard way that information is encoded for storage in a computer file and the mechanical or electrical designs can be represented in 2D or 3D.*

- **Comments:**

  - *The native file format of design allows makers to study, modify and make an OSH design according to its license. For example, the native design file formats consist of 3D design in STEP format, 2D drawings in .cdr, .svg, .ai format, Circuit diagram in Tiny CAD file format, Printed Circuit Board (PCB) of electronic projects.*
  - *The standard file formats support rapid prototyping, 3D printing, and the surface geometry of a 3D design without the possibility for modification. For example, the standard design file formats include: CAD files in an interchange format (STL format), 2D drawings (SVG or JPEG), Manufacturing export formats (G-code, STEP-NC), Circuit board design formats (Gerber RS-274X, Excellon file.*

#### *Example of design file formats:* 
*1. [MIT Emergency Ventilator CAD files](https://e-vent.mit.edu/resources/downloads/)*

*2. [Farmbot CAD files](https://genesis.farm.bot/v1.5/Extras/cad)*

  ```
  Metadata:
  
  - CAD files
    - Native file format
    - Standard file format
  ```

### **3. Characteristics of the materials**

- **Definition:** *The characteristics of the materials are those that make the materials have different reactions to heat, electricity, light, force, etc.* 

- **Comments:**

  - *Materials are chosen based on factors including working properties, aesthetics, environmental impact, function, manufacturing processes, etc. It is important to choose a material fit for the purpose.*
  - *A description of material characteristics will provide information that designers could consider in selecting materials for a given application.*

```
  Metadata:
  
  - Mechanical characteristics like hardness, elasticity, plasticity, toughness, etc. 
  - Manufacturing properties like castability, machinability rating, etc.
  - Electrical characteristics like electrical resistivity and conductibility, etc.
  - Thermal characteristics like melting point,thermal conductivity, etc.
  - Chemical properties like corrosion resistance, surface tension, etc.
  - Etc.
  ```
  
  #### *Example of material characteristics*:
  
*Figure below shows the material characteristics of two bars due to the contact force.*

![Image of material characteristics](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Material%20characteristics.jpg)

> Source: Amr Assie, 2010.
  
  ### **4. Open-source structural modelling environment**

```
  Metadata:
  
  - OpensCAD
  - Inkscape
  - Tiny CAD
  - KiCAD
  - ADINA
  - Etc.
  ```
