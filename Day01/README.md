# Day 01 – Introduction to FPGA
## Objective
- Understand the evolution of programmable logic devices.
- Learn what an FPGA is.
- Compare FPGA and ASIC.
- Explore FPGA applications.
- Understand the basic FPGA architecture.
---

## Evolution of Programmable Logic Devices
Programmable logic devices evolved to allow designers to implement custom digital hardware without manufacturing a new integrated circuit every time.
The evolution is:
- PLA (Programmable Logic Array)
- CPLD (Complex Programmable Logic Device)
- FPGA (Field Programmable Gate Array)
- 
FPGA enables designers to build customizable hardware while studying important design parameters such as:
- Area
- Speed
- Power

## FPGA Development Board
The workshop uses the **Basys-3 FPGA Development Board**.
An FPGA board contains:
- FPGA chip
- Push buttons
- Switches
- LEDs
- Seven-segment display
- USB programming interface
- GPIO connectors
These peripherals help implement and verify digital designs.

> **Insert Screenshot 2 here**
> **Caption:** Basys-3 FPGA Development Board

---

# 3. What is an FPGA?

FPGA stands for

**Field Programmable Gate Array**

It is an integrated circuit that can be programmed by the designer after manufacturing.

Unlike fixed-function ICs, an FPGA can implement different digital circuits simply by changing its configuration.

FPGA designs are described using Hardware Description Languages (HDLs) such as:

- Verilog HDL
- VHDL

FPGA internally consists of:

- Look-Up Tables (LUTs)
- Flip-Flops (FFs)
- Configurable Logic Blocks (CLBs)
- Programmable Routing

> **Insert Screenshot 3 here**
>
> **Caption:** What is an FPGA?

---

# 4. FPGA vs ASIC

| FPGA | ASIC |
|-------|------|
| Reprogrammable | Cannot be reprogrammed after fabrication |
| Uses configurable hardware | Dedicated hardware |
| Faster development | Longer development cycle |
| Lower initial cost | Higher fabrication cost |
| Suitable for prototyping | Suitable for mass production |

ASIC design flow:

RTL → Synthesis → Physical Design → Fabrication

FPGA design flow:

RTL → Synthesis → Bitstream Generation → FPGA Programming

> **Insert Screenshot 4 here**
>
> **Caption:** FPGA vs ASIC

---

# 5. Applications of FPGA

FPGAs are widely used in:

- Hardware Acceleration
- Signal Processing
- Device Controllers
- Embedded Systems
- Aerospace
- High Performance Computing (HPC)
- Machine Learning and AI

> **Insert Screenshot 5 here**
>
> **Caption:** Applications of FPGA

---

# 6. Basic FPGA Architecture

An FPGA mainly consists of:

- Configurable Logic Blocks (CLBs)
- Programmable Interconnect
- Programmable I/O Blocks
- Configuration Memory
- Clock Network

### Configurable Logic Block (CLB)

A CLB contains:

- Look-Up Tables (LUTs)
- Carry Chain
- Multiplexers
- Flip-Flops

Configuration memory stores the **bitstream** generated after synthesis.

This bitstream programs the FPGA hardware.

> **Insert Screenshot 6 here**
>
> **Caption:** Basic FPGA Architecture

---

# Key Takeaways

- FPGA is a programmable digital hardware device.
- Verilog/VHDL are used to describe FPGA hardware.
- FPGA can be reprogrammed multiple times.
- FPGA is ideal for prototyping and hardware acceleration.
- CLBs, LUTs, Flip-Flops, and Routing form the FPGA architecture.

---

# Learning Outcome

After completing Day 01, I understood:

- Evolution of programmable logic devices.
- FPGA fundamentals.
- FPGA vs ASIC.
- FPGA applications.
- Basic FPGA architecture.
