# **Manufacturing**

*I would like to enable makers to understand the process by which raw materials transform into a final product.*

## **How to document a manufacturing process?**


*Manufacturing instructions can guide the makers to follow a process for replicating a product. Manufacturing instructions mean full description and instructions concerning raw material, operating conditions, and process to be employed for the manufacture and assembly of the product.
The bill of marterial (BOM) is the document that describes all the components and there reference. If the component is to be purchased one should find all the information regired to buy the part. If the part is to be manufactured one should find all the description of the manufacturing instructions as described below.*

### *1. Bill of material (BOM)*
<details>
  <summary>Click to see the guideline</summary>
 
 - **Definition:** *A bill of materials (BOM) is a comprehensive list of parts, items, and other materials required to create a product, as well as instructions required for gathering and using the required materials.*

```
What should includes the bill of material (not limited to...)?

   1. Part number
   2. Item name
   3. Description
   4. Quantity
   5. Unit of measure
   6. Manufacturer name
   7. Seller name
   8. Procurement type
   9. Cost
   10. BOM notes
   11. ...
   ```
</details>

<details>
  <summary>Click to see the example</summary>
 
 #### *Example: [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/bill_of_materials)*
  
![image](https://user-images.githubusercontent.com/59058909/124725125-e8025280-df0c-11eb-9be0-67c3670dca17.png)

*BOM of JPL open-source Rover*

</details>

### BOM Template

 #### Bill of material
 
 *You can use this template on the App diagram to define bill of material of your project/product.*
 
 ![image](https://user-images.githubusercontent.com/59058909/124730192-69f47a80-df11-11eb-84ee-73d1ebbc0061.png)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FBOM%20template.drawio" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FBOM%20template.png">Edit in diagrams.net</a>
 
 ### *2. Manufacturing instructions should include:*
 
 #### *2.1. Manufacturing technology*
  <details>
  <summary>Click to see the guideline!</summary>
 
  - **Definition:** *It means all the machinery, equipment and processes that are used to manufacture products.*

 ```
 What should include the documentation of manufacturing technology?
 
 Machines and processes used 

   1. CNC machine tools for handling or machining metal or other rigid materials
     - Milling machines
     - Cutting, Drilling machines
    
   2. Other common manufacturing tools
     - 3D printing (FDM, SLS...) (https://en.wikipedia.org/wiki/3D_printing)
     - Burning machining technology 
       - Laser cutting
       - Plasma cutting
     - Wire cutting (EDM)
 
   3. Finishing and its tool kit: to achieve the right properties such as surface quality, geometrical accuracy and mechanical properties, the finishing is essential. 
     - Sanding after 3D printing
     - Cold welding
     - Gap filling
     - Blasting
     - Polishing
     - Priming and painting
     - Heat treatments
     - Etc.
  
 How to visualize the manufacturing technology? 
  1. Images 
  2. Videos  
 ```
 </details>
 
  <details>
  <summary>Click to see the examples!</summary>
 
   #### *Example 1:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly#3-machiningfabrication)
   
   #### *Example 2:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Build_Sequence) 
  </details>
 
   #### Template of Manufacturing technology
   
  1. Machines and processes used
   * CNC machine tools
     * ...
   * Other common manufacturing tool
     * ...
   * Finishing
     * ...
  2. Vizualization via images and videos
 
 
   #### *2.2. Machining parameters for each process*
   
<details>
  <summary>Click to see the guideline!</summary>
 
  - **Definition:** *Machining parameters are all those parameters that are inherent to any machining operation and should have a suitable finite value to smooth and efficient removal of materials. It is necessary to mention them in the documentation to allow an easy replication.*
  
   ```
 What should include the documentation of machining parameters?

     - Cutting speed
     - Feed rate 
     - Cutting force
     - Depth of cut
     - Etc.
   ```    
   </details>
 
 
<details>
  <summary>Click to see the examples!</summary>
 
#### *Example of 3D printer parameters* 

 * Extruder setting 
     * Extrusion multiplier
     * Retraction distance 
     * Retraction speed 
     * Coasting
 * Layer setting
     * First layer height
     * First layer speed
 * Infill setting
     * Internal/Eternal fill pattern
</details>
 
  #### Template of machining parameters
  
  *You can use this template on the App diagram to define bill of material of your project/product.*
 
![image](https://user-images.githubusercontent.com/59058909/124744988-97482500-df1f-11eb-8a3a-0474185083b3.png)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FMachining%20parameters.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2Fmachnining%20paramters.png">Edit in diagrams.net</a>

 #### *2.3. Manufacturing sequences and instructions*
 <details>
  <summary>Click to see the guideline!</summary>
 
  - **Definition:** *Manufacturing sequences refer to step-by-step machining and manufacturing processes in a target-oriented arrangement to enable highly efficient manufacturing.*

```
What does include the documentation of manufacturing sequences and instructions?
 
  1. Name of related machine of each each step
  2. Describing the sequence of machining process of each step
    - Drilling
    - Cutting
    - Milling
    - etc.
  3. Describing the needed shape on the workpiece according to standard file format( refer to manufacturing file format)
  ``` 
</details>

 <details>
  <summary>Click to see the examples!</summary>
 
   #### *Example 1:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly#3-machiningfabrication)
  </details>
  
   #### Template of manufacturing sequences
 
  1. Machine name:...
  2. Mahining process description:...
  3. Geometrical description of the needed shape 
 
 #### *2.4. Manufacturing files (STL, svg or G-code, ...)*
<details>
  <summary>Click to see the guideline!</summary>
 
  - **Definition:** *Standard file formats support some of the manufacturing processes and the surface geometry of a design without the possibility of modification.*

```
What does include the documentation of standard file formats for the manufacturing process?
 
  1. CAD files in an interchange format such as STL that is suitable for 3D priniting 
  2. Nominal geometry and its allowable variation by using symbolic language on 2D drawings like SVG, JPEG and PDF format that is suitable for laser cutting
  3. Manufacturing export formats such as G-code, STEP-NC is suitable for CNC machining
  4. Circuit board design formats such as Gerber RS-274X, excellon that is suitable for vector photoplotters 2D mechanical NC machines
  ``` 
</details>

<details>
  <summary>Click to see the examples!</summary>
 
#### *Example 1:* [Automated Tea Infuser, Standard file (STL format)](https://wikifactory.com/+fablabbratislava/automated-tea-infuser/contributions/3f2c490)

#### *Example 2:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Specifications), [2D drawing file](https://wiki.satnogs.org/File:C1001.png)
</details>

 #### Template of manufacturing files
     
 Identifying the geometry by standard file formats
 
  1. Adequated 2D/3D files for each manufacturing process
 

 
