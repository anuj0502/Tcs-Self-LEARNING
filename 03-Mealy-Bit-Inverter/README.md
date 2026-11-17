# Experiment 3: Mealy machine: binary bit inverter

**Type:** `mealy`  
**Tool:** JFLAP 7.1  
**States:** 1  
**Transitions:** 2  
**Initial state:** q0  
**Final states:** Not applicable (transducer)

## Aim
A one-state Mealy machine. Input 0 produces output 1, and input 1 produces output 0.

## Transition details

| From | Input | To | Output |
|---|---|---|---|
| q0 | 0 | q0 | 1 |
| q0 | 1 | q0 | 0 |

## Test cases
Input 0101 gives output 1010.

## Procedure
1. Open JFLAP 7.1.
2. Select File → Open and choose `automaton.jff`.
3. Inspect the transition graph.
4. Use the relevant Input menu to run strings and verify results.

## Result
The provided JFLAP model is preserved exactly as uploaded. Test outcomes should be confirmed in JFLAP.
