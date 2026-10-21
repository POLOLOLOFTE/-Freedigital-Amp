# -Freedigital-Amp

a full analogic amplificator 2.1, built around tda2030. very Open Source!!! so everyone can make it like they want!!
For Half Life (Hackclub)

the audio from a standard jack comes in and it goes trough some componets to introduce it to 3 tda2030 (the main amplificator process) they are three so one is for the right signal one if for the left and the third is for the subwoofer.
it's designed on a small foarm 100x100mm custom pcb and the tda2030 need passive cooling even if they have a thermal shut down emergency mode.

INPUT:
it work with one jack from a phone/computer and 16 volt from a powersupply aon 3-4 amps.

OUTPUT:
there are three screw clamp (other than the audio) or spring clamp on the rear where you put the positive and negative of the speakers... remember the speakers shouldn't more than 50w 8ohms each

SETTINGS:
there are three potenziometers for each tda2030 so you can control endidually the left, right and subwoofer audio

Extra Note:
The pcb isn'perfect there can be some static noise from the circuit and it's not made for staying 24/7 powered at 100% of volume

   **%%%%%%%%%**
  **IMPORTANT**
   **%%%%%%%%%**
   
 The pcb is UNTESTED so it can blew up for something wrong do NOT fully thrust the system so much
 I am NOT rensponsible if it blow up CAPACITORS ot TDA2030s

<img width="567" height="557" alt="Screenshot 2026-10-16 181143" src="https://github.com/user-attachments/assets/ffa974b5-e071-4e65-8fea-99d9b6d0ac7d" />

<img width="562" height="546" alt="Screenshot 2026-10-16 180414" src="https://github.com/user-attachments/assets/37fb3b2d-e78e-40dc-a61d-dd7f1cc6056d" />

<img width="1074" height="875" alt="Screenshot 2026-10-11 110512" src="https://github.com/user-attachments/assets/cf056830-d130-4135-bc88-f4818dc7755c" />


This is the material that you accually need to make it:

U1, U2, U3		TDA2030	
  
D1–D6		1N4001	(they are 6 and you can put similar diods in it)
  
R1, R2		10k	sub low-pass filter

R4, R5, R6, R7, R18, R19		100k	8V bias divider

R14, R15, R16		22k	feedback

R8, R9, R10		680Ω	pin 2 network

R11, R12, R13		1Ω	output stability network



R17		10Ω 5W	in parallel with L1

L1  	1–2µH	turns wound on R17

(for cost reason thoose two are thogheter... like you connect the resistor and then you run 10-12 spirals of copper wire)



C1, C2, C3		10µF 25V	input coupling

C5, C7, C8		22µF 25V	pin 2 network

C4, C15, C16		2200µF 25V	output coupling

C6	1	2200µF 25V	power supply reservoir

C9, C10, C11		100nF	output stability network

C12, C13, C14		100nF	supply decoupling at pin 5

C17		220nF	sub filter

RV1, RV2, RV3		10k potentiometer	volume-for each speaker

J1		3.5mm audio jack	input

J2, J3, J4		2-pin terminal block speakers

J5		2-pin terminal block	16V power input

J6		5-pin terminal block	test points

then you need the custom pcb: you find it in the extra folder

and remember about the speakers 2 standard and 1 subwoofer: max 4ohms 50w
