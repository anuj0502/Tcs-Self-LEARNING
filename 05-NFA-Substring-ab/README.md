# Experiment 5: NFA recognizing substring ab

**Type:** `fa`  
**Tool:** JFLAP 7.1  
**States:** 3  
**Transitions:** 6  
**Initial state:** q0  
**Final states:** q2

## Aim
A three-state NFA that nondeterministically searches for an `ab` substring over a,b.

## Transition details

| From | Input | To | Output |
|---|---|---|---|
| q0 | a | q0 | — |
| q2 | a | q2 | — |
| q0 | b | q0 | — |
| q2 | b | q2 | — |
| q1 | b | q2 | — |
| q0 | a | q1 | — |

## Test cases
Accepted: ab, aab, baba; rejected: aaa, bbb, ba.

## Procedure
1. Open JFLAP 7.1.
2. Select File → Open and choose `automaton.jff`.
3. Inspect the transition graph.
4. Use the relevant Input menu to run strings and verify results.

## Result
The provided JFLAP model is preserved exactly as uploaded. Test outcomes should be confirmed in JFLAP.
