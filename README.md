# PWM-Motor-Driver

Brushless motors have both superior efficiency and durability however
they require more complex control methods. Two of the more common
control methods include sinusoidal pulse width modulation and trapezoidal
pulse width modulation. This project seeks to design, build and evaluate
a brushless motor control circuit that implements both of these techniques
without the use of positional feedback information.
This circuit is realized through the coalescence of several smaller subcircuits including that of a Wien Bridge Oscillator, Triangle Wave Generator,
Three Phase Generator, Three Phase Comparator, a Modulation/Inversion
Circuit, and an H-Bridge Driver. Physical analysis of the initial prototype revealed several imperfections arising from the non-idealities present
in real world devices. These include instability in Wien Bridge Oscillations,
deviations from expected phase shifts, and the presence of back-emf voltage
waveforms generated through the rotating of the motor.
In conclusion it was successfully shown that both SPWM and TPWM
control techniques were capable of actuating the motor in frequency ranges
between 5Hz to 95Hz while also allowing for the regulation of overall
current delivered to the motor. Lastly it was observed that in accordance
with expectations the method of SPWM control produced smoother actuation in contrast to the more bumpy TPWM technique.