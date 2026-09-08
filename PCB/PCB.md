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

<img width="1401" height="721" alt="image" src="https://github.com/user-attachments/assets/7f86c337-d58e-4a7b-8147-16b3090b7ebd" />

The final PCB is a split design, but connected in the middle rather than being fully split halves, which limits mobility, but creates an easier design to manufacture around.

## Design decisions

One decision I made was using Gateron Clear switches because they have a relatively low actuation force, which means less strain on finger joints, allowing long sessions of programming to be less detrimental on joint health.

## Current status

The PCB design is complete and manufacturing files have been generated.
