
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

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

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="583" height="212" alt="image" src="https://github.com/user-attachments/assets/86346628-8ce9-4111-bee2-db75fccc4d96" />

---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**

<img width="586" height="124" alt="image" src="https://github.com/user-attachments/assets/f610baf0-cc23-4ad1-bae5-bd2db4578261" />

---

## TABULATION  
**Transmission through Analog Link**

<img width="1600" height="1312" alt="image" src="https://github.com/user-attachments/assets/f6dca46e-57fd-496d-8d1e-a0932e882526" />

| Frequency     | Output Signal (Vo) | Gain (Vo/Vi) | Gain in dB |
|---------------|--------------------|--------------|------------|
| 50 Hz         | 138 V              | 0.644        | 0.988      |
| 8.33 Hz       | 150 V              | 0.700        | 1.549      |
| 9.86 Hz       | 138 V              | 0.691        | 1.605      |
| 10.2 kHz      | 148 V              | 0.691        | 1.605      |
| 15 kHz        | 148 V              | 0.684        | 1.624      |
| 16 kHz        | 148 V              | 0.672        | 1.726      |
| 33 kHz        | 148 V              | 0.682        | 1.824      |
| 3 MHz         | 136 V              | 0.28         | 1.526      |

---

## MODEL GRAPH

<img width="674" height="331" alt="image" src="https://github.com/user-attachments/assets/13e223cc-328e-4fd9-ac2d-af32f260732d" />

<img width="1350" height="990" alt="image" src="https://github.com/user-attachments/assets/3fe49f1e-569a-44e0-b4a1-87957157b112" />


---

## RESULT
Hence, the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link is verified.

