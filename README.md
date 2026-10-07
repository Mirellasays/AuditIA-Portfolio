# AuditIA

**Clinical AI Evaluation for Medical Auditing**

AuditIA is an independent portfolio project by **Mirella Batista Cruz, MD**, focused on the evaluation of generative AI in high-stakes medical-auditing workflows.

> **Status:** Development and exploratory evaluation. AuditIA is not a clinically validated medical device and is not intended for autonomous coverage or patient-care decisions.

## Purpose

Medical auditing requires structured evidence review, explicit criteria, uncertainty management, and accountable human judgment. AuditIA explores how these same disciplines can inform the evaluation of Clinical AI systems.

The public repository demonstrates the project's **evaluation philosophy, safety priorities, and governance approach**. Implementation details, complete prompts, scoring rubrics, benchmark datasets, internal test suites, and proprietary workflow logic are intentionally not published.

## Evaluation areas

AuditIA currently explores:

- Evidence grounding
- Logical consistency
- Missing-information handling
- Case isolation
- Robustness to untrusted source content
- Uncertainty and escalation
- Traceability and human oversight

See [Evaluation Framework](docs/evaluation-framework.md).

## Safety testing

The private development work includes synthetic adversarial and edge-case testing across categories such as incomplete evidence, logical-rule handling, context isolation, and instruction robustness.

The public [Test Catalogue](tests/synthetic-test-cases.md) describes these categories without disclosing the complete benchmark, prompts, expected-output specifications, or scoring rules.

## Safety & governance

AuditIA follows a physician-supervised approach centered on:

- Human-in-the-loop review
- Explicit evidence boundaries
- No silent completion of missing clinical data
- Case separation
- Appropriate escalation of uncertainty
- Traceability over persuasive fluency
- Privacy by design

See [Safety & Governance](docs/safety-governance.md).

## Current status

### Demonstrated in this portfolio
- Structured Clinical AI evaluation methodology
- Synthetic safety and failure-mode testing
- Iterative evaluation of model behavior
- Human-oversight and traceability principles
- Explicit validation boundaries

### Development roadmap
- Expanded benchmark design
- Formalized error taxonomy and performance measures
- Reproducible evaluation runs
- Version/change tracking
- Independent reviewer comparison

Roadmap items are not claims of completed validation.

## Public portfolio vs. private development

This repository is intentionally a **portfolio layer**, not a complete implementation.

**Public:** project purpose, high-level methodology, safety principles, selected evaluation categories, limitations.

**Private:** full prompts, system instructions, proprietary workflow logic, detailed scoring rubrics, complete benchmark/test set, unpublished analyses, implementation artifacts, and any future confidential materials.

## Project owner

**Mirella Batista Cruz, MD**  
Physician | Medical Auditing | Clinical AI Evaluation | AI Governance & Clinical Safety  
Ribeirão Preto, São Paulo, Brazil

[LinkedIn](https://www.linkedin.com/in/mirella-batista-cruz)

## Intellectual property and permitted use

Copyright © 2026 Mirella Batista Cruz. **All rights reserved.**

This repository is provided for portfolio review and informational purposes only. No license is granted to reproduce, modify, distribute, sublicense, commercialize, create derivative works from, incorporate into another product or service, or use the materials to develop or benchmark a competing system without prior written permission from the copyright owner.

Viewing the repository does not constitute a transfer or license of intellectual-property rights. See [LICENSE](LICENSE) and [NOTICE](NOTICE).

## Disclaimer

AuditIA is an independent educational and exploratory Clinical AI evaluation project. Public examples are synthetic and have no normative value. Nothing in this repository constitutes medical advice, a coverage authorization or denial, regulatory guidance, or a validated autonomous clinical decision-support system.
