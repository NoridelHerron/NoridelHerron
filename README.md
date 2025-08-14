# Noridel Herron

**Computer Engineering | RTL Design | CPU Architecture | Verification | VHDL Projects**

---

## 🔍 About Me

I’m a Computer Engineering student passionate about **RTL design, verification, and computer architecture**. I built a custom **5-stage pipelined RISC-V CPU** from scratch in VHDL, featuring full hazard detection, stalling/forwarding, and jump/branch execution.

Now I’m developing a more advanced **Superscalar CPU with dual-issue execution**, modular control logic, and instruction-level parallelism. I also started the **LearnToBuildCPU refactor project** — an educational rewrite of my original pipeline CPU to help learners understand HDL design through modular, readable VHDL and Verilog code.

My workflow centers around **randomized testbenches (20K–100K tests), waveform debugging, and assertion-based verification**. I enjoy turning self-driven learning into reusable tools for others.

---

## ⚡ Highlights
✅ Built a **5-stage pipelined RISC-V CPU** in VHDL with hazard detection, stall/forwarding, and branching.
✅ Designed a **dual-issue Superscalar CPU** with advanced hazard handling, alignment, and large-scale verification for each module (20K–100K randomized tests).
✅ Created the LearnToBuildCPU refactor project — a modular, **multi-HDL** (VHDL, Verilog, SystemVerilog) rewrite aimed at new learners.
✅ Developed **reusable randomized testbench and waveform debugging** workflows for module- and system-level verification.

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

**Superscalar CPU – Completed to Scope** (Private)
Explores instruction-level parallelism through dual-issue execution, advanced hazard detection, and modular stage design. All major components are integrated and verified with 20K–100K randomized test cases. Since I’ve implemented branching in previous CPU designs, I chose to pause before adding it here and instead focus on refactoring for reuse in future work, including my capstone.

**LearnToBuildCPU – Refactor Project** – In Progress (Private)
A clean, modular, and tri-language (VHDL, Verilog, SystemVerilog) redesign of my pipelined CPU. Includes guided tasks, documentation, and test infrastructure for learners and contributors. Currently private while undergoing refactoring and IP review.

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
- **Chris Stratford** – For reviewing my early RTL work and sharing insights on modular HDL design and IP protection considerations. He was the first to give me a true code review, along with specific recommendations that helped me improve my design quality.
- **Charles Manning** – For providing in-depth, constructive feedback that pushed me to think more deeply about architecture choices and signal clarity, and for being consistently responsive to my technical questions.
- **Mazen Ahmed** – For introducing the use of record types in VHDL, which greatly improved the clarity and reusability of my design.
- **William “Stripes” Murray** – For encouraging visibility by sharing my work with broader audiences and supporting its educational potential.
- **Frank Bruno** – For reviewing my ALU design and emphasizing synthesis-friendly approaches using direct arithmetic over behavioral tricks.

---

📫 Contact

📧 Email: noridel.herron@gmail.com
🔗 GitHub: [@NoridelHerron](https://github.com/NoridelHerron)
Linkedn: [https://www.linkedin.com/public-profile/settings?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_self_edit_contact-info%3BXOBONUc%2FQ0aEoYfSz1c4Ow%3D%3D](https://www.linkedin.com/in/noridel-h-5a5534156/)


⸻

## 📝 Final Note

These projects started as a way to challenge myself and build a strong technical portfolio. But with time and encouragement from professionals, I’ve realized they hold broader value — not just as personal milestones, but as open-source learning tools.

They will be back. Stronger, cleaner, and ready to help others learn to build.
