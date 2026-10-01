# qdbg

gdb for quantum circuits. Step through a circuit gate by gate in the terminal, inspect amplitudes, per-qubit state, and entanglement, and break on conditions.

Status: early scaffold, nothing works yet.

## Planned

- TUI stepper (forward/back) over OpenQASM circuits
- Amplitude and probability view, per-qubit Bloch bars
- Entanglement view (entropy per qubit, mutual-information map)
- Breakpoints, e.g. `break when q2 entangled`, `break when P(|111>) > 0.5`

## Dev

```sh
uv sync
uv run qdbg
uv run pytest
```
