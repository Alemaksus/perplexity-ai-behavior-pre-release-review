# Pre-Release AI Behavior & Risk Review

## Executive Summary

This document summarizes decision-relevant behavioral risk patterns observed across five representative user journeys in Perplexity AI (free, logged-out path). The review does not assess factual correctness of answers. Instead, it focuses on **how information is presented**: how sources are used, how uncertainty is communicated, and how recommendations are framed for users making real decisions.

These patterns matter before release (or broad adoption) because users may rely on AI-generated responses to make **purchasing, technical, or strategic decisions**. When authoritative tone, mixed-quality sources, or under-communicated uncertainty combine, the result can be avoidable decision errors, misaligned expectations, and erosion of user trust.

---

## What This Review Provides

- Identification of **cross-cutting AI behavior risk classes** observed across multiple user journeys.
- A **decision impact perspective** describing how these patterns can influence user choices and trust.
- Clearly defined **scope boundaries** to prevent overgeneralization of the findings.

This document is intended as a pre-release or pre-adoption artifact to support informed decision-making, not as a comprehensive evaluation of system correctness or performance.

---

## Assessed User Journeys

The review is based on five representative user journey types:

- Comparative evaluation (AI tool comparison)
- Capability boundary inquiry (limitations and constraints)
- Purchase decision support (upgrade recommendations)
- Drawback-focused inquiry (product criticism)
- Production readiness guidance (engineering and development risk)

These journeys represent common classes of real-world queries where users are likely to act on the output.

---

## Cross-Cutting Risk Classes

### Risk Class 1: Mixed Source Authority Without Signaling

Responses combine authoritative sources (official documentation, established media) with anecdotal or speculative sources (community discussions, rumors, blog posts) without clearly signaling differences in evidentiary weight. Claims supported by secondary or interpretive sources may read with the same authority as claims backed by primary documentation. Users may overestimate the reliability of speculative statements or treat anecdotal experiences as broadly representative.

---

### Risk Class 2: Uncertainty Not Elevated as a Decision Factor

Uncertainty is often communicated indirectly through conditional language rather than made explicit as a first-class decision input. For unreleased products or evolving capabilities, speculative information can appear in a similar tone to confirmed information. Users may underestimate the risk of acting on incomplete data or over-trust guidance in contexts where constraints materially matter.

---

### Risk Class 3: Alternatives Not Explicitly Contrasted

Trade-offs are discussed, but opposing viewpoints or “when the opposite choice is better” conditions are not consistently contrasted at the claim level. Alternative decision paths (such as deferring a decision until official information is available) may be implied but are not clearly framed as viable options. Users may miss safer or more appropriate alternatives.

---

### Risk Class 4: Claim-to-Source Traceability Friction

Sources are present (inline or as a list), but the mapping between specific claims and specific sources is not always explicit. Multiple sources may support a category of statements without indicating which source substantiates which claim. This increases verification effort and raises the likelihood that users accept conclusions without checking alignment.

---

### Risk Class 5: Confidence Level Not Calibrated to Evidence Strength

Responses often use advisory or prescriptive language even when underlying evidence is mixed, speculative, or anecdotal. Conditional limitations may read as general characteristics, and drawbacks are sometimes immediately softened by mitigation within the same narrative. Users may make decisions based on perceived consensus rather than on the strength of primary evidence.

---

### Risk Class 6: Mitigation Guidance Without Prioritization Criteria

Mitigation strategies and “best practices” are suggested, but criteria for prioritizing which constraints are most critical or most likely to occur are not clearly provided. Guardrails and reviews are described as mitigations without evidence or criteria to evaluate whether they are sufficient. Users may invest effort in low-impact mitigations while underestimating residual risk.

---

## Decision Impact Overview

Together, these patterns can reduce decision quality by inflating perceived certainty and obscuring the strength of supporting evidence. Under-communicated uncertainty increases the chance of acting on incomplete or evolving information. When alternatives are not clearly contrasted, users may default to immediate action even when deferral would be safer. Mixing anecdotal and authoritative sources without signaling can shift decisions toward sentiment rather than evidence. Finally, conceptual guidance without prioritization criteria makes it harder to translate advice into effective action.

---

## Scope & Limitations

This review reflects snapshot-in-time behavior observed through **free, logged-out access only**. No API access, paid features, or privileged internal tools were used. The assessment is OSINT-based and does not evaluate factual correctness, model performance, or internal system design. Observed behavior, sourcing, and UX may change over time.

---
