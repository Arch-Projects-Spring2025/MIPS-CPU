# MIPS-CPU

### Single-Cycle and Pipelined MIPS Processor Implementations

A collection of MIPS processor designs developed in Logisim Evolution as part of the Computer Architecture course at Sharif University of Technology.

This project explores two fundamental processor architectures: a classic single-cycle MIPS processor and a pipelined MIPS processor. The goal is to understand how processor organization affects performance, complexity, and instruction execution.

---

## Overview

The MIPS architecture is widely used in computer architecture education because of its clean instruction set and straightforward datapath design.

This project implements:

* A Single-Cycle MIPS Processor
* A Pipelined MIPS Processor
* Supporting datapath and control logic
* Memory and register subsystems

Both designs were built and tested using Logisim Evolution.

---

## Single-Cycle Processor

The single-cycle implementation executes every instruction within a single clock cycle.

### Features

* 32-bit MIPS architecture
* Register File
* Arithmetic Logic Unit (ALU)
* Instruction Memory
* Data Memory
* Control Unit
* Branch and Jump Support

### Advantages

* Simple architecture
* Easy to debug
* Clear datapath organization

### Limitations

* Long clock period
* Lower throughput compared to pipelined processors

---

## Pipelined Processor

The pipelined implementation improves performance by overlapping instruction execution.

### Pipeline Stages

```text
IF  → Instruction Fetch
ID  → Instruction Decode
EX  → Execute
MEM → Memory Access
WB  → Write Back
```

Multiple instructions can be processed simultaneously at different stages of the pipeline, increasing instruction throughput.

### Concepts Explored

* Pipeline organization
* Instruction-level parallelism
* Control signal propagation
* Datapath partitioning

---

## Educational Objectives

This project was developed to gain practical experience with:

* CPU Datapath Design
* Control Unit Design
* MIPS Instruction Execution
* Pipeline Architecture
* Digital Logic Design
* Computer Architecture Fundamentals

---

## Tools Used

* Logisim Evolution
* MIPS ISA
* Digital Logic Design Techniques

---

## Repository Contents

The repository contains the Logisim circuit implementations and supporting project materials for both processor designs.

---

## Related Project

This processor family served as the basis for the MIPS-VPU project, which extends the architecture with a custom 128-bit SIMD Vector Processing Unit.

➡️ See: MIPS-VPU

---

## Authors

* Parmis Hemasian
* Sobhan Aghasi Zadeh

Computer Architecture Course – Spring 2025

Sharif University of Technology
