# AI Pre-Release Stress Test

(Independent Risk Assessment Before Launch)

A fixed-scope, **3 working day** independent stress assessment designed to surface decision-relevant risks in an AI product before launch, a public demo, or onboarding initial customers. The focus is on observed behavior and user exposure in realistic journeys, not on benchmarking model capability. Some risks may not appear in internal testing but become material once real users rely on the system in decision-relevant contexts. The assessment prioritizes user exposure and decision impact over raw model capability.

## 1. Who This Is For

Growing AI SaaS teams preparing for launch, a public demo, or onboarding first clients—especially when AI output may influence user decisions, trust, or expectations. Typical stakeholders include founders, CTOs, product leads, and engineering owners responsible for release posture and customer risk.

## 2. What We Test

- **Behavioral Variability**  
  Stability of outputs across repeated runs and minor prompt variations, including drift in recommendation strength, implied confidence, tone, structure, and decision framing.

- **Boundary & Safety Consistency**  
  Consistency of refusals, safe-completion behavior, and boundary handling across adjacent prompts and edge cases.

- **Knowledge Reliability (if RAG is used)**  
  Retrieval-dependent behavior: source surfacing, citation/claim alignment, and whether uncertainty is appropriately signaled when evidence is weak or ambiguous.

- **Failure & Recovery Patterns (for agent/tool-based systems)**  
  How agentic flows behave under partial failures: tool errors, timeouts, missing context, and recovery behavior that affects user outcomes.

## 3. What You Receive

- **Structured Risk Heatmap**: a compact view of major risk areas and where they concentrate across assessed journeys
- **Top 3 Risk Signals**: the strongest recurring indicators of decision exposure observed during the assessment window
- **Release Recommendation (Go / Conditional / Delay)**: an executive-facing posture statement tied to observed risk patterns
- **Mitigation Suggestions**: practical, prioritized mitigation themes aligned to user-decision impact (not implementation-specific prescriptions)

## 4. What Is Not Included

This engagement is not:

- Continuous monitoring or long-term telemetry-based evaluation
- Model fine-tuning, training, or prompt-library buildout
- A full red-team engagement across broad adversarial surfaces
- Long-term QA outsourcing or ongoing release management

## 5. Timeline

- **3 working days**
- **Fixed scope**: focused coverage of **3–5 representative user journeys** agreed at the start of the engagement

## 6. Engagement Format

- **Remote**
- Access via **staging**, **demo environment**, or **API** (as applicable) using agreed credentials and constraints
