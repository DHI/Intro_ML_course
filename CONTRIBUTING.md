# Contributing to Intro_ML_course

Thanks for contributing.

## Setup

1. Create and activate a virtual environment.
2. Install the core tools used in this repository:

```bash
pip install jupyter pandas numpy scikit-learn matplotlib seaborn tensorflow
```

3. Launch Jupyter and open the relevant notebook:

```bash
jupyter notebook
```

## Branch and PR Flow

1. Create a branch from `main` (for example `feature/module-6-cnn-exercise` or `fix/assignment-split-validation`).
2. Keep commits focused and descriptive.
3. Open a pull request to `main` with a short summary of:
   - What changed
   - Why it changed
   - How it was tested

## Repository Guidelines

- Keep notebook changes focused on the task at hand.
- Do not commit large generated outputs unless required for the course material.
- Keep datasets in their existing module folders and avoid unnecessary file moves.
- Use clear markdown explanations in notebooks for any new modeling steps.
- Avoid mixing broad refactors with behavioral changes in one PR.

## Testing and Validation

Before submitting:

1. Re-run edited notebook cells from top to bottom.
2. Verify there are no execution errors.
3. Confirm key outputs and plots are reproducible.

If your change affects model behavior, include a short note in the PR describing expected output changes and how you validated them.
