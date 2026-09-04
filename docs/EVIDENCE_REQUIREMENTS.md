# Evidence Requirements

**Document Version:** Public v1

**Status:** Public Engineering

---

# Purpose

This document defines the recommended engineering evidence that should accompany an independent VRP validation report.

The objective is to improve reproducibility, transparency, and technical confidence.

Engineering conclusions should be supported by observable evidence.

---

# Engineering Principle

Claims without evidence should not be treated as engineering conclusions.

Every important observation should be traceable to reproducible validation.

---

# Required Evidence

Every validation report should include, where applicable:

- execution logs
- validation reports
- benchmark output
- manifests
- environment description
- software versions
- execution timestamps

The objective is to allow another engineering team to understand how the evaluation was performed.

---

# Recommended Evidence

Participants are encouraged to include:

- system information
- CPU information
- memory information
- operating system version
- virtualization platform
- compiler version
- repository revision
- validation configuration

Additional environmental information improves reproducibility.

---

# Engineering Reports

Reports should describe:

- evaluation objective
- methodology
- observed behavior
- unexpected observations
- engineering conclusions

Reports should distinguish observed facts from interpretation.

---

# Raw Evidence

Whenever possible, preserve original engineering evidence.

Examples include:

- raw execution logs
- benchmark outputs
- generated manifests
- validation summaries

Raw evidence should not be modified after execution.

---

# Screenshots

Screenshots may support engineering reports.

They should not replace:

- logs
- reports
- benchmark output
- reproducible engineering evidence

Screenshots are supplementary.

---

# Confidential Information

Evidence should never disclose:

- proprietary customer information
- protected runtime implementation
- confidential engineering assets
- information restricted by agreement

Participants remain responsible for protecting confidential information.

---

# Evidence Integrity

Engineering evidence should accurately represent the executed validation.

Evidence should not be selectively edited to strengthen conclusions.

Unexpected observations should remain documented.

---

# Final Principle

Engineering evidence is valuable because it allows independent reviewers to understand, reproduce, and evaluate technical conclusions.

Observable evidence should always take precedence over unsupported claims.