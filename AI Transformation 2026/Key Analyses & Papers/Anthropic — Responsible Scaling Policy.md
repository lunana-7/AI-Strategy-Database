---
tags:
  - Analysis
  - AI-Safety
  - Governance
  - Anthropic
  - "2026"
parent: "[[Key Analyses & Papers MOC]]"
created: 2026-04-07
author: Anthropic
type: policy-analysis
---

# Anthropic — Responsible Scaling Policy (RSP)

> Anthropic's **Responsible Scaling Policy** is the most influential corporate AI safety framework to date — a structured approach to scaling AI capabilities while maintaining safety guardrails, now in its third version (v3.0, February 2026).

---

## Overview

Anthropic, the maker of Claude, introduced the Responsible Scaling Policy in September 2023 as the industry's first formalized framework for **tying AI capability increases to safety evaluations**. The core principle: before deploying a more powerful model, demonstrate that your safety measures are adequate for its capability level.

The RSP has been updated three times, with each version reflecting the rapidly evolving risk landscape. It has catalyzed similar frameworks at OpenAI, Google DeepMind, and other frontier labs.

---

## The ASL Framework

The RSP centers on **AI Safety Levels (ASLs)** — a tiered system inspired by biosafety levels (BSL-1 through BSL-4):

### ASL-1: No Meaningful Risk
- AI systems with no significant uplift over existing tools
- Standard security and deployment practices sufficient

### ASL-2: Current Frontier Models (Present Day)
- Models that match but don't meaningfully exceed the capabilities of non-AI baselines for catastrophic misuse
- Requires: harmlessness training, usage policies, basic security
- All currently deployed Claude models operate at ASL-2

### ASL-3: Materially Elevated Risk
- Models that provide a meaningful uplift in catastrophic misuse capabilities (e.g., bioweapons, cyberattacks)
- Requires: enhanced containment, advanced red-teaming, information security measures
- Anthropic's ASL-3 defenses include "Constitutional Classifiers" — a novel approach to filtering dangerous outputs

### ASL-4 and Beyond: Not Yet Defined
- Would apply to models with capabilities approaching or exceeding human expert level in dangerous domains
- Specific requirements will be defined as capabilities approach these thresholds
- The "define as you go" approach is intentional — avoid premature specification

---

## RSP Version 3.0 (February 2026)

The third version represents the most significant structural update:

### What Changed
1. **Frontier Safety Roadmaps** — Detailed public documents outlining safety research goals and timelines
2. **Risk Reports** — Quantitative risk assessments across all deployed models
3. **Unilateral vs. Industry Commitments** — Clearer separation between what Anthropic commits to alone versus what it recommends for the industry
4. **Capabilities-to-Mitigations Map** — Explicit mapping of capability thresholds to required safety measures

### Safety Research Goals
Specific goals outlined in v3.0 include:
- Investigating unconventional approaches to high-level information security
- Automating red-teaming processes at scale
- Systematic measures to align Claude with its constitutional framework
- Centralizing records of critical AI development activity
- Publishing proposals for scalable AI regulation

---

## Industry Impact

The RSP's influence extends well beyond Anthropic:

- **OpenAI** adopted a broadly similar "Preparedness Framework" within months
- **Google DeepMind** published its "Frontier Safety Framework" following the RSP model
- **Meta** referenced RSP-style evaluations in its responsible release policies
- Several governments cited the ASL framework in their regulatory guidance
- The concept of "if-then" safety commitments (if capabilities reach X, then implement safety measure Y) has become an industry standard

---

## Critical Assessment

### Strengths
- **Concreteness** — Unlike vague AI ethics statements, the RSP ties specific capabilities to specific actions
- **Adaptability** — The "define as needed" approach avoids premature lock-in
- **Transparency** — Public commitment creates accountability
- **Catalytic** — Prompted competitor adoption of similar frameworks

### Criticisms and Debates
- **Self-regulation concerns** — Critics argue companies shouldn't set their own safety standards
- **Enforcement mechanism** — Who holds Anthropic accountable to its own commitments?
- **Evolving commitments** — The v3.0 update drew scrutiny for revising earlier pledges
- **Race dynamics** — Does publishing safety thresholds create perverse incentives for competitors to rush past them?
- **Measurement challenges** — How precisely can you measure "meaningful uplift" in dangerous capabilities?

---

## Connections

- [[AI Governance 2026]] — RSP as a model for corporate AI governance
- [[Responsible AI 2026]] — Practical implementation of responsible AI principles
- [[Foundation Models 2026]] — ASL levels directly tied to model capabilities
- [[EU AI Act 2026]] — Regulatory frameworks that may codify RSP-like requirements
- [[Dario Amodei — Machines of Loving Grace]] — Amodei's optimism contextualized by RSP's safety framework
- [[Ilya Sutskever — Safe Superintelligence]] — Both address safety-capability tradeoffs, from different angles
- [[Mustafa Suleyman — The Coming Wave]] — Suleyman's "containment" thesis aligns with the ASL approach

---

## Sources

- [Anthropic — Responsible Scaling Policy](https://www.anthropic.com/responsible-scaling-policy)
- [RSP Version 3.0](https://www.anthropic.com/news/responsible-scaling-policy-v3)
- [Frontier Safety Roadmap](https://www.anthropic.com/responsible-scaling-policy/roadmap)
- [Constitutional Classifiers (Research)](https://www.anthropic.com/research/constitutional-classifiers)
