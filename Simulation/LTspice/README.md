# LTspice Simulation Evidence

I used LTspice to investigate the analogue front end before PCB implementation.

The material in this folder documents simulation work covering:

- 3rd-order Sallen-Key low-pass filtering
- bias / VCOM generation
- pseudo-differential analogue behaviour
- ADC input behaviour
- transient and pulse response

The public portfolio currently contains the simulation notes, the `MCP6001.lib` model and captured schematic / waveform images.

It does **not** currently include a complete reproducible set of the original `.asc` and `.net` source files, so I present this folder as simulation evidence rather than as a complete LTspice project archive.

## Included evidence

- `LTSpice_BiasGen_ACAnalysis.JPG` — bias-generator AC analysis
- `SalenKeyCct.JPG` — Sallen-Key circuit capture
- `SalenKey_Bode.JPG` — filter frequency response
- `TransAnalysis.JPG` — transient analysis
- `TransAnalysis10kHz.JPG` — 10 kHz transient response
- `PulseResponse.JPG` — pulse response
- `psuedoDiff.JPG` — pseudo-differential simulation capture
- `psuedoDiffVADC_Neg.JPG` — ADC-related pseudo-differential result
- `MCP6001.lib` — op-amp model used during simulation

This evidence complements the Python/Jupyter analysis in `Simulation/Python_Analysis/`.
