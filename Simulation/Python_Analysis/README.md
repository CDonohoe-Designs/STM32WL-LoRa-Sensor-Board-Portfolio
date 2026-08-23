# Python-Based Filter Analysis

I used Python/Jupyter to complement the LTspice work with scriptable time-domain and frequency-domain analysis of the analogue filter path.

## Analysis included

- FFT comparison of noisy and filtered signals
- Signal-to-noise analysis
- Sallen-Key magnitude / phase response
- 10 kHz sine-wave response
- Step / pulse response

## Notebooks

- `Python_FFT.ipynb`
- `Python_SNR.ipynb`
- `SallenKey_Analysis.ipynb`

## Result images

The generated plots are stored in [`results images/`](results%20images/):

- `Python_SNR.jpg`
- `Python_SallenKey_Bode.jpg`
- `Python_TimeDomain_Step_Sine.jpg`
- `Pyton_FFT.jpg`
- `TimeDomain_Pulse.jpg`
- `TimeDomain_Sine.jpg`

The analysis uses NumPy, SciPy and Matplotlib and provides an independent check of the filter behaviour documented in the hardware design.
