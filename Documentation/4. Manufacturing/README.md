# **Manufacturing**

*I would like to enable makers to understand the process by which raw materials transform into a final product.*

## **How to document a manufacturing process?**


*Manufacturing instructions can guide the makers to follow a process for replicating a product. Manufacturing instructions mean full description and instructions concerning raw material, operating conditions, and process to be employed for the manufacture and assembly of the product.
The bill of marterial (BOM) is the document that describes all the components and there reference. If the component is to be purchased one should find all the information regired to buy the part. If the part is to be manufactured one should find all the description of the manufacturing instructions as described below.* 

## **How to document a manufacturing process a workpiece?**

*If the part is to be manufactured one should find all the description of the manufacturing instructions as described below.* 

### *1. Bill of material (BOM)*
<details>
  <summary>Click to see the guideline</summary>
 
 - **Definition:** *A bill of materials (BOM) is a comprehensive list of parts, items, and other materials required to create a product, as well as instructions required for gathering and using the required materials.*

```
What should includes the bill of material (not limited to...)?

   1. Part number
   2. Item name
   3. Raw material
   4. Manufacturer part number
   5. Digi-Key part number
   6. Description
   7. Manufactured part (link to manufacturing instruction)
   8. Purchased part (link to seller)
   9. Quantity
   10. Price
   11. Manufacturing standard lead time
   12. Packaging
   13. BOM notes
   14. ...
   ```
</details>

<details>
  <summary>Click to see the example</summary>
 
 #### *Example 1: [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/bill_of_materials)*
  
![image](https://user-images.githubusercontent.com/59058909/124725125-e8025280-df0c-11eb-9be0-67c3670dca17.png)

*BOM of JPL open-source Rover*
  
 #### *Example 2: [SatNOGS Rotator v3](https://gitlab.com/librespacefoundation/satnogs/satnogs-rotator/blob/master/rotator-bom.ods)
  
 #### *Example 3: [Krab v1.0](https://projects.fablabs.io/@avishek/krab-v10)

</details>

### BOM Template

 #### Bill of material
 
 *You can use this template on the App diagram to define bill of material of your project/product.*
 
![image](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/BOM%20template%201.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FBOM%20template.drawio" target="_blank">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FBOM%20template%20of%20manufactured%20workpiece.png">Edit in diagrams.net</a>
 
  ### *2. Manufacturing instructions should include:*
 
 #### *2.1. Manufacturing technology*
  <details>
  <summary>Click to see the guideline!</summary>
 
  - **Definition:** *It means all the machinery, equipment, and processes that are used to manufacture products.  Manufacturing technology guide for finding the type of necessary technology to produce the part. In that case, it should describe the most suitable technology according to the context.*

 ```
 What should include the documentation of manufacturing technology?
 
 Type of machines used 

   1. CNC machine tools for machining metal or other rigid materials
     - Milling machines
     - Lathe
     - Cutting, drilling machines
     - Etc.
    
   2. Other common manufacturing tools
     - 3D printing (FDM, SLS...) (https://en.wikipedia.org/wiki/3D_printing)
     - Thermoforming
     - Burning machining technology (laser cutting, Plasma cutting, ...) 
     - Bonding technologies (Solder,cold welding,arc welding,adhesive bonding ...)  
  
   3. Finishing: to achieve the right properties such as surface quality, geometrical accuracy and mechanical properties, the finishing is essential. 
     - Sanding after 3D printing
     - Gap filling
     - Blasting
     - Polishing
     - Priming and painting
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
   
*You can use this template on the App diagram to define manufacturing technology.*
 
![image](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Manufacturing%20technology.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FManufacturing%20technology.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FManufacturing%20technology.png">Edit in diagrams.net</a>

 #### *2.2. Manufacturing sequences and instructions*
 <details>
  <summary>Click to see the guideline!</summary>
 
  - **Definition:** *Manufacturing sequences refer to step-by-step machining and manufacturing processes in a target-oriented arrangement to enable manufacturing.*
  
  - **Comments:**
  
      * Machining sequence should define for the manufacturing of each part.
      * Process parameters are all those parameters that are inherent to any machining operation and should have a suitable finite value to smooth and efficient removal of materials. 

```
What does include the documentation of manufacturing sequences and instructions?
 
  1. Name of related machine of each each step
  2. Describing step by step sequence of the machining process
    - Machine
    - Type of operation
    - Tools description 
    - Process parameters
       - Cutting speed
       - Feed rate 
       - Depth of cut
       - Layer thickness
       - Etc.
    - Raw material
  ``` 
</details>

 <details>
  <summary>Click to see the examples!</summary>
 
   #### *Example 1:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly#3-machiningfabrication)
  
   #### *Example 2:* [DIY Dremel CNC design and parts](https://www.thingiverse.com/thing:3004773) and [its CAM file for machining](https://www.estlcam.de/) 
  
   #### *Example 3:* 3D printer parameters 

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
  
   #### *Example 4:* This table shows an example of the manufacturing sequences.
  
  ![image](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Example%20of%20machining%20sequences.jpg)
  </details>
  
  #### Template of manufacturing sequences
  
  *You can use this template on the App diagram to define manufacturing sequences of each parts.*
 
![image](https://github.com/OPEN-NEXT/wp2.3_Guideline-for-documentation-of-OSH-design-reuse/blob/main/Sources/Images/Manufacturing%20sequences.jpg)

 <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2FMachining%20parameters.drawio">Edit As New</a> | <a href="https://app.diagrams.net/#Hamerezoji1362%2Fdrawio-github%2Fmaster%2Fmachnining%20paramters.png">Edit in diagrams.net</a>
 
 
 #### *2.3. Manufacturing files (STL, svg or G-code, ...)*
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
  
#### *Example 3:* Types of CAD format of [transmagic](https://transmagic.com/cad-formats/)
</details>

 #### Template of manufacturing files
     
 Identifying the geometry by standard file formats
 
  1. Adequated 2D/3D files for each manufacturing process
 
