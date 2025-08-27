# Noridel Herron

**Computer Engineering | RTL Design | CPU Architecture | Verification | VHDL Projects**

---

## 🔍 About Me

I’m a Computer Engineering student driven by a passion for **problem solving** — and CPU design has been the perfect playground to exercise that skill. I built a custom **5-stage pipelined RISC-V CPU** from scratch in VHDL, featuring **full hazard detection, stalling/forwarding, and jump/branch execution**. Through this, I discovered a deep interest in **RTL design, verification, and computer architecture**, which continue to shape my learning journey.

I also built a more advanced **Superscalar CPU** with dual-issue execution, modular control logic, and instruction-level parallelism. I also started the **LearnToBuildCPU refactor project** — an educational rewrite of my original pipeline CPU to help learners understand HDL design through modular, readable VHDL and Verilog code.

My workflow centers around **randomized testbenches (5K–1M tests), waveform debugging, and assertion-based verification**. I enjoy turning self-driven learning into reusable tools for others.

---

## ⚡ Highlights
✅ Built a **5-stage pipelined RISC-V CPU** in VHDL with hazard detection, stall/forwarding, and branching.
✅ Designed a **dual-issue Superscalar CPU** with advanced hazard handling, alignment, and large-scale verification for each module (10K–100K randomized tests).
✅ Created the LearnToBuildCPU refactor project — a modular, **multi-HDL** (VHDL, Verilog, SystemVerilog) rewrite aimed at new learners.
✅ Developed **reusable randomized testbench and waveform debugging** workflows for module- and system-level verification.

---

## 🚧 Projects

**Superscalar CPU – Completed to Scope** (Private)
Explores instruction-level parallelism through dual-issue execution, advanced hazard detection, and modular stage design. All major components are integrated and verified with 10K–100K randomized test cases. Hazard resolution is complete. 

**LearnToBuildCPU – Refactor Project – In Progress** (Public)
A clean, modular, and tri-language (VHDL, Verilog, SystemVerilog) redesign of my pipelined CPU. Includes guided tasks, documentation, waveform/test summaries, and test infrastructure for learners and contributors. While some parts are optimized and centralized, others are intentionally left modular or locally declared — offering room for exploration and hands-on refactoring. A VHDL version is synthesizable on FPGA; contributions using Verilog/SV are welcome.

**Pipelined RISC-V CPU in VHDL** – Completed
Implements a 5-stage Harvard pipeline (IF, ID, EX, MEM, WB) with hazard detection, stalling/forwarding logic, and jump/branch control. Verified with 5,000+ randomized test cases. This design served as the foundation for my later superscalar and refactor projects.

---

## 🧠 Skills & Tools

**Languages**:
VHDL (primary), Verilog (learning), SystemVerilog (learning), C, C++

**Tools**:
Vivado, ModelSim, GitHub

**Technical Focus**:
- RTL Design & Simulation
- Pipeline & Superscalar CPU Architectures
- Hazard Detection & Forwarding
- Waveform Debugging
- Randomized Testbenches (20K–1M)
- HDL Refactoring
- Educational Open-Source Development

---

## 🤝 Contributors

Superscalar CPU
- **Venkateshwarlu Yejella**: Register file and branching unit with testbench
- **Madhu Kanithi**: ROM with testbench
- **Nefeli Metallidou**: WB stage

LearnToBuildCPU
- **S N Ravindra**: ALU in Verilog (Under Extra folder)

---

## 🙏 Special Thanks

I’d like to acknowledge the engineers who offered meaningful technical feedback and guidance throughout this journey:
- **Chris Stratford** – For reviewing my early RTL work and sharing insights on modular HDL design and IP protection considerations. He was the first to give me a true code review, along with specific recommendations that helped me improve my design quality.
- **Charles Manning** – For providing in-depth, constructive feedback that pushed me to think more deeply about architecture choices and signal clarity, and for being consistently responsive to my technical questions.
- **Mazen Ahmed** – For introducing the use of record types in VHDL, which greatly improved the clarity and reusability of my design.
- **William “Stripes” Murray** – For encouraging visibility by sharing my work with broader audiences and supporting its educational potential.
- **Frank Bruno** – For reviewing my ALU design and emphasizing synthesis-friendly approaches using direct arithmetic over behavioral tricks.

---

📫 Contact

📧 Email  : noridel.herron@gmail.com
🔗 GitHub : [@NoridelHerron](https://github.com/NoridelHerron)
🔗 Linkedn: (https://www.linkedin.com/in/noridel-h-5a5534156/)

---

## 📝 Final Note

These projects started as a way to challenge myself and build a strong technical portfolio. But with time and encouragement from professionals, I’ve realized they hold broader value — not just as personal milestones, but as open-source learning tools.

