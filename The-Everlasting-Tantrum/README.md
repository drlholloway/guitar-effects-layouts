# The Everlasting Tantrum

## Introduction
**The Everlasting Tantrum** is my take on an unreleased fuzz pedal that was designed by DOD and Devi Ever. It was essentially a Hyperion followed by a Big Muff style tone stack and then a booster stage afterwards. I've augmented it with a switch to bypass the tone stack, another switch to allow you to choose between three different Devi Ever fuzzes, and an oscillation potentiometer that lets you introduce feedback into the fuzz circuit itself.

## Schematic
![Schematic](<Grindhaus Fuzz.svg>)

## PCB
![PCB](<the-everlasting-tantrum-2025-09-21.png>)

## Faceplate
![Faceplate](<the-everlasting-tantrum-faceplate-2025-09-21.png>)

## Tayda Drill Template
The pedal is designed to use a 125B enclosure. You can use purchase an enclosure from Tayda and use the following template:
[The Everlasting Tantrum Drill Template](https://drill.taydakits.com/box-designs/new?public_key=S0pqNkJnV1BzY3hzMG5XK1VDK2J4UT09Cg==).

## BOM

### Resistors

| Component Name | Value | Note               |
|----------------|-------|--------------------|
| R1             | 1M    | Pull down resistor |
| R2             | 1k    |                    |
| R3             | 2M2   |                    |
| R4             | 10k   |                    |
| R5             | 2M2   |                    |
| R6             | 10k   |                    |
| R7             | 39k   | Big Muff Tone Stack|
| R8             | 39k   | Big Muff Tone Stack|
| R9             | 150k  |                    |
| R10            | 2M2   |                    |
| R11            | 10k   |                    |
| RLED1          | 1k    | Current limiting resistor, choose to taste |

### Capacitors

| Component Name | Value | Note               |
|----------------|-------|--------------------|
| C1             | 100nF | Film               |
| C2             | 100nF | Film               |
| C3             | 100nF | Film               |
| C4             | 100nF | Film               |
| C5             | 100nF | Film               |
| C6             | 100nF | Film               |
| C7             | 4nF   | Film, Big Muff Tone Stack |
| C8             | 10nF  | Film, Big Muff Tone Stack |
| C9             | 100nF | Film               |
| C10            | 100nF | Film               |
| C100           | 100uF | Electrolytic       |
| C101           | 100nF | Film               |

### Diodes

| Component Name | Value   | Note               |
|----------------|---------|--------------------|
| D1             | LED 3mm | choose your poison, 5mm works as well. |
| D2             | 1N5817  |                    |

### Transistors

| Component Name | Value   | Note               |
|----------------|---------|--------------------|
| Q1             | MPSA18  |                    |
| Q2             | MPSA18  |                    |
| Q3             | 2N2907A |                    |
| Q4             | MPSA18  |                    |

### Potentiometers, Switches, Jacks, etc.

| Component Name | Value   | Note                 |
|----------------|---------|----------------------|
| INPUT1         | 100kB   | 16mm right angle pot |
| OSC1           | 10kA    | 16mm right angle pot |
| TONE1          | 100kB   | 16mm right angle pot |
| VOL1           | 100kA   | 16mm right angle pot |
| SW1            | SPDT    | On / Off / On        |
| SW2            | DPDT    | On / On              |
| Footswitch     | 3PDT    |                      |
| audio jack x2  | mono    |                      |
| dc jack        | 9v      |                      |

### Notes

1. R7, R8, C7, and C8 make up the Big Muff style tone stack. You can modify these to taste and choose other Big Muff style tone stacks (Triangle, Green Russian, etc.)
2. If you use the faceplate, make sure you mount the LED directly against the PCB as it will get a stronger light.
