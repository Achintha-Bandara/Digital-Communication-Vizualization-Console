# 📡 Digital Communication Visualization Console

An embedded system designed to visualize and demonstrate fundamental concepts in digital communication systems. This project was developed as part of the fulfilment of the **Electronic Design Realization module (EN2160)**.

---

## 🧠 Overview

This device functions as an interactive educational lab instrument that allows users to explore the complete digital communication pipeline — from message input to transmission and reception — with real-time visual feedback.

The system integrates multiple displays, LEDs, and input controls to provide intuitive insight into how data is encoded, transmitted, affected by noise, and decoded.

---

## ⚙️ Features

### 🔤 Input System
- User message input via keypad (symbols A–E)
- Interactive menu-driven interface

---

### 📦 Source Coding
- Fixed-length coding
- Huffman coding (with probability input)
- Shannon-Fano coding

---

### 🛡️ Channel Coding
- Parity bits (error detection)
- Cyclic Redundancy Check (CRC)
- Hamming Code (error detection and correction)

---

### 📡 Modulation
- Amplitude Shift Keying (ASK)
- Binary Phase Shift Keying (BPSK)
- Quadrature Phase Shift Keying (QPSK)
- Quadrature Amplitude Modulation (QAM)

---

### 📊 Visualization
- Time-domain waveform display
- Constellation diagrams
- Step-by-step algorithm visualization
- Bitstream and encoding representation via LEDs

---

### 🌐 Channel Simulation
- Adjustable noise using analog control (knob)
- Transmission and reception visualization

---

## 🖥️ Hardware Architecture

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

## 🎯 Objectives

- Provide an intuitive understanding of digital communication systems
- Visualize abstract concepts such as encoding, modulation, and noise
- Bridge theoretical knowledge with practical implementation
- Serve as a low-cost educational lab tool

## 🎓 Acknowledgment

Developed as part of the **Electronic Design Realization module (EN2160)**.
