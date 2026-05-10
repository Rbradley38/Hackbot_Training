# Hackbot_Training

Repository scaffold for training an uncensored local model with [Unsloth](https://github.com/unslothai/unsloth).

## Purpose

This repository is intended to hold:
- training datasets and prompts
- training scripts/notebooks
- reproducible run configuration
- exported model artifacts (stored outside git)

## Suggested repository structure

```text
.
├── data/              # local datasets (gitignored by default)
├── notebooks/         # experimentation and prototyping
├── scripts/           # reusable training/eval scripts
├── configs/           # run and hyperparameter configs
├── outputs/           # checkpoints, logs, adapters (gitignored)
└── README.md
```

## Getting started

1. Create the project folders:
   - `data/`, `notebooks/`, `scripts/`, `configs/`, `outputs/`
2. Set up your Python environment and install Unsloth and your training stack.
3. Add your dataset under `data/`.
4. Store run settings under `configs/`.
5. Run training from `scripts/` or notebooks and write results to `outputs/`.

## Notes

- Keep model weights/checkpoints out of git.
- Commit only code, configs, and lightweight metadata needed to reproduce runs.
