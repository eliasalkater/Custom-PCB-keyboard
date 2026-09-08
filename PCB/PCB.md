# PCB Design

## Overview

The first PCB version for this project has already been completed.

The PCB is a 2-layer board designed for a 70% mechanical keyboard with
74 keys and USB-C connectivity and uses a Raspberry Pi Pico.

## Design goals

- Support the full keyboard matrix
- Use USB-C for connectivity
- Keep the PCB as compact as practical
- Use a 2-layer PCB
- Make the board compatible with the planned case

## Final design



### Main components

- Microcontroller: Raspberry Pi PIco
- Switches: Gateron Clear Switches
- Diodes: 1N4148

## PCB layout

<img width="1401" height="721" alt="image" src="https://github.com/user-attachments/assets/94c3b016-8e4b-4b96-a1f2-d91f35624a3f" />


The final PCB is a split design, but connected in the middle rather than being fully split halves, which limits mobility, but creates an easier design to manufacture but also work around regarding the design of the 3D printed case.

## Design decisions

One decision I made was using Gateron Clear switches because they have a relatively low actuation force, which means less strain on finger joints, allowing long sessions of programming to be less detrimental on joint health.

## Current status

The PCB design is complete and manufacturing files have been generated.
