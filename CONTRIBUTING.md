# Contributing to ZeeML Open-Source Repositories

Thank you for your interest in contributing to **ZeeML** ([https://zeeml.com](https://zeeml.com)) open-source extensions, IDE plugins, SDKs, and research benchmark datasets.

## Core Engineering Guardrails

1. **Deterministic & Reproducible Logic:**
   - Every calculation, schema flattener (`JSON <-> CSV`), grading conversion matrix, and linguistic cadence metric (`burstiness`, `Yule's K`, `reading time`) must produce identical outputs across browser, CLI, and IDE runtimes.
   - Compare outputs against our reference web workbenches at [https://zeeml.com/tools](https://zeeml.com/tools).
2. **Zero Bloated Dependencies:**
   - Keep core packages and browser extensions free of unnecessary third-party runtime dependencies so package footprints remain lightweight and auditable.
3. **Accessibility & UI Clarity (`zml-*` Design System):**
   - UI components in browser popups, Gutenberg blocks, and IDE panels must maintain WCAG AA/AAA contrast ratios and full keyboard navigation.

## Pull Request Workflow

1. Fork the target repository under [@Zee-ML](https://github.com/Zee-ML) and create a descriptive feature or bugfix branch (`feat/rfc4180-nested-arrays` or `fix/cgpa-ects-rounding`).
2. Add or update unit tests covering your change.
3. Ensure all linters and build checks pass locally before opening a Pull Request.
4. Reference the corresponding live specification on [https://zeeml.com](https://zeeml.com) in your PR description.
