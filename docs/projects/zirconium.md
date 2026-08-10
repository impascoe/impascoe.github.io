---
title: Zirconium
---

# Zirconium

[Repository: impascoe/Zirconium](https://github.com/impascoe/Zirconium)

Zirconium (`.zr`) is an experimental, pre-alpha programming language implemented in Zig. The current work is a minimal end-to-end front-end pipeline for small function-based programs.

## Current pipeline

1. Tokenise identifiers, unsigned integer literals, and basic symbols.
2. Parse simple function declarations and integer-literal return statements.
3. Construct an abstract syntax tree.
4. Print a debug representation through a custom CLI.
5. Run parser tests with `zig build test`.

## Technical focus

The project centres on Zig, compiler front-end design, tokenisation, parsing, abstract syntax trees, command-line tooling, and early unit tests.

## Next areas of work

The planned direction includes arithmetic expressions, function parameters, source-span diagnostics, a symbol table, a type-system scaffold, a tree-walk interpreter, and arena-based memory management.

Zirconium is a practical study of language design and the trade-offs involved in parsing, diagnostics, and execution models.
