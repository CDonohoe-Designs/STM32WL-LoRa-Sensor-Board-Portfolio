# LTspice Simulation Files

This folder includes all LTspice `.asc` and `.net` files used to simulate:

- ✅ 3rd-Order Sallen-Key Filter (Cutoff ~25 kHz)
- ✅ Bias Generator using Op-Amp for VCOM (1.65 V)
- ✅ Differential ADC signal drive using pseudo-differential structure

### 📂 Files
- `LTspice_Sallen_key_MCP6001_filter.asc` – Cascaded RC + Sallen-Key stages
- `LTspice_Sallen_Key_Diff_Output.asc` – ADC pseudo-differential output simulation
- `LTspice_Sallen_Key_Diff_Output.net` – Netlist version
- `Plots_Schematics/*.JPG` – Output waveforms and schematic captures

Useful for analyzing analog signal integrity before digitization.
