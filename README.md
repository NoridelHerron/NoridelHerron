# Noridel Herron

**Computer Engineering | RTL Design | CPU Architecture | Verification | VHDL Projects**

---

## 🔍 About Me

I’m a Computer Engineering student passionate about **RTL design, verification, and computer architecture**. I built a custom **5-stage pipelined RISC-V CPU** from scratch in VHDL, featuring full hazard detection, stalling/forwarding, and jump/branch execution.

Now I’m developing a more advanced **Superscalar CPU with dual-issue execution**, modular control logic, and instruction-level parallelism. I also started the **LearnToBuildCPU refactor project** — an educational rewrite of my original pipeline CPU to help learners understand HDL design through modular, readable VHDL and Verilog code.

My workflow centers around **randomized testbenches (20K–100K tests), waveform debugging, and assertion-based verification**. I enjoy turning self-driven learning into reusable tools for others.

---

## ⚡ Highlights
✅ **Pipelined RISC-V CPU**
- Harvard architecture, 5-stage pipeline (IF–WB)
- Hazard detection, stall/forwarding, jump/branch control
- 5,000+ randomized test cases
- Waveform-driven debugging

⚙️ **Superscalar CPU (In Progress)**
- Dual-issue datapath with modular control
- All pipeline components integrated
- Pending: Stall logic, branching, and flushing
- **20K–100K** randomized test cases across modules
- Verified via waveform inspection and testbench automation
- Collaborating with contributors from Greece and the US

🧠 **LearnToBuildCPU – Refactor Project (In Progress)**
- Modular rewrite of the original pipeline CPU
- Will be written in both VHDL, Verilog, System Verilog
- Designed for new learners, with task-based contributions
- Temporarily private while being refactored and reviewed for IP and licensing
- Will be republished with documentation and learning materials

---

**🔐 Why It’s Private (For Now)**

In earlier posts, I mentioned keeping everything open and public — and that’s still my goal. However, after receiving thoughtful technical feedback, I’ve come to understand the importance of reviewing IP protection and licensing options before fully releasing certain designs.

Because of this, I’ve decided to:
- Refactor the work myself across multiple HDLs
- Complete final verification and documentation
- Ensure proper safeguards are in place for its reuse and attribution

Once finalized, I plan to republish it openly, welcoming learners and collaborators back into the project with clearer structure and purpose.

---

## 🚧 Projects

🔹 **Superscalar CPU – In Progress** (Private)

This project explores instruction-level parallelism through dual-issue execution, advanced hazard detection, and modular stage design. All major components are integrated; stall logic, branching, and flushing are in development. Test coverage across modules ranges from 20K to 100K randomized cases.

🔹 **LearnToBuildCPU – Refactor Project – In Progress** (Private)

A clean, modular, and **tri-language (VHDL + Verilog + System Verilog)** redesign of my pipelined CPU. Will be designed for learners and contributors, this project includes guided tasks, documentation, and test infrastructure. It is currently private while undergoing internal refactoring and IP review.

🔹 **Pipelined RISC-V CPU in VHDL – Completed**

This is the original CPU project that seeded both the Superscalar and LearnToBuildCPU refactor efforts. It implements a full 5-stage Harvard pipeline (IF, ID, EX, MEM, WB), with working hazard detection, stalling/forwarding logic, and control flow via jump and branch instructions.

Most modules were functionally verified using 5,000+ randomized test cases, especially the ALU, ex stage, and more. At the system level, this CPU currently supports a core subset of RISC-V instructions: R-type, I-type (immediate), load, branch (BEQ), and jump.

This project reflects my foundational knowledge in RTL and computer architecture. The instruction coverage and modular clarity will be significantly expanded in the LearnToBuildCPU refactor project, which builds on this system as a reusable and educational platform.

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
- Randomized Testbenches (20K–100K)
- HDL Refactoring
- Educational Open-Source Development

---

## 🤝 Contributors

Superscalar CPU
- **Venkateshwarlu Yejella**: Register file and branching unit with testbench
- **Madhu Kanithi**: ROM with testbench
- **Nefeli Metallidou**: WB stage

LearnToBuildCPU
- **S N Ravindra**: ALU in Verilog

---

## 🙏 Special Thanks

I’d like to acknowledge the engineers who offered meaningful technical feedback and guidance throughout this journey:
- **Chris Stratford** – For reviewing my early RTL work and sharing insights on modular HDL design and IP protection considerations.
- **Mazen Ahmed** – For introducing the use of record types in VHDL, which greatly improved the clarity and reusability of my design.
- **William “Stripes” Murray** – For encouraging visibility by sharing my work with broader audiences and supporting its educational potential.
- **Charles Manning** – For in-depth comments that pushed me to think deeper about architecture choices, and signal clarity.
- **Frank Bruno** – For reviewing my ALU design and emphasizing synthesis-friendly approaches using direct arithmetic over behavioral tricks.

---

📫 Contact

📧 Email: noridel.herron@gmail.com
🔗 GitHub: NoridelHerron

⸻

## 📝 Final Note

These projects started as a way to challenge myself and build a strong technical portfolio. But with time and encouragement from professionals, I’ve realized they hold broader value — not just as personal milestones, but as open-source learning tools.

They will be back. Stronger, cleaner, and ready to help others learn to build.
