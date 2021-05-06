## **How to document a structural model of mechnical products?**

 ### **1. Architectural structure**

- **Definition:** *The architectural structure is a physical or logical layout of the components of a system design and their internal and external connections.*

- **Comments:**

  - *An architectural structure shall specify the mechnical components and their sub-components. For example, the mechanical components a robot consist:*
    * Joint combinations
    * Brackets
    * Gear
    * motor shaft adapters
    * stepper motor
    * Etc.
  - *An architectural structure can represent in the format a tree or graph by SysML or UML, etc.*  

 ```
Documentation of architectural component should provide the information to answer the question that include:
 
 -  How should provide/make the components?  
 -  Is it possible to buy the components?  
 -  How to reproduce the components?
 -  etc. 
  ```

#### *Example 1: Architectural structure of* [Makair ventilator](https://github.com/makers-for-life/makair/blob/master/docs/Architecture/export/%5BPAB%5D%20Structure.jpg) 

![Image of Architectural structure of Makair ventilator](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Makair%20architectural%20structure.jpg)

#### *Example 2: architectural structure of* [MPS ventilator](https://www.monolithicpower.com/en/mps-open-source-ventilator)

![Image of Structural graph of PSLab](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Architecture%20of%20structural%20model.jpg)

You can use this template to define the architectural structure of your project/product.

#### *[Template of architectural structure of mechanical products](https://app.diagrams.net/#G1GCkQGQB4dYQCXf016Il42YpoE1dwrAtm)*


### **2. Modelling a design in native file format**

- **Definition:** *A file format is a standard way that information is encoded for storage in a computer file and the mechanical designs can be represented in 2D or 3D.*

- **Comments:**

  - *The native file format of design allows makers to study, modify and make an OSH design according to its license.* 
    - *The native design file formats consist:* 
       * 3D design such as STEP format
       * 2D drawings such as .cdr, .svg, .ai format
    

#### *Example of design file formats:* 
*1. [MIT Emergency Ventilator, Native CAD files (STEP format)](https://e-vent.mit.edu/resources/downloads/)*

*2. [Farmbot, Native CAD files](https://genesis.farm.bot/v1.5/Extras/cad)*


  ```
  The stuctural model consist the native file format that provide the modifying a design for designers.
  - CAD files
    - Native file format
  ```

### **3. Characteristics of the materials**

- **Definition:** *The characteristics of the materials are those that make the materials have different reactions to heat, electricity, light, force, etc.* 

- **Comments:**

  - *Materials are chosen based on factors including working properties, aesthetics, environmental impact, function, manufacturing processes, etc. It is important to choose a material fit for the purpose.*
  - *A description of material characteristics will provide information that designers could consider in selecting materials for a given application.*

```
  The material characteristics of the structural model of mechanical parts consist: 
  
  - Mechanical characteristics like hardness, elasticity, plasticity, toughness, etc. 
  - Manufacturing properties like castability, machinability rating, etc.
  - Thermal characteristics like melting point,thermal conductivity, etc.
  - Chemical properties like corrosion resistance, surface tension, etc.
  ```
  
  #### *Example of material characteristics*:
  
*Figure below shows the material characteristics of two bars due to the contact force.*

![Image of material characteristics](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Material%20characteristics.jpg)

> Source: Amr Assie, 2010.
  
 ## **How to model or modify a native design  file?**
 
 ### **Open-source structural modelling environment**

```
Different types of open-source software can be used for modeling a mechanical design or modifying a native design file including

  - OpensCAD
  - Inkscape
  - Etc.
  ```
