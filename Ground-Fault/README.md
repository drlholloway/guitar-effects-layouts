# Ground Fault
| Front | Guts |
|-------|------|
| To Do | To Do |

## Table of Contents
1. [Introduction](#introduction)
2. [Schematic](#schematic)
3. [PCB](#pcb)
4. [Faceplate](#faceplate)
5. [Tayda Drill Template](#tayda-drill-template)
6. [BOM](#bom)
7. [Notes](#notes)

## Introduction

Ground Swell is a clone of Fuzzhugger FX's [Arc Flash](https://www.youtube.com/watch?v=OBF0-cEVhbo) pedal that is, sadly, out of production. The [trace](https://forum.pedalpcb.com/threads/fuzzhugger-arc-flash.10081/post-361108) is from the user Almondcity on the PedalPCB forums. The only large changes I've made to the trace is more filtering on the DC input, otherwise it is exactly as presented in the trace.

## Schematic
![Schematic](ground-fault-schematic.png)

## PCB
![PCB](ground-fault-pcb.png)

## Faceplate
![Faceplate](ground-fault-faceplate.png)

## Tayda Drill Template
[Tayda 125B](https://drill.taydakits.com/box-designs/new?public_key=VUFTUjk3Z09yUTNtdURocVpsd3NtZz09Cg==) drill template

## BOM

### Resistors

| Component Name | Value | Note               |
|----------------|-------|--------------------|
| R1             | 1M    |  |
| R2             | 100k  |  |
| R3             | 1M    |  |
| R4             | 100k  |  |
| R5             | 1k    | Current limiting resistor, choose to taste |

### Capacitors

| Component Name | Value | Note               |
|----------------|-------|--------------------|
| C1             | 33nF  | Film               |
| C2             | 10u   | Electrolytic       |
| C3             | 2u2   | Electrolytic       |
| C4             | 10u   | Electrolytic       |
| C5             | 100nF | Film               |
| C6             | 100u  | Electrolytic       |
| C7             | 100nF | Film               |

### Diodes

| Component Name | Value   | Note               |
|----------------|---------|--------------------|
| D1             | LED 5mm red | |
| D2             | 1N34A   |                    |
| D3             | LED 5mm red | |
| D4             | 1N5817  |                    |
| D5             | LED 3mm | Status LED, pick your poison |

### Transistors

| Component Name | Value   | Note               |
|----------------|---------|--------------------|
| Q1             | 2N5089  |                    |
| Q2             | 2N5089  |                    |

### Potentiometers, Switches, Jacks, etc.

| Component Name | Value   | Note                 |
|----------------|---------|----------------------|
| RV1 - GAIN     | 500kB   | 16mm right angle pot |
| RV2 - FREQUENCY| 250kA   | 16mm right angle pot |
| RV3 - LEVEL    | 100kA   | 16mm right angle pot |
| SW1 - MODE     | DPDT    | On / On              |
| Footswitch     | 3PDT    |                      |
| audio jack x2  | mono    |                      |
| dc jack        | 9v      |                      |

## Notes
1. There is a slight difference in the Arc Flash over time. My Arc Flash pedal as R1 connected to lug 3 of RV1 then to ground as opposed to the trace I used from almondcity where it comes off lug 2 of RV1 then to ground. I can't tell a difference between them, so I just kept it the same. If you really want the same version as what I have you can simply leave R1 unoccupied and then solder a 1M resistor to pins 1 and 3 of the RV1 potentiometer.

## Licensing

[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This layout is licensed with a Creative Commons BY-NC-SA 4.0 license (Attribution, Non-commercial, Share-alike).
