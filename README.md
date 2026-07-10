# modular-body-config-lab

Public notebook for modular CAD configuration studies and replay-oriented simulation inputs.

## Purpose

This repository captures a bounded learning path for modular CAD configuration work. The intent is to practice configuration discipline, interface vocabulary, and exportable table structure before connecting any CAD output to replay-oriented simulation.

The first useful output is a clean configuration artifact, not a complex model.

## Current focus

- define a public project boundary
- record learning notes as short notebook entries
- describe a small configuration schema
- keep one seed configuration table under version control
- reserve `exports/` for later CAD or table exports

## Initial exercise

Model or sketch a simple modular platform vocabulary:

- `base_body_v0`
- `module_slot_v0`
- `blank_module_v0`
- `sensor_placeholder_v0`
- `relay_placeholder_v0`
- `lighting_placeholder_v0`

These are placeholders for configuration learning. They are not operational system designs.

## Configuration artifact

The first retained configuration table is:

```text
config/modular-platform-config-v0.csv
```

It records coarse module classes such as mass, power, cooling, external geometry, lighting capability, and simulation role.

## Boundary

This repository is public and intentionally non-sensitive. It should stay focused on CAD configuration literacy, modular interface discipline, and simulation-input preparation.

Out of scope:

- weapons
- tactics
- evasion
- stealth
- defense simulation
- controlled or sensitive data
- operational system design
- flight, CFD, durability, or load claims

## Repository map

```text
docs/learning-log.md             running learning notes
docs/project-boundary.md         public scope and exclusions
docs/configuration-schema.md     CSV field definitions
notebooks/0001-evening-start.md  first bounded CAD/configuration exercise
config/modular-platform-config-v0.csv
exports/README.md                placeholder for future generated exports
```
