# FPGA-Based Secure Communication System

A hardware security project that combines UART communication with chaos-inspired encryption concepts on a Xilinx Spartan-7 FPGA.

## Features

- UART Transmitter and Receiver implemented in Verilog
- Simplex and Full-Duplex Communication
- XOR-based Encryption and Decryption
- Chua's Circuit simulation for chaos generation
- Inductor-less Chua Circuit implementation
- LTspice and FPGA validation

---

## System Overview

```text
Input Data
    │
    ▼
XOR Encryption
    │
    ▼
UART Transmission
    │
    ▼
UART Reception
    │
    ▼
XOR Decryption
    │
    ▼
Recovered Data
```

Future work replaces the fixed XOR key with a dynamically generated chaotic key from synchronized Chua oscillators.

---

## Chua's Circuit

Chua's Circuit is a nonlinear electronic circuit capable of generating chaotic signals.

Applications:

- Secure Communication
- Random Number Generation
- Chaos-Based Cryptography

The project includes:

- Classical Chua Circuit
- Inductor-less Chua Circuit
- Multi-scroll Chua Oscillator simulations

---

## Hardware & Tools

### FPGA
- Xilinx Spartan-7
- Verilog HDL
- Vivado

### Circuit Design
- LTspice
- KiCad

---

## Repository Structure

```text
hardware/
├── kicad/
├── ltspice/

fpga/
├── uart_tx.v
├── uart_rx.v
├── xor_encryptor.v
├── xor_decryptor.v
└── top_module.v

simulations/
results/
docs/
```

---

## My Contributions

- Developed UART communication modules in Verilog
- Implemented duplex communication framework
- Integrated XOR-based encryption/decryption
- Performed FPGA validation on Spartan-7
- Simulated chaotic circuits in LTspice

---

## Future Improvements

- FPGA implementation of Chua oscillator
- Dynamic chaos-based key generation
- Real-time secure communication
- Hardware random number generation

---

## License

Academic and Research Use.
