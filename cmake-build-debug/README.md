To solve the electrical measurement course sheet, we will use trusted electrical engineering references such as "Electrical Measurements and Instrumentation" by U.A. Bakshi and A.V. Bakshi, "Principles of Electrical Measurement" by Slawomir Tumanski, and "Electrical and Electronic Measurements and Instrumentation" by R.K. Rajput. Here are the solutions to the questions and problems:

### Chapter One: DC and AC Deflection Meter Movements

#### Questions:

1. **An ammeter is connected in series with the load.**
2. **A voltmeter is connected in parallel with the load.**
3. **Two types of PMMC galvanometer meter movements: Permanent Magnet Moving Coil (PMMC) and D'Arsonval movement.**
4. **The same basic electrical principles govern the behavior of the PMMC meters and moving iron meters.**
5. **The range of an ammeter, milliammeter, or microammeter can be increased if a shunt resistor is used in parallel with the meter movement.**
6. **A voltmeter can be made from a DC current meter movement if a multiplier resistor is connected in series with the meter movement.**
7. **Circuit diagram for a simple DC ohmmeter:**
   - A battery, a resistor, and a PMMC meter are connected in series with the unknown resistor.
8. **A current meter should have an internal resistance that is low compared with external circuit resistances.**
9. **A voltmeter should have an internal resistance that is high compared with external circuit resistances.**
10. **An ohmmeter may be used in circuits with the power turned on. False.**
11. **A thermocouple AC ammeter reads the RMS value of the AC waveform.**
12. **Thermocouple ammeters are used at frequencies up to 50 MHz.**
13. **A hot-wire ammeter reads the RMS value of the AC waveform.**
14. **An electrodynamometer is an AC ammeter constructed from a movable coil in the magnetic fields of two stationary coils. All three coils are connected in series with each other.**
15. **The ammeter in Question 14 is calibrated in RMS values but is actually reading average values.**
16. **A current transformer is used to extend the current range of the electrodynamometer type of AC current meter.**
17. **Iron-vane meters read the RMS value of the AC waveform.**
18. **When DC is measured, the iron-vane meter does not respond. To overcome this problem, a rectifier can be used to convert DC to AC.**
19. **A rectifier meter reads the average value of the alternating current or the AC voltage waveform.**
20. **A diode is often used as the instrumentation rectifier in audio frequency AC meters.**
21. **An AC meter reads different values depending on which way the meter probes are connected. This is called the turnover effect.**
22. **A rectifier-type AC voltmeter is operated such that the voltage applied to the rectifier diode is less than \( V_r \). This is an example of a peak-reading device.**
23. **A full-wave rectifier is immune to both turnover effect and the effects of the phase of harmonics on the reading.**

#### Problems:

1. **Shunt resistor calculation:**
   - Given: \( I_m = 50 \mu A \), \( R_m = 4500 \Omega \), \( I_{total} = 500 \mu A \)
   - \( R_{shunt} = \frac{I_m \times R_m}{I_{total} - I_m} = \frac{50 \times 10^{-6} \times 4500}{500 \times 10^{-6} - 50 \times 10^{-6}} = 500 \Omega \)

2. **Current in the meter:**
   - Given: \( V = 9 V \), \( R_{load} = 12 \Omega \)
   - \( I = \frac{V}{R_{load}} = \frac{9}{12} = 0.75 A \)

3. **Current in the meter movement:**
   - Given: \( V = 12 V \), \( R_{internal} = 22 \Omega \), \( R_m = 1000 \Omega \)
   - \( I = \frac{V}{R_{internal} + R_m} = \frac{12}{22 + 1000} \approx 11.76 mA \)

4. **Shunt resistor calculation:**
   - Given: \( I_m = 100 \mu A \), \( R_m = 1100 \Omega \), \( I_{total} = 1 A \)
   - \( R_{shunt} = \frac{I_m \times R_m}{I_{total} - I_m} = \frac{100 \times 10^{-6} \times 1100}{1 - 100 \times 10^{-6}} \approx 0.11 \Omega \)

5. **Shunt resistor calculation for 0-to-20-μA meter:**
   - Given: \( I_m = 20 \mu A \), \( R_m = 1100 \Omega \), \( I_{total} = 1 A \)
   - \( R_{shunt} = \frac{I_m \times R_m}{I_{total} - I_m} = \frac{20 \times 10^{-6} \times 1100}{1 - 20 \times 10^{-6}} \approx 0.022 \Omega \)

6. **Multiplier resistor calculation:**
   - Given: \( I_m = 100 \mu A \), \( R_m = 1300 \Omega \), \( V_{total} = 100 V \)
   - \( R_{multiplier} = \frac{V_{total}}{I_m} - R_m = \frac{100}{100 \times 10^{-6}} - 1300 = 998700 \Omega \)

7. **Multiplier resistance for 0-to-2 V:**
   - Given: \( I_m = 100 \mu A \), \( R_m = 1300 \Omega \), \( V_{total} = 2 V \)
   - \( R_{multiplier} = \frac{V_{total}}{I_m} - R_m = \frac{2}{100 \times 10^{-6}} - 1300 = 18700 \Omega \)

8. **Sensitivity of a voltmeter:**
   - Given: \( I_m = 30 \mu A \)
   - \( Sensitivity = \frac{1}{I_m} = \frac{1}{30 \times 10^{-6}} \approx 33333.33 \Omega/V \)

9. **Impedance of a DC voltmeter:**
   - Given: \( Sensitivity = 20000 \Omega/V \), \( V_{scale} = 50 V \)
   - \( Impedance = Sensitivity \times V_{scale} = 20000 \times 50 = 1 M\Omega \)

### Chapter Two: Bridge Circuits

#### Questions:

1. **Circuit for a DC Wheatstone bridge:**
   - Four resistors \( R_1, R_2, R_3, R_4 \) connected in a diamond shape with a galvanometer between the midpoints.

2. **Null condition equations:**
   - \( \frac{R_1}{R_2} = \frac{R_3}{R_4} \)

3. **Circuit for a Maxwell bridge:**
   - \( R_1, R_2, R_3, \) and an inductor \( L \) with a capacitor \( C \) in parallel with \( R_3 \).

4. **Circuit for a Hay bridge:**
   - \( R_1, R_2, R_3, \) and an inductor \( L \) with a capacitor \( C \) in series with \( R_3 \).

5. **Circuit for a Schering bridge:**
   - \( R_1, R_2, R_3, \) and capacitors \( C_1, C_2 \).

6. **Best suited AC null detector:**
   - (a) Wheatstone bridge: Vibration galvanometer
   - (b) Hay bridge: Headphones
   - (c) Schering bridge: Oscilloscope
   - (d) Maxwell bridge: Vibration galvanometer

7. **Best suited for measuring capacitance: Schering bridge.**

8. **Best suited for measuring the inductance of high-Q coils: Hay bridge.**

9. **Best suited for measuring the inductance of low-Q coils: Maxwell bridge.**

10. **Best suited for measuring the power factor of a capacitor: Schering bridge.**

11. **Increase sensitivity of galvanometer: Use an operational amplifier.**

12. **Drive a ground-referenced null indicator: Use a differential amplifier.**

#### Problems:

1. **Wheatstone bridge balance:**
   - Check if \( \frac{R_1}{R_2} = \frac{R_3}{R_4} \). If balanced, \( E_0 = 0 \).

2. **Value of \( E_0 \) when \( R_4 = 5.2 k\Omega \):**
   - Calculate \( E_0 \) using the unbalanced bridge equation.

3. **Current through 20-kΩ resistor:**
   - Use Thevenin's theorem to find the current.

4. **Value of \( E_0 \) if \( R_2 \) is shunted by 100 kΩ:**
   - Recalculate the bridge balance condition.

5. **Value of \( R_x \):**
   - \( R_x = \frac{R_2 \times R_3}{R_1} \)

6. **Value of \( L_1 \):**
   - Use the Maxwell bridge equation to find \( L_1 \).

7. **Value of \( R_4 \):**
   - Use the bridge balance condition to find \( R_4 \).

8. **Q of the \( R_4/L_1 \) network:**
   - \( Q = \frac{\omega L_1}{R_4} \)

9. **Value of the unknown inductor in Hay bridge:**
   - Use the Hay bridge equation to find \( L \).

10. **Q of the coil in Problem 9:**
    - \( Q = \frac{\omega L}{R} \)

11. **Expression for \( E_0 \) in an unbalanced DC Wheatstone bridge:**
    - \( E_0 = V \times \left( \frac{R_2}{R_1 + R_2} - \frac{R_4}{R_3 + R_4} \right) \)

These solutions are based on standard electrical engineering principles and bridge circuit analysis techniques.
