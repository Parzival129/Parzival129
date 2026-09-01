<div align="center">

# Russell Tabata

**Computer Engineering @ University of Toronto**
*I work at the hardware/software boundary — CPUs, FPGAs, kernels, and the tooling that verifies them.*

Chasing a career in **digital design & verification**: the silicon inside the devices people actually use.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/russell-tabata)
[![Hackaday](https://img.shields.io/badge/Hackaday-1A1A1A?style=flat-square&logo=hackaday&logoColor=white)](https://hackaday.io/Trs.eity88)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:tabatarussell@gmail.com)

</div>

---

### About

I like building things from the gates up. Over the last couple of years that's meant a 16-bit CPU made of elementary logic gates, a self-reconfiguring FPGA SoC, and a small x86 kernel — and, just as often, the **testbenches and CI that prove they actually work.**

Most of my projects live at the seam between hardware and software: RTL and verification on one side, C and low-level systems on the other. I'm especially drawn to processor and FPGA design, and to the idea of eventually working on GPUs, AI accelerators, and consumer silicon.

---

### Featured Projects

- **[protean](https://github.com/Parzival129/protean)** — A self-reconfiguring FPGA handheld: a `picorv32`-based SoC on a Tang Nano 20K that hot-swaps between runtime *personas* (a Game Boy, a logic analyzer). Hand-written RTL for I²C, SPI-flash, and video timing, **clock-domain crossing** on a dual-clock framebuffer, self-checking testbenches, and a fully open-source toolchain (Yosys · nextpnr · Apicula).

- **[Hack-16-CPU-Verilog](https://github.com/Parzival129/Hack-16-CPU-Verilog)** — A working 16-bit computer (Hack ISA) built from elementary logic gates up through the ALU, CPU, and RAM in Verilog — plus a custom assembler that turns symbolic assembly into machine code the processor runs.

- **[nue-kernel](https://github.com/Parzival129/nue-kernel)** — A homebrew i386 x86 kernel in C and assembly: bootloader handoff, GDT/IDT, and a physical memory manager, brought up and debugged in QEMU + GDB.

- **[RISC-V (U of T Open Source Society)](https://github.com/UTOSS/risc-v)** — Contributing SystemVerilog RTL and testbenches to a 5-stage **RV32I** pipeline targeting FPGA synthesis.

- **[ViSTA — Vibro-Sensory Travel Aid](https://hackaday.io/project/196160-vista-vibro-sensory-travel-aid-headset)** — An award-winning navigation headset for the blind (< $100, 54 ms latency) using computer vision offloaded to mobile, tested with the CNIB. *Rick Hansen Difference Maker of the Year, 2025.*

---

### Toolbox

**Languages**
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1A1A1A?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-1A1A1A?style=flat-square)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Hardware & EDA**
![RTL Design](https://img.shields.io/badge/RTL%20Design-6E4AA0?style=flat-square)
![Verification](https://img.shields.io/badge/Verification-6E4AA0?style=flat-square)
![CDC](https://img.shields.io/badge/Clock--Domain%20Crossing-6E4AA0?style=flat-square)
![Icarus Verilog](https://img.shields.io/badge/Icarus%20Verilog-1A1A1A?style=flat-square)
![Yosys](https://img.shields.io/badge/Yosys-1A1A1A?style=flat-square)
![nextpnr](https://img.shields.io/badge/nextpnr-1A1A1A?style=flat-square)
![GTKWave](https://img.shields.io/badge/GTKWave-1A1A1A?style=flat-square)
![Renode](https://img.shields.io/badge/Renode-5C2D91?style=flat-square)
![QEMU](https://img.shields.io/badge/QEMU-FF6600?style=flat-square&logo=qemu&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-1A1A1A?style=flat-square)
![Altium](https://img.shields.io/badge/Altium-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)

**Platforms**
![Tang Nano / Gowin](https://img.shields.io/badge/Tang%20Nano%20%2F%20Gowin-2E7D52?style=flat-square)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### Currently

- **Building** — `protean`, and the verification tooling around my hardware projects
- **Learning** — SystemVerilog verification (UVM, functional coverage, assertions) and timing closure
- **Seeking** — Summer 2027 internships in **Design Verification / RTL / low-level systems**
- **Ask me about** — FPGAs, CPU design, kernels, and retro-hardware restomods

---

<div align="center">
