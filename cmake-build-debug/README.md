Here are the **rules** used to solve each kind of problem from the given solved sheet:

---

### **1. Error Percentage Calculation**
**Rule:**  
The percentage error of a measurement instrument is calculated as:
\[
\text{Error Percentage} = \pm \frac{\text{Error}}{\text{Full Scale Value}} \times 100
\]
For a specific reading, the error percentage is:
\[
\text{Error Percentage} = \pm \frac{\text{Error}}{\text{Reading}} \times 100
\]

**Example:**  
For a pressure gauge with a range of 0-10 bar and an error of ±0.15 bar:
- Full scale error percentage: \(\pm \frac{0.15}{10} \times 100 = \pm 1.5\%\)
- Error percentage at 2.0 bar: \(\pm \frac{0.15}{2} \times 100 = \pm 7.5\%\)

---

### **2. Equipment Accuracy and Suitability**
**Rule:**  
To determine the suitability of a sensor, calculate the error percentage at a specific reading:
\[
\text{Error Percentage} = \pm \frac{\text{Max Error}}{\text{Reading}} \times 100
\]
The sensor with the **lower error percentage** is more suitable.

**Example:**  
For Sensor A (0-1 bar) and Sensor B (0-10 bar) with ±5% full-scale accuracy:
- Sensor A error at 0.9 bar: \(\pm \frac{0.05}{0.9} \times 100 = \pm 5.6\%\)
- Sensor B error at 0.9 bar: \(\pm \frac{0.5}{0.9} \times 100 = \pm 55\%\)
- **Conclusion:** Sensor A is more suitable.

---

### **3. Static Sensitivity Calculation**
**Rule:**  
Sensitivity is the ratio of the change in output to the change in input:
\[
\text{Sensitivity} = \frac{\Delta \text{Output}}{\Delta \text{Input}}
\]

**Example:**  
For a spring scale where 15 kg produces a 2 cm deflection:
\[
\text{Sensitivity} = \frac{2 \, \text{cm}}{15 \, \text{kg}} = 1.333 \, \text{mm/kg}
\]

---

### **4. Sensitivity of a Measuring System**
**Rule:**  
The overall sensitivity of a system is the product of the sensitivities of its components:
\[
\text{Overall Sensitivity} = k_1 \times k_2 \times k_3
\]

**Example:**  
For a system with:
- Transducer sensitivity: \(0.25 \, \text{mV/°C}\)
- Amplifier gain: \(2.5 \, \text{V/mV}\)
- Recorder sensitivity: \(4 \, \text{mm/V}\)
\[
\text{Overall Sensitivity} = 0.25 \times 2.5 \times 4 = 2.5 \, \text{mm/°C}
\]

---

### **5. Sensitivity Drift Calculation**
**Rule:**  
Sensitivity drift is the change in sensitivity due to environmental factors (e.g., temperature):
\[
\text{Sensitivity Drift} = \text{Sensitivity}_{\text{New}} - \text{Sensitivity}_{\text{Old}}
\]

**Example:**  
For an instrument calibrated at 20°C and used at 50°C:
- Sensitivity at 20°C: \(2.62\)
- Sensitivity at 50°C: \(2.94\)
\[
\text{Sensitivity Drift} = 2.94 - 2.62 = 0.32
\]

---

### **6. Zero Drift Calculation**
**Rule:**  
Zero drift is the change in the output when the input is zero, due to environmental factors:
\[
\text{Zero Drift} = \text{Output}_{\text{New}} - \text{Output}_{\text{Old}}
\]

**Example:**  
For a load cell calibrated at 21°C and used at 35°C:
- Zero drift: \(0.2 \, \text{mm} = 200 \, \mu \text{m}\)

---

### **7. Sensitivity and Zero Drift Coefficients**
**Rule:**  
The drift coefficients are calculated as:
\[
\text{Zero Drift Coefficient} = \frac{\text{Zero Drift}}{\Delta \text{Temperature}}
\]
\[
\text{Sensitivity Drift Coefficient} = \frac{\text{Sensitivity Drift}}{\Delta \text{Temperature}}
\]

**Example:**  
For a load cell with a temperature change of 14°C:
- Zero drift coefficient: \(\frac{200}{14} = 14.2857 \, \mu \text{m/°C}\)
- Sensitivity drift coefficient: \(\frac{2}{14} = 0.1429 \, (\mu \text{m per kg})/°C\)

---

### **8. Graph-Based Sensitivity Calculation**
**Rule:**  
For a linear input-output relationship, sensitivity is the slope of the graph:
\[
\text{Sensitivity} = \frac{\Delta \text{Output}}{\Delta \text{Input}}
\]

**Example:**  
For a platinum resistance thermometer:
\[
\text{Sensitivity} = \frac{400 - 200}{200 - 100} = 2 \, \Omega/°C
\]

---

### **9. Deflection Calculation for a Pressure Measuring System**
**Rule:**  
The deflection on the chart is calculated as:
\[
\text{Deflection} = \text{Sensitivity} \times \text{Pressure Change}
\]

**Example:**  
For a system with sensitivity \(0.68 \, \text{mm/bar}\) and a pressure change of 30 bar:
\[
\text{Deflection} = 0.68 \times 30 = 20.4 \, \text{mm}
\]

---

These rules are based on standard principles of instrumentation and measurement, as described in textbooks like **"Measurement and Instrumentation Principles" by Alan S. Morris** and **"Principles of Measurement Systems" by John P. Bentley**.
