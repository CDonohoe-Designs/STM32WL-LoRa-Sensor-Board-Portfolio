# Python Simulation — Sallen-Key Anti-Aliasing Filter

I used this Python analysis to examine the 3rd-order Sallen-Key low-pass filter used in the analogue front end.

## Objectives

- simulate a noisy analogue input;
- examine the filter frequency response;
- compare time-domain sine and pulse behaviour;
- inspect FFT results; and
- estimate the effect of filtering on the simulated signal-to-noise ratio.

## Tools

- Python 3
- NumPy
- SciPy
- Matplotlib

The analysis uses a cutoff frequency of approximately **25 kHz**.

## Result plots

### Bode response

![Bode response](results%20images/Python_SallenKey_Bode.jpg)

### Time-domain response

![Time-domain response](results%20images/Python_TimeDomain_Step_Sine.jpg)

### FFT comparison

![FFT comparison](results%20images/Pyton_FFT.jpg)

### SNR analysis

![SNR analysis](results%20images/Python_SNR.jpg)

The SNR notebook is a numerical experiment rather than a hardware measurement, so I treat its absolute values as simulation results rather than measured board performance.

## Purpose

This work complements the LTspice analysis and gives me a second, scriptable way to examine the expected analogue-filter behaviour before physical hardware validation.
