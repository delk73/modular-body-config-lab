# Configuration schema

The initial configuration artifact is:

```text
config/modular-platform-config-v0.csv
```

The table is intentionally coarse. It exists to practice configuration discipline before detailed CAD export or simulation ingestion.

## Fields

| Field | Meaning |
| --- | --- |
| `platform_variant` | Named base platform variant. |
| `module_name` | Stable module identifier. |
| `module_role` | Coarse role for configuration grouping. |
| `mass_class` | Relative mass class, not measured mass. |
| `power_class` | Relative electrical power demand class. |
| `cooling_class` | Relative cooling need. |
| `external_geometry_class` | Coarse geometry relationship to body envelope. |
| `lighting_capability` | Placeholder visible/status lighting class. |
| `sim_role` | Intended role for later replay-oriented simulation ingestion. |
| `notes` | Short human note. |

## Allowed starting vocabulary

Use small vocabularies until CAD exports require expansion.

```text
mass_class: low | medium | high
power_class: none | low | medium | high
cooling_class: none | low | medium | high
external_geometry_class: flush | pod | protruding | internal
lighting_capability: none | status_visible | formation_visible | arrival_announcement
```

## Rule

Do not encode operational claims in this table. Keep it to configuration and placeholder simulation-input classes.
