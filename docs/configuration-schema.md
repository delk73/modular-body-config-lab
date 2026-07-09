# Configuration Schema

This document defines the first simple configuration table used by the notebook.

The schema is intentionally small. It is meant to describe placeholder modular assembly variants, not final engineering designs.

## Table

`config/modular-platform-config-v0.csv`

## Columns

| Column | Meaning |
|---|---|
| `platform_variant` | Name of the base placeholder platform variant |
| `module_name` | Name of the interchangeable module |
| `module_role` | Abstract role of the module |
| `mass_class` | Coarse mass class: `none`, `low`, `medium`, or `high` |
| `power_class` | Coarse power class: `none`, `low`, `medium`, or `high` |
| `cooling_class` | Coarse cooling class: `none`, `low`, `medium`, or `high` |
| `external_geometry_class` | Coarse external geometry class, such as `flush` or `pod` |
| `lighting_capability` | Abstract visible-state capability |
| `sim_role` | Intended downstream simulation role |
| `notes` | Human-readable notes |

## Boundary

The table describes abstract configuration metadata only. It does not encode weapons, tactics, evasion, stealth, or operational behavior.
