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

/* Program for flipflops and verify its truth table in quartus using Verilog programming.
![WhatsApp Image 2026-03-12 at 2 49 47 PM](https://github.com/user-attachments/assets/ea0252e8-23f6-481d-8e65-6b0b09520992)

Developed by: RegisterNumber: J.Harshini :212224050120

*/

**RTL LOGIC FOR SISO Shift Register**
![WhatsApp Image 2026-03-12 at 2 50 21 PM](https://github.com/user-attachments/assets/d5d8c5bd-16f0-4284-ba0f-573d3ff4a9f2)

**TIMING DIGRAMS FOR SISO Shift Register**
![WhatsApp Image 2026-03-12 at 2 50 03 PM](https://github.com/user-attachments/assets/9f9344da-744a-480d-a0eb-650abd4be926)

**RESULTS**
