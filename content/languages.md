# Languages, libraries & IRs

Languages are grouped by paradigm. Each entry notes its host/implementation language where known.

## Functional & higher-order

- [Qunity](https://github.com/mikhailmints/qunity) (OCaml) - A unified functional language that expresses classical and quantum computation in one consistent syntax, with reversible semantics that treat quantum control flow as a first-class construct.
- [Quipper](https://github.com/thephoeron/quipper-language) (Haskell) - A scalable, higher-order functional quantum language embedded in Haskell, designed to describe large quantum circuits under the classical-control (QRAM) model.
- [QWire](https://github.com/inQWIRE/QWIRE) (Coq) - A minimal, formally verified core language for quantum circuits ("choir") that interfaces with an arbitrary classical host language following the QRAM model.
- **QML** (Functional) - A functional quantum language whose design is guided by its categorical semantics, integrating reversible and irreversible computation via strict linear logic.
- **qGCL** - A quantum extension of Dijkstra's Guarded Command Language introducing quantum alternation and quantum choice to support the superposition of programs.

## Procedural & imperative

- [Silq](https://github.com/silq-lang/silq) (D) - A high-level quantum language that automatically and safely uncomputes temporary values, letting programs implicitly drop intermediate results as in classical code for shorter, more intuitive quantum programs.
- [Twist](https://github.com/psg-mit/twist-popl22) (OCaml) - A quantum language whose type system tracks purity and entanglement, letting programmers state and statically verify assumptions about which qubits are entangled.
- [Tower](https://github.com/psg-mit/tower-oopsla22) (OCaml) - A language for building pointer-based data structures that live in quantum superposition, letting quantum algorithms use familiar structures such as linked lists and trees.
- [Scaffold](https://github.com/epiqc/ScaffCC) (C++) - A C-like quantum programming language compiled by the ScaffCC toolchain, aimed at expressing and analyzing large-scale quantum programs.
- [Q#](https://github.com/microsoft/qsharp-compiler) (C#) - Microsoft's high-level, hardware-agnostic domain-specific language for scalable quantum programming.
- **QCL** - One of the first quantum programming languages: a procedural, C-like language bringing classical concepts (memory management, flow control) to quantum computing.
- **isQ** - An imperative quantum programming language and integrated software stack that compiles to QIR, OpenQASM, and other intermediate representations.
- **RQC++** - A notation for recursively defined quantum circuits and quantum recursive programs.

## Embedded & high-level

- [Qrisp](https://github.com/eclipse-qrisp/Qrisp) (Python) - A high-level Python framework that raises quantum programming above the circuit level with managed QuantumVariables and automatic qubit allocation.
- [Qwerty](https://github.com/gt-tinker/qwerty) (Python) - A high-level, basis-oriented quantum language embedded in Python that abstracts away individual qubits and gates in favor of reasoning about bases and functions.
- [Guppy](https://www.quantinuum.com/blog/guppy-programming-the-next-generation-of-quantum-computers) (Python) - Quantinuum's Python-embedded DSL for high-level hybrid quantum-classical programs with rich, Pythonic control flow.
- [Qiwi](https://github.com/Abhinandan-Pal/qiwi) (Python) - A beginner-friendly quantum language offering high-level abstractions with dead-qubit elimination and dynamically sized data types.
- **Qurts** (Rust) - A high-level extension of Rust that leverages Rust's ownership and type systems to provide automatic uncomputation and quantum control.

## Circuit libraries

- [Qiskit](https://github.com/Qiskit/qiskit) (Python) - IBM's open-source SDK for composing, simulating, and running quantum circuits.
- [Cirq](https://github.com/quantumlib/Cirq) (Python) - Google's Python framework for writing, optimizing, and running circuits on NISQ devices.
- [t|ket〉](https://github.com/Quantinuum/tket) (Python) - Quantinuum's retargetable optimizing compiler and `pytket` toolkit for NISQ devices.
- [ProjectQ](https://github.com/ProjectQ-Framework/ProjectQ) (Python) - An open-source framework that compiles high-level quantum programs to a range of simulator and hardware backends.
- [pyQuil](https://github.com/rigetti/pyquil) (Python) - Rigetti's Python library for writing and running programs in the Quil instruction language.

## Intermediate representations

- [OpenQASM](https://github.com/openqasm/openqasm) (Python) - An imperative quantum assembly language and intermediate representation for describing quantum circuits.
- [QIR](https://github.com/qir-alliance/qir-spec) (LLVM) - The Quantum Intermediate Representation, an LLVM-based specification for representing quantum programs across toolchains.
- [SQIR](https://github.com/inQWIRE/SQIR/) (Coq) - A small quantum intermediate representation embedded in Coq for formally verified compilation and program proofs.
- [Quantum Control Machine](https://github.com/psg-mit/qcm-artifact) (OCaml) - An instruction set architecture whose conditional jump is restricted to the conditions under which control flow can be correctly realized in superposition.

## Quantum optimal & hardware control

The qosf [Awesome Quantum Software](https://github.com/qosf/awesome-quantum-software) list uses "quantum control" in its other sense — optimizing and calibrating the physical pulses that steer qubits. Those tools are included here for completeness.

**Python**
- [C3](https://github.com/q-optimize/c3) - Open-loop, closed-loop and automated Control, Calibration and Characterization of quantum devices.
- [Krotov](https://github.com/qucontrol/krotov) - Python implementation of Krotov's method for quantum optimal control.
- [Qibo](https://github.com/qiboteam/qibo) - Platform-agnostic quantum hardware control module with drivers for multiple instruments.
- [Quanlse](https://github.com/baidu/Quanlse) - Quantum control solutions via a cloud SDK, developed by [Baidu Quantum](https://research.baidu.com/Research_Areas/index-view?id=75).
