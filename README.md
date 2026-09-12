# No Embedding

A directory of research on high-level quantum programming languages. Most material is related
to **quantum control** — and in particular **quantum control flow**: the branching, iteration,
and recursion that depend on data held in superposition — with some on uncomputation and
debugging.

Unlike classical control flow, which a program counter resolves from definite data, quantum
control flow must keep its guard in superposition without measuring it. This single difference
shapes much of the language design, semantics, and verification work collected here. The
[Quantum optimal & hardware control](content/languages.md#quantum-optimal--hardware-control)
section covers the other meaning of "quantum control" — the pulse-level steering of physical
qubits.

<a href="https://gitlab.com/nexa/nexa">
<img src="https://img.shields.io/badge/License-CC--0-blue.svg" /></a>

## Contents

The list is split by topic — click through for the full entries:

- [Languages, libraries & IRs](content/languages.md) — functional, procedural, embedded languages, circuit libraries, intermediate representations, and hardware/pulse-level control tools.
- [Literature](content/papers.md) — surveys, foundations, quantum control flow, semantics & type systems, languages/frameworks/compilers, uncomputation, verification & debugging.
- [Research groups & institutions](content/groups.md)
- [Reports](#reports) — longer write-ups built from this list.
- [Reference](#reference) · [License](#license)

## Reports

- [Control Flow in Quantum Full-Stack Libraries](content/reports/control-flow-report.md) — a capability and correctness assessment of control flow support across quantum full-stack libraries.
- [Quantum Control: Research Questions & Sub-Areas](content/reports/research-questions.md) — a map of the open problems in quantum control flow and the research sub-areas organized around them.

## Reference

- [awesome-quantum-software](https://github.com/qosf/awesome-quantum-software#readme)
- [awesome-quantum-programming-languages](https://github.com/fuyu-quant/awesome-quantum-programming-languages#readme)
- [awesome-quantum-computing](https://github.com/desireevl/awesome-quantum-computing#readme)
- [awesome-qsharp](https://github.com/ebraminio/awesome-qsharp#readme)

## Contributing

The list lives in [`content/`](content/) as plain Markdown, one file per topic
(`languages.md`, `papers.md`, `groups.md`), plus [`content/reports/`](content/reports/) and
[`content/logos/`](content/logos/) for institution logos. Edit those files to add or update
entries. [`index.html`](index.html) is a hand-written static page for GitHub Pages that mirrors
this list with the old site's look — when you change the content here, update it too.

## License

<a href="https://gitlab.com/nexa/nexa">
<img src="https://img.shields.io/badge/License-CC--0-blue.svg" /></a>
