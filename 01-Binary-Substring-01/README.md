# Experiment 1: Binary substring 01

**Type:** `fa`  
**Tool:** JFLAP 7.1  
**States:** 3  
**Transitions:** 5  
**Initial state:** q0  
**Final states:** q2

## Aim
A finite automaton that reaches its accepting state after reading 01. The supplied q2 loop is labelled `0,1` as a single JFLAP read value; this may need splitting into separate 0 and 1 transitions for intended binary-alphabet behavior.

## Transition details

| From | Input | To | Output |
|---|---|---|---|
| q1 | 0 | q1 | — |
| q0 | 1 | q0 | — |
| q2 | 0,1 | q2 | — |
| q0 | 0 | q1 | — |
| q1 | 1 | q2 | — |

## Test cases
Examples for the intended substring language: 01, 001, 1010; nonexamples: 0, 111, 100.

## Procedure
1. Open JFLAP 7.1.
2. Select File → Open and choose `automaton.jff`.
3. Inspect the transition graph.
4. Use the relevant Input menu to run strings and verify results.

## Result
The provided JFLAP model is preserved exactly as uploaded. Test outcomes should be confirmed in JFLAP.
