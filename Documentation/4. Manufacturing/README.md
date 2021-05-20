*This guideline helps to understand the necessities for manufacturing documentation. Also, there is a [template](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Documentation/3.%20Design/Structural%20model/Electronics/README.md#template) below that allows you to fill own manufacturing documentation according to content of guideline.*

# **Manufacturing**

*I would like to enable makers to understand the process by which raw materials transform into a final product.*

## **How to document a manufacturing process?**


*Manufacturing instruction can guide the makers to follow a process for remanufacturing a product. Manufacturings instructions mean full descriptions and instructions concerning raw materials usage, operating conditions, process, and quality standards to be employed in the manufacture of products.*


 ### **Manufacturing instructions can include:** 
 
 #### *1. Manufacturing technology*
 
  - **Definition:** *It means all the machinery, equipment and processes that are used to manufacture products.*


 ```
 What does include the documentation of manufacturing technology?
 
 1. Machine tool is a machine for handling or machining metal or other rigid materials, usually by
     - Turning tools
     - Milling tools
     - Grinding tools
     - Cutting tools
     - Drilling tools
     - Boring tools
     - etc. 
 2. Manufacturing process   
     - 3D printing stereo lithography
     - Wire cutting
     - Burning machining technology 
       - Laser cutting
       - Plasma cutting
     - Computerized machining technology 
       - CNC machinig 
     - Machining process technology
       - Milling
       - Drilling
       - Grinding
     - etc.
  3. Machining parameters are all those parameters that are inherent to any machining operation and should have a suitable finite value to smooth and efficient removal of materials.
     - Cutting speed
     - Feed rate (mm/sec)
     - Cutting force
     - Depth of cut
     - Etc.
     
 How to visualize the manufacturing technology? 
 
  1. Images 
  2. Videos  
 ```
 
   #### *Example 1:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly#3-machiningfabrication)
   
   #### *Example 2:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Build_Sequence) 
   
#### *2. Identifying the geometry by standard file formats*

  - **Definition:** *Standard file formats support some of the manufacturing processes and the surface geometry of a design without the possibility of modification.*

```
What does include the documentation of standard file formats for the manufacturing process?
 
  1. CAD files in an interchange format such as STL that is suitable for 3D priniting 
  2. Nominal geometry and its allowable variation by using symbolic language on 2D drawings like SVG, JPEG and PDF format that is suitable for laser cutting
  3. Manufacturing export formats such as G-code, STEP-NC is suitable for CNC machining
  4. Circuit board design formats such as Gerber RS-274X, excellon that is suitable for vector photoplotters 2D mechanical NC machines
  ``` 

#### *Example 1:* [Automated Tea Infuser, Standard file (STL format)](https://wikifactory.com/+fablabbratislava/automated-tea-infuser/contributions/3f2c490)

#### *Example 2:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Specifications), [2D drawing file](https://wiki.satnogs.org/File:C1001.png)


#### *3. Material selection*

 - **Definition:** *Material selection is a step in the process of designing any physical object. The main goal of material selection is to use the critical requirements of each part to define the performance requirement of the material.*

```
What does comprise teh documentation of material selection?

 1. Identifying the type of material
    - Metal
    - Plastic
    - Composite
    - Ceramic
    - etc.
2. Identifying the characteristics of the material for manufacturing (refer to structural model)
3. Environmental impacts
   - recyclability
   - Properties  
```

#### *6. Post-processing and its tool kit*
 
 - **Definition:** *To achieve the right properties such as surface quality, geometrical accuracy and mechanical properties, the post processing is essential.* 
 
   ```
   What does contain the documentaion of post-processing?
   
   1. The name of post-processes and their sequence including 
      - Sanding after 3D printing
      - Cold welding
      - Gap filling
      - blasting
      - Polishing
      - Priming and painting
      - Etc.

    How to visualize the post-processing?
    
    1. Images 
    2. Videos  
   ```
   #### *Example: [Post processing for FDM printed parts](https://www.3dhubs.com/knowledge-base/post-processing-fdm-printed-parts/#introduction)*
   
#### *7. Bill of material (BOM)*

 - **Definition:** *A bill of materials (BOM) is a comprehensive list of parts, items, assemblies, and other materials required to create a product, as well as instructions required for gathering and using the required materials.*

```
What does consist the bill of material?

   1. Part number
   2. Item name
   3. Description
   4. Quantity
   5. Unit of measure
   6. Procurement type
   7. Cost
   8. BOM notes
   ```

 #### *Example: [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/bill_of_materials)*


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

