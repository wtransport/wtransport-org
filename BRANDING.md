# WTransport Design Semantics

This document defines the visual taxonomy, architectural metaphors, and deterministic color semantics for the WTransport organization and its protocol implementations.

## Architectural and Lexical Metaphor

The official mascot is the wasp. Its biological characteristics serve as a visual metaphor for the protocol's core technical primitives: low-latency transmission, high-concurrency execution, and lightweight protocol overhead. Furthermore, the nomenclature establishes a deterministic lexical alignment: the initial grapheme "W" unifies the mascot ("Wasp") with the underlying protocol ("WebTransport").

## Morphological Semantics

The geometric composition of the mascot encodes specific WebTransport protocol features:

- **Tripartite Stripes**: Denote the multiplexing of independent, ordered byte streams over a unified connection space.
- **Ocular Dots**: Represent the capability for discrete, unreliable datagram transmission.
- **Paired Wings**: Abstract the bidirectional flow of asynchronous stream I/O via embedded counter-directional arrows.
- **Terminal Stinger**: Signifies the abrupt execution of state teardown and abortive termination primitives.

## Color Taxonomy and Implementation Mapping

The visual assets use a dichotomy of stroke-based and solid-fill designs to distinguish between abstract specifications and concrete implementations. The hex values provide deterministic chromatic alignment with their respective programming language ecosystems:

### The WTransport Organization

- **Palette**: Monochrome (Hex: `#000000` stroke, `#FFFFFF` fill)
- **Semantics**: Represents the root organization, foundational protocol specifications, and language-agnostic architectural standards. The explicit stroke-only treatment signifies the abstract nature of the specification.

### PyWebTransport

- **Palette**: Amber (Hex: `#FFC107`)
- **Semantics**: Represents the async-native WebTransport stack for Python. The solid chromatic fill denotes a concrete implementation, providing a visual alignment with the broader Python ecosystem.

### WTransport-RS

- **Palette**: Deep Rust (Hex: `#BF360C`)
- **Semantics**: Represents the async-native WebTransport stack for Rust. The solid chromatic fill denotes a concrete implementation, providing a visual alignment with the broader Rust ecosystem.
