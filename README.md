# NEMA-17-Heat-Sink-Thermal-Analysis-Design

This project presents a complete thermal design and performance evaluation of a custom radial heat sink used to cool a NEMA 17 stepper motor under forced convection.

It includes:
- Python Calculaotr for thermal analysis.
- CAD model of heat sink and fan adapter designed in Solidworks.
- NEMA 17 heat sink assembly with a 40mm x 40mm axial fan.
- Visuals include PNG images of the assembly and individual components.

## Motivation
Stepper motors like the NEMA 17 can overheat if used for extended periods or enclosed environments. This project provides an optimized cooling solution using aluminum radial fins and a compact axial fan, designed to maintain safe operating temperatures and improve motor longevity.

## Project Structure
```
heat_sink_thermal_analysis/
├── heat_sink_calculator.py       # Python script for analysis
├── cad_files/                    # SolidWorks .SLDPRT and .SLDASM files
├── images/                       # PNGs: renders, 4-view layout
└── README.md                     # Project description (this file)
```

---

## Next Steps
- [ ] Add FEA-based temperature distribution validation
- [ ] Integrate CFD simulation for detailed airflow analysis

## Contact
Made by [Sai Sawant](https://www.linkedin.com/in/saisawant/) — Mechanical Engineering @ UNC Charlotte

Feel free to fork, use, or build upon this project!
