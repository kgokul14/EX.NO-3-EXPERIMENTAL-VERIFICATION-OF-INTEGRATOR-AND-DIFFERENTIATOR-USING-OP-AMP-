3. ##**EX.NO:
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
<img width="513" height="395" alt="image" src="https://github.com/user-attachments/assets/676cd7de-0fc6-4900-83ce-cbce4c46326a" />



## MODEL GRAPH
<img width="490" height="285" alt="image" src="https://github.com/user-attachments/assets/e58e9f19-15a7-46ba-bb31-c0946df45407" />


<img width="489" height="297" alt="image" src="https://github.com/user-attachments/assets/168fc52d-39ad-4dd3-8570-efc981a5ca6a" />


---

## DESIGN

<img width="519" height="447" alt="image" src="https://github.com/user-attachments/assets/9abf42dc-c14c-4dad-bece-2957ea3bf656" />
 	

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


## TABULATION
<img width="541" height="274" alt="image" src="https://github.com/user-attachments/assets/3e301c6f-a5a4-4699-9520-341bd9a16d72" />


---

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1157" height="854" alt="image" src="https://github.com/user-attachments/assets/1aed8850-663f-486b-bdd1-55749da40d7b" />




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
<img width="543" height="421" alt="image" src="https://github.com/user-attachments/assets/692edccb-958d-4f41-8822-008422cb8da2" />




## MODEL GRAPH

(i)	 SINE WAVE INPUT

<img width="645" height="341" alt="image" src="https://github.com/user-attachments/assets/259ad990-840d-4693-8ccf-5b67a80cb8ff" />

---

AND

(ii) SQUARE WAVE INPUT

<img width="500" height="426" alt="image" src="https://github.com/user-attachments/assets/20df17c2-8dc0-4945-b5fc-067505112de2" />



---


## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

 ## TABULATION

<img width="511" height="337" alt="image" src="https://github.com/user-attachments/assets/f00649b7-7372-4ded-becd-45cf61ab8191" />
                   |
		

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1127" height="762" alt="image" src="https://github.com/user-attachments/assets/bc34e660-27b8-4b5d-8c1a-f4a5e7ede11c" />




---

RESULT:

<img width="652" height="421" alt="image" src="https://github.com/user-attachments/assets/716446f7-08ea-426e-92be-611126d52235" />

---



