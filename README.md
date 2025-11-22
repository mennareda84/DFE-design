# DFE-design
This repository contains the design implementation of a multistage Digital Front End (DFE) for the SI-Clash competition, powered by IEEE SSCS AUSC.

## Project Structure
```
DFE-design/
│
├── fractional_decimator/
│   ├── RTL/                # RTL source code for fractional decimator
│   ├── golden_model/       # Python reference model for fractional decimator
│   └── testbench/          # Testbench and verification scripts for fractional decimator
│
├── notch_filter/
│   ├── 2_4MHz_notch/
│   │   ├── RTL_16_coe/     # RTL code for 2.4 MHz notch filter (16-bit)
│   │   ├── RTL_20_coe/     # RTL code for 2.4 MHz notch filter (20-bit)
│   │   ├── golden_model/   # Python models for 2.4 MHz notch filter
│   │   └── testbench/      # Testbench for 2.4 MHz notch filter
│   ├── 5MHz_notch/
│   │   ├── RTL/            # RTL code for 5 MHz notch filter (20-bit)
│   │   ├── golden_model/   # Python models for 5 MHz notch filter
│   │   └── testbench/      # Testbench for 5 MHz notch filter
│
├── cic_decimator/
│   ├── RTL/                # RTL source code for CIC decimator
│   ├── golden_model/       # Python reference model for CIC decimator
│   └── testbench/          # Testbench for CIC decimator
│
└── README.md
```
