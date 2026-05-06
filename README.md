# USB-C PD Power Board

A compact USB-C Power Delivery input board designed in KiCad.

## Overview

This board negotiates USB-C Power Delivery input voltage and generates regulated power rails for embedded electronics, robotics, development boards, and lab use.

## Key Features

- USB-C Power Delivery sink input
- Standalone PD negotiation controller
- Input voltage support up to 20 V
- Main regulated 5 V output
- Auxiliary 3.3 V output
- Input and output protection
- Status LEDs
- Test points for bring-up and debugging
- Designed in KiCad

## Target Specifications

| Parameter | Target |
|---|---:|
| Input connector | USB-C |
| PD role | Sink |
| Input voltage | 5 V / 9 V / 12 V / 15 V / 20 V |
| Main output | 5 V |
| Main output current | up to 3 A |
| Auxiliary output | 3.3 V |
| PCB | 2-layer / 4-layer |
| EDA | KiCad |

## Project Structure

```text
hardware/kicad      KiCad project files
hardware/datasheets Component datasheets
hardware/exports    Schematic PDF, board images, BOM
hardware/gerbers    Manufacturing files
hardware/assembly   Assembly drawings and pick-and-place files
hardware/3d         3D renders and models
docs                Documentation
production          Production notes and revisions
notes               Engineering notes
