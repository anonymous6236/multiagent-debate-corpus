# kg_cfr_full corpus

This directory is a self-contained corpus of multi-agent debate trajectories.
It contains 90 knowledge-grounded trajectories across 3 crisis scenarios
(aegis_blackout, cerberus_biocontainment, synapse_orbital_strike),
with 30 runs per scenario. The runs were generated with a deterministic
seed for reproducibility and are used across ongoing research threads.

No author names, institution names, or paper titles are included.

## Contents

- trajectories/
  - <scenario>/
    - kg_cfr_full/
      - run_XX.json

## Scenarios

- aegis_blackout
- cerberus_biocontainment
- synapse_orbital_strike

## Notes

- Each file is a single trajectory JSON with session metadata and turn logs.
- The condition folder is fixed as kg_cfr_full for all runs.
- Filenames are normalized to run_00.json through run_29.json per scenario.
