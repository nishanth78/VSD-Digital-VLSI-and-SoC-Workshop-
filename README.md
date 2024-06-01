# VSD-Digital-VLSI-and-SoC-Workshop
# Day-1
#### Synthesis: Converts RTL to a circuit out of components from the standard cell library. 
Here, We will see the synthesis for picorv32(CPU Core) using the openlane flow and generate the netlist and other necessary reports after the synthesis step.</p>
In the image below, we can see that all the required files (openlane, pdks, etc.) are available, and ensured that all the necessary files are present.
![Screenshot from 2024-06-01 13-05-27](https://github.com/nishanth78/VSD-Digital-VLSI-and-SoC-Workshop-/assets/97909927/7f06b3af-2fd4-41b0-ae88-08404e891cee)
 #### Process Design Kit: The interface between FAB and the designers.
 * After running docker command, we can see the below terminal
![3](https://github.com/nishanth78/VSD-Digital-VLSI-and-SoC-Workshop-/assets/97909927/3c94c8f5-713c-4069-8976-dd770d86de3e)

* We use the flow.tcl command, which includes an "interactive" option that runs the process step by step, allowing us to compare the results.
![4](https://github.com/nishanth78/VSD-Digital-VLSI-and-SoC-Workshop-/assets/97909927/88e90410-67da-49ef-9492-bb36827df33f)
* Design setup preparation completed(shown in below image). command: prep -design picorv32a
