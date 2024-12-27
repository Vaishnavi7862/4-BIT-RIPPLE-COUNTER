# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* write all the steps invloved */

**PROGRAM**
![Screenshot 2024-12-27 215228](https://github.com/user-attachments/assets/035f74f8-e2e2-48b1-8c3f-e31eea7e72e7)

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by:VAISHNAVI.D RegisterNumber:24900005
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**
![Screenshot 2024-12-27 215238](https://github.com/user-attachments/assets/e09f3408-5530-4ef7-993b-84e78ecb5786)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![Screenshot 2024-12-27 215253](https://github.com/user-attachments/assets/2f0fe175-91ad-47a9-a702-4527ffb64824)

**RESULTS**
BIT RIPPLE COUNTER was studied and verified successfully using quartus software
