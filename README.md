# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

/* write all the steps invloved */

**PROGRAM**

 <img width="801" height="220" alt="image" src="https://github.com/user-attachments/assets/329c603b-ee03-4693-8500-4cec162f5f9d" />

 
/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:k.sadhana RegisterNumber:25013407

*/

**RTL LOGIC FOR SISO Shift Register**
<img width="1126" height="473" alt="image" src="https://github.com/user-attachments/assets/266560ab-088e-4c18-8dbb-65dbc1cfd7fd" />


**TIMING DIGRAMS FOR SISO Shift Register**
<img width="994" height="437" alt="image" src="https://github.com/user-attachments/assets/817877b2-9028-4c3b-b645-c7e4f3010fc5" />


**RESULTS**

 Thus the Serial-In Serial-Out shift register is implemented and verified
