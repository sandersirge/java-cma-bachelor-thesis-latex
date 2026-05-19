# Thesis: Extending the CMa Virtual Machine in Java to Support Function Calls

## Overview

This repository contains my bachelor’s thesis, which focuses on extending the CMa virtual machine (an abstract stack-based machine) implemented in Java to support function calls. The work is presented as a LaTeX project and combines theoretical analysis with practical implementation.

## Motivation

The motivation for this work comes from a deep interest in compilers, virtual machines, and the execution of imperative programming languages. The project is closely related to the University of Tartu course "Automaadid, keeled, translaatorid" ("Automata, Languages, Translators"), which covers the theoretical foundations of computation and translation mechanisms. This thesis continues those concepts in practice by extending the CMa virtual machine to support function calls, a key feature for modeling real program control flow.

## Goal

The main goal of this thesis is to extend the CMa virtual machine in Java by adding support for function calls. This required:

- Designing and implementing new instructions for function call and return
- Introducing stack frame management and additional registers (frame pointer, extreme pointer, heap pointer)
- Ensuring correct handling of nested and recursive calls
- Maintaining compatibility with existing instructions and programs

## Implementation

The CMa virtual machine is a stack-based abstract machine that models the execution of compiled imperative code. The extension implemented in this thesis adds support for function calls by:

- Adding 13 new machine instructions (e.g., MARK, CALL, ENTER, RETURN, SLIDE, LOADR, STORER, etc.)
- Extending the interpreter with stack frame and register management
- Updating the instruction type system to support new argument patterns
- Ensuring the runtime environment remains correct for nested and recursive calls

## Results

As a result of this work:

- The CMa simulator was extended to support function calls, including nested and recursive invocations
- 13 new instructions were implemented and integrated into the interpreter
- 46 JUnit tests were created to verify correctness, including unit, integration, and regression tests
- 1251 lines of new code were added, and all existing functionality was preserved

This project demonstrates how theoretical concepts from automata theory and compiler design can be realized in a practical system. The extension enables the CMa virtual machine to model realistic program control flow and provides a foundation for further enhancements, such as dynamic memory management.
