# Precision Buffer with Low Input Capacitance

Following project is a precision buffer developed in scope of project EMPIR project QuADC (see documentation.pdf for details).

The main goal was flatness below 0.1 µV/V up to 10 kHz. Calibration uncertainty at 1 MHz requirement was 5 µV/V. Input capacitance as low as possible. Output impedance as low as possible. The circuit uses bootstrapping of the supply voltages which reduces errors significantly and also ensure very low apparent input shunting capacitance. Cost for the solution is limited stability. The buffer cannot be supplied from low impedance source otherwise it tends to oscillate. It designed as output bufffer for the resistive voltage dividers.
