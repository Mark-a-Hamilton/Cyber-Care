# 🛡️ Cyber Care — Rules of Engagement (RoE)

This document defines the non-negotiable boundaries, permissions, and responsibilities governing all Cyber Care engagements. It protects clients, contributors, and the platform’s ethical integrity.

---

## 🔒 Core Rules

### 1. Consent Is Mandatory
- ❌ No privileged actions (e.g. active scans, remediation, data exports) without documented client consent.
- ✅ Consent must be explicit, revocable, and logged via VC metadata.
- ⚠️ Implied or verbal consent is insufficient for privileged operations.

### 2. Passive Reconnaissance Is Limited
- ✅ Allowed only on public-facing assets post-inquiry, pre-engagement.
- ❌ No authentication, probing, or fingerprinting beyond public visibility.
- ✅ Results must be shared transparently and framed as preliminary.

### 3. Privilege Elevation Requires Justification
- ❌ No elevation without written approval and documented rationale.
- ✅ Scripts must respect user boundaries and include rollback options.

### 4. AI Involvement Must Be Disclosed
- ✅ AI-generated summaries, diagnostics, or recommendations must be clearly marked.
- ❌ No AI-led remediation or decision-making without human oversight.

### 5. Data Handling Is Strictly Controlled
- ❌ No data export, sharing, or off-platform storage without written consent.
- ✅ All exports must be logged and versioned.

---

## 🚫 Prohibited Actions

| Action                             | Status     | Notes |
|------------------------------------|------------|-------|
| Active scans without consent       | ❌ Forbidden | Even if client is aware verbally |
| Remediation without approval       | ❌ Forbidden | Must be logged with VC block |
| Privilege escalation without RoE   | ❌ Forbidden | Requires documented justification |
| AI-led decisions without review    | ❌ Forbidden | Human oversight required |
| Data export without consent        | ❌ Forbidden | Must be written and timestamped |
| Fear-based or coercive language    | ❌ Forbidden | Empathy and clarity required |

---

## ✅ Permitted Actions (With Conditions)

| Action                             | Status     | Conditions |
|------------------------------------|------------|------------|
| Passive diagnostics                | ✅ Allowed  | Public assets only |
| Repeat scans post-mitigation       | ✅ Allowed  | Must be logged and versioned |
| AI-assisted summaries              | ✅ Allowed  | Must be disclosed |
| Contributor suggestions            | ✅ Allowed  | Must follow ethical framing |
| Client-led remediation             | ✅ Encouraged | Supported with guidance |

---

## 🧭 Contributor Responsibilities

- Log all actions using VC metadata blocks.
- Pause immediately if ethical ambiguity arises.
- Escalate unclear consent, suspicious activity, or client distress.
- Maintain plain-English documentation for all client-facing outputs.
- Uphold the principle of “reasonable effort” in every engagement.

---

## 🔁 Engagement Lifecycle (Reference Only)

This RoE governs all phases of engagement, including:
- Pre-engagement passive recon
- Consent acquisition and scope definition
- Active diagnostics and remediation
- Post-mitigation verification
- Final reporting and closure

Each phase must comply with the rules above. Deviations require stewardship review and documented justification.

---

## 🧾 Amendments & Stewardship

This RoE is version-controlled. Proposed changes must:
- Preserve ethical clarity
- Enhance contributor empowerment
- Be reviewed and approved by the Cyber Care stewardship team.
