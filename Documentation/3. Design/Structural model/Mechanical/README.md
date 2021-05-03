## **How to document a mechanical structural model?**

 ### **1. Architectural structure**

- **Definition:** *The architectural structure is a physical or logical layout of the components of a system design and their internal and external connections.*

- **Comments:**

  - *An architectural structure shall specify the mechnical components and their sub-components. For example, te mechanical component a robot consist:*
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

#### *Example of architectural structure:* [PSLab](https://pslab.io/) 

![Image of Structural graph of PSLab](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Structural_graph.png)


### **2. Modelling a design in native or standard file format**

- **Definition:** *A file format is a standard way that information is encoded for storage in a computer file and the mechanical or electrical designs can be represented in 2D or 3D.*

- **Comments:**

  - *The native file format of design allows makers to study, modify and make an OSH design according to its license. For example, the native design file formats consist of 3D design in STEP format, 2D drawings in .cdr, .svg, .ai format, Circuit diagram in Tiny CAD file format, Printed Circuit Board (PCB) of electronic projects.*
  - *The standard file formats support rapid prototyping, 3D printing, and the surface geometry of a 3D design without the possibility for modification. For example, the standard design file formats include: CAD files in an interchange format (STL format), 2D drawings (SVG or JPEG), Manufacturing export formats (G-code, STEP-NC), Circuit board design formats (Gerber RS-274X, Excellon file.*

#### *Example of design file formats:* 
*1. [MIT Emergency Ventilator, Native CAD files (STEP format)](https://e-vent.mit.edu/resources/downloads/)*

*2. [Farmbot, Native CAD files](https://genesis.farm.bot/v1.5/Extras/cad)*

*3. [Automated Tea Infuser, Standard file (STL format)](https://wikifactory.com/+fablabbratislava/automated-tea-infuser/contributions/3f2c490)*

*4. [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Specifications), [2D drawing file](https://wiki.satnogs.org/File:C1001.png)*


  ```
  
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
  
  ### **Open-source structural modelling environment**

```
  
  - OpensCAD
  - Inkscape
  - Tiny CAD
  - KiCAD
  - ADINA
  - Etc.
  ```

