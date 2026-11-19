# cll-bench

**benchmarks** — part of [CLL](https://github.com/CLT-Wasim/CLL), the Conserving Logic Language.

> Read [`AGENTS.md`](./AGENTS.md) first. It points at the binding rules; this README is only a summary.

## Purpose

Benchmark kernels, the three required baselines (PyTorch plain, PyTorch + gradient checkpointing, PyTorch reversible), and the published results tables with commands and raw output.

## Status

Pre-v1. Nothing here is shipped until a command produced the result and the result is in a
results table with the command that produced it. See the milestone list in
[`ROADMAP.md`](https://github.com/CLT-Wasim/CLL/blob/main/ROADMAP.md).

## Layout

* `kernels/`
* `baselines/`
* `results/`

## Language policy

CLL for kernels; Python only in `baselines/` for the PyTorch comparison models (AGENTS.md section 3).

## License

Apache-2.0. See [`LICENSE`](./LICENSE).
