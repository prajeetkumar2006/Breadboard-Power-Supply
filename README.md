<h1 align="center">Breadboard Power Supply</h1>

## Description

Dual regulated power supply module converting 12 V DC to stable 5 V and 3.3 V outputs. Uses LM7805 for 5 V regulation and LM317 for adjustable 3.3 V output. Includes voltage selector jumpers, breadboard headers, and screw terminals for flexible output routing. Designed for powering microcontrollers, sensors, and prototyping circuits reliably.

## Hardware Used (BOM)

- DC Barrel Jack (with internal switch)
- SPDT Toggle Switch (Power ON/OFF)
- LM7805 Voltage Regulator (TO-220, 5V)
- LM317 Adjustable Voltage Regulator (TO-220, 3.3V)
- Resistors:
  - 330 Ω ×2 (LM317 voltage divider, LED current limit)
  - 560 Ω ×1 (LM317 voltage divider)
- Capacitors:
  - 10 µF Electrolytic ×1 (Input filtering)
  - 1 µF Electrolytic ×1 (3.3V output stability)
  - 0.1 µF Ceramic ×1 (5V output decoupling)
- LED ×1 (Power indicator)
- Jumper Headers (1×3, voltage selection)
- Pin Headers (1×2, breadboard output)
- Screw Terminal Connectors (2-pin, external output)
- PCB / Prototype Board

## Features
- Dual regulated outputs: 5V and 3.3V
- Selectable voltage routing via jumpers
- On-board power indication
- Designed for breadboard and external loads

## PCB Dimensions (Reference vs Current Design)

This power supply module is intended to be breadboard compatible.

### Reference Design Dimensions
- Overall Height: **49.7840 mm**
- Overall Width: **33.7822 mm**
- Side Extension Height: **40.6400 mm**

### Current PCB Design Dimensions
- Overall Height: **52.4256 mm**
- Overall Width: **31.0388 mm**
- Side Extension Height: **45.7708 mm**





