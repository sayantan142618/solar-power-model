🌞 Solar Power Generation Model for Home (MATLAB Simulink)

This repository contains a MATLAB Simulink model for simulating solar power generation for residential applications. It demonstrates how solar photovoltaic (PV) systems can be designed, modeled, and analyzed for household electricity needs.

## 📂 Project Contents

- `solar_power_generation_model.slx`: Main Simulink model file.
- `README.md`: Project documentation and instructions.

## ⚙️ Requirements

- MATLAB R2020a or later
- Simulink
- Simscape
- Simscape Electrical (if used)

## 🚀 Getting Started

1. Clone or download this repository.
2. Open MATLAB.
3. Navigate to the project directory.
4. Open the Simulink model:
   ```matlab
   open_system('solar_power_generation_model.slx')
5. Click Run to simulate the system.

🖼 Model Overview
The model simulates a rooftop solar PV system suitable for home use. It includes:

Photovoltaic (PV) Array

DC-DC Converter (optionally with MPPT)

Inverter (DC to AC conversion)

Residential Load

Optional Grid Connection

📊 Simulation Outputs
Solar power generation

Load demand vs supply

Power imported/exported to the grid

System efficiency

🔧 Customization
Adjust PV array parameters to suit your region.

Add battery storage or MPPT controller.

Modify load characteristics.
