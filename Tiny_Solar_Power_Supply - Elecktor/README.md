# Tiny Solar Supply
A tiny solar-powered regulated 3.3V supply based on the AP3015 boost converter. Charges a 1.2V Ni-MH AA battery from a solar panel during the day, and automatically powers your circuit at night.
# Components
ReferenceComponentDescriptionU1AP3015 / AP3015AStep-up DC/DC converterL1ASPI-0630LRShielded SMD inductorQ1N-ch MOSFETDay/night auto-switchD1, D2Schottky diodeOutput & charge diodesC1, C2, C3CapacitorsFiltering & bypassR1–R4ResistorsFeedback & biasJ1Connector3.3V outputJ2ConnectorBattery inputJ3JumperManual On/OffJ4ConnectorSolar panel input
# Output Voltage
VOUT = 1.23 × (1 + R1/R2) → default 3.3 V
# Files
scheamtic_image.pdf
3D View (PNG)
Gerber Files

# Tools Used
KiCad 5

# Reference
Based on Elektor Labs – Tiny Solar Supply
# Status
Design Complete
# 3d image
![Solar PCB 3d](Solar%20PCB_3d.png)
# Schematic View 
[View Schematic](View_schematic_image.pdf)
