<p align="center">
  <img src="./jkgo_logo.svg" width="180" alt="J.K.GO Logo"/>
</p>

<p align="center">
  <a href="https://jkgo.kr">
    <img src="https://img.shields.io/badge/site-jkgo.kr-181717?style=flat-square" alt="Website"/>
  </a>
  <a href="#focus-areas">
    <img src="https://img.shields.io/badge/focus-Virtual%20Hardware%20Debugger-0059ff?style=flat-square" alt="Focus: Virtual Hardware Debugger"/>
  </a>
  <a href="https://www.qemu.org/docs/master/devel/tcg.html">
    <img src="https://img.shields.io/badge/based%20on-QEMU%20TCG-ff6f00?style=flat-square" alt="Based on QEMU TCG"/>
  </a>
  <a href="#about-jkgo">
    <img src="https://img.shields.io/badge/domain-System%20Virtualization%20%7C%20Forensics-4b5563?style=flat-square" alt="Domain: System Virtualization | Forensics"/>
  </a>
</p>

# J.K.GO — Journey of Kernel, Let’s GO
Exploring the invisible layers between hardware and software.  
우리는 커널과 가상 하드웨어의 경계를 넘나들며, 보이지 않는 시스템 내부를 재구성합니다.

**Official Website:** https://jkgo.kr

---

## About J.K.GO
**J.K.GO**는 운영체제 내부 구조, 가상화 기술, 그리고 하드웨어 추상화 계층을 깊이 탐구하는 저수준 시스템 연구·개발 팀입니다.  
우리는 QEMU 기반의 가상 하드웨어 디버거(Virtual Hardware Debugger)를 구축하며, 단순한 에뮬레이션을 넘어 **정확한 시스템 관찰·재현·제어**를 목표로 합니다.

주요 연구 분야:

- x86_64 Guest Analysis  
- IRQ Timeline Reconstruction  
- Snapshot-based State Rewinding  
- Deterministic Replay & Execution Tracing  
- Virtual Machine Introspection (VMI)

운영체제, 하이퍼바이저, 하드웨어 모델 사이의 ‘보이지 않는 흐름’을 드러내어  
개발자, 보안 연구자, 시스템 엔지니어의 이해를 확장할 수 있는 도구를 개발합니다.

---

## Focus Areas

### Virtual Hardware Debugger
- QEMU Multi-threaded TCG 기반 동적 번역 계층 분석  
- IRQ, APIC, Timer, MMU, I/O 등 하드웨어 이벤트 타임라인 시각화  
- 게스트 OS 수정 없이 내부 상태 추적  
- Deterministic execution을 위한 스냅샷 기반 복원 엔진 구현

### System Virtualization
- x86_64 Paging Structures 실시간 분석  
- VM-Exit 기반 이벤트 로깅  
- SMP 환경 CPU 상태 및 캐시 일관성 연구  
- Hypervisor 관점에서의 커널 동작 분석

### Memory Forensics
- 증분 스냅샷 기반 메모리 변화량(delta) 캡처  
- PFN Database 및 Page Table 구조 복원  
- Time-travel 기반 시스템 상태 재구성  
- 메모리 변조 감지 및 분석 자동화

---

## Our Vision
“Recreate, Observe, and Control the System — without physical hardware.”

우리는 물리 장비 없이 운영체제가 겪는 모든 이벤트와 상태 변화를  
정확하게 재현하고 관찰하며 제어하는 연구 환경을 구축하고 있습니다.

목표:

- 완전한 소프트웨어 기반 디버깅 환경 구축  
- 운영체제 내부 동작의 정밀한 관찰  
- 반복 가능한 시스템 연구 플랫폼 제공  
- 시간 축(Time-Indexed) 기반 시스템 분석 패러다임 제시  

우리는 단순한 디버거의 수준을 넘어,  
**시스템 전체를 시간축에서 해석하는 플랫폼**을 만들고자 합니다.

---

## Current Projects

### SVHD — Snapshot-based Virtual Hardware Debugger
- IRQ 기반 Snapshot Timeline  
- Memory/CPU State Diffing  
- Instruction-level Execution Trace  
- APIC, PIT, LAPIC, I/O 등 가상 하드웨어 이벤트 재구성  
- PFN & Page Table Analysis Toolkit  
- Guest OS Timeline Reconstruction Engine

### JKGO Toolchain
- Snapshot Loader  
- Forensic Analyzer  
- QEMU Plugin Framework  
- Timeline/Page Table Visualization Tools

---

## Collaboration
다음 분야와의 협업을 환영합니다:

- 운영체제 및 시스템 소프트웨어 개발  
- 메모리 포렌식 및 VMI 연구  
- 가상화 및 에뮬레이션 기술  
- QEMU / KVM / Xen / Bochs 개발자 및 연구자  

---

## Join the Journey
보이지 않는 시스템 내부를 탐색하는 여정에 함께하고 싶다면  
언제든 Issue 또는 PR을 통해 참여해 주세요.

**Journey of Kernel — Let’s GO deeper.**

**Official Website:** https://jkgo.kr
