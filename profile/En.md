<p align="center">
  <img src="./jkgo_logo.svg" width="190" alt="J.K.GO Logo"/>
</p>

<p align="center">
  <a href="https://jkgo.kr">
    <img src="https://img.shields.io/badge/Website-jkgo.kr-0A0A0A?style=flat&logo=google-chrome&logoColor=ffffff" alt="Website Badge"/>
  </a>
  <a href="#focus-areas">
    <img src="https://img.shields.io/badge/Focus-Virtual%20Hardware%20Debugger-0059FF?style=flat&logo=logmein&logoColor=ffffff" alt="Focus Badge"/>
  </a>
  <a href="https://www.qemu.org/docs/master/devel/tcg.html">
    <img src="https://img.shields.io/badge/Built%20On-QEMU%20TCG-FF6F00?style=flat&logo=qemu&logoColor=ffffff" alt="QEMU Badge"/>
  </a>
  <a href="#about-jkgo">
    <img src="https://img.shields.io/badge/Domain-System%20Virtualization%20%7C%20Forensics-1F2937?style=flat" alt="Domain Badge"/>
  </a>
</p>

<br/>

# J.K.GO — Journey of Kernel, Let’s GO
Exploring the invisible layers between hardware and software.  
We operate under the slogan **“All In, Always.”**

**Official Website:** https://jkgo.kr

---

## About J.K.GO
**J.K.GO** is a research and development team specializing in low-level system internals, virtualization, and hardware abstraction layers.  
We develop a QEMU-based **Virtual Hardware Debugger**, aiming not just to emulate but to **reconstruct, observe, and control** the entire system with precision.

Primary research areas include:

- x86_64 Guest Analysis  
- IRQ Timeline Reconstruction  
- Snapshot-based State Rewinding  
- Deterministic Replay & Execution Tracing  
- Virtual Machine Introspection (VMI)

Our goal is to reveal the “invisible flow” between the operating system, hypervisor, and hardware model—  
providing tools that enable researchers and developers to deeply understand system behavior.

---

## Focus Areas

### Virtual Hardware Debugger
- Deep inspection of QEMU’s Multi-threaded TCG translation layer  
- Visualization of hardware event timelines (IRQ, APIC, MMU, Timer, I/O, etc.)  
- Non-invasive tracing without modifying the guest operating system  
- Snapshot-based deterministic execution and replay engine  

### System Virtualization
- Real-time analysis of x86_64 paging structures (PML4 → PT)  
- VM-Exit–driven event logging & execution flow reconstruction  
- CPU state inspection in SMP environments & cache coherency modeling  
- Hypervisor-level analysis of kernel behavior  

### Memory Forensics
- Incremental snapshot diffing of memory state  
- PFN database reconstruction & automated page table walking  
- Time-travel reconstruction of historical system states  
- Memory tampering detection and forensic automation  

---

## Our Vision
**“Recreate, Observe, and Control the System — without physical hardware.”**

We build technologies that enable us to precisely reproduce and analyze every event inside the operating system—  
**without requiring any physical hardware at all.**

Our long-term vision includes:

- A fully software-based debugging and analysis environment  
- High-fidelity OS behavior observation tools  
- A repeatable, research-friendly virtualization platform  
- A new paradigm for analyzing systems through a **time-indexed perspective**  

Beyond a debugger,  
we aim to create a **platform that interprets the entire system through the dimension of time.**

---

## Current Projects

### SVHD — Snapshot-based Virtual Hardware Debugger
- IRQ-driven snapshot timeline generation  
- Memory & CPU state diffing engine  
- Instruction-level execution trace logging  
- Reconstruction of APIC, LAPIC, PIT, I/O event flows  
- PFN & Page Table analysis toolkit  
- Guest-driven timeline reconstruction engine  

### JKGO Toolchain
- Snapshot Loader  
- Memory Forensics Analyzer  
- QEMU Plugin Development Framework  
- Page Table / Timeline Visualization Toolkit  

---

## Collaboration
We welcome collaboration in the following fields:

- OS & System Software Engineering  
- Memory Forensics / VMI Research  
- Virtualization and Emulation Technology  
- QEMU / KVM / Xen / Bochs Developers  

---

## Join the Journey
If you want to explore the invisible depths of system internals,  
feel free to join us through Issues or Pull Requests.

**Journey of Kernel — Let’s GO deeper.**

**Official Website:** https://jkgo.kr
