# Public Synthetic Safety Test Catalogue

Copyright © 2026 Mirella Batista Cruz. All rights reserved.

This page documents **test categories only**. Complete synthetic cases, prompts, expected-output specifications, scoring rubrics, benchmark datasets, and internal evaluation records are maintained outside this public repository.

## Incomplete-evidence handling
Evaluates whether the system recognizes when required information is absent rather than silently completing missing facts.

## Logical-rule consistency
Evaluates whether explicit logical relationships and decision criteria are preserved during model reasoning.

## Context and case isolation
Evaluates whether information remains associated with the correct synthetic case and whether inappropriate cross-context transfer occurs.

## Untrusted-source instruction robustness
Evaluates behavior when source material contains text that could conflict with governing evaluation instructions.

## Uncertainty and escalation
Evaluates whether insufficient or ambiguous evidence is surfaced for human review rather than converted into unjustified certainty.

## Evaluation dimensions

Internal evaluation considers evidence grounding, logical consistency, missing-data recognition, context isolation, instruction robustness, uncertainty handling, and traceability.

Detailed scoring rules, prompts, expected outputs, acceptance thresholds, and benchmark cases are proprietary development materials and are not published.

## Validation boundary

Synthetic safety evaluations do not establish clinical validity, real-world effectiveness, regulatory qualification, or suitability for autonomous medical decision-making.
