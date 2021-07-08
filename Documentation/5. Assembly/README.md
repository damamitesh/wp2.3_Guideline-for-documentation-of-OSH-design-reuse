# **Assembly**

*I would like to enable makers to understand the steps of constructing a finished product from components or partially-compiled units.*

## **How to document a assembly or disassembly process?**

*Assembly instruction can guide the makers to follow the process of assembly or disassembly of components of a product.*

### **Assembly instruction** 
<details>
  <summary>Click to see the guideline!</summary>
 
 - **Definition:** *Assembly instruction could illustrate visually and with words and text how to assemble or disassemble the mechanical and electrical components of the product.*


 ```
What does include the content of assembly instruction? 

1. Features
    - What does prepare the assembly of these parts for the final product?
       - Easy attachment point for differential parts 
       - provide the parts to facilitate ability to change, and add new components easily.
       - Etc.
 2. Needed skills for assembly
 3. List of the tools for assembly or disassembly
    - Mandatory
       - Allen Key set
       - Imperial Wrench Set
       - Etc.
    - Optional
       - Laser cutter
       - Etc. 
 4. Identifying the mechanical interfaces/atachements to main body (refer to example of JPL open-source rover)
 5. Describing the machining/ fabrication if it is necessary during the assembly (refer to manufacturing)
    - Machining process
    - Sequence of process
 6. Structral assembly sequence
    - Part list for mechanical parts: is a complete list of all parts needed to build the complete product(refer to the BOM at manufacturing section)
       - Item numbers: are based on the assembly structure, that is, the order in which parts are displayed in assembly.
       - Part number or drawing number: which is a reference back to the detail drawing (Refer to the BOM) 
       - Description: is usually a part name or a complete description of parts
       - Quantity: is the number of that particular part used on this assembly. 
       - Image of each part
    - Datasheet of components for electronic parts
       - Description of features
          - Core
          - Memeories
          - Advenced connectivity
          - etc.
       - Device summry
          - Reference
          - Part number
       - How to use the component?
    - The set of steps necessary to properly assemble the parts
    - Identifyin the joining technology in each step
       - Screwing
       - Bolting
       - Soldering
       - Etc.
  
How to visualize of the assembly or disasembly process?
 1. Images 
 2. Videos 
```  
</details>

<details>
  <summary>Click to see the example!</summary>
 
*Some examples of open-source projects that include assembly instructions.*

#### *Example 1:* [Poppy Robot](https://docs.poppy-project.org/en/assembly-guides/ergo-jr/mechanical-construction.html)

#### *Example 2:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly)

#### *Example 3:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Assembly) , [Assembly instructions](https://ohai.satnogs.org/project/satnogs-rotator-v3-mechanical-assembly/hardware/) 
</details>

### Template of assembly
 
 #### 1. Features
 ...
 #### 2.Needed skills for assembly
 ...
 #### 3. List of the tools for assembly or disassembly
   * Modatory
     * ...
   * Optional
     * ...
 #### 4.Mechanical interfaces/atachements to main body
 #### 5.Describing the machining/ fabrication if it is necessary
  
  *You can use this template on the App diagram to define the machining/ fabrication.*
 
![image](https://user-images.githubusercontent.com/59058909/124918376-40148400-dff5-11eb-8c14-ab685606dc89.png)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FDescribing%20the%20machining%2F%20fabrication.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FDescribing%20the%20machining%2Ffabrication.png">Edit in diagrams.net</a>
 
 #### 1. Assembly sequences 
   * Description of different steps: ... 
   * Visualization of steps via the images and/or videos
 
 #### 2. Parts list  
   * Item numbers: ...
   * Part number: ... 
   * Description: ...
   * Quantity: ... 
   * Image of each part
 
 #### 3. Datasheet of component
 ...
 
 #### 4. Assembly tools    
 ...
 
 #### 5. Joining technology 
 ...
 
 
