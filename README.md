# Project-Portfolio
A collection of projects I have worked on, currently all related to my university studies

MSP430 Microcontroller projects

MK1 - Seven-segment counter
  Implemented a tilt-controlled 7-segment counter in MSP430 assembly. The system counts up or down 
depending on tilt input, updates a 7-segment display, and controls RGB LEDs via pushbuttons.
Features input debouncing, subroutines, binary segment control, and software delay loops.

MK2 - Melody player
  Created a melody player on the MSP430 microcontroller using TimerA and GPIO toggling to drive a 
piezo buzzer. Implemented note frequency tables, duration timing, and a melody array in assembly.
Experimented with timer-based PWM generation and frequency division algorithms for tone synthesis.

MK3 - LED controller
  Implemented a multi-channel RGB LED controller in MSP430 assembly using ADC sampling and PWM 
generation. Enabled dynamic color intensity control via a potentiometer with button-selected 
channels, fully configured via register-level programming without libraries.

MK4 - Seven-segment controller with interrupt
  Designed an interrupt-driven 7-segment display counter in MSP430 assembly with hardware-based
timing and button input control. Implemented lookup tables, timer interrupts, and state toggling 
logic to handle run/stop and up/down modes.

Altium Projects

oblig4BGJ - 4-Band Analog Audio Equalizer — PCB Project
  Designed a 4-band analog audio equalizer using active band-pass filters based on NE5532 op-amps.
Developed all schematics, power supply stage, and PCB layout in Altium Designer, including custom 
component libraries. Implemented RC filter networks for four frequency bands, dual-rail power supply,
and low-noise analog grounding strategy. Verified design through ERC/DRC checks and BOM generation.

555-timer - Clock
  Designed and simulated a digital clock circuit using a 555 timer and SN74LS90 counters. Implemented
cascading logic for minute and second counting, integrated BCD decoding, and created full schematic
and BOM documentation in Altium Designer.



