## **How to document a structural model of electrical products?**

 ### **1. Architectural structure**

- **Definition:** *The architectural structure is a physical or logical layout of the components of a system design and their internal and external connections.*

- **Comments:**

   - *An architectural structure shall specify the electricam components and their sub-components. For example, the electrical components a robot consist:*
     * DC motor
     * A/D converter
     * DC converters  
     * Rotor
     * Sensor system
     * Motherboard
     * kit
     * Resistor
     * Transistors
     * IC
     * Sensors
     * Etc.
  - *An architectural structure can represent in the format a tree or graph by SysML or UML, etc.*  

 ```
Documentation of architectural component should provide the information to answer the question that include:
 
 -  How should provide/make the components (for example, kit, board, etc.)?  
 -  Is it possible to buy the components?  
 -  How to reproduce the device of electrical components?
 -  etc. 
  ```

#### *Example of Architectural structure of* [PX4 Vision](https://wikifactory.com/+holybro/px4-vision) 

![Image of architectural structure of PX4 Vision](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Architecture%20of%20electrical%20structural%20model.jpg)

You can use this template to define the architectural structure of your product.

#### *[Template of architectural structure of electrical products ](https://app.diagrams.net/#G1oI6ne1JC-2uzSOeJaEgVNyJSjEN41-Xh)*




### **2. Modelling a design in native or standard file format**

- **Definition:** *A file format is a standard way that information is encoded for storage in a computer file and the mechanical or electrical designs can be represented in 2D or 3D.*

- **Comments:**

  - *The native file format of design allows makers to study, modify and make an OSH design according to its license. 
    - *The native design file formats consist:* 
       * Printed Circuit Board (PCB)such as .gbr, .lib format 
       * Schematic diagram 
       * Etc.
  

#### *Example of native design file formats:* 

*1. [AmbovVent](https://github.com/AmboVent-1690-108/AmboVent/tree/master/1-Electronics)*

*2. [Nasa-JPL](https://github.com/nasa-jpl/open-source-rover/tree/master/electrical/pcb/arduino_uno_sheild/gerbers/rev_b)*


  ```
  
  The stuctural model of electronic products consist the native file format that provide the modifying for designers.
  - CAD files
    - Native electronic file format
 
  ```

### **3. Characteristics of the materials**

- **Definition:** *The characteristics of the materials are those that make the materials have different reactions to heat, electricity, light, force, etc.* 


```
  The material characteristics of the structural model of electrical parts consist
  
  - Electrical characteristics like electrical resistivity and conductibility, etc.
 
  ```
  
  
  ### **Open-source structural modelling environment**

```
Different types of open-source software can be used for modeling a electrical design or modifying a native design file including

  - Tiny CAD
  - KiCAD
  - ADINA
  - Etc.
  ```
