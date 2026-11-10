---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## [cbril](https://github.com/XFabian/cbril) (C++20, LLVM)
A toolchain for the Bril IR, written from scratch: CFG construction, a dataflow framework,
dominator tree and dominance frontiers, SSA construction, loop detection and simplification,
DCE, LVN, GVN, sparse conditional constant propagation, and an LLVM IR backend.

## [rwetac](https://github.com/XFabian/rwetac) (Rust)
An optimizing compiler for the Eta language targeting WebAssembly, with a configurable pass
pipeline and a Wasmer-based runtime. It translates a three-address-code IR with unstructured
jumps back into WebAssembly's structured control flow. It is now the course compiler for the
Compiler Construction course at the University of Trento.

## [eta-wasm](https://github.com/XFabian/eta-wasm) (OCaml)
A smaller Eta-to-WebAssembly compiler with a CFG-based dataflow framework.

## Research artifacts
- [Spectector-Combined](https://github.com/XFabian/Spectector-Combined): extension of the
  Spectector static analyzer that detects combinations of Spectre attacks (CCS'22).
- [secure_comp_lifting](https://github.com/XFabian/secure_comp_lifting): artifact for the
  POPL'25 paper on lifting compiler security guarantees against Spectre attacks.
