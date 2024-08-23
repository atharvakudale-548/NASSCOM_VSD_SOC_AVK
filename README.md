## NASSCOM_VSD_SOC_AVK
###  2 Weeks Course ORGANIZED BY VSD IN ASSOCIATION WITH NASSCOM</p>
## Contents
### **Day 1 : Inception of open-source EDA OpenLANE and sky130 PDK **</p>
#### D1_SK1 How to talk to computers </p>
##### D1_SKY_L1 -- **QFN - 48 Package chips** </p>
**Processor/SOC**
![Screenshot (63)](https://github.com/user-attachments/assets/7a39c1e8-2c63-42d7-991c-f0a715972bd7) </p>
- The above image represent the overall viw of SoC and what are the various components included in it like . A SOC is s an integrated circuit that integrates most or all components of a computer or other electronic system. </p>
![Screenshot (66)](https://github.com/user-attachments/assets/9364655e-fe0e-4910-8949-3e64649195e6) </p>
![Screenshot (67)](https://github.com/user-attachments/assets/fee2d6a4-34fc-4cf3-a9f5-85bce775b7ed) </p>
![Screenshot (68)](https://github.com/user-attachments/assets/a7d35d09-c82d-4680-b16b-5515a060d746) </p>
![Screenshot (69)](https://github.com/user-attachments/assets/06da1ebf-e084-4517-99bc-5e2e0f7c61b0) </p>
![Screenshot (70)](https://github.com/user-attachments/assets/2905a7af-0967-4742-b163-8b5c65598990) </p>
![Screenshot (71)](https://github.com/user-attachments/assets/cccf752c-490b-4aab-bcb4-bc08c2bcca7b) </p>
![Screenshot (73)](https://github.com/user-attachments/assets/054ac960-92ae-457d-9078-a59a7bfcb943) </p>
The chip is in the center. </p>
1. **QFN PACAKGE** </p>
- QFN is a no lead package.Like any other IC package , the function of QFN package is to connect silicon die of the IC to the circuit board. </p>
2. **PAD** </p>
- Pad is used to send signal from inside to outside and vice versa . </p>
3. **DIE** </p>
-  die, in the context of integrated circuits, is a small block of semiconducting material on which a given functional circuit is fabricated. </p>
4. **CORE** </p>
-  Processor cores can be a microcontroller, microprocessor (μP),digital signal processor (DSP) or application-specific instruction set processor (ASIP) core </p>
5. **Foundary IPs** </p>
- IPs are designed and are essential to design PLL , ADC and SRAM . </p>
6. **Macros** </p>
- Macros are designs that are frequently used in circuit design. </p>
7. **IO Pads** </p>
- IO pads are a way of communication between the core and the outside world. </p>
##### D1_SKY_L2 **-- Introduction to RISC -V** </p>
ISA - Instruction Set Architecture . As we know computers only understand binary numbers. But we as humans are aware of writing high level programming languages such as C , C++,Python ,etc. In this process, RISC -V Implementation is done and then transfered to machine level. Bits get executed to layout . HDL is way to interact with RISC-V and layout design. </p>
![Screenshot (75)](https://github.com/user-attachments/assets/92e42112-580c-4364-8a93-436fd6922805) </p>
##### D1_SKY_L3 **From Software Applications to Hardware** </p>
When a use any application , there are many functions and features that we encounter. There is not a direct path between the software and the hardware , it goes through various stages before interacting with the hardware. </p>
![Screenshot (81)](https://github.com/user-attachments/assets/c1bfa400-4408-4b5d-9e1b-8d083fd0c27c) </p>
- Operating System OS : The task of OS is to convert the general tasks and various I/O operations into high level language like C,C++ </p>
- Compiler - Compiler converts the C/C++ code into instructions in the form of *.exe file </p>
- Assembler - The job of assembler is to covert instructions tinto binary which is then fed to hardware and it generates the output. </p>
#### D1_SK2 SOC Design and Openlane </p>
##### D1_SKY_L1 **Introduction to all components of an open-source digital ASIC designV** </p>
1. **RTL Design** </p>
RTL design is a crucial step in the VLSI design flow, which involves the creation of electronic circuits using integrated circuits (ICs). It involves the specification of a digital circuit in terms of the flow of digital signals between hardware registers, and the logical operations performed on those signals. </p>
2. **EDA Tools** </p>
Electronic design automation (EDA), also referred to as electronic computer-aided design (ECAD), is a category of software tools for designing electronic systems such as integrated circuits and printed circuit boards. </p>
3. **PDKs** </p>
Process Design Kits are the interface between the Fabrication companies and the designers. They seperate the design from the technology. </p>
4. **Google Skywater 130nm PDK** </p>
The Google SkyWater 130nm PDK is an open-source Process Design Kit (PDK) provided by SkyWater Technology Foundry in collaboration with Google. </p>
![Screenshot (93)](https://github.com/user-attachments/assets/072e6fb3-f18a-4531-9f26-2eb910e71d2a) </p>
![Screenshot (95)](https://github.com/user-attachments/assets/83a0c4af-df6e-49a3-a043-01d37ceeee0c) </p>
##### D1_SKY_L2 **RTL2GDS Flow** </p>
![Screenshot (98)](https://github.com/user-attachments/assets/8255db07-6dbd-44b3-b55a-460e935b6e44) </p>
![Screenshot (99)](https://github.com/user-attachments/assets/887229ca-2a83-43d2-b48e-edea26e200f3) </p>
![Screenshot (103)](https://github.com/user-attachments/assets/13272a78-3c5e-4a93-b568-6223709da959) </p>
![Screenshot (105)](https://github.com/user-attachments/assets/40b40a0e-cc07-41b3-8060-d903e5905547) </p>
![Screenshot (106)](https://github.com/user-attachments/assets/d9cc1ddf-58cd-4569-8162-cf157ac56a0a) </p>
![Screenshot (107)](https://github.com/user-attachments/assets/3cdde963-6a70-4e0e-975e-67c9210e5fc8) </p>
![Screenshot (108)](https://github.com/user-attachments/assets/e28ec162-5d20-4e55-9d63-b2bee718aa36) </p>
![Screenshot (109)](https://github.com/user-attachments/assets/3508af2c-94c0-4e3d-b54f-347464d9b83a) </p>
![Screenshot (110)](https://github.com/user-attachments/assets/31d922ed-bd63-4ac2-ba31-0b8c9336eb6a) </p>
![Screenshot (111)](https://github.com/user-attachments/assets/d053414a-fd29-4d71-8d85-dd8a43e2c3f9) </p>
1. RTL - RTL is an implementation of digital circuits using Verilog </p>
2. Synthesis - It is used to convert RTL implementation into gate level netlistwith the help of a standard cell lobrary. </p>
3. Floor/Power Planning - It is the arrangement of different blocks and elements for minimizing the area for the peripherals and the IO pads.Power planning is used for the efficient power distribution throughtout the chip. </p>
4. Place - It is performed in two stages a) Global Placement - where optimal position is done and b) Detailed Placement - SC are minimally altered . </p>
5. Clock Tree Synthesis - It verifies the clock signal has the connection made across the whole chip. It is used to minimize clock skew, latency. </p>
6. Routing - Connects the placed standard cells with metal wires, creating the final layout. </p>
7. Sign-off - Once routing is done , the chip undergoes verification steps like Timing Verifications (DRC and LVS) and STA for timing verifications. </p>
##### D1_SKY_L3 **OpenLANE and Strive Chipsets** </p>
![Screenshot (112)](https://github.com/user-attachments/assets/6096693e-c2d3-458d-b741-68895f061134) </p>
![Screenshot (113)](https://github.com/user-attachments/assets/3c419348-5b8b-4e77-83e1-da62448df61e) </p>
- OpenLane is an automated RTL to GDSII flow based on several components including OpenROAD, Yosys, Magic, Netgen, CVC, SPEF-Extractor, KLayout and a number of custom scripts for design exploration and optimization. The flow performs all ASIC implementation steps from RTL all the way down to GDSII. </p>
- In efabless , the company has a SoC called Strive.They have various versions and contains several features. </p>
##### D1_SKY_L3 **OpenLANE ASIC Flow** </p>
![image](https://github.com/user-attachments/assets/2234c8c8-d865-4a5e-adec-fffc8d953858) </p>
#### D1_SK3 Get Familiar with Open Source EDA Tools </p>
##### D1_SKY_L1 **OpenLANE Directory Structure** </p>
Complete RTL2GDS withou manual interaction </p>
- Undersatnding Linux Commands </p>
1. `pwd `- The pwd command writes to standard output the full path name of your current directory (from the root directory). </p>
2. `cd` - Change directory </p>
3. `ls -ltr` - It lists everything in the folder in chronological order. </p>
##### D1_SKY_L2 **Design Preperation Step** </p>
- Lab for running synthesis </p>
`cd Desktop` </p>
`cd work/tools/openlane_working_dir` </p>
`cd openlane` </p>
`docker` </p>
`./flow.tcl -interactive` </p>
`package require openlane 0.9` </p>
`prep -design picorv32a` </p>
`run_synthesis` </p>
![Screenshot (127)](https://github.com/user-attachments/assets/4bbe524e-a45c-4e9e-9823-a845e170c8b4) </p>
![Screenshot (128)](https://github.com/user-attachments/assets/5c2798ba-dbeb-4e81-8433-5ad5c554f7e9) </p>
![Screenshot (130)](https://github.com/user-attachments/assets/21ced0a8-03fd-407d-9961-a68a5b9e2f1a) </p>
![Screenshot (292)](https://github.com/user-attachments/assets/ef04f268-0fe2-4396-aed0-a2b11e7b658c) </p>
- Flop Ratio = Number of D Flip Flops / Number of Cells </p>
`Flop Ratio = 1613/14876 = 0.1084` </p>
i.e. 10.84% </p>
### **Day 2 : Good vs Bad Floorplan and Library Cells** </p>
#### D2_SK1 Chip Floor Planning Considerations </p>
##### D2_SK1_L1 -- **Utilization factor and aspect ratio** </p>
1.Define Width and Height of Core and Die </p>
- Assume the width and height as 1 sq unit and 1 sq unit each . Then UF is 1 . </p>
- Utilization factor = (Area occupied by netlist)/(Total area of core) </p>
- Aspect Ratio = Height / Width </p>
![Screenshot (133)](https://github.com/user-attachments/assets/1f55385b-2f3f-459e-92e0-a24b12cd54cf) </p>
Netlist defines the connectivity between all the components . </p>
- **Core** - It is a section of the chip where the fundamental logic of design is placed . </p>
- **Die** - It consists of core,is a samll semiconductor material specimen on which the fundamental circuit is fabricated. </p>
- In reality , 50-60% UF is achieved. </p>
-When aspect ratio is 1 , chip is square sized. </p>
##### D2_SK1_L2 -- **Concept of Pre-placed Cells** </p>
![Screenshot (136)](https://github.com/user-attachments/assets/889ba322-5692-473c-88c9-02f1a5678ba9) </p>
- Divide the circuit in some fashioned to reduce size
  1. Cut-off
  2. Extend IO Pins
  3. Black Box the boxes </p>
![Screenshot (137)](https://github.com/user-attachments/assets/787fd1dd-3d4e-473b-93a8-f4dfa9c0413b) </p>
-The arrangement of these IPs is referred as **floorplanning**
-These IPs have user defined locations and hence are placed in chip befor automated placement-and-routing and are called **pre-placed cells** </p>
##### D2_SK1_L3 -- **Decoupling Capacitors** </p>
- Responsibility of PS to supply VTG to transition capacitor from 0 to 1.But in reality , supply drops in physical wires due to resistance .</p>
-Addition of decoupling capacitor in parallel with circuit . Every time the circuit switches, it draws current from Cd , whereas RL network is used to replenish the charge into Cd.
![Screenshot (142)](https://github.com/user-attachments/assets/c1b1a4e1-73bf-48d3-b128-11f6bc33809f) </p>
![Screenshot (143)](https://github.com/user-attachments/assets/e8cabe3e-6a14-4024-be9b-99c83741d327) </p>
##### D2_SK1_L4 -- **Power Planning** </p>
- Only one power supply . Consider circuit as black box.  </p>
- To retain same signal from driver to load , PS is given.</p>
- If ground bounce goes beyond noise margin , voltage drops </p>
- the solution is **Multiple Power Supply** , if circuit needs current , it can tap from nearest power supply. </p>
![Screenshot (148)](https://github.com/user-attachments/assets/0e02d9c6-d1e7-4603-bc3d-2881eb2b1dd8) </p>
![Screenshot (149)](https://github.com/user-attachments/assets/10f5a73e-d639-4e40-9d89-3d036972feb8) </p>
##### D2_SK1_L5 -- **Pin Placement and Logical Cell Placement Blockage** </p>
The connectivity information between the gates is coded using VHDL/Verilog language and is called as 'Netlist'.
![Screenshot (151)](https://github.com/user-attachments/assets/f0bb462e-49ef-45e0-b4bf-fba6287cf4df) </p>
The frontend team who decides the netlist connectivity input and output and the backend team who done the pin placements. So according to the pin placements, we have to locate the preplaced blocks nearer to the inputs of the preplaced blocks. </p>
![Screenshot (152)](https://github.com/user-attachments/assets/bd1aa354-5767-4609-8057-149901291f70) </p>
##### D2_SK1_L6 -- **Steps to Run Floorplan using OpenLANE** </p>







