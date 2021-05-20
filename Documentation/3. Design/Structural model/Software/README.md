*This guideline helps to understand the necessities for documentation. Also, there is a [template](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Documentation/3.%20Design/Structural%20model/Software/README.md#template) below that allows you to fill own project documentation according to content of guideline.*

## **How to document the software section of a project?**

 ### **1. Software architecture**

*The software architecture represents the repository details of all the software that is necessary for reusing and running the project.*

 ```
1. what minimum documentation should the architectural structure provide?

- A model specifying the kinds of components and their sub-components of software in the format of a tree  or graph (refer to the example below)

2. How to implement the architectural model?
 
- The name of modeling language for representation 
  - SysML (Block Definition, Activity, or Internal Block diagram)
  - UML
- The name of software for modeling the tree or graph representation
  - Papyrus
  - Modelio
  - Capella 
  ```
 
#### *Example of software architecture of* [PX4 Vision](https://docs.px4.io/master/en/concept/architecture.html#px4-architectural-overview) 


#### *[Template of software architecture](https://app.diagrams.net/?libs=general;uml#G1MlfmgE-MK0jfELJd3EfE1epv03GCdpde)*

 ### **2. Documentation of different parts of software**

 ```
This part based on the different products could include

- Description of programming algorithm   
- The source code. 
- Version of software
 ```

### *Examples:* 

*1. [Nasa-JPL](https://github.com/nasa-jpl/open-source-rover/tree/master/software)*

*2. [AmboVent](https://github.com/AmboVent-1690-108/AmboVent/tree/master/3-Software)*

*3. [Poppy project](https://docs.poppy-project.org/en/installation/)*

### Template
<details>
  <summary>Click to expand!</summary>
 
  #### 1. Documentation of software architecture
  1. A model specifying of components *([Template of software architecture](https://app.diagrams.net/?libs=general;uml#G1MlfmgE-MK0jfELJd3EfE1epv03GCdpde))*
  2. Name of modeling language
     * UML
     * ...
  3. Name of Software for modeloing the architecture
     * Online app diagram
     * ...
 
 #### 2. Documentation of different parts of software
  1. Description of programming algorithm 
     * representation of algorithm 
  2. The source code
  3. Programming software
     * Name
     * Version
 
</details>


