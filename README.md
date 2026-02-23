## Experiment No: 4
INTEGRATOR USING OP-AMP (μA741)
## Aim
To design and simulate an Integrator circuit using μA741 in Proteus Design Suite and verify that the output is proportional to the integral of the input voltage.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R = 10 kΩ
•	Capacitor Cf = 0.01 µF
•	Signal Generator
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="1159" height="622" alt="Screenshot 2026-02-02 092446" src="https://github.com/user-attachments/assets/700de443-e80e-4e31-ba38-cbccb0bb7e9e" />

## Connection Details:
•	Input signal → Resistor (R) → Inverting terminal (Pin 2)
•	Feedback capacitor (Cf) → Between Output (Pin 6) and Pin 2
•	Non-inverting terminal (Pin 3) → Ground
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
An Integrator circuit produces an output voltage proportional to the integral of the input voltage.
## Working Principle:
•	When input is constant → output is ramp signal
•	Output is inverted
•	Output depends on time
For Sine Wave Input:
•	Output lags input by 90°
•	Output amplitude decreases with frequency
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistor, capacitor, signal generator, and CRO.
3.	Connect circuit in integrator configuration.
4.	Apply ±15V power supply.
5.	Set input waveform (1V, 1kHz).
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
## Tabulation
S.No	           Input Signal	 Frequency	      Expected Output	               Practical Observation
<img width="680" height="329" alt="image" src="https://github.com/user-attachments/assets/cbd0ba0d-f050-445e-9e94-ce4bcdf0ba85" />

## Waveforms

<img width="1374" height="879" alt="Screenshot 2026-02-02 091946" src="https://github.com/user-attachments/assets/9e9e0af8-995d-45a0-a7ac-4cd842118989" />
<img width="1378" height="878" alt="Screenshot 2026-02-02 092344" src="https://github.com/user-attachments/assets/273dfde6-2912-4b07-a907-d350deb6e336" />
<img width="1377" height="879" alt="Screenshot 2026-02-02 092430" src="https://github.com/user-attachments/assets/23a2e90d-224a-4369-bfa5-f5e0e38a7a57" />



## Result
The Integrator circuit using μA741 Op-Amp was successfully designed and simulated in Proteus.
The output waveform is proportional to the integral of the input signal.
The circuit behaves as an integrator.
## Conclusion
•	Output lags input by 90° (for sine input).
•	Output amplitude decreases with increase in frequency.
•	Used in waveform generation and analog computation.
## Viva Questions
1.	What is an integrator circuit?<br>
A circuit that produces output proportional to the integral of input voltage.
2.	Write the output equation of integrator.<br>
Vout​=−RC1​∫Vin​dt
3.	Why does output lag input?<br>
Because integration of sine gives negative cosine, which lags by 90°.
4.	What happens at very low frequency?<br>
Output amplitude becomes very large and may saturate.
5.	What is practical integrator?<br>
An integrator with an additional resistor in parallel with the capacitor to prevent saturation and improve stability.
