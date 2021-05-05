# **Manufacturing**

*I would like to enable makers to understand the process by which raw materials transform into a final product.*

## **How to document a manufacturing process?**


*Manufacturing instruction can guide the makers to follow a process for remanufacturing a product. Manufacturings instructions mean full descriptions and instructions concerning raw materials usage, operating conditions, process, and quality standards to be employed in the manufacture of products.*


 ### **Manufacturing instructions could include:** 
 
 #### *1. Manufacturing technology*
 
 *It means all the machinery, equipment and processes that are used to manufacture products. So,documentation of manufacturing technology consists*

   - Machine tool is a machine for handling or machining metal or other rigid materials, usually by
     - Turning tools
     - Milling tools
     - Grinding tools
     - Cutting tools
     - Drilling tools
     - Boring tools
     - etc. 
  - Manufacturing process and its machine name  
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
   - Machining parameters are all those parameters that are inherent to any machining operation and should have a suitable finite value to smooth and efficient removal of materials.
     - Cutting velocity
     - Feed rate
     - Depth of cut
     - Etc.
   
   #### *Example 1:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/mechanical/body_assembly#3-machiningfabrication)
   
   #### *Example 2:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Build_Sequence) 
   
#### *2. Standard file formats*

*Different types of standard file formats support rapid prototyping, 3D printing, and the surface geometry of a design without the possibility for modification. The standard design file formats include:*
 
  - CAD files in an interchange format such as STL format that is suitable for 3D priniting 
  - 2D drawings like SVG or JPEG
  - Manufacturing export formats such as G-code, STEP-NC
  - Circuit board design formats such as Gerber RS-274X, excellon 

#### *Example 1:* [Automated Tea Infuser, Standard file (STL format)](https://wikifactory.com/+fablabbratislava/automated-tea-infuser/contributions/3f2c490)*

#### *Example 2:* [SatNOGS Rotator v3](https://wiki.satnogs.org/SatNOGS_Rotator_v3#Specifications), [2D drawing file](https://wiki.satnogs.org/File:C1001.png)*

    
#### *3. Describe nominal geometry and its allowable variation by using symbolic language on drawing such as Geometric Dimensioning and Tolerancing (GD&T).*

 *It can define in [2D drawing native files](https://github.com/OPEN-NEXT/wp2.3_template/blob/main/Documentation/3.%20Design/Structural%20model/Mechanics/README.md#2-modelling-a-design-in-native-file-format)*


#### *4. Material selection*

 - Identifying the type of material
    - Metal
    - Plastic
    - Composite
    - Ceramic
    - etc.
- Identifying the [characteristics of the material](https://github.com/OPEN-NEXT/wp2.3_template/tree/main/Documentation/3.%20Design/Structural%20model/Mechanics#3-characteristics-of-the-materials) for manufacturing
- Environmental impacts  

#### *6. Post-processing and its tool kit*
 
   - Sanding after 3D printing
   - Cold welding
   - Gap filling
   - Polishing
   - Priming and painting
   - Etc. 
   
   #### *Example:* [post processing for FDM printed parts](https://www.3dhubs.com/knowledge-base/post-processing-fdm-printed-parts/#introduction)*
   
#### *7. Bill of material (BOM) that consists*

   - Part number
   - Item name
   - Description
   - Quantity
   - cost
   - Etc.

 #### *Example:* [JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover/tree/master/bill_of_materials)*


#### *8. Visualization of the manufacturing process*

*It is possible to visualize each part of manufacturing instruction by providing*

- Images 
- Videos 
- Etc.
 ```
