# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**

<img width="623" height="293" alt="image" src="https://github.com/user-attachments/assets/a6910844-6f43-4795-8e49-5af96fbb0596" />


**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  
  <img width="776" height="378" alt="image" src="https://github.com/user-attachments/assets/2faabc37-51ec-487b-8706-a33138048251" />



  **MODEL GRAPH:**
  
<img width="532" height="372" alt="image" src="https://github.com/user-attachments/assets/120c5c43-9ab2-4e63-b090-28c9229b6868" />


  **TABULATION:**
  
<img width="1280" height="960" alt="WhatsApp Image 2026-09-24 at 10 06 10 AM" src="https://github.com/user-attachments/assets/307f2dd5-25d2-4897-887f-2d6a99035502" />

 

**MODEL CALCULATION:**

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  
  <img width="733" height="340" alt="image" src="https://github.com/user-attachments/assets/f9f191d7-546c-4a50-a675-8d92ebf942bd" />



  **MODEL GRAPH:**
  
<img width="467" height="306" alt="image" src="https://github.com/user-attachments/assets/41a15669-0c06-44cb-af40-a0038b01f6f5" />


  **TABULATION:**

<img width="1280" height="831" alt="WhatsApp Image 2026-09-24 at 10 06 11 AM" src="https://github.com/user-attachments/assets/5703e405-ab8d-4a86-8dcb-c6d3513071ea" />


  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  
<img width="748" height="442" alt="image" src="https://github.com/user-attachments/assets/30c981ed-fe57-41bd-b9dc-d299e29e3ee9" />


  **MODEL GRAPH:**
  
<img width="722" height="315" alt="image" src="https://github.com/user-attachments/assets/44269c6a-e557-49e2-866f-773f2da6c114" />


  **TABULATION:**

<img width="1276" height="1280" alt="image" src="https://github.com/user-attachments/assets/62bee8ee-4e43-4eb8-a35f-8dd1968c89f9" />

  **GRAPH**


<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/95b10efa-5bdf-46cd-bfeb-2a384d2a1e24" />

<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/e8510692-7b0d-464d-82d9-8bc1c81d9bce" />


**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**


<img width="944" height="1181" alt="image" src="https://github.com/user-attachments/assets/df56bb06-b5bd-409e-8c46-c0bf2ab376a5" />

<img width="1181" height="944" alt="WhatsApp Image 2026-09-24 at 10 18 08 AM (1)" src="https://github.com/user-attachments/assets/d13933fe-d750-40e8-bf7c-7f9d6f7e45ba" />

<img width="1181" height="944" alt="WhatsApp Image 2026-09-24 at 10 18 08 AM" src="https://github.com/user-attachments/assets/f5a3aec5-f85d-41c9-8d91-81b7da8f6857" />

  

**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






