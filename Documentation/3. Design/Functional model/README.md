# **Functional model**

*I would like to enble makers to understand what the product and its parts are for.* 

## **What is a functional model?**

* A description of the functions performed by a product.
* An opportunity to break down a product into smaller pieces that can be more easily understood.
* At the highest level of a functional breakdown (black box view), service functions are the effects (intended by its stakeholders) of the interaction of the product with its environment.([Specification](https://github.com/OPEN-NEXT/wp2.3_template/tree/main/Documentation/2.%20Specification#specification))
* At the intermediate and lowest levels of a functional breakdown (white box view), technical functions are input-output relationships transforming matter, energy or information flows. They are expressing in a non-solution neutral way and observable from inside the product. A set of technical function is necessary for the realization of a service function.

## **Why should you define functional model?**

* A functional model helps to break down a complicated problem into simple sub-problems.
* A functional model helps to anticipate failures occurring when an intended effect of the product is no longer produced on its environment.
* A function is the main input to derive the functional requirements required to define the conditions of use of the product as well as to provide objective evidences through the validation and verification activities. 

## **How to document a functional model?**

*The documentation of technical functions, which requires adopting an internal (white box) viewpoint on the product, consists in breaking down the service function into sub-functions. The decomposition process is no more solution neutral as it requires to make a decision at every indenture level. The functional decomposition requires two modelling approaches: function tree and functional graph.*

 ### **1. Functional tree**

- **Definition:** *The functional tree is a top-down decomposition of function into sub-functions that helps to simplify the problem to solve.*

- **Comments:**

  - *A top-down and bottom up reading of the functional tree provides insight on the “how” and “why”, respectively.*
  - *The decomposition process should be stopped when technical function is sufficiently detailed to reuse, make, or buy a design solution.*
  - *The functional requirements should identify for decomposition of functions. The functional requirement includes: What we want to achieve a minimum set of requirements a system must satisfy.([Specification](https://github.com/OPEN-NEXT/wp2.3_template/tree/main/Documentation/2.%20Specification#specification))*

  ```
  - Functional requirements (FR)
    - FR1: ...
    - FR2: ...
    - ...
  ```

#### *Example of functional requirements*:
*Functional decomposition of service that ADD-ONS of XYZ cargo provides for the food producers to preserve the quality of food in* [XYZ CARGO ADD-ONS](https://projects.opennext.eu/@xyz-cargo-add-ons/xyz-cargo-add-ons)

  ```
  - Functional requirements (FR)
    - FR1: To maintain the quality of food, food producer needs to main the material at cold temperature (between 3 °C and 10 °C) for short-term preservation (3h) or long-term preservation (24h).
    - FR2: ADD-ONS shall fix the internal ADD-ONS temperature for 7 °C.
    - FR3: To create a cold ambient in the cooling down system, the ADD-ONS shall compress the low temperature and pressured gas to start the cooling cycle.
    - ...
  ```

#### *Tempalte of functional tree*:



### **2. Functional graph**


- **Definition:** *The functional graph is a multi-level logical articulation of technical functions.*

- **Comments:**

  - *Relationships between functions are in/out-going flows of matter, energy or information.*
  - *Logical AND/OR gates can be used to define concurrent or sequential functions.*
  - *Articulation of technical function can describe as input-output relationships transforming flows by using the functional modeling language in the format of the graph*
  
#### *Example 1 of functional Graph*:
*Functional graph of the relationship between technical functions for maintaining of food quality by ADD-ONS of XYZ cargo*

![Image of functional tree](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Sources/Images/Functional%20graph%20of%20XYZ%20cargo%20ADD-ONS.jpg)

> Figure 2. Articulation of relationships between technical functions 

#### *Example 2 of functional Graph*:
*The block diagram in the link below shows the flow and functions of the hardware and firmware of POCKET SCIENCE LAB(PSLab)*

[Functional diagram of Hradware and firmware of PSLab](https://github.com/fossasia/pslab-hardware#block-diagram)


### **3. Functional modelling language**

```
  - UML (Use Case diagram)
  - SysML (Block Definition, Activity, or Internal Block diagram)
  - SADT/IDEF0 
  - Functional flow block diagram.
 
  ```
  
  ### **4. Open-source functional modelling environment**

```
 
  - Papyrus
  - Modelio
  - Capella
  - etc.
  ```
