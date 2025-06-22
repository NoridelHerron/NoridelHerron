# Noridel Herron

**Computer Engineering | RTL Design | CPU Architecture | Verification | VHDL Projects**

---

## 🔍 About Me

I’m a Computer Engineering student with a focus on **RTL design**, **verification**, and **computer architecture**. I recently completed a custom **5-stage pipelined RISC-V CPU** using **Harvard architecture** in VHDL, with full support for **hazard detection**, **stalling/forwarding**, and **jump/branch execution**. My current work builds on that foundation through the development of a **Superscalar CPU**, where I’m implementing **dual-issue execution** and more advanced hazard handling.

I validate my designs through **randomized testbenches**, **assertion-based verification**, and **waveform inspection**. I enjoy tackling challenging hardware design problems and continuously seek to deepen my understanding through hands-on exploration.

---

## ⚡ Highlights

- ✅ **Pipelined RISC-V CPU** (Completed):  
   - Harvard architecture, 5-stage pipeline (IF, ID, EX, MEM, WB)  
   - Implements hazard detection, stall/forwarding resolution, and control flow (branch/jump)  
   - 5,000+ randomized test cases, waveform-based debugging, and TCL scripting  
- ⚙️ **Superscalar CPU** (In Progress):  
   - Dual-issue datapath and advanced hazard resolution  
   - Verified ALU, decoder, control unit, forwarding and hazard detection logic
   - 20,000+ randomized test cases applied during module verification
   - integrated ALUs and forwarding unit in ex stage (waveform verified).
---

## 🚧 Projects

### 🔹 [Superscalar CPU](https://github.com/NoridelHerron/SUPERSCALAR_CPU) – In Progress (June 2025)  
This project builds on my prior pipeline design and introduces **dual-issue execution** to explore instruction-level parallelism and data/control hazards across parallel paths. I focus on modular, test-driven development using randomized testbenches and waveform validation.

#### Verified Modules:
- ALU (with flags, adder/subtractor logic)
- Instruction Decoder
- Control Unit
- Hazard Detection Unit
- Forwarding Unit

🔜 Upcoming:
- Integration of decoder, register file, control and hazard logic  
- VHDL-to-Verilog wrapper for compatibility

---

### 🔹 [Pipelined RISC-V CPU in VHDL](https://github.com/NoridelHerron/Pipelined-RISC-V-CPU-in-VHDL-From-Scratch-to-Simulation) – Completed (June 2025)  
My first complete CPU design using Harvard architecture and a traditional 5-stage pipeline. Key control and data hazards are handled via dedicated detection logic and resolved through stalling and forwarding. Also includes **jump and branch support**.

**Key Features:**
- Instruction fetch, decode, execute, memory, and writeback pipeline stages  
- Hazard detection unit with stall/forward resolution  
- Support for control transfer (branches/jumps)  
- TCL scripts for batch simulation and waveform automation  
- 5,000+ randomized test cases covering edge/corner cases

📌 Finalized and stable; available for review or forking.

---
## Archive Repos (Earlier Work)
The earlier-stage modules listed below were **foundational to my learning and development**. Their integration and refinement can be seen in the **main pipeline repository**, where the fully integrated CPU resides. While these standalone components have been **superseded** by the final pipeline version, the **testbenches, notes, and design patterns—especially** those involving randomized testing—may still be helpful for anyone learning VHDL or CPU architecture.

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

---

## 🧠 Skills & Tools

### 💻 Languages  
- **VHDL** (primary), Verilog(Learning), SystemVerilog(Learning),C, C++
### 🧰 Tools & Platforms  
- Vivado, XSim, ModelSim  
- GitHub  
- TCL scripting (test automation)

### 🔬 Technical Focus  
- RTL Design & Simulation (VHDL)  
- Harvard Architecture CPU Design  
- Pipelined and Superscalar Execution  
- Hazard Detection & Resolution (stall/forward)  
- Control Flow (jump/branch) Implementation  
- Testbench & Assertion-Based Verification  
- Waveform Debugging  
- Randomized Testing & Validation

---

## 🚀 Opportunities I’m Seeking

I'm currently exploring:
- **Internships or Full-time** in digital hardware design, RTL development, or verification  
- **Undergraduate research** in CPU microarchitecture or FPGA-based systems  
- Collaboration on open-source or academic projects in hardware systems or computer architecture

---

## 📫 Contact

- 📧 **Email**: noridel.herron@gmail.com  
- 🔗 **GitHub**: [NoridelHerron](https://github.com/NoridelHerron)  
- 🔗 **LinkedIn**: *[Insert if available]*

---

## 🙏 Final Note

This GitHub reflects my self-driven learning in CPU design and digital systems. I welcome constructive feedback, contributions, and conversations. Thank you for stopping by!
