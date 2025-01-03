# T-FLIPFLOP-POSEDGE

**AIM:**

To implement  T flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**T Flip-Flop**

T flip-flop is the simplified version of JK flip-flop. It is obtained by connecting the same input ‘T’ to both inputs of JK flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of T flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/458a68fe-2d08-4a9d-ac4f-7ae0480ce0bd)

 
This circuit has single input T and two outputs Qtt & Qtt’. The operation of T flip-flop is same as that of JK flip-flop. Here, we considered the inputs of JK flip-flop as J = T and K = T in order to utilize the modified JK flip-flop for 2 combinations of inputs. So, we eliminated the other two combinations of J & K, for which those two values are complement to each other in T flip-flop. The following table shows the state table of T flip-flop.

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, T flip-flop can be used for one of these two functions such as Hold, & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of T flip-flop. Inputs Present State Next State

![image](https://github.com/naavaneetha/T-FLIPFLOP-POSEDGE/assets/154305477/cdd7fb32-539f-4b66-bb8d-f305a153c886)

 
From the above characteristic table, we can directly write the next state equation as Q(t+1)=T′Q(t)+TQ(t)′ ⇒Q(t+1)=T⊕Q(t)

**Procedure**

Open Quartus Prime software and create a new project.

Write the Verilog code for the T flip-flop.

Compile the project to ensure there are no syntax errors.

Generate the RTL (Register Transfer Level) schematic to verify circuit connections.

Create a testbench to simulate the functionality of the T flip-flop.

Apply different test cases for T input.

Verify the state transitions based on the characteristic table.

Generate timing diagrams to observe state changes.

Validate the simulation results against the functional table.

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming. 
Developed by: T Isaac Raja 
RegisterNumber:24900178
*/

![image](https://github.com/user-attachments/assets/d43c1c60-aba5-4e8f-9d18-3e790b874660)


**RTL LOGIC FOR FLIPFLOPS**

![image](https://github.com/user-attachments/assets/d3d84d44-3eae-4dd2-8957-c6a16389f6e0)


**TIMING DIGRAMS FOR FLIP FLOPS**

![image](https://github.com/user-attachments/assets/7b87a0f1-678d-4abe-b45f-03100be108be)


**RESULTS**

The T flip-flop was successfully implemented in Verilog, and its functionality was validated using the characteristic table and timing diagrams. The results confirm correct toggling and holding behavior based on the input.
