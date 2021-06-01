## **How to document a structural model of electrical products?**

 ### **1. Architectural structure**

- **Definition:** *The architectural structure is a physical or logical layout of the components of a system design and their internal and external connections.*

 ```
 1. What minimum documentation should the architectural structure provide?

    - A model specifying the kind of components and their sub-components in the format of a tree  or a graph (refer to example 1 and 2) such as
      - DC motor
      - A/D converter
      - DC converters  
      - Rotor
      - Sensor system
      - Motherboard
      - kit
      - Resistor
      - Transistors
      - IC
      - Sensors
      - Etc.

2. How to implement the architectural model?

  - Use modeling language for representation, such as
    - SysML (Block Definition, Activity, or Internal Block diagram)
    - UML
  - Use open-source software for modeling the tree or graph representation, such as
    - Papyrus
    - Modelio
    - Capella 
  ```

*The links below show some kinds of the architectural structure of the electrical product.*

#### *Example 1: Architectural structure of* [PX4 Vision](https://wikifactory.com/+holybro/px4-vision) 

![Image of architectural structure of PX4 Vision](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Architecture%20of%20electrical%20structural%20model.jpg)

<a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FArchitecture%20of%20electrical%20structural%20model.drawio" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FArchitecture%20of%20electrical%20structural%20model.png" target="_blank">Edit in diagrams.net</a>

You can use the files on GitHub as templates to define the architectural structure of your project/product. (see Edit As New or Edit in diagram.net above).

#### *Example 2: Architectural structure of* [PSLab](https://pslab.io/) 

![Image of Structural graph of PSLab](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Structural_graph.png)

#### *Example 3: Architectural structure of* [Open-Source-Ventilator](https://github.com/ermtl/Open-Source-Ventilator/blob/master/hardware/datasheets/A4988.pdf)

![Image of Structural graph of Open-Source-Ventilator](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Architectural%20stracture%20of%20open%20source%20ventilator.png)

#### *Example 4: Architectural structure of* [ GlasVent emergency ventilator](https://onlinelibrary.wiley.com/doi/10.1002/gch2.202000046) (refer to figure 6 of the link)


### **2. Modelling a electrical design in an editable file format**

- **Definition:** *An editable file format is a standard way that information is encoded for storage and allow the makers to study, modify the layout of circuit diagram, Printed Circuit Board (PCB) and Schematic diagram.* 

 ```
To reuse a electrical design, it should provide information consist of:

 1. Preferable file format
   - Editable file formats that could be:
     - Source formats such as .gbr, .lib format   
     - Neutral formats such as Kicad_mod, kicad_pcb
 2. Preferable open-source software 
   - Tiny CAD
   - KiCAD
   - ADINA
  ```
  

#### *Example of an editable design file formats:* 

*1. [Nasa-JPL, source files](https://github.com/nasa-jpl/open-source-rover/tree/master/electrical/pcb/arduino_uno_sheild/gerbers/rev_b)*

*2. [AmbovVent, Neutral files ](https://github.com/AmboVent-1690-108/AmboVent/tree/master/1-Electronics)*

### Template
<details>
  <summary>Click to expand!</summary>
  
  ### Documentation of structural model of electrical products
 
  #### 1. Architectural structure documentation
  1. A model specifying of components <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FArchitecture%20of%20electrical%20structural%20model.drawio" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FArchitecture%20of%20electrical%20structural%20model.png" target="_blank">Edit in diagrams.net</a>
  2. Name of modeling language
     * UML
     * ...
  3. Name of Software
     * Online app diagram
     * ...
 
 #### 2. Documentation a design in an editable file format
  1. 3D/2D file format
     * Source formats
     * Neutral formats
  2. Name of Software
     * FreeCAD
     * ...
 
</details>

