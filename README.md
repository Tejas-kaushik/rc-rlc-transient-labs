# RC & RLC Transient Response Labs (University of Glasgow)

This repo contains my lab reports on **RC** and **LCR/RLC** transient response measurements, including calculations and validation using **OrCAD/PSpice**.

## Contents
- `pdf` — RC transient response (step response + time constant)
- `pdf` — LCR transient response (underdamped + critical damping)

## Tools & Equipment
- OrCAD / PSpice (transient simulation)
- Oscilloscope + waveform generator + multimeter (lab instrumentation)

## Key Results (high level)
### RC step response
- Measured time constants: **τ ≈ 156 μs** and **τ ≈ 94 μs** under different resistance conditions. :contentReference[oaicite:0]{index=0}  
- Estimated component values: **C ≈ 18.8 nF**, **R ≈ 5.0 kΩ**; resistor verified by DMM (**~5004 Ω**). :contentReference[oaicite:1]{index=1}  

### LCR transient response
- From measured peak decay and period: **α ≈ 75 s⁻¹**, **ω₀ ≈ 511 rad/s**. :contentReference[oaicite:2]{index=2}  
- Estimated: **L ≈ 3.8 H**, **coil resistance ≈ 580 Ω**. :contentReference[oaicite:3]{index=3}  
- Critical damping resistance: **R_c ≈ 3.9 kΩ** (matches theory). :contentReference[oaicite:4]{index=4}  

## What this demonstrates
- Building circuits from schematics and capturing transient responses on an oscilloscope  
- Extracting system parameters (τ, α, ω₀, damping regime) from measurements  
- Comparing measured behaviour against simulation (OrCAD/PSpice) and theory
