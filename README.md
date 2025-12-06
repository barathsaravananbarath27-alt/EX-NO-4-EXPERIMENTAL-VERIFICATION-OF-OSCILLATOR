# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR
4. ##**EX.NO:* ## EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
	DATE:
 ##AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
 ##THEORY:
 ##RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR
![WhatsApp Image 2025-12-05 at 22 43 45_47d48f62](https://github.com/user-attachments/assets/4de9a04b-6d58-41d6-a5ea-257cb5e8b527)



---

## MODEL GRAPH
![WhatsApp Image 2025-12-05 at 22 44 06_f63220ac](https://github.com/user-attachments/assets/90305351-5f16-44b6-8235-f3aaee01b589)

## DESIGN
<img width="1600" height="1325" alt="image" src="https://github.com/user-attachments/assets/939ebc17-b957-4854-af9e-9b4bc988ff9f" />


## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION

![WhatsApp Image 2025-12-05 at 22 45 51_3bb2f602](https://github.com/user-attachments/assets/ed28650d-dada-4c54-b569-44cae7eae572)


---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-05 at 22 46 48_984b6e17](https://github.com/user-attachments/assets/ff546a08-1f05-4e2d-9ef6-dc3d6e04e3ad)


---
## THEORY
 ##WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR
![WhatsApp Image 2025-12-05 at 22 47 32_1b7ba4ee](https://github.com/user-attachments/assets/4006f285-d3f8-440a-b3cf-ee8faf58d0b0)


---
## MODEL GRAPH
![WhatsApp Image 2025-12-05 at 22 48 01_b434d70f](https://github.com/user-attachments/assets/11beada7-1c77-4b7a-b522-84aae3cc63d9)

---

## DESIGN
![WhatsApp Image 2025-12-05 at 22 48 33_62ab2727](https://github.com/user-attachments/assets/42180a56-a86d-43a7-a732-0eafea472e21)

## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ
<img width="1600" height="1325" alt="image" src="https://github.com/user-attachments/assets/219dd44f-b92b-4fda-97d6-7372e1c28be7" />

---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION

![WhatsApp Image 2025-12-05 at 22 49 09_52666c9f](https://github.com/user-attachments/assets/5ed565a5-5e10-4f69-bd6b-6173a10ba9ee)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-12-05 at 22 50 17_f29e0c2b](https://github.com/user-attachments/assets/1c5f6991-e249-4616-973a-492dfaaaabb8)


---
## RESULT:

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
