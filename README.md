<img width="1920" height="1080" alt="DCVC-pitch" src="https://github.com/user-attachments/assets/11a73ae0-f59d-4dd0-a54a-d8d3205573af" />

# Digital Communication Visualization Console

An embedded system designed to visualize and demonstrate fundamental concepts in digital communication systems.

---

## Overview

This device functions as an interactive educational lab instrument that allows users to explore the complete digital communication pipeline - from message input to transmission and reception - with real-time visual feedback.

The system integrates multiple displays, LEDs, and input controls to provide intuitive insight into how data is encoded, transmitted, affected by noise, and decoded.

---

## Features

### Input System
- User message input via keypad (symbols A–E)
- Interactive menu-driven interface

---

### Source Coding
- Fixed-length coding
- Huffman coding
- Shannon-Fano coding

---

### Channel Coding
- Parity bits (error detection)
- Cyclic Redundancy Check (CRC)

---

### Modulation
- Amplitude Shift Keying (ASK)
- Binary Phase Shift Keying (BPSK)
- Quadrature Phase Shift Keying (QPSK)
- Quadrature Amplitude Modulation (QAM)
- Frequency Shift Keying (FSK)

---

### Visualization
- Time-domain waveform display
- Constellation diagrams
- Step-by-step algorithm visualization
- Bitstream and encoding representation via LEDs

---

### Channel Simulation
- Adjustable noise using analog control (knob)
- Transmission and reception visualization

---

## Hardware Architecture

- Microcontroller: STM32
- Displays:
  - 2 × 3.5" SPI TFT displays
- Input:
  - Push buttons / keypad
- Output:
  - LED arrays for code visualization
- Analog input:
  - Potentiometer for noise control

---

## Objectives

- Provide an intuitive understanding of digital communication systems
- Visualize abstract concepts such as encoding, modulation, and noise
- Bridge theoretical knowledge with practical implementation
- Serve as a low-cost educational lab tool

## Acknowledgment

Developed as part of the **EN2160 - Electronic Design Realization** module.
