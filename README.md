# TCS Self-Learning — 5 JFLAP Experiments

A collection of five Theory of Computation / TCS self-learning experiments, organized as a GitHub-ready repository.

## Experiments

| No. | Experiment | Type | Folder |
|---|---|---|---|
| 1 | Binary substring 01 | Finite automaton | [01-Binary-Substring-01](01-Binary-Substring-01/) |
| 2 | Epsilon-transition NFA | Finite automaton | [02-Epsilon-NFA](02-Epsilon-NFA/) |
| 3 | Mealy machine: binary bit inverter | Mealy machine | [03-Mealy-Bit-Inverter](03-Mealy-Bit-Inverter/) |
| 4 | Moore machine: parity of ones | Moore machine | [04-Moore-Parity](04-Moore-Parity/) |
| 5 | NFA recognizing substring ab | Finite automaton | [05-NFA-Substring-ab](05-NFA-Substring-ab/) |

## How to use

1. Install or launch JFLAP 7.1.
2. Open an experiment folder and load `automaton.jff` via **File → Open**.
3. Review that experiment's README for its aim, transitions, and suggested test inputs.
4. Run the automaton using JFLAP's simulation controls.

## Notes

- The five `.jff` files are unchanged copies of the uploaded originals.
- Experiment 1 contains a transition labelled `0,1` in the source file. It is preserved as-is; for a conventional binary automaton, inspect whether that should be two separate transitions.
- This repository was organized from the provided files; the external GitHub reference repository could not be retrieved, so its exact layout was not replicated.
- The original files were created with JFLAP 7.1 according to their XML comments.

## Repository structure

```text
TCS-Self-Learning-5-Experiments/
├── README.md
├── 01-Binary-Substring-01/
├── 02-Epsilon-NFA/
├── 03-Mealy-Bit-Inverter/
├── 04-Moore-Parity/
└── 05-NFA-Substring-ab/
```

Each experiment folder contains `README.md` and `automaton.jff`.
