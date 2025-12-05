<p align="center">
  <img src="./jkgo_logo.svg" width="190" alt="J.K.GO Logo"/>
</p>
<p align="center">
  <a href="./README.md"><b>한국어</b></a> • 
  <a href="./En.md"><b>English</b></a>
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
우리는 **"All In, Always."** 라는 슬로건으로 활동합니다.

**Official Website:** https://jkgo.kr

---

## About J.K.GO
**J.K.GO**는 운영체제 내부 구조, 가상화 기술, 그리고 하드웨어 추상화 계층을 깊게 탐구하는 저수준 시스템 연구·개발 팀입니다.  
우리는 QEMU 기반의 Virtual Hardware Debugger를 구축하며, 단순한 에뮬레이션을 넘어 **정확한 시스템 관찰·재현·제어**를 목표로 합니다.

주요 연구 분야:

- x86_64 Guest Analysis  
- IRQ Timeline Reconstruction  
- Snapshot-based State Rewinding  
- Deterministic Replay & Execution Tracing  
- Virtual Machine Introspection (VMI)

운영체제, 하이퍼바이저, 하드웨어 모델 사이의 ‘보이지 않는 흐름’을 드러내어  
개발자 및 보안 연구자가 시스템 동작을 정밀하게 이해할 수 있도록 돕습니다.

---

## Focus Areas

### Virtual Hardware Debugger
- QEMU Multi-threaded TCG 기반 번역 계층 분석  
- IRQ, APIC, MMU, Timer, I/O 등 하드웨어 이벤트 타임라인 시각화  
- 게스트 OS 수정 없이 내부 상태 비침투적(non-invasive) 추적  
- Deterministic Execution을 위한 Snapshot 복원 엔진 구축  

### System Virtualization
- x86_64 Paging Structures (PML4 → PT) 실시간 분석  
- VM-Exit 기반 이벤트 로깅 & 머신 내부 흐름 재구성  
- SMP 환경 CPU 상태 분석, Cache Coherency 모델 연구  
- Hypervisor-level 커널 동작 연구  

### Memory Forensics
- 증분 스냅샷 기반 메모리 변화량(delta) 캡처  
- PFN Database 재구성 및 Page Table Walk 자동화  
- Time-travel 기반 시스템 상태 재생성  
- 메모리 변조 탐지 및 포렌식 자동화  

---

## Our Vision

**“Recreate, Observe, and Control the System — without physical hardware.”**

우리는 물리 장비 없이도 운영체제 내부에서 발생하는 모든 이벤트와 상태 변화를  
**정확하고 반복 가능하게** 재현하는 기술을 개발합니다.

궁극적인 목표는 다음과 같습니다:

- 완전한 소프트웨어 기반 디버깅 환경 구축  
- 운영체제 내부 동작의 정밀한 관찰  
- 반복 가능한 실험·연구 플랫폼 제공  
- Time-Indexed 기반 시스템 분석 패러다임 정착  

우리는 단순한 디버거가 아니라,  
**시스템 전체를 시간축 위에서 해석하는 플랫폼**을 구축하고자 합니다.

---

## Current Projects

### SVHD — Snapshot-based Virtual Hardware Debugger
- IRQ 기반 Snapshot Timeline  
- Memory/CPU State Diffing  
- Instruction-level Execution Trace  
- APIC, PIT, LAPIC, I/O 이벤트 흐름 재구성  
- PFN & Page Table 구조 복원  
- Guest OS Timeline Analysis Engine  

### JKGO Toolchain
- Snapshot Loader  
- Memory Forensic Analyzer  
- QEMU Plugin Development Framework  
- Page Table / Timeline Visualization Toolkit  

---

## Collaboration

협업 환영 분야:

- 운영체제 / 시스템 소프트웨어 개발  
- 메모리 포렌식 / VMI 연구  
- 가상화 및 에뮬레이션 기술 연구  
- QEMU / KVM / Xen / Bochs 개발자  

---

## Join the Journey

보이지 않는 시스템 내부를 탐험하는 여정에 함께하고 싶다면  
언제든 Issue 또는 PR로 참여해 주세요.

**Journey of Kernel — Let’s GO deeper.**

**Official Website:** https://jkgo.kr
