# Thesis: Extending the Functionality of a Simple C Abstract Machine implementation written in Java

## Overview

This repository contains my thesis, which focuses on extending the functionality of a simple C abstract machine. The work is presented as a LaTeX project and combines both theoretical analysis and practical implementation.

## Motivation

The choice of this topic stems from my strong interest in compilers, assembly, and machine-level programming. These areas provide a deeper understanding of how high-level code is translated and executed at a lower level.

This thesis is also closely connected to the university course "Automaadid, keeled, translaatorid" ("Automata, Languages, Translators"), which introduces the theoretical foundations of computation, formal languages, and translation mechanisms such as compilers and interpreters. The project serves as a practical continuation of these concepts, allowing me to explore how they apply in a concrete implementation.

## Goal

The main goal of this applied academic work is to deepen understanding of how compiled code from imperative programming languages is executed step by step.

A key focus is on:

- Understanding the execution model of a stack-based virtual machine
- Exploring how abstract machines simplify the behavior of real hardware
- Analyzing how instructions are processed and how program state evolves during execution

From a practical perspective, the work involves extending the abstract machine by adding support for executing function callback steps. This introduces additional complexity in how execution is managed and requires careful consideration of how:

- The runtime environment is affected
- The call stack is manipulated
- Existing components must be adapted to maintain compatibility

## Implementation

The abstract machine used in this thesis is a stack-based virtual machine, which serves as an abstraction of real physical hardware. This design simplifies the understanding of machine-level execution while still preserving essential concepts such as:

- Stack frames
- Function calls
- Instruction sequencing

The extension implemented in this work focuses on integrating callback execution into this model and ensuring that the system remains consistent and well-structured after the modification.

## Results

As a result of this work:

- A deeper understanding of the execution of compiled imperative code is achieved
- The internal workings of a stack-based abstract machine are explored in detail
- A functional extension supporting callback execution is implemented
- The impact of this extension on the machine's architecture and environment handling is analyzed

This project demonstrates how theoretical concepts from automata theory and compiler design translate into practical systems and highlights the challenges involved in extending execution models while preserving correctness.
