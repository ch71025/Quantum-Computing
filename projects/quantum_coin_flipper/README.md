# Quantum Coin Flipper Project

## Overview
A quantum version of a coin flip that demonstrates superposition and measurement.

## Classical vs Quantum Coin
- **Classical:** 50% heads, 50% tails (pseudo-random)
- **Quantum:** Actually both simultaneously until measured, then collapses

## Physics Principle
Applying a Hadamard gate to |0⟩ creates:
$$
H|0⟩ = \frac{|0⟩ + |1⟩}{\sqrt{2}}
$$

Measuring gives:
- |0⟩ with 50% probability
- |1⟩ with 50% probability

## Implementation Plan
1. Create single qubit circuit
2. Apply Hadamard gate
3. Measure qubit
4. Repeat for statistics
5. Compare to classical random

## Learning Objectives
- Understand quantum superposition
- Implement basic quantum circuit
- Visualize measurement probabilities

## Status: Planning Phase
*Code implementation coming soon*
