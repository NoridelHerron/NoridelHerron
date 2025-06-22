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

## 🧱 Archive & Core Modules

Standalone components used during development. Useful for reference, learning, and reuse:

- [**INSTRUCTION_FETCH**](https://github.com/NoridelHerron/INSTRUCTION_FETCH) – Program counter + instruction memory  
- [**ID_STAGE**](https://github.com/NoridelHerron/ID_STAGE) – Instruction decoder, immediate extractor, control unit  
- [**EX_STAGE**](https://github.com/NoridelHerron/EX_STAGE) – ALU wrapper, pipeline register integration  
- [**MEM_STAGE**](https://github.com/NoridelHerron/MEM_STAGE) – Memory access logic (lw/sw)  
- [**DATA_MEM**](https://github.com/NoridelHerron/DATA_MEM) – Word-addressable memory with assertions  
- [**ALU_with_testBenches_vhdl**](https://github.com/NoridelHerron/ALU_with_testBenches_vhdl) – 32-bit ALU with flag logic  
- [**32x32-bit Register File**](https://github.com/NoridelHerron/32x32-bit-Register-File-in-VHDL-) – Dual-read, single-write register file  
- [**MEMORY_MODULE**](https://github.com/NoridelHerron/MEMORY_MODULE) – Preloadable instruction memory

---

## 🧠 Skills & Tools

### 💻 Languages  
- **VHDL** (primary), C, C++

### 🧰 Tools & Platforms  
- Vivado, XSim, ModelSim  
- Git/GitHub  
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
- **Spring/Summer 2026 internships** in digital hardware design, RTL development, or verification  
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
