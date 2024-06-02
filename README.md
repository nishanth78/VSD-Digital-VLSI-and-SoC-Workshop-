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
![5](https://github.com/nishanth78/VSD-Digital-VLSI-and-SoC-Workshop-/assets/97909927/51e5bb3d-9552-4b0c-888f-c6841345f7bd)
* After executing the above commands, we can observe that the "runs" directory is created, storing the results of each intermediate step.
* Now, we can use the command "run_synthesis" to run the synthesis and generate a netlist.
![6](https://github.com/nishanth78/VSD-Digital-VLSI-and-SoC-Workshop-/assets/97909927/7644719f-46fa-4f47-b2ba-0dbe3bf6b914)
* Below file generated as a report after synthesis step.
![7](https://github.com/nishanth78/VSD-Digital-VLSI-and-SoC-Workshop-/assets/97909927/d3f8f510-7fce-4ee4-9a6a-f219dc1ee306)
Number of D-Flip flops are mentioned as "sky_130_fd_sc_hd_dfxtp_2" = 1613 </p>
Total Number of cells = 14876 </p>
Flop ratio =  0.1084 (10.84%) </p>
