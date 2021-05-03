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
  - *The functional requirement describes the achievement of the minimum set of requirements a system must satisfy.([Specification](https://github.com/OPEN-NEXT/wp2.3_template/tree/main/Documentation/2.%20Specification#specification))*

#### *Example of functional requirements*:
*In below, we describe the functional requirement that ADD-ONS of XYZ cargo provides for the food producers to preserve the quality of food [XYZ CARGO ADD-ONS](https://projects.opennext.eu/@xyz-cargo-add-ons/xyz-cargo-add-ons).*


  ```
  - In this example, we assumed a refrigerator on the ADD-ONS could help the food producers to cool down and preserve the temperature of foods. So, we defined some functional requirements (FR) based on this assumption that consist:
 
    - FR1: To maintain the quality of food, food producer needs to main the material at cold temperature (between 3 °C and 10 °C) for short-term preservation (3h) or long-term preservation (24h).
    - FR2: ADD-ONS shall fix the internal ADD-ONS temperature for 7 °C.
    - FR3: To create a cold ambient in the cooling down system, the ADD-ONS shall compress the low temperature and pressured gas to start the cooling cycle.
    - FR4: the cooling down system shall control the pressure of exit hot gas 
    - FR5: the hot and pressured exit gas needs to meet the cooler external ambient temperature to become a liquid.
    - ...

  ```

#### *Example and template of functional tree*:

*The decomposition of technical functions creates a functional tree and, the technical functions are defined based on the functional requirements. Functional tree of mentioned example about the refrigerator on the ADD-ONS represented in the link below and, you can use it as a template to define the functional tree of your project/product.*

#### *[Template of functional tree](https://app.diagrams.net/#G1EqpAVkNAmx8KzblQqgSOSND7bq5UQ069)*


### **2. Functional graph**

- **Definition:** *The functional graph is a multi-level logical articulation of technical functions.*

- **Comments:**

  - *Relationships between functions are in/out-going flows of matter, energy or information.*
  - *Logical AND/OR gates can be used to define concurrent or sequential functions.*
  - *Articulation of technical function can describe as input-output relationships transforming flows by using the functional modeling language in the format of the graph*
  
#### *Example 1 and template of functional graph*:
*Functional graph of the relationship between technical functions for maintaining food quality by ADD-ONS of XYZ cargo based on the functional tree. This template can be used as a template to define the technical graph of your project/product.*

#### *[Template of functional graph](https://app.diagrams.net/?libs=general;er#G1Vu8S5Zbqh19NMXCAXzxuCz5O-CRGU6Mm)*


#### *Example 2 of functional Graph*:
*The links below show some functional block diagrams of kinds of open-source projects*

* [Functional diagram of Renesas’ ventilator](https://www.rs-online.com/designspark/ventilator-design-solution-from-renesas-electronics)

* [Functional diagram of GlasVent emergency ventilator](https://onlinelibrary.wiley.com/doi/10.1002/gch2.202000046)

* [Functional diagram of MPS Open-Source Ventilator](https://www.monolithicpower.com/applications/medical/ventilator-open-source.html)

* [Functional diagram of Open-Source-Ventilator](https://github.com/ermtl/Open-Source-Ventilator/blob/master/hardware/datasheets/A4988.pdf)


## **How to express and draw a functional model?**

### **Functional modelling language**

*Functional modelling languages is any artificial language that can be used to express information or knowledge or system in a structure that is defined by a consistent set of rules. These functional modeling languages help to represent the functional tree and graph.* 

```
  - UML (Use Case diagram)
  - SysML (Block Definition, Activity, or Internal Block diagram)
  - SADT/IDEF0 
  - Functional flow block diagram
  -Etc.
  ```
  
  ### **Open-source functional modelling environment**

*The open-source software can be used to draw the functional models through the representation by using the functional modeling language.*

```
  - Papyrus
  - Modelio
  - Capella
  - Etc.
  ```
