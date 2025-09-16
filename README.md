# Experiment 3: Create and Use Classes and Objects to Model APB Packet.

---

## Aim  
To design and verify an **APB (Advanced Peripheral Bus) packet model** using **SystemVerilog object-oriented programming concepts** such as classes and objects, and simulate it using **ModelSim 2020.1**.

---

## Apparatus Required  
- Computer with **Windows OS**  
- **ModelSim 2020.1** (or later)  
- SystemVerilog source code editor  

---

## Description about APB Packet Modeling  
The **Advanced Peripheral Bus (APB)** is part of the AMBA protocol family used for connecting low-bandwidth peripherals.  
In this experiment, we use **SystemVerilog OOP concepts** to model an APB packet.  

- **Classes and Objects** in SystemVerilog allow abstraction and modularity.  
- An APB packet generally contains:  
  - **Address**  
  - **Data**  
  - **Control signals** (Read/Write, Select, Enable, Ready)  
- Using OOP, packets can be **created, initialized, randomized, and reused**, simplifying testbench construction.  

---

## Features  
- Written in **SystemVerilog OOP style**  
- Defines an **APB Packet class** with properties (address, data, control signals)  
- Includes **methods** for packet initialization and display  
- Demonstrates **object creation and manipulation**  
- Simulated using **ModelSim 2020.1**  

---

## Procedure  

1. **Open ModelSim 2020.1**  
   - Launch ModelSim from Start Menu.  

2. **Create a New Project**  
   - `File → New → Project`.  
   - Name it `APB_Packet_Project`.  

3. **Add SystemVerilog Files**  
   - Create a file `apb_packet.sv` → Define the APB Packet class.  
   - Create a file `apb_tb.sv` → Instantiate objects and test the class.  

4. **Compile the Files**  
   - Select both `.sv` files.  
   - Right-click → **Compile Selected**.  
   - Ensure no errors exist.  

5. **Start Simulation**  
   - `Simulate → Start Simulation`.  
   - Select the testbench module (`apb_tb`).  

6. **Add Signals and Run**  
   - Add relevant signals to the waveform.  
   - Run the simulation for required time.  

7. **Analyze Output**  
   - Observe the creation and display of APB packets.  
   - Verify correct modeling of properties and methods.  

---

## SystemVerilog Code   

### APB Packet Class (`apb_packet.sv`)  
```systemverilog
// Skeleton code for APB Packet class
class apb_packet;

  // Declare properties (e.g., address, data, control signals)

  // Constructor

  // Method to display packet
endclass
```
---
## SystemVerilog Code   

### APB Packet Class (`apb_tb.sv`) 
```systemverilog
// Skeleton code for APB Packet Testbench
module apb_tb;

  // Declare object of apb_packet class

  initial begin
    // Create object
    // Initialize values
    // Call display method
  end

endmodule
```
---
## Simulation Output

The simulation is carried out using ModelSim 2020.1.

Output log will show the APB packet details created using class objects.

(Insert console output screenshot here after simulation)

---

## Result

The design and verification of an APB packet model using SystemVerilog classes and objects was successfully carried out in ModelSim 2020.1.
The experiment demonstrated how OOP concepts simplify modeling and reusability in SystemVerilog testbenches.
