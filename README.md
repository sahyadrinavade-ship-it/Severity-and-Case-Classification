# Severity-and-Case-Classification
*Task ID:* task4

## Objective
Classify adverse drug reactions based on seriousness and expectedness. Evaluate multiple cases and determine their clinical impact using pharmacovigilance guidelines (ICH E2A / CIOMS criteria).

## Reference Definitions

- *Serious ADR:* results in death, is life-threatening, requires/prolongs hospitalization, causes persistent/significant disability, is a congenital anomaly, or is another medically important event.
- *Expected ADR:* the nature/severity is consistent with the approved product labeling / reference safety information.
- *Unexpected ADR:* not listed in the current labeling, or differs from it in nature, severity, or specificity.

## Case Classification Table

| Suspected Drug | Adverse Reaction | Seriousness | Expectedness | Justification |
|---|---|---|---|---|
| Amoxicillin | Skin rash, itching | Non-serious | Expected | Mild hypersensitivity reaction, well documented in labeling, does not meet seriousness criteria |
| Ibuprofen | GI bleeding requiring hospitalization | *Serious* | Expected | Hospitalization is a seriousness criterion; GI bleeding is a well-known, labeled NSAID risk |
| Metformin | Lactic acidosis | *Serious* | Unexpected | Life-threatening / medically important event; not consistent with routine expected profile at standard use |
| Atorvastatin | Elevated liver enzymes (mild) | Non-serious | Expected | Mild, reversible, and a recognized/labeled statin effect — doesn't meet seriousness threshold |
| Ciprofloxacin | Tendon rupture | *Serious* | Expected | Causes significant disability (seriousness criterion); tendon rupture is a labeled fluoroquinolone class warning |

## Summary

| Metric | Count |
|---|---|
| Total Cases | 5 |
| Serious | 3 |
| Non-serious | 2 |
| Unexpected | 1 |

## Analysis
Three of the five cases met seriousness criteria — GI bleeding requiring hospitalization, lactic acidosis, and tendon rupture — each satisfying at least one ICH E2A seriousness criterion (hospitalization, life-threatening, or significant disability). Only the metformin-associated lactic acidosis case was classified as unexpected, as it represents a rare, medically important event not routinely anticipated with standard dosing; the remaining reactions align with known labeling for their respective drug classes.
