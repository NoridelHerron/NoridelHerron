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
   - integrated multiple units in two stages (tcl, waveform, and manually verified).
   - Collaborating with contributors from multiple countries to explore instruction-level parallelism
- 🧠 **LearnToBuildCPU** – Refactor Project (In Progress):
   - Educational and beginner-friendly refactor of original pipelined CPU
   - Modular design with both VHDL and Verilog support
   - Active collaboration with global contributors
   - Designed as an open-source learning resource with tasks and documentation for new learners

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
- Integrated the decoder, register file, control and hazard logic in ID_Stage
- Integrated the forwarding unit and ALUs in EX_Stage

🔜 Upcoming:

- IF Stage

🌐 I’m currently collaborating with contributors from multiple countries on this project, fostering a diverse and supportive learning environment.

---

### LearnToBuildCPU – Refactor Project – In Progress (June 2025)
A community-focused refactoring of my original pipelined CPU project to make it more modular, well-documented, and beginner-friendly. This project features both VHDL and Verilog implementations and is designed to help others learn CPU architecture by contributing or studying the code.

Key goals:
- Simplify modules while keeping architecture accurate
- Provide dual-language support (VHDL and Verilog)
- Encourage learning by contribution (even for beginners!)
- Assign clear, self-contained tasks for contributors

🌐 I’m working with contributors from around the world to build an educational CPU design resource — the kind of hands-on project I wish I had when I was starting out.

### 🔹 [Pipelined RISC-V CPU in VHDL](https://github.com/NoridelHerron/Pipelined-RISC-V-CPU-in-VHDL-From-Scratch-to-Simulation) – Completed (June 2025)  
This project serves as the **baseline** architecture for my **LearnToBuildCPU project**, providing a fully functional and verified starting point for learners and contributors. It uses **Harvard architecture** and a traditional 5-stage pipeline. Key control and **data hazards** are handled via dedicated detection logic and resolved through **stalling and forwarding**. Also includes **jump and branch support**.

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

## 🙏 Special Thanks

I would like to extend my heartfelt gratitude to the following individuals who have contributed to my growth and this project in meaningful ways:
- Chris Stratford – For giving me my very first code review and offering valuable suggestions to improve the structure and quality of my implementation.
- Mazen Ahmed – For introducing me to the use of record types in VHDL, which enhanced both clarity and organization in my design.
- William (Bill) "Stripes" Murray – For generously sharing my work with others and encouraging broader engagement with my project.
- Charles Manning – For consistently providing insightful feedback that challenged my thinking and helped refine my approach.
- Frank Bruno – For reviewing my ALU implementation and explaining the importance of using direct addition and subtraction for practical and optimized synthesis.

---

## 🤝 Contributors

Special thanks to the following contributors who played an essential role in the 
**Superscalar project**:
- Vankateshwarlu Yejella – For designing the register file and fully verifying its functionality through rigorous testing.
- Madhu Kanithi – For developing the data memory module and thoroughly verifying its correctness.
- Nefeli Metallidou - WB Stage
- 
**LearnToBuildCPU project**:
- S N Ravindra - ALU in verilog
    
---

## 📫 Contact

- 📧 **Email**: noridel.herron@gmail.com  
- 🔗 **GitHub**: [NoridelHerron](https://github.com/NoridelHerron)  
- 🔗 **LinkedIn**: *[]*

---

## 🙏 Final Note

This GitHub reflects my self-driven learning in CPU design and digital systems. I welcome constructive feedback, contributions, and conversations. Thank you for stopping by!
