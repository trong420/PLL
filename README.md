# pll

<div align="center">

<h1>Design Phase Locked Loop Circuit With CMOS 130nm Technology</h1>
</div>


**1. FPD - Phase Frequency Detector** 

- Change to the lab2_dp directory, invoke IC Compiler and start the GUI:

- Open the orca_setup cell from the orca_lib.mw design library


- Apply timing and optimization controls which are specified



**2. Initialize the floorplan** 

- Create the corner and P/G cells and define all pad cell positions using a provided script:


**3. Preplace the macros connected to I/O pads** 

- In this task you will identify the macros that are connected to I/O pad cells and you 


**4. Perform Virtual Flat Placement**

- Apply a sliver size of 10 to prevent standard cells from being placed in narrow channels (< 10 um) between macros:
  

**5. Create P/G Ring Around Macros Groups**

- We have created a script to create P/G rings around six groups of macros.


- See this report: [report_qor](https://github.com/trong420/icc/blob/main/lab3_placement/report_qor.txt)
---
NEXT
- LAB3: [Design Planning](https://github.com/trong420/icc/tree/main/lab3_placement)
