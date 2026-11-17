# Experiment 2: Epsilon-transition NFA

**Type:** `fa`  
**Tool:** JFLAP 7.1  
**States:** 14  
**Transitions:** 16  
**Initial state:** q0  
**Final states:** q1

## Aim
An epsilon-NFA with 14 states, using a and b transitions and epsilon transitions. The graph includes a reachable branch for ab, but the accepting state is reached via that branch; other branches form epsilon cycles.

## Transition details

| From | Input | To | Output |
|---|---|---|---|
| q5 | ε | q6 | — |
| q8 | ε | q12 | — |
| q11 | ε | q9 | — |
| q13 | ε | q9 | — |
| q3 | ε | q2 | — |
| q12 | b | q13 | — |
| q4 | a | q5 | — |
| q2 | ε | q3 | — |
| q0 | ε | q2 | — |
| q3 | ε | q4 | — |
| q2 | ε | q8 | — |
| q10 | a | q11 | — |
| q7 | ε | q1 | — |
| q8 | ε | q10 | — |
| q9 | ε | q3 | — |
| q6 | b | q7 | — |

## Test cases
Try `ab` as an accepted input; try `a`, `b`, and the empty string as rejected inputs.

## Procedure
1. Open JFLAP 7.1.
2. Select File → Open and choose `automaton.jff`.
3. Inspect the transition graph.
4. Use the relevant Input menu to run strings and verify results.

## Result
The provided JFLAP model is preserved exactly as uploaded. Test outcomes should be confirmed in JFLAP.
