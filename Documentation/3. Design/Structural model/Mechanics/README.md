## **How to document a structural model of mechnical products?**

 ### **1. Architectural structure**

- **Definition:** *The architectural structure is a physical or logical layout of the components of a system design and their internal and external connections.*


 ```
Documentation of the architectural structure of a mechanical product should provide information including:
 
1. Specifying the kinds of components and their sub-components in the format of a tree  or graph
2. The name of modeling language for representation 
  - UML
  - SysML
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
     - Native file format
     - Standard  file format
 2. Preferable software* 
   - OpensCAD
   - Inkscape
   - FreeCAD
  ```

#### *Example of editable file formats:* 

*1. [Farmbot, Native CAD files](https://genesis.farm.bot/v1.5/Extras/cad)*

*2. [MIT Emergency Ventilator, Standard CAD files](https://e-vent.mit.edu/resources/downloads/)*


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
  

  ```
