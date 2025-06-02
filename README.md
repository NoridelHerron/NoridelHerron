# Noridel Herron

**Computer Engineering | Digital Design | VHDL Projects**

**Welcome to my GitHub!**
  I’m currently pursuing a degree in Computer Engineering, with a focus on digital design and hardware architecture. My latest project is a fully custom, 5-stage pipelined RISC-V CPU built entirely in VHDL — complete with modular RTL components, working forwarding logic, and waveform-based debugging for integration.

  Earlier in my journey, I built key components like a 32-bit ALU, memory modules, and a full register file, all tested with both fixed and randomized testbenches. Through hands-on debugging and iteration, I’ve refined my understanding of control flow, hazard detection, and pipelined timing.

I'm open to feedback, collaboration, and new challenges — especially around CPU design, verification, or system-level architecture. Let’s connect and learn together!

## ⚠️ Learning Disclaimer

I am still learning, and this project is part of my hands-on learning process. If you find any bugs, mistakes, or incorrect assumptions in my work or documentation, please trust yourself, double-check with trusted resources, and feel free to let me know!
I expect to make many improvements and corrections as I continue developing this project and deepening my understanding.
If you have suggestions or spot issues, I truly welcome the feedback so I can continue improving.

## Featured Projects
### [Pipelined-RISC-V-CPU-in-VHDL-From-Scratch-to-Simulation](https://github.com/NoridelHerron/Pipelined-RISC-V-CPU-in-VHDL-From-Scratch-to-Simulation) 
## Project Status:
### Current Status:
Pipeline Refactored and Verified — Current Status (June 2, 2025):
I completed a major refactoring of my pipelined RISC-V CPU project today. The pipeline structure is now clean and verified:
- Decoder + Hazard Detection Unit combined → simplifies stage control
- Execution + Forwarding Unit combined → ensures efficient data hazard resolution
- Forwarding paths and stall logic fully verified in waveform
- No red waves, no hazards leaking through — clean, stable pipeline

### Next steps:
- Update documentation
- Add branch and jump instruction support.
- clean up
- Then, if you have suggestions or challenges, I’d love to take them on
- **Longer term**: integrate shared memory and visualize/compare behavior of multiple CPU architectures side by side

## Archive Repos (Earlier Work)
The following repositories are older versions of individual pipeline stages.
➡️ My latest and integrated CPU is in the main pipeline repo.
However, some notes — especially on randomized testbench design — may still be useful to others learning VHDL and CPU architecture:

### [INSTRUCTION_FETCH](https://github.com/NoridelHerron/INSTRUCTION_FETCH)  
VHDL implementation of the Instruction Fetch stage for a custom RISC-V pipeline CPU. Includes program counter, instruction memory interface, and testbench validation.

### [ID_STAGE](https://github.com/NoridelHerron/ID_STAGE)  
Implements the Instruction Decode stage of a 5-stage pipelined RISC-V CPU. Extracts opcode, register values, function codes, and immediate values from a 32-bit instruction. Generates control signals and interfaces with the register file to retrieve operands.

### [EX_STAGE](https://github.com/NoridelHerron/EX_STAGE)  
Execute stage for a pipelined RISC-V CPU. Integrates ALU, forwarding inputs, and control logic with pipeline register support. Validated using a randomized testbench.

### [MEM_STAGE](https://github.com/NoridelHerron/MEM_STAGE)
Implements the Memory stage of a 5-stage pipelined RISC-V CPU. Handles lw and sw instructions, memory read/write via DATA_MEM, and passes necessary control signals. Verified with 5000 randomized test cases and waveform analysis, including intentional bug injection.

### [DATA_MEM](https://github.com/NoridelHerron/DATA_MEM)  
Synchronous 32-bit word-addressable memory module with support for 1024 memory locations. Includes a reusable formatting function and randomized testbench with assertion-based verification and waveform validation.

### [ALU_with_testBenches_vhdl](https://github.com/NoridelHerron/ALU_with_testBenches_vhdl)  
A fully functional 32-bit ALU in VHDL with signed/unsigned operations, flag generation (Z, N, C, V), and comprehensive testbenches including randomized edge-case validation.

### [32x32-bit Register File](https://github.com/NoridelHerron/32x32-bit-Register-File-in-VHDL-)  
Implements a synchronous register file with 32 registers, each 32 bits wide. Supports dual-read, single-write, write protection for x0, and reset logic. Verified using randomized testbenches.

### [MEMORY_MODULE](https://github.com/NoridelHerron/MEMORY_MODULE)  
Instruction memory unit used in the IF stage. Designed to preload instruction data for fetch testing with reset and read-only control.


## Skills
- **Languages:** VHDL(primary), C, C++
- **Tools:** Vivado, XSim, GitHub
- **Core Concepts**: RTL Design, Pipelined CPU Architecture, Data/Control Hazard Detection, Forwarding Logic, Testbench Development, Waveform-Based Debugging, Assertion-Based Verification
---

## Contact
**Email:** noridel.herron@gmail.com  
**GitHub:** [NoridelHerron](https://github.com/NoridelHerron)
---

> *I focus on building working logic, validating results, and documenting everything as if I were handing it off to a team. If you're hiring for digital design, I’d love to show you what I can do.*
