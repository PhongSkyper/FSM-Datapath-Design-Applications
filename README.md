# FSM-Datapath-Design-Applications

## Overview

A collection of advanced digital system design projects demonstrating the application of Finite State Machines (FSM) combined with datapaths in SystemVerilog. This course covers design methodology from high-level specifications through RTL implementation.

## Projects Overview

### 1. Vending Machine Controller
**Complete Implementation:** FSM → Datapath → SystemVerilog RTL

A fully functional vending machine controller that manages coin input, product selection, and dispensing logic.

**Components:**
- High-Level State Machine (HLSM) specification
- Datapath architecture with arithmetic and control logic
- SystemVerilog RTL implementation
- Complete design flow from specification to implementation

**Features:**
- Finite state machine for operational sequencing
- Multi-coin denomination support
- Product inventory management
- Change calculation and dispensing logic

---

### 2. Product Measurement System
**Partial Implementation:** HLSM → Datapath (No RTL)

A measurement system for acquiring and processing sensor data with state-machine-based control.

**Components:**
- High-Level State Machine (HLSM) design
- Datapath architecture for measurement and signal processing
- Control flow specification
- No SystemVerilog implementation (specification phase only)

**Features:**
- Sensor data acquisition sequencing
- Signal processing pipeline
- Measurement validation and filtering
- Data storage management

---

### 3. Min/Max Accelerator
**Partial Implementation:** HLSM → Datapath (No RTL)

An accelerator unit for computing minimum and maximum values from data streams using parallel processing architecture.

**Components:**
- High-Level State Machine (HLSM) for operation sequencing
- Datapath with parallel comparison and selection logic
- Multi-stage pipeline architecture
- No SystemVerilog implementation (specification phase only)

**Features:**
- Parallel min/max comparison
- Pipeline-based processing
- Data stream buffering
- Result accumulation and output

---

### 4. Memory Mapping
**Specification Only:** Memory Map Table + Implementation Circuit

Address translation and memory mapping architecture for embedded systems.

**Components:**
- Memory mapping table specification
- Virtual-to-physical address translation circuit
- TLB (Translation Lookaside Buffer) implementation
- No FSM or Datapath implementation (hardware mapping circuit only)

**Features:**
- Address translation logic
- Memory protection boundaries
- Cache-friendly access patterns
- Efficient mapping circuit design

---

## Project Statistics

| Project | HLSM | Datapath | RTL | Status |
|---------|------|----------|-----|--------|
| Vending Machine | ✓ | ✓ | ✓ | Complete |
| Product Measurement | ✓ | ✓ | ✗ | Specification |
| Min/Max Accelerator | ✓ | ✓ | ✗ | Specification |
| Memory Mapping | ✗ | ✗ | ✓ Circuit | Specification |

## Design Methodology

This project demonstrates the complete digital system design flow:

1. **Specification Phase** - Define requirements and behavior using HLSM
2. **Datapath Design** - Design arithmetic and control logic circuits
3. **RTL Implementation** - Implement in SystemVerilog (where applicable)
4. **Verification** - Validate functionality against specifications

## Tools & Technologies

- **Design Specification**: High-Level State Machines (HLSM), Datapath diagrams
- **HDL**: SystemVerilog
- **Methodology**: FSM + Datapath Co-design

## Key Learning Outcomes

- FSM design and state machine optimization
- Datapath architecture and resource sharing
- Control signal generation and synchronization
- SystemVerilog RTL implementation of complex controllers
- Design-to-implementation flow

## Project Structure

```
PROJECT3/
├── README.md (this file)
├── docs/
│   ├── Vending Machine Controller documentation
│   ├── Product Measurement System documentation
│   ├── Min/Max Accelerator documentation
│   └── Memory Mapping documentation
├── vending_machine/
│   ├── fsm/                  # FSM specification
│   ├── datapath/             # Datapath architecture
│   └── rtl/                  # SystemVerilog implementation
├── measurement_system/
│   ├── hlsm/                 # High-Level State Machine
│   └── datapath/             # Datapath design (Specification only)
├── min_max_accelerator/
│   ├── hlsm/                 # High-Level State Machine
│   └── datapath/             # Datapath design (Specification only)
└── memory_mapping/
    └── mapping_circuit/      # Memory mapping implementation
```

## Implementation Status

### ✓ Complete
- **Vending Machine Controller** - Full FSM, Datapath, and RTL implementation

### ⊙ Specification Phase
- **Product Measurement System** - FSM and Datapath designed, awaiting RTL
- **Min/Max Accelerator** - FSM and Datapath designed, awaiting RTL
- **Memory Mapping** - Circuit implementation only, mapping table specified

## Future Work

- RTL implementation for Product Measurement System
- RTL implementation for Min/Max Accelerator
- Testbench development for all modules
- Performance and resource utilization analysis
- Hardware synthesis and mapping

## Author

**Course Project**
FSM-Datapath Design Applications

---

**Last Updated:** November 1, 2025
**Status:** Specification & Implementation Phase ⊙
