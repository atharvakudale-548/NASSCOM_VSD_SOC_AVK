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
- Run the floorplan </p>
Using the docker method run the following command </p>
`run_Floorplan` </p>
![Screenshot (294)](https://github.com/user-attachments/assets/1962a08c-05c6-4be5-ab68-b74b38e3d5d6) </p>
![Screenshot (295)](https://github.com/user-attachments/assets/ceb3d40b-0aaf-403b-824e-005265323c90) </p>
`openlane/configuration$pwd`</p>
`openlane/configuration$ls -ltr` </p>
`openlane/configuration$less README.md` </p>
`openlane/configuration$less floorplan.tcl` </p>
##### D2_SK1_L7 -- **Review Floorplan files and steps to view** </p>
![Screenshot (296)](https://github.com/user-attachments/assets/79d24d13-a25d-4a5b-a3bf-214de795b960) </p>
##### D2_SK1_L8 -- **Review Floorplan files and steps to view** </p>
![Screenshot (297)](https://github.com/user-attachments/assets/2905201c-f070-4e7a-ba03-e893d0596568) </p>
![Screenshot (298)](https://github.com/user-attachments/assets/91475fb1-6788-4b01-bebe-eb355ec885cc)</p>
#### D2_SK2 Library binding and placement </p>
##### D2_SK2_L1 -- **Netlist binding and initial place design** </p>
- All are available in library with timing , width and heights conditions . </p>
- Big shape for lesser resistance </p>
-A Library in the context of integrated circuit (IC) design refers to a collection of pre-designed, pre-characterized components (cells) that are used during various stages of the design process </p>
![Screenshot (155)](https://github.com/user-attachments/assets/48bfb3c8-11b8-41c0-bbdc-4e0cfd134693) </p>
##### D2_SK2_L2 -- **Optimize placement using estimated wirelength and capacitence** </p>
In this stage , optimization of placement is done .</p>
It is very improtant and difficult step to find a proper placement between two elements .
##### D2_SK2_L3 -- **Ideal final clock is 0** </p>
##### D2_SK2_L4 -- **Need for libraries and characterization** </p>
**Congestion-aware placement using RePlAce** </p>
Global Placement: Initial rough positioning of cells with a focus on managing congestion.</p>
Detailed Placement: Fine-tuning of cell positions to optimize local routing and meet design constraints.</p>
RePlAce integrates both global and detailed placement stages, with an emphasis on managing and reducing congestion throughout the placement process.</p>
`run_placement` </p>
![Screenshot (300)](https://github.com/user-attachments/assets/e8a97204-8abe-44bd-a7b9-027cc881432e) </p>
- Load placement.def in magic layout </p>
`cd Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/29-07_10-25/results/placement/` </p>
`magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.placement.def &` </p>
![Screenshot (301)](https://github.com/user-attachments/assets/cc7a71eb-1593-4f5c-b3ee-19184ffa5e9f) </p>
![Screenshot (302)](https://github.com/user-attachments/assets/1a3fdd89-616b-4cb9-987d-ee7bf8ecb94d) </p>
#### D2_SK3 **Cell Design and Characterization flows** </p>
##### D2_SK3_L1 -- **Inputs for Cell Design Flow** </p>
Standard cells are present in the library . Library consists of cells of different functionality,sizes and thresholds . </p>
![Screenshot (161)](https://github.com/user-attachments/assets/d0ff23ae-5a12-45f5-ab45-031a7d7d20d4) </p>
![Screenshot (164)](https://github.com/user-attachments/assets/42730800-bdba-420d-b3c0-5fb14c3b1030) </p>
##### D2_SK3_L2 -- **Circuit Design Steps** </p>
![Screenshot (164)](https://github.com/user-attachments/assets/99e2694d-912c-4657-8206-a3d19daea1d4) </p>
##### D2_SK3_L3 -- **Layout Design** </p>
![Screenshot (165)](https://github.com/user-attachments/assets/1a15e991-f842-40a0-ae20-ac5d6ea5e829) </p>
![Screenshot (165)](https://github.com/user-attachments/assets/b601ddb4-0c9d-4720-a4b7-138bb6ced601) </p>
##### D2_SK3_L4 -- **Characterization** </p>
- Steps in Characterization Flow </p>
Steps: </p>
1. Read in the modules files </p>
2. Read the extract spiece Netlist</p>
3. Define the Behaviour of Buffer</p>
4. Read Sub ckt of Buffers</p>
5. Attach the power sources</p>
6. Apply the stimulus</p>
7. Necessary Output Capacitance</p>
8. Provide the necessary stimulus command</p>
9. Guna software</p>
![Screenshot (169)](https://github.com/user-attachments/assets/39ee8ae5-5a99-4382-b2cb-f8b3d0e23199) </p>
#### D2_SK4 **Timing Characterization** </p>
##### D2_SK4_L1 -- **Timing Threshold Definition** </p>
![Screenshot (170)](https://github.com/user-attachments/assets/b6349549-3415-4b10-9ec0-ccdf003700fa) </p>
![Screenshot (174)](https://github.com/user-attachments/assets/d919983b-e8bc-4711-8871-da808f40b805) </p>
##### D2_SK4_L2 -- **Propagation Delay and Transition Time** </p>
![Screenshot (175)](https://github.com/user-attachments/assets/c584a6a6-79f2-4ab2-8f80-25afffd21aa3) </p>
![Screenshot (176)](https://github.com/user-attachments/assets/27146e42-693f-411a-bdcf-93637a30deae) </p>

### **Day 3 : Design Library Cell using magic layout and ngspice characterization**</p>
#### D3_SK1 CMOS Inverter ngspice simulations </p>
##### D3_SK1_L0 -- **IO Placer Revision** </p>
Run the command </p>
`set ::env(FP_IO_MODE) 2` </p>
![Screenshot (303)](https://github.com/user-attachments/assets/05417dbe-5ec8-4c1b-b2e5-a586bb1568d0) </p>
![image](https://github.com/user-attachments/assets/e2b69809-5294-4b33-9757-5a7373382d48) </p>
##### D3_SK1_L1 -- **Spice deck creation for CMOS Inverter** </p>
- Connectivity information about the netlist</p>
- Component values</p>
- Pmos should be wider than nmos</p>
- identify and 'name' the nodes</p>
![Screenshot (178)](https://github.com/user-attachments/assets/bfb1efa8-d862-46ad-b0b7-63ad1cf3883f) </p>
![Screenshot (179)](https://github.com/user-attachments/assets/09cc2abc-88e8-4106-8681-b85074467147)</p>
![Screenshot (180)](https://github.com/user-attachments/assets/a23f8711-e94c-4d26-883e-16ab303776ba)</p>
![Screenshot (181)](https://github.com/user-attachments/assets/21a8a41f-1011-488c-bc76-f388c2d3b32f)</p>
##### D3_SK1_L2 -- **Spice Simulation** </p>
![Screenshot (185)](https://github.com/user-attachments/assets/6c3da8b7-3c9f-446d-bf4d-235c06328b1e)</p>
##### D3_SK1_L3 -- **Switching Threshold Vm** </p>
![Screenshot (188)](https://github.com/user-attachments/assets/827b0238-0e2c-4528-933e-158139be3b80) </p>
##### D3_SK1_L4 -- **Static and Dynamic Simulation** </p>
![Screenshot (190)](https://github.com/user-attachments/assets/a8d9240d-e6c0-4b7c-8a1a-2e027454ba5f)</p>
##### D3_SK1_L5 -- **Lab steps to gitclone vsdstdcelldesign** </p>
Commands :- </p>
`cd Desktop/work/tools/openlane_working_dir/openlane` </p>
`git clone https://github.com/nickson-jose/vsdstdcelldesign` </p>
`cd vsdstdcelldesign` </p>
`cp /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech` </p>
`ls` </p>
`magic -T sky130A.tech sky130_inv.mag &` </p>
![Screenshot (304)](https://github.com/user-attachments/assets/0f1d0a6b-1cfc-4401-8b56-2067d68e219c) </p>
![Screenshot (305)](https://github.com/user-attachments/assets/18fb4ddf-2678-4927-90f7-a2f88e879063) </p>
#### D3_SK2 Inception of Layout CMOS fab process </p>
##### D3_SK2_L1 -- **Create Active Regions** </p>
![Screenshot (193)](https://github.com/user-attachments/assets/cacb8a2f-2a2d-4851-a397-df92488ae039) </p>
![Screenshot (198)](https://github.com/user-attachments/assets/d2a22b86-cc94-4c2c-aff1-6d207da3909e)</p>
##### D3_SK2_L2 -- **N- well and P-well** </p>
![Screenshot (201)](https://github.com/user-attachments/assets/a1f241ac-8638-4de5-9e91-6ae66d3bcc80)</p>
![Screenshot (204)](https://github.com/user-attachments/assets/5af7eab2-47f3-496e-9731-25f3f60fd66f)</p>
##### D3_SK2_L3 -- **Create Gate Terminal** </p>
![Screenshot (211)](https://github.com/user-attachments/assets/a5ee421c-9f9c-446d-abe2-2e021e48e33f)</p>
##### D3_SK2_L4 -- **LDD Formation** </p>
![Screenshot (214)](https://github.com/user-attachments/assets/01e0bc6d-5199-4b74-974d-b71f9b86b797)</p>
![Screenshot (216)](https://github.com/user-attachments/assets/7a02984b-7ed2-487e-9f14-3e8e59ac402b)</p>
##### D3_SK2_L5 -- **Source and Drain** </p>
![Screenshot (227)](https://github.com/user-attachments/assets/83e54f67-ae9d-410a-b65a-8c9eac4e80fc)</p>
##### D3_SK2_L6 -- **Local Interconnect** </p>
##### D3_SK2_L7 -- **Higher level metal formation** </p>
![Screenshot (248)](https://github.com/user-attachments/assets/684e6576-eb79-4acf-996f-bc9fcc50af87)</p>
##### D3_SK2_L8 -- **Lab intro to SKY130 basic layers layout and LEP using inverter** </p>
##### D3_SK2_L9 -- **Lab steps to create std cell layout and extract spice netlist** </p>
`pwd` </p>
`extract all` </p>
`ext2spice cthresh 0 rthresh 0`</p>
`ext2spice` </p>
![Screenshot (306)](https://github.com/user-attachments/assets/eb66d23f-2a32-4a8d-9218-34ccd0384566)</p>
-in terminal `openlane/vsdstdcelldesign/$ngspice sky130_inv.spice` </p>
![Screenshot (307)](https://github.com/user-attachments/assets/2f44fffd-2ae5-4dd6-9107-fe361bb579c8)</p>
`plot y vs time a` </p>
Calculate rise time and fall time </p>
`cd`</p>
`wget http://opencircuitdesign.com/open_pdks/archive/drc_tests.tgz`</p>
`tar xfz drc_tests.tgz`</p>
`cd drc_tests`</p>
`ls -al`</p>
`gvim .magicrc`</p>
`magic -d XR &`</p>
- in tkcon window</p>
`paint v2`</p>
`cif see VIA2`</p>
![Screenshot (309)](https://github.com/user-attachments/assets/0cc90eab-0ccf-44a1-b62a-bde2cfa1443a)</p>
![Screenshot (311)](https://github.com/user-attachments/assets/056843a7-f2e3-43cb-8b26-0beaedc8081e)</p>
![Screenshot (312)](https://github.com/user-attachments/assets/704ecd98-d076-4e03-8061-ec29790a024f)</p>
![Screenshot (313)](https://github.com/user-attachments/assets/78409976-e278-49b4-be82-343ce94cb3fa)</p>
![Screenshot (314)](https://github.com/user-attachments/assets/246cd8a6-6156-4b8a-b14b-3d7a8e615852)</p>
![Screenshot (315)](https://github.com/user-attachments/assets/d768c1e9-cf3e-4b8c-9cbb-18970c01de4e)</p>
![Screenshot (317)](https://github.com/user-attachments/assets/87a6ee85-2059-4ced-ac3b-b986766041b0)</p>
![Screenshot (320)](https://github.com/user-attachments/assets/e5c4befe-3df1-46ca-8e73-b75e7880b0fd)</p>
![Screenshot (324)](https://github.com/user-attachments/assets/7d459b96-9b90-4031-a1ff-2f2bfbbf595c)</p>
`in tkcon window` </p>
`tech load sky130A.tech`</p>
`drc style drc(full)`</p>
`drc check`</p>
`drc why`</p>
