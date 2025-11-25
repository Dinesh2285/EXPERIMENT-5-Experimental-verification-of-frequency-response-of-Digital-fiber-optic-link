
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---
<img width="903" height="528" alt="image" src="https://github.com/user-attachments/assets/e0cb7815-a431-4e28-8cb5-8ed9949d8e64" />
Fiber optic links can be used for transmission of digital as well as analog signals. Basically a fiber optic link contains three main elements, a transmitter, an optical fiber and a receiver. The transmitter module takes the input signal in electrical form and then transforms it into optical (light) energy containing the same information. The optical fiber is the medium which takes the energy to the receiver. At the receiver light is converted back into electrical form with the same pattern as originally fed to the transmitter.

TRANSMITTER:

LED, digital DC coupled transmitters are one of the most popular varieties due to their ease of fabrication. We have used a standard TTL gate to drive a NPN transistor, which modulates the LED SFH450V or SFH 756V source. (Turns it on and off).

RECEIVER:

SFH-551V is a digital optodetector. It delivers a digital output, which can be processed directly with little additional external circuitry. The integrated circuit inside the SFH551V optodetector comprises the photodiode device, a transimpedance amplifier, a comparator and a level shifter.

The photodiode converts the detected light into a photocurrent. With the aid of an integrated lens the light emanating from the plastic Fiber is almost entirely focused on the surface of the diode. At the next stage the trans-impedance amplifier converts the photocurrent into a voltage. In the comparator, the voltage is compared to a reference voltage. In over to ensure good synchronism between the reference and the trans- impedance output voltage, the former is derived from a second circuit of a similar kind, which incorporates a “blind” photodiode. The comparator derives a level shifter with an open collector output stages. Here a catch diode (similar to Schottky-TTL) prevents the saturation of the output transistor, thus limiting the output voltage to the supply voltage.
 


## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---
<img width="837" height="430" alt="image" src="https://github.com/user-attachments/assets/a3faabe3-10e5-4771-a519-36e013ac144c" />



## BLOCK DIAGRAM
<img width="508" height="306" alt="image" src="https://github.com/user-attachments/assets/65365527-ac92-45d9-9ce2-928ab029baaa" />


---

## CONNECTION DIAGRAM 
<img width="471" height="227" alt="image" src="https://github.com/user-attachments/assets/d357f92d-8a43-4f56-b144-c1879a0578a5" />



---

## TABULATION  
**Transmission through Digital Link**
![WhatsApp Image 2025-11-12 at 13 47 08_4fa2d81d](https://github.com/user-attachments/assets/62a001cb-2de3-415c-a4d6-3bd6d3c2d21c)

---

## MODEL GRAPH
![WhatsApp Image 2025-11-12 at 13 45 40_b6fd0271](https://github.com/user-attachments/assets/65cfd980-64a8-4547-be5c-d1435c648ffa)


---

## RESULT

thus the relationship between input and received signal in 660mm fiber optic cable is found using Digital link 
