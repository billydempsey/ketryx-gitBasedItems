---
itemId: tc-basic-dose-001
itemType: Test Case
itemTitle: Verify basic dose calculation
itemTests: spec-basic-dose-001
---

# Verify basic dose calculation

## Item fields

### Description

Verify that the system calculates the dose as `dose_mg = patient_weight_kg * dose_per_kg_mg` and rounds to the nearest whole milligram.

### Steps

1. Configure `dose_per_kg_mg = 2`.
2. Enter `patient_weight_kg = 70`.
3. Trigger dose calculation.
4. Observe the displayed dose.

### Expected result

The displayed dose is `140 mg`.
