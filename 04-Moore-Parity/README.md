# Experiment 4: Moore machine: parity of ones

**Type:** `moore`  
**Tool:** JFLAP 7.1  
**States:** 2  
**Transitions:** 4  
**Initial state:** q0  
**Final states:** Not applicable (transducer)

## Aim
A two-state Moore machine with E and O outputs. q0 represents even parity, q1 represents odd parity; input 1 toggles and input 0 preserves parity.

## Transition details

| From | Input | To | Output |
|---|---|---|---|
| q1 | 1 | q0 | E |
| q0 | 0 | q0 | E |
| q0 | 1 | q1 | O |
| q1 | 0 | q1 | O |

## State outputs

- q0: E
- q1: O

## Test cases
For input 101, outputs by state including initial state: E, O, O, E.

## Procedure
1. Open JFLAP 7.1.
2. Select File → Open and choose `automaton.jff`.
3. Inspect the transition graph.
4. Use the relevant Input menu to run strings and verify results.

## Result
The provided JFLAP model is preserved exactly as uploaded. Test outcomes should be confirmed in JFLAP.
