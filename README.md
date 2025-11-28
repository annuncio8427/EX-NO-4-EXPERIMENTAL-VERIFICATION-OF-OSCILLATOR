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

w![WhatsApp Image 2025-11-28 at 3 39 18 PM](https://github.com/user-attachments/assets/894b3e33-bbad-4a33-85e6-f6df3a01f14a)




---

## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 3 40 39 PM](https://github.com/user-attachments/assets/81f65c19-0543-455f-bcf3-fb798363e915)


## DESIGN
![WhatsApp Image 2025-11-28 at 3 44 49 PM](https://github.com/user-attachments/assets/7b22ec2e-727f-4d3a-aae4-601f4d41a437)


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

![WhatsApp Image 2025-11-28 at 3 42 55 PM](https://github.com/user-attachments/assets/2b3df973-5927-43f3-a746-b5f70fdeb7c4)

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 6 32 19 PM](https://github.com/user-attachments/assets/f6435118-abc4-418a-bf90-d514be5d7b55)


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

![WhatsApp Image 2025-11-28 at 3 45 32 PM](https://github.com/user-attachments/assets/7c6312b9-3ef9-43c0-ad71-6d1f56aa9f6f)



---
## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 3 46 07 PM](https://github.com/user-attachments/assets/aa1effc6-5a67-4e42-969b-f714af1bb72c)


---

## DESIGN
![WhatsApp Image 2025-11-28 at 3 46 39 PM](https://github.com/user-attachments/assets/44aac112-608f-4b2f-a922-fa44c6d9f30c)

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
---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---
## TABULATION/OBSERVATION

![WhatsApp Image 2025-11-28 at 3 47 29 PM](https://github.com/user-attachments/assets/c9430b8a-0196-4aff-b08b-fa4549fa1196)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-28 at 6 31 54 PM](https://github.com/user-attachments/assets/b069aeb7-5504-46a9-bd39-cbf6d56a79cd)

![WhatsApp Image 2025-11-28 at 3 49 07 PM](https://github.com/user-attachments/assets/90be1b83-456a-434d-a10f-06759fda848b)



---
## RESULT:

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
