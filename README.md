# Frequency Detection Circuit Using Op-Amps

## Overview

This project involves the design, simulation, and implementation of a frequency detection circuit using operational amplifiers. The circuit converts an unknown sinusoidal input signal into a DC voltage proportional to its frequency. The project includes schematic and PCB design files, simulation results, and a detailed technical report.

---

## 📌 Objective

To create a circuit capable of detecting the frequency of a sinusoidal signal and converting it into a measurable DC voltage, enabling frequency analysis without an oscilloscope or frequency counter.

---

## 🧠 Working Principle

1. **Signal Conditioning**: The sinusoidal input is first conditioned using an op-amp-based zero-crossing detector to generate a square wave.
2. **Monostable Multivibrator**: Converts each cycle into a pulse of fixed duration.
3. **Integrator or Low-Pass Filter**: Averages the pulse train into a DC voltage that varies linearly with frequency.
4. **Output Stage**: The final DC output can be read using a multimeter.

---

## 🔧 Tools and Technologies Used

- **LTspice**: For simulating and validating the circuit behavior.
- **EAGLE**: For schematic design and PCB layout.
- **Op-Amps**: Used for signal processing stages (e.g., LM324 or equivalent).
- **Multimeter**: To measure the output DC voltage corresponding to frequency.

---

## 🗂️ Project Files

| File | Description |
|------|-------------|
| `PCB design.brd` | EAGLE board layout file |
| `PCB design.sch` | EAGLE schematic file |
| `PCB design.png` | Schematic/PCB image preview |
| `README.md` | Project documentation |
| `Report on Frequency Detector.pdf` | Detailed explanation of theory, design, calculations, and results |
| `design blocks.dbl` | Block diagram or design structure file (assumed for visual layout or planning) |
| `*.asc` / LTspice files | Simulation circuits and results |

---

## ✅ Features

- Converts sinusoidal signals (variable frequency) to a DC voltage output.
- Linear relationship between frequency and voltage.
- Suitable for real-time monitoring with minimal hardware.
- Compact and low-cost solution.

---

## 📈 Simulation and Testing

- Simulated using LTspice to validate performance and linearity.
- Output voltage was tested across a range of frequencies to confirm consistency.
- PCB designed and reviewed for real-world implementation.

---

## 🧪 Applications

- Educational demonstration of frequency detection.
- Basic instrumentation projects.
- Embedded systems requiring analog frequency monitoring.
- Low-cost signal analysis setups.

---

## 📎 How to Use

1. Connect the sinusoidal input signal to the input terminal of the circuit.
2. Power the op-amp circuit with the recommended dual or single power supply.
3. Read the output voltage using a multimeter.
4. Use the linear transfer function (from report) to interpret the frequency.

---

## 📃 Documentation

Please refer to `Report on Frequency Detector.pdf` for:

- Complete theoretical background
- Circuit analysis and calculations
- Design decisions
- PCB snapshots
- Testing and result interpretation

---

## 📌 Notes

- Ensure proper power supply filtering for accurate readings.
- Input signal should be within expected amplitude range for reliable zero-crossing detection.
- Calibration may be required depending on the op-amp and resistor tolerances used.

---

## 🛠️ Future Improvements

- Add microcontroller interface to digitally display the frequency.
- Expand range using frequency dividers or advanced signal conditioning.
- Implement auto-scaling for broader frequency bands.

---

## 👨‍💻 Author

*Ezhilkirthik M*  
*AMRITA SCHOOL OF ENGINEERING, AMRITA VISHWA VIDYAPEETHAM *  
*Date: 01 April 2025*

---

