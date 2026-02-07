# Perplexity AI — OSINT-based pre-release behavioral review (public)

This repository contains **manually captured, verbatim test logs** for a **public OSINT-based pre-release behavioral review** of Perplexity AI.

## Scope

- **Access path**: Free user path only
- **No privileged access**: No internal tools, no partner access
- **No API use**: No API keys, no automated retrieval
- **Capture method**: Manual runs and manual copy/paste of responses and sources shown

## Focus

- **Sources / evidence**: What sources were shown and how claims are supported
- **Uncertainty / alternatives**: What uncertainty is stated (or missing) and what plausible alternatives exist

## Adding a new test log

- **Where**: Add new logs to `tests_raw/`
- **Format**: `{NN}_{keyword}.md`
  - `NN`: two-digit sequential number (`01`, `02`, `03`, ...)
  - `keyword`: short lowercase slug derived from the query’s main keyword(s), max 20 chars, hyphen-separated
  - **Examples**:
    - `01_gemini-vs-chatgpt.md`
    - `02_gemini-boundaries.md`
    - `03_iphone-upgrade.md`
    - `04_iphone-drawbacks.md`
    - `05_cursor-vibe-coding.md`
- **How**: Copy `templates/test_log_template.md`, fill fields, and paste the verbatim answer and sources shown.

## Disclaimer

This is **not a product review** and does not attempt to rate quality or recommend usage. It is a **snapshot of observed behavior** from specific manual runs; outputs, UX, and sourcing behavior can change over time.

