# Analog Circuits and Common Electronic Components

[中文](README.md) | [English](README-English.md)

This repository organizes learning materials about analog circuits, common electronic components, semiconductor devices, and hardware-parameter English terminology. The content is based on the PDF and DOCX materials in `docs/` and is suitable for embedded software engineers, hardware beginners, and electronics fundamentals study.

## Materials

### Analog Circuits and Common Electronic Components

- [PDF course material](docs/模拟电路基础与常用元器件.pdf)
- [DOCX editable version](docs/模拟电路基础与常用元器件.docx)

### Common English for Hardware Parameters

- [PDF glossary](docs/硬件参数常用英文.pdf)
- [DOCX editable version](docs/硬件参数常用英文.docx)

## Learning Roadmap

```text
Electrical fundamentals
    ├── Current, voltage, resistance, and circuits
    ├── DC, AC, low-voltage, and high-voltage electricity
    └── Ohm's law, power, Joule's law, series, and parallel circuits
            ↓
Common electronic components
    ├── Resistors, capacitors, and inductors
    ├── Ferrite beads, relays, fuses, and connectors
    ├── Buzzers, crystals, batteries, and regulator ICs
    └── Multimeters and circuit simulation software
            ↓
Analog circuits and semiconductors
    ├── Analog signals and analog circuits
    ├── Diodes and Zener diodes
    ├── Bipolar junction transistors
    └── MOSFETs
            ↓
Typical circuit practice
    ├── Varistors, pull-up resistors, and pull-down resistors
    ├── Current-limiting resistors and zero-ohm resistors
    └── Filtering, coupling, and bypass capacitors
            ↓
Measurement and engineering practice
    ├── Common electrical symbols
    ├── DC regulated power supplies
    └── Oscilloscopes and multimeters
```

## Contents

### Chapter 1: Electrical Fundamentals

- Understand current, voltage, resistance, and the basic structure of a circuit.
- Distinguish direct current from alternating current and low-voltage systems from high-voltage systems.
- Learn the basic concepts of open circuits, closed circuits, short circuits, and household circuits.
- Study Ohm's law, power calculations, and Joule's law.
- Understand the basic characteristics of series and parallel circuits.

### Chapter 2: Common Electronic Components

- Use circuit simulation software to observe basic circuit behavior.
- Understand resistor resistance, power rating, tolerance, and resistance identification.
- Learn fixed resistors, variable resistors, and special resistors such as photoresistors, thermistors, and varistors.
- Understand capacitor capacitance, voltage rating, tolerance, fixed capacitors, variable capacitors, and supercapacitors.
- Learn the energy-storage and DC-pass/AC-block characteristics of inductors.
- Learn ferrite beads, relays, fuses, connectors, and tactile switches.
- Distinguish active and passive buzzers and understand their common parameters.
- Learn the basic parameters of crystals, batteries, and voltage-regulator ICs.
- Learn the basic functions, measurement methods, and safety requirements of multimeters.

### Chapter 3: Analog Circuit Fundamentals

- Distinguish continuous analog signals from discrete digital signals.
- Understand how analog circuits filter, amplify, and transfer signals.
- Understand the one-way conduction characteristic of diodes.
- Learn the use of LEDs, seven-segment displays, and Zener diodes.
- Understand the basic structures and switching principles of NPN and PNP transistors.
- Understand how MOSFETs use an electric field to control current.
- Use the light-sensitive lamp example to connect sensor signals with component control.

### Chapter 4: Typical Circuit Practice

- Varistors: overvoltage protection and voltage clamping for surge events.
- Pull-up resistors: keep a signal line at a logic-high level when idle.
- Pull-down resistors: keep a signal line at a logic-low level when idle.
- Current-limiting resistors: keep component current within the normal operating range.
- Zero-ohm resistors: bridging, debugging, measurement, and PCB routing adjustments.
- Filter capacitors: suppress noise in power and signal paths.
- Coupling capacitors: block DC components while passing AC signals.
- Bypass capacitors: provide a low-impedance path for high-frequency noise.

### Chapter 5: Appendix and Instrument Use

- Common electrical symbols such as `VCC`, `GND`, `AC`, and `DC`.
- Input, output, constant-voltage, and constant-current states of DC regulated power supplies.
- Basic use cases for multimeters and oscilloscopes.

## Hardware Parameter Vocabulary

| English | Meaning |
| --- | --- |
| `DC / Direct Current` | Direct current |
| `AC / Alternating Current` | Alternating current |
| `Current` | Electric current |
| `Voltage` | Voltage |
| `Power` | Power |
| `Rated Power` | Rated power |
| `Rated Current` | Rated current |
| `Rated Voltage` | Rated voltage |
| `Resistance` | Resistance value |
| `Capacitance` | Capacitance |
| `Tolerance` | Allowed tolerance |
| `Temperature Range` | Temperature range |
| `Operating Temperature Range` | Operating temperature range |
| `Maximum / MAX` | Maximum value |
| `Minimum / MIN` | Minimum value |
| `Maximum Working Voltage` | Maximum working voltage |
| `Maximum Allowable Voltage` | Maximum allowable voltage |
| `Withstand Voltage` | Withstand voltage |
| `Overload Voltage` | Overload voltage |
| `Forward Voltage` | Forward voltage |
| `Varistor Voltage` | Varistor voltage |
| `Maximum Clamping Voltage` | Maximum clamping voltage |
| `Surge Current` | Surge current |
| `Impulse Response Time` | Impulse response time |
| `Storage Temperature Range` | Storage temperature range |

## Component Selection Checklist

When reading a component datasheet, confirm at least:

- Operating voltage and maximum allowable voltage.
- Operating current, maximum current, and surge current.
- Power rating, thermal conditions, and operating temperature range.
- Nominal value, tolerance, accuracy, and temperature coefficient.
- Package, pin definition, polarity, and mounting orientation.
- Normal operating conditions, overload conditions, and protection behavior.

Rated and maximum values in a datasheet define important engineering limits. Components should not be replaced only by appearance or a similar part name.

## Safety Notes

- Mains and high-voltage circuits involve electric-shock, short-circuit, and fire hazards and must not be treated as low-voltage experiments.
- Before measuring, confirm the multimeter function, probe sockets, range, and the expected signal level.
- Never connect a multimeter in current mode directly across a power source.
- Do not change ranges, move components, or alter wiring casually while a circuit is powered.
- Check polarity, voltage rating, and discharge state when working with capacitors, regulated supplies, and batteries.
- For real designs and repairs, follow datasheets, laboratory procedures, and applicable safety standards.

## Directory Structure

```text
analog-circuits-and-components/
├── README.md
├── README-English.md
└── docs/
    ├── 模拟电路基础与常用元器件.pdf
    ├── 模拟电路基础与常用元器件.docx
    ├── 硬件参数常用英文.pdf
    └── 硬件参数常用英文.docx
```

## Keywords

`Analog Circuits` `Electronic Components` `Circuit Fundamentals` `Resistor` `Capacitor` `Inductor` `Diode` `BJT` `MOSFET` `Power Supply` `Oscilloscope` `Multimeter`
