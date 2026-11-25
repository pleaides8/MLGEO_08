# AGENTS.md for MLGEO_08

## Project
Course repository for assignments and mini projects on my own MLGEO project.
Every number and figure here must be regenerated from a fresh clone using
the commands in README.md.

## Environment and compute
- Run all code through `pixi run`; add packages only with `pixi add`, and
  commit pixi.toml and pixi.lock together.
- Do not install packages with pip or conda outside pixi.

## Data and provenance
- Fetch values that a provider publishes (station coordinates, velocities,
  catalogs) and cite the URL and retrieval date; do not recompute or retype them.
- Download data with a script in this repository, not by hand, and record the
  dataset DOI or URL, version, and retrieval date in README.md.
- Never modify raw data files; write processed data to a separate folder.

## Code and workflow


- Every reported number and figure comes from a command listed in README.md.

## Reporting and credit

- Mark AI-drafted commits: "AI-assisted: <tool>, <what it drafted>".

## Verification
- Run `pixi run smoke` before reporting any result, and show its last line.
- Report the exact commands you ran and the commit hash they ran on.
- If a check fails or a value cannot be fetched, say so; do not substitute an estimate.
