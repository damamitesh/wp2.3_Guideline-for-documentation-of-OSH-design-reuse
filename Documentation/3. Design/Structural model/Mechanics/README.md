## **How to document a structural model of mechnical products?**

 ### **1. Architectural structure**

- **Definition:** *The architectural structure is a physical or logical layout of the components of a system design and their internal and external connections.*


 ```
Documentation of the architectural structure of a mechanical product should provide information including:
 
1. Specifying the kinds of components and their sub-components in the format of a tree  or graph (refer to example 1 and 2)
2. The name of modeling language for representation 
  - SysML (Block Definition, Activity, or Internal Block diagram)
  - UML
3. The name of software for modeling the tree or graph representation
  - Papyrus
  - Modelio
  - Capella  
  ```

*The links below show some kinds of architectural structure of open-source projects*

#### *Example 1: architectural structure of* [MPS ventilator](https://www.monolithicpower.com/en/mps-open-source-ventilator)

![Image of Structural graph of PSLab](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Architecture%20of%20mechanical%20structural%20model.jpg)

<a href="https://app.diagrams.net/#G1GCkQGQB4dYQCXf016Il42YpoE1dwrAtm" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/#G1GCkQGQB4dYQCXf016Il42YpoE1dwrAtm" target="_blank">Edit in diagrams.net</a>

You can use the files on GitHub as templates to define the architectural structure of your project/product. (see Edit As New or Edit in diagram.net above).


#### *Example 2: Architectural structure of* [Makair ventilator](https://github.com/makers-for-life/makair) 

![Image of Architectural structure of Makair ventilator](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Architectural%20structure%20of%20makair%20ventilator.jpg)

<a href="https://app.diagrams.net/#G1DN3jEDVI9DlEGjVZ8jHI2kTvyz1dFT_O" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/#G1DN3jEDVI9DlEGjVZ8jHI2kTvyz1dFT_O">Edit in diagrams.net</a>

#### *Example 3: architectural structure of* [GlasVent emergency ventilator in format of block diagram](https://onlinelibrary.wiley.com/doi/10.1002/gch2.202000046)


### **2. Modelling a design in an editable file format**

- **Definition:** *An editable file format is a standard way that information is encoded for storage and allow the makers to study, modify the geometry of a model and reuse it.* 

 ```
To reuse a design model, it should provide information consist of:

 1. Preferable 3D/2D file format
   - Editable file formats that could be:
     - Native formats such as .FCStd format of FreeCAD 
     - Neutral formats such as STEP files
 2. Preferable software* 
   - OpensCAD
   - Inkscape
   - FreeCAD
  ```

#### *Example of editable file formats:* 

*1. [Farmbot, Native CAD files](https://genesis.farm.bot/v1.5/Extras/cad)*

*2. [MIT Emergency Ventilator, Standard CAD files](https://e-vent.mit.edu/resources/downloads/)*


### **3. Characteristics of the materials**

- **Definition:** *The characteristics of the materials are those that identify the reactions of materials reactions to heat, electricity, light, force, etc.* 

  - *Selection of materials  based on factors including properties for behavioral analysis, environmental impact, manufacturing processes in design reuse.* 

```
  The material characteristics of mechanical parts consist: 
  
  1- Identifying the kind of characteristics and its properties: 
  
    - Mechanical characteristics like hardness, elasticity, plasticity, toughness, etc. 
    - Manufacturing properties like castability, machinability rating, etc.
    - Thermal characteristics like melting point,thermal conductivity, etc.
    - Electrical characteristics like electrical resistivity and conductibility, etc.
    - Chemical properties like corrosion resistance, surface tension, etc.
    
  2- Clarifying the necessary definition of each property   
  ```
  
  #### *Example of material characteristics*:
  
*Figure below shows some physical properties of superalloy base elements.*

![Image of material characteristics](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/material%20characteristics%20example.jpg)

> Source: Kutz, M. ed., 2002. Handbook of materials selection. John Wiley & Sons.
  

  ```
