3. #**EX.NO:
** 3  EXPERIMENTAL VERIFICATION OF INTEGRATOR AND DIFFERENTIATOR USING OP-AMP 
            
**DATE:**  
             3A INTEGRATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
INTEGRATOR
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as,
Vo = - (1/Rf C1 ) ∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.
CIRCUIT DIAGRAM
## CIRCUIT DIAGRAM
![301](https://github.com/user-attachments/assets/2a936089-658a-4a5a-bfae-884e430dd648)


## MODEL GRAPH
![302](https://github.com/user-attachments/assets/cfc37d4f-2594-4e6d-b4b2-f3aef8dbbfe9)

![303](https://github.com/user-attachments/assets/de1327ad-81d2-4bed-9d65-ecaff1be7630)


---

## DESIGN

![304](https://github.com/user-attachments/assets/664e922a-d84b-4a0f-94c0-814df9a2b3f8)


## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


## TABULATION
![305](https://github.com/user-attachments/assets/ed027624-e49a-40bd-adc3-251488bba99f)


---

## OUT PUT WAVEFORM AND DISCUSSION 
![306](https://github.com/user-attachments/assets/728ae71b-091f-40c3-a5f3-b199633d6b46)


---
**DATE:**  
             3 B DIFFERENTIATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,
Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1.	Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 µF, calculate the value of Rf.
2.	Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.

The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 14 24 00_139bde15](https://github.com/user-attachments/assets/10b2916a-3da7-4bbc-82ff-906cd7b53e27)




## MODEL GRAPH

(i)	 SINE WAVE INPUT

![WhatsApp Image 2025-11-28 at 14 24 27_85475250](https://github.com/user-attachments/assets/1a3def52-0cbf-4555-8aef-0204ddbb4ee0)


AND

(ii) SQUARE WAVE INPUT

![WhatsApp Image 2025-11-28 at 14 24 41_b05c070d](https://github.com/user-attachments/assets/c4e5d35c-1730-48a1-8727-f710652f82f0)

---

## DESIGN


## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

 ## TABULATION
![WhatsApp Image 2025-11-28 at 14 29 33_4fcb6500](https://github.com/user-attachments/assets/254abbf3-edd6-462e-a523-b38d0fc42e8b)

		

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 17 57 49_61224d3e](https://github.com/user-attachments/assets/5e346077-ad39-44ff-a222-c0571e9be882)



RESULT:
Thus an Integrator and Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.
![WhatsApp Image 2025-11-28 at 14 32 08_d9f079a5](https://github.com/user-attachments/assets/6e2ee858-e659-41cc-b327-cf0a6e9c55cf)




