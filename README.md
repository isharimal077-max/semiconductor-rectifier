# semiconductor-rectifier
AC to DC rectification experiment using semiconductor diodes (half-wave and full-wave)
![Half Wave Rectifier](docs/images/half-wave.png)
![Full Wave Rectifier](docs/images/full-wave.png)
Semiconductor Rectifier Project

A practical demonstration of how a p–n junction diode converts AC into DC using half-wave and full-wave rectification. Includes circuits, LED tests, theoretical summary, and a complete project report stored in the docs/ folder.

Overview

This project explores how semiconductor diodes behave as rectifiers. Two circuits were built and tested:

Half-wave rectifier (single diode)

Full-wave bridge rectifier (four diodes)

LEDs were used as load indicators to verify current flow, polarity, and rectified output. The goal was to observe how AC can be converted to pulsating DC and compare the behavior of both rectifier types.

Features

Half-wave rectifier circuit

Full-wave bridge rectifier

LED polarity and conduction tests

Practical observations and results

Theory summary

Full physics report in /docs/report.docx

Circuit Diagrams

Add your diagrams to docs/images/ and reference them here. Example:

![Half Wave Rectifier](docs/images/half-wave.png)
![Full Wave Rectifier](docs/images/full-wave.png)


If you don’t have diagrams yet, create simple ones later and upload them.

How Rectification Works

A diode conducts when forward biased and blocks current when reverse biased.

In a half-wave rectifier, only the positive (or negative) half of AC passes.

In a bridge rectifier, both halves of AC are routed to the load with the same polarity.

This produces pulsating DC, which can be smoothed using a capacitor (optional upgrade).

Results

In half-wave mode, the LED glows only during forward-biased cycles.

Reversing the diode stops conduction (LED off or very dim).

In a full-wave bridge, the LED glows more steadily because both halves of AC contribute.

Under DC testing, the LED glows only if the anode is positive.

These results match the theoretical behavior of p–n junction diodes.

Folder Structure
semiconductor-rectifier/
│
├── README.md
├── LICENSE
│
├── docs/
│   ├── report.docx
│   └── images/
│       ├── half-wave.png
│       ├── full-wave.png
│       └── observations.png
│
└── circuits/
    ├── half-wave.falstad
    └── full-wave.falstad


Add images, simulations, or breadboard photos here to make your repo stronger.

Report

The full physics project report is included in:

/docs/report.docx

Author

Isha Rimal
Grade XII — Physics Project
