# Noridel Herron

**Computer Engineering | Digital Design | VHDL Projects**

**Welcome to my GitHub!**
I’m currently pursuing a degree in Computer Engineering, with a strong focus on digital design and hardware architecture. After completing a fully custom, **5-stage pipelined RISC-V CPU** in VHDL, I’ve now moved on to building a **Superscalar CPU**, expanding on concepts like parallel instruction issue, dual-path hazard resolution, and tighter execution timing.

Earlier in my journey, I designed and verified key components such as a 32-bit ALU, memory modules, and a full register file, using both fixed and randomized testbenches. I’ve strengthened my skills in control flow, hazard detection, pipelined timing, and verification through waveform inspection, manual calculation, and automation with TCL scripting.

I’m open to feedback, collaboration, and new challenges — especially in CPU design, system architecture, and RTL verification. Let’s connect and learn together!
## ⚠️ Learning Disclaimer

I am still learning, and this project is part of my hands-on learning process. If you find any bugs, mistakes, or incorrect assumptions in my work or documentation, please trust yourself, double-check with trusted resources, and feel free to let me know!
I expect to make many improvements and corrections as I continue developing this project and deepening my understanding.
If you have suggestions or spot issues, I truly welcome the feedback so I can continue improving.

## Featured Projects
## [Superscalar CPU]([https://github.com/NoridelHerron/INSTRUCTION_FETCH](https://github.com/NoridelHerron/SUPERSCALAR_CPU))  – Current Progress (June 2025) 
This project is my next step beyond a basic pipelined design, applying what I’ve learned to a more complex architecture with dual-issue capability and tighter performance goals. While this is still a work in progress, several core components have been completed and fully verified.

### Verified Modules
- ALU (with internal adder and subtractor):
- Decoder
- Control Unit
- Hazard Detection Unit:

All modules are **thoroughly tested using 20,000 randomized test cases**, including edge cases. All operations **verified through waveform inspection** and cross-checked using manual and online calculation.

**NEXT**:
- Forwarding Unit (June 16, 2025)

## [Pipelined-RISC-V-CPU-in-VHDL-From-Scratch-to-Simulation](https://github.com/NoridelHerron/Pipelined-RISC-V-CPU-in-VHDL-From-Scratch-to-Simulation) – Final Milestone (June 2025)
I now consider this project completed and do not plan to refactor it further. Instead, I will apply what I learned here to my ongoing Superscalar CPU project and future architectural designs. However, if I receive constructive feedback or discover needed corrections, I’ll absolutely revisit and patch those areas. Refactoring and expansion will be left open to other project explorers or future collaborators.

## Archive Repos (Earlier Work)
The **earlier-stage modules** listed below were foundational to my learning and development. Their integration and refinement can be seen in the **main pipeline repository**, where the fully integrated CPU resides.
➡️ While these standalone components have been **superseded** by the final pipeline version, the testbenches, notes, and design patterns—especially those involving randomized testing—may still be helpful for anyone learning VHDL or CPU architecture.

[INSTRUCTION_FETCH](https://github.com/NoridelHerron/INSTRUCTION_FETCH)  
VHDL implementation of the Instruction Fetch stage for a custom RISC-V pipeline CPU. Includes program counter, instruction memory interface, and testbench validation.

[ID_STAGE](https://github.com/NoridelHerron/ID_STAGE)  
Implements the Instruction Decode stage of a 5-stage pipelined RISC-V CPU. Extracts opcode, register values, function codes, and immediate values from a 32-bit instruction. Generates control signals and interfaces with the register file to retrieve operands.

[EX_STAGE](https://github.com/NoridelHerron/EX_STAGE)  
Execute stage for a pipelined RISC-V CPU. Integrates ALU, forwarding inputs, and control logic with pipeline register support. Validated using a randomized testbench.

[MEM_STAGE](https://github.com/NoridelHerron/MEM_STAGE)
Implements the Memory stage of a 5-stage pipelined RISC-V CPU. Handles lw and sw instructions, memory read/write via DATA_MEM, and passes necessary control signals. Verified with 5000 randomized test cases and waveform analysis, including intentional bug injection.

[DATA_MEM](https://github.com/NoridelHerron/DATA_MEM)  
Synchronous 32-bit word-addressable memory module with support for 1024 memory locations. Includes a reusable formatting function and randomized testbench with assertion-based verification and waveform validation.

[ALU_with_testBenches_vhdl](https://github.com/NoridelHerron/ALU_with_testBenches_vhdl)  
A fully functional 32-bit ALU in VHDL with signed/unsigned operations, flag generation (Z, N, C, V), and comprehensive testbenches including randomized edge-case validation.

[32x32-bit Register File](https://github.com/NoridelHerron/32x32-bit-Register-File-in-VHDL-)  
Implements a synchronous register file with 32 registers, each 32 bits wide. Supports dual-read, single-write, write protection for x0, and reset logic. Verified using randomized testbenches.

[MEMORY_MODULE](https://github.com/NoridelHerron/MEMORY_MODULE)  
Instruction memory unit used in the IF stage. Designed to preload instruction data for fetch testing with reset and read-only control.

## Skills
- **Languages:** VHDL(primary), C, C++
- **Tools:** Vivado, XSim, GitHub
- **Core Concepts**:
  - RTL Design
  - Pipelined CPU Architecture
  - Data/Control Hazard Detection
  - Forwarding and stall Logic
  - Testbench Development
  - Waveform-Based Debugging
  - Assertion-Based Verification
---

## Contact
**Email:** noridel.herron@gmail.com  
**GitHub:** [NoridelHerron](https://github.com/NoridelHerron)
---

> *I focus on building working logic, validating results, and documenting everything as if I were handing it off to a team. If you're hiring for digital design, I’d love to show you what I can do.*
