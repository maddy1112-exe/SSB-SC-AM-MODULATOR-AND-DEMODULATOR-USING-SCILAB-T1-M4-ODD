# SSB-SC-AM-MODULATOR-AND-DEMODULATOR-USING-SCILAB-T1-M4-ODD
# SSB-SC-AM MODULATOR AND DEMODULATOR

## AIM

To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics.

---

## EQUIPMENTS REQUIRED

* Computer with i3 Processor
* SCI LAB

> **Note:** Keep all the switch faults in off position.

---

## ALGORITHM
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/a476c9aa-6203-48c8-b897-375c01844b1a" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/13730a23-3b94-4909-b735-87c8cb255edb" />

### 1. Define Parameters:

* **Fs:** Sampling frequency.
* **T:** Duration of the signal.
* **Fc:** Carrier frequency.
* **Fm:** Frequency of the message signal.
* **Amplitude:** Maximum amplitude of the message signal.

### 2. Generate Signals:

* **Message Signal:** The baseband signal that will be modulated.
* **Carrier Signal:** A high-frequency signal used for modulation.
* **Analytic Signal:** Constructed using the Hilbert transform to get the in-phase and quadrature components.

### 3. SSBSC Modulation:

* **Modulated Signal:** Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.

### 4. SSBSC Demodulation:

* **Mixing:** Multiply the SSBSC signal with the carrier to retrieve the message signal.
* **Low-pass Filtering:** Apply a low-pass filter to remove high-frequency components and recover the original message signal.

### 5. Visualization:

Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.

---

## PROCEDURE

* Refer Algorithms and write code for the experiment.
* Open SCILAB in System.
* Type your code in New Editor.
* Save the file.
* Execute the code.
* If any Error, correct it in code and execute again.
* Verify the generated waveform using Tabulation and Model Waveform.

---

## TABULATION

| Sl. No. | SIGNAL                 | AMPLITUDE (V) | FREQUENCY (Hz) |
| ------- | ---------------------- | ------------- | -------------- |
| **1**   | **Message Signal**     | **Theory:**   | **Practical:** |
|         |                        |               | **Theory:**    |
|         |                        |               | **Practical:** |
| **2**   | **Carrier Signal**     | **Theory:**   | **Practical:** |
|         |                        |               | **Theory:**    |
|         |                        |               | **Practical:** |
| **3**   | **Modulated Signal**   | **Practical** |                |
|         |                        | **Emax =**    |                |
|         |                        | **Emin =**    |                |
| **4**   | **Demodulated Signal** | **Practical** |                |

---

## MODEL GRAPH
<img width="1607" height="867" alt="SSB-SC" src="https://github.com/user-attachments/assets/de7bc614-382c-433a-aa2e-987a91b87f3c" />




