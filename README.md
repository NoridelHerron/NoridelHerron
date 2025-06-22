 # Noridel Herron

**Computer Engineering | RTL Design | CPU Architecture | Verification | VHDL Projects**

---

## 🔍 About Me

I’m a Computer Engineering student with a strong focus on **digital logic, RTL design**, **verification** and **computer architecture**. I recently completed a fully custom, **5-stage pipelined RISC-V CPU** (Harvard architecture) in VHDL, with built-in **hazard detection**, **stalling and forwarding logic**, and **jump/branch execution**. I’m now developing a **Superscalar CPU**, exploring dual-issue execution, tighter timing, and parallel hazard resolution.

My work combines **testbench development**, **assertion-based verification**, and **waveform inspection** to validate functionality. I turn architecture concepts into modular VHDL implementations and learn through hands-on design and deep debugging.

I'm actively seeking opportunities in **digital/RTL design**, **CPU microarchitecture**, **verification** or **FPGA-based systems**, and I’m open to collaboration, mentorship, and feedback.

---

## ⚡ Recent Highlights

- **5-Stage Pipelined RISC-V CPU (Harvard Architecture)** – VHDL, Completed  
- Implemented **hazard detection unit**, **stalling and forwarding resolution**, and **jump/branch logic**  
- Developed all pipeline stages (IF, ID, EX, MEM, WB) 
- **Superscalar CPU** – Dual-issue, hazard-aware architecture (In Progress)  
- Fully Verified ALU, Decoder, Control Unit, Forwarding Unit, and Hazard Detection Unit with 20,000 test cases.
✔️ Used waveform analysis, manual debugging, and TCL scripting

---

## 🚧 Projects

### 🔹 [Superscalar CPU](https://github.com/NoridelHerron/SUPERSCALAR_CPU) – **Work in Progress (June 2025)**  
My most recent project expands the capabilities of my pipelined CPU by introducing **dual-issue execution**, parallel instruction handling, and tighter performance goals. It builds on lessons from my first pipeline while pushing toward instruction-level parallelism and deeper hazard analysis.

#### ✅ Verified Modules
- ALU (with internal adder/subtractor and flag logic)
- Control Unit
- Instruction Decoder
- Hazard Detection Unit
- Forwarding Unit

All modules are **tested with 20,000+ randomized cases**, with validation via waveform inspection and manual verification.

#### 🔄 Next:
- Integrate decoder, register file, control and hazard detection unit.
- Write wrapper for the register file to make it compatible with vhdl.

---

### 🔹 [Pipelined RISC-V CPU in VHDL](https://github.com/NoridelHerron/Pipelined-RISC-V-CPU-in-VHDL-From-Scratch-to-Simulation) – **Completed (June 2025)**  
This was my first fully integrated CPU project, built with **Harvard architecture** and all 5 classic pipeline stages. I implemented **hazard detection**, **stalling**, and **forwarding logic** to resolve data/control dependencies. The design includes support for **jump and branch logic**, tested across randomized and corner-case inputs.

Key Features:
- 5-Stage Harvard Architecture: IF, ID, EX, MEM, WB  
- Fully integrated hazard detection + resolution (stall/forward)  
- Supports conditional branches and jumps  
- Manual and automated validation using TCL scripting + waveform inspection  
- 5,000+ randomized test cases used in regression and stress testing

📌 Finalized and stable; open to review-based patches.

---

## 🧱 Archive & Core Modules

Standalone modules used during pipeline development, now archived or merged. Great for studying design patterns, testbench structures, or waveform debugging.

- [**INSTRUCTION_FETCH**](https://github.com/NoridelHerron/INSTRUCTION_FETCH) – Program counter, instruction memory, reset logic  
- [**ID_STAGE**](https://github.com/NoridelHerron/ID_STAGE) – Instruction decoder, immediate extractor, control unit  
- [**EX_STAGE**](https://github.com/NoridelHerron/EX_STAGE) – ALU wrapper, forwarding logic, EX pipeline registers  
- [**MEM_STAGE**](https://github.com/NoridelHerron/MEM_STAGE) – Handles load/store (lw/sw), DATA_MEM access  
- [**DATA_MEM**](https://github.com/NoridelHerron/DATA_MEM) – 1024-word memory with randomized testbench and assertions  
- [**ALU_with_testBenches_vhdl**](https://github.com/NoridelHerron/ALU_with_testBenches_vhdl) – 32-bit ALU with flags (Z, N, C, V)  
- [**32x32-bit Register File**](https://github.com/NoridelHerron/32x32-bit-Register-File-in-VHDL-) – Dual-read, single-write register file with write protection for x0  
- [**MEMORY_MODULE**](https://github.com/NoridelHerron/MEMORY_MODULE) – Instruction memory unit for fetch testing

---

## 🧠 Skills & Tools

### 💻 Languages
- **VHDL** (primary)
- C, C++

### 🧰 Tools & Environments
- Vivado, XSim, ModelSim
- Git & GitHub
- TCL Scripting (Vivado simulation automation)

### 🔬 Core Competencies
- RTL Design and Simulation (VHDL)
- Harvard Architecture CPU Design
- Pipelined Processor Development (RISC-V)
- Dual-Issue Execution (Superscalar CPU – in progress)
- Hazard Detection Unit Design
- Stall and Forwarding Logic Implementation
- Jump and Branch Execution Control
- Waveform Debugging and Timing Validation
- Randomized Testbench Development
- Assertion-Based Verification

---

## 🚀 What I’m Looking For

I'm currently seeking:
- **Internships (Spring 2026)** in RTL design, verification, or computer architecture  
- **Research projects** in CPU design, FPGA development, or custom hardware acceleration  
- **Mentorship or collaboration** opportunities in low-level system design

I’m especially interested in teams focused on:
- CPU microarchitecture or FPGA SoC design  
- RISC-V instruction sets and extensions 
- RTL-to-GDS flow and ASIC prototyping  
- Verifications
---

## 📫 Contact

- 📧 **Email**: noridel.herron@gmail.com  
- 🔗 **GitHub**: [NoridelHerron](https://github.com/NoridelHerron)  
- 🔗 **LinkedIn**: *[Insert if available]*

---

## 🙏 Note to Viewers

This GitHub reflects my **active learning journey** in digital design and architecture. If you find areas for improvement or want to collaborate, I welcome your input!

Thanks for visiting — and let’s connect!
