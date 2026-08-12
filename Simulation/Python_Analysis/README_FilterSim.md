# 🧪 Python Simulation: Sallen-Key Anti-Aliasing Filter Analysis

This simulation models a 3rd-order Butterworth Sallen-Key low-pass filter used as an anti-aliasing stage in the STM32WL analog front-end.

## 📌 Objectives

- Simulate a noisy analog input and observe filtering.
- Verify SNR improvement, plot step/sine responses and frequency response.

## 🛠 Tools Used

- Python 3.x
- Matplotlib (plotting), NumPy/SciPy (filter design, SNR)
- Cutoff: ≈ 25 kHz | Q ≈ 1.23

## 📈 Results Overview

### ✅ Bode Response
- Cutoff ≈ 25 kHz, roll-off ≈ 60 dB/dec.
- Low phase distortion in passband.

![Bode Plot](PytonSallenKeyBode.JPG)

### ⏱ Time-Domain Response

- **Sine Input**: Clean 10 kHz output
- **Pulse Input**: Fast settling, low overshoot

![Time-Domain](pythonTimeDomain_Step&Sine.JPG)

### 🔊 FFT Spectrum

- Good high-frequency noise suppression.
- Cutoff behavior confirmed.

![FFT Plot](Pyton_FFT.JPG)

### 🔍 SNR Analysis

- Before Filtering: ~6 dB
- After Filtering: ~–0.25 dB
- Noise simulation artifact noted.

![SNR](Python_SNR.JPG)

## 📄 Summary

This filter preserves bandwidth and minimizes distortion, suitable for ADC front-end. Confirms theory with practical results.

## 🧠 Next Steps

- Compare with LTspice version.
- Validate component tolerances.
- Integrate into STM32WL board.

---
*Author: Caoilte Donohoe — Embedded & RF Systems Design*
