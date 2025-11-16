
---

## 🧪 PROCEDURE

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
5. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
6. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
7. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
8. Record values of Vf and If, and plot the characteristic curve between them.

---

## 🔌 CONNECTION DIAGRAM
<img width="908" height="580" alt="image" src="https://github.com/user-attachments/assets/37c75d16-e2e6-43f9-9c13-9e14ae185401" />



---

## 📊 TABULATION

### LED Forward Characteristics

| Forward Voltage Vf (V) | Forward Current If (mA) |
|------------------------|-------------------------|
| 1.5                    |     1.0                 |
| 1.6                    |     2.0                 |
| 1.7                    |     4.0                 |
| 1.8                    |     6.5                 |
| 1.9                    |     9.0                 |
| 2.0                    |     12.0                |
| 2.1                    |      15.0               |
---

## 📈 MODEL GRAPH
<img width="423" height="358" alt="image" src="https://github.com/user-attachments/assets/ff8a5abf-323e-4f3a-ba43-68e545315c75" />


---

## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
