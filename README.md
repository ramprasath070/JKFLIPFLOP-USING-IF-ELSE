# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

Inputs:

J and K are the two inputs.
Q is the current state (output) of the flip-flop.
Q_next is the next state (output after processing the inputs).
A clock signal triggers the flip-flop.
Behavior:

If J = 0 and K = 0: No change in output (state remains the same).
If J = 0 and K = 1: Reset the output (Q_next = 0).
If J = 1 and K = 0: Set the output (Q_next = 1).
If J = 1 and K = 1: Toggle the output (Q_next = ~Q).

**PROGRAM**

DEVELOPED BY:RAM PRASATH S, Register Number:24900195
![DE ex7 code](https://github.com/user-attachments/assets/a7614281-6b4e-4d04-9b2e-46eb3f5bb704)


**RTL LOGIC FOR FLIPFLOPS**

![DE ex7 diagram](https://github.com/user-attachments/assets/641c8c4e-d99e-4be1-bcc4-bd22d009097e)


**TIMING DIGRAMS FOR FLIP FLOPS**

![DE ex7 waveform](https://github.com/user-attachments/assets/3b66aa31-d8a0-4cce-8790-c10c87eef740)


**RESULTS**

The implemention of   JK flipflop using verilog and validating their functionality using their functional tables
