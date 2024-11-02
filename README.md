# AM16K: 16-bit Educational RISC Processor

A fully functional 16-bit processor implementation in Proteus, featuring a complete instruction set with arithmetic, logical, and shift operations. This educational processor design demonstrates fundamental computer architecture principles through a modular, top-down approach.

## Architecture Overview

The AM16K implements a basic but complete processor architecture with five major components:
- Control Unit with Logic Gates
- Arithmetic Logic Unit (ALU)
- Common Bus System
- Register Array
- Memory Module (32 slots × 16-bit)

### Key Features
- 16-bit word size
- 32 memory slots
- 9 general-purpose registers
- Modular design approach
- Complete RTL instruction support
- Comprehensive testing interface

## Core Components

### Control Unit
- 4×16 Decoder
- 4-bit Sequence Counter
- 3×8 Decoder
- Instruction Register
- Control Logic Gates
- Timing signal generation

### ALU Capabilities
- Arithmetic Operations
  - Addition
  - Subtraction
  - Increment
  - Decrement
- Logical Operations
  - AND
  - OR
  - XOR
  - NOT
- Shift Operations
  - Left shift
  - Right shift
  - Circular shift

### Memory System
- 32 memory slots
- 16-bit word size
- Read/Write control
- 5-bit addressing
- Direct and indirect memory referencing

### Bus System
- Multiplexer-based selection
- Common data pathway
- Inter-component communication

## Implementation Details

### Development Environment
- Proteus 8 Simulation Software
- Native I/O components for testing

### Register Structure
- Implementation using flip-flop arrays
- 1-bit register building blocks
- Multiple register configurations

## Testing and Validation

### Verified Operations
- Register Transfer Language (RTL) instructions
- Memory read/write operations
- Direct and indirect memory referencing
- All arithmetic operations
- All logical operations
- All shift operations

### Test Components
- Logic states
- Thumbtacks
- Logic probes
- 7-segment displays

## Project Structure

```
/src
  ├── control_unit/
  │   ├── sequence_counter/
  │   ├── decoders/
  │   └── control_gates/
  ├── alu/
  │   ├── arithmetic_unit/
  │   ├── logic_unit/
  │   └── shift_unit/
  ├── memory/
  │   ├── memory_array/
  │   └── address_decoder/
  ├── registers/
  └── common_bus/
```

## Getting Started

### Prerequisites
- Proteus 8 or later
- Basic understanding of digital logic
- Familiarity with computer architecture concepts

### Installation
1. Clone the repository
2. Open the main project file in Proteus
3. Load the provided test configurations

## Extra
- AMD's 29k architecture (inspiration for naming)

