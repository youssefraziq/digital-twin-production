# Digital Twin — Production Cell (Sanitized Code Extract)
**Author:** Youssef Raziq

This repository contains a sanitized, synthetic-data notebook reproducing the
calculation logic, classification pipeline, dashboard logic, 3D data contract
and improvement-action engine of a real-time production monitoring and
digital-twin system deployed on a 3-machine production cell (P2, P3, M0,
M1M2M3), including:

- OEE / MTBF / MTTR calculation from timestamped machine events
- Vision-based OK/NOK quality classification (Keyence IV4-G500CA sensor)
  and PLC/pneumatic-cylinder rejection logic
- Shop-floor dashboard color-coding logic
- 3D digital-twin (Siemens Tecnomatix Plant Simulation) OPC UA data contract
- Power BI improvement-action rule engine
- ## Contents

notebooks/
├── digital_twin_kpi.ipynb   # runnable notebook
└── digital_twin_kpi.html    # static viewable export, no install needed

## Data disclaimer

All data in this notebook is synthetically generated (fixed-seed random
generators). No confidential production data, machine configuration, or
company-specific information is included. Real hardware photos included
(TEEPTRAK acquisition module, Keyence vision sensor, shop-floor dashboards,
Tecnomatix 3D model, Power BI report) illustrate the deployed system; no
proprietary product design or internal software configuration is shown.

## How to run

pip install -r requirements.txt
jupyter notebook notebooks/digital_twin_kpi_vision_demo.ipynb

Or simply open notebooks/digital_twin_kpi_vision_demo.html in any browser
— no installation required.
