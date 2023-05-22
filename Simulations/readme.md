To verify the design of the tesla coil various simulations were performed using LTspice. These simulations were:

1. Gate Drive Signal Generation
Here we used 555 timer IC (U1) to generate around 730KHz signal. R1, R2 are the potentiometers that can be tuned to produce required frequency.
This signal goes through various Schmitt triggers to produce required output. The R,C,D component reduces the ON pulse width so that a margin of dead time can be created between the two output drives.
The Drive1 is complementary of Drive2 with a little dead time between those two pulses.

Now, an another 555 timer IC (U2) is used to interrupt the produced drive signal at much lower frequency (<1KHz). The duty cycle of the interrupt signal can be adjusted by adjusting R6. Although it will also change the frequency but it will remain less than 1KHz.


2. Music Input
An OPAMP based PWM signal generation from music signal is simulated. Generally, from the mobile audio jack the output voltage is 0.8V peak. Hence it need to be first amplified. The OPAMP U1 amplify the signal and the OPAMP U2 acts as a comparator to output PWM signal.
The reference Voltage of the comparator can be adjusted by adjusting the R5 resistor Value.
In practice, LM358 Dual OPAMP IC was used.

3. Feedback Tesla Coil
This circuit uses an antenna as a feedback to self-sustain the oscillations. (Basically an advance version of Slayer Exciter) Here the interrupter is also implemented by simply connecting the feedback to the interrupt signal through a Diode. 
Resistor selection R1, R2, R3 is also important to reduce overloading effect (in case of R1) and to sustain the oscillations.
Diodes D3 and D4 are to limit input voltage to 5V

4. Diode Voltage Limiting
This circuit simulates the voltage limiting using two fast recovery diodes.

5. Slayer Exciter
Simulates traditional BJT based slayer exciter circuit.
