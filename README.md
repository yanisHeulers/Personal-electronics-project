# ±5V Power Supply from 9V Battery

This project implements a compact power supply that generates ±5 V rails from a single 9 V battery.

## Principle

The system works in two stages:

1. A voltage regulator converts the 9 V battery into a stable +5 V supply.
2. A DC-DC converter then generates a −5 V rail from the +5 V supply.

This results in two output voltages:

+5 V  
−5 V

## Tools used
- KiCad (schematic and PCB design)

## Repository structure
Personal-electronics-project
│
├── KiCad-project
│ ├── schematic.kicad_sch
│ ├── pcb.kicad_pcb
│ └── custom_symbols.kicad_sym
│
└── README.md
## Schematic

![Schematic](schematic_power_suply_PM5.png)

## PCB Layout

![PCB](pcb_power_suply_PM5.png)

## Author

Yanis Heulers  
Electrical Engineering Student — Polytechnique Montréal
