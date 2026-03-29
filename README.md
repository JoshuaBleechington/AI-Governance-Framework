# AI Governance & Compliance Framework
### NIST AI RMF · EU AI Act · ISO/IEC 42001 · Responsible AI
<img width="1408" height="768" alt="Firefly_Gemini Flash_The funny one — great for keeping people engaged-__-A stressed cartoon robot buried u 964978" src="https://github.com/user-attachments/assets/1e4e1043-232d-4d04-b16c-ca6a8671e047" />



In this project, I researched, mapped, and applied the leading AI governance frameworks to a real organizational context — demonstrating how a security and GRC professional would evaluate, classify, and manage AI system risk in a modern enterprise environment.

**Inception State:** The organization had no AI governance policy, no inventory of AI tools in use, and no framework for evaluating risk before deploying AI-powered systems.

**Completion State:** A documented AI governance program aligned to NIST AI RMF, EU AI Act risk tiers, and ISO/IEC 42001 — including an AI system inventory, risk classifications, policy templates, and a compliance comparison across frameworks.

---

> 🤖 **[View Interactive AI Governance Dashboard →](https://joshuableechington.github.io/AI-Governance-Framework/ai-governance-dashboard.html)**
> *Includes EU AI Act Risk Pyramid, NIST AI RMF Core Functions, Interactive Risk Classifier, and Framework Comparison*
> 📋 **[AI Vendor Risk Questionnaire (Interactive) →](https://joshuableechington.github.io/AI-Governance-Framework/ai-vendor-questionnaire.html)**
---

## Why AI Governance Matters Now

AI is no longer just a technology issue — it is a **risk, compliance, and governance issue**. Organizations deploying AI tools face exposure across three dimensions:

- **Regulatory** — The EU AI Act is now in force. US federal agencies are adopting NIST AI RMF. State-level AI laws are accelerating.
- **Reputational** — Biased hiring algorithms, opaque credit decisions, and manipulative AI have resulted in public backlash and litigation.
- **Operational** — Unmanaged AI models drift, hallucinate, and produce unpredictable outputs that can create liability.

Security and GRC professionals who understand AI governance frameworks are among the most sought-after in the market heading into 2026.

---

## Technology & Frameworks Applied

| Framework | Type | Jurisdiction | Focus |
|---|---|---|---|
| **NIST AI RMF 1.0** | Voluntary | United States | Risk lifecycle (Govern, Map, Measure, Manage) |
| **EU AI Act** | Binding Regulation | European Union | Risk-tier classification + prohibitions |
| **ISO/IEC 42001** | Certifiable Standard | Global | AI Management System (AIMS) |
| **OECD AI Principles** | Voluntary | International | Human-centric AI design principles |

---

## Table of Contents

- [Project Overview](#project-overview)
- [NIST AI RMF — Core Functions](#step-1-nist-ai-rmf--core-functions)
- [EU AI Act — Risk Tier Classification](#step-2-eu-ai-act--risk-tier-classification)
- [AI System Inventory & Risk Assessment](#step-3-ai-system-inventory--risk-assessment)
- [Governance Policy Development](#step-4-governance-policy-development)
- [Conditional Controls by Risk Tier](#step-5-conditional-controls-by-risk-tier)
- [Framework Comparison](#step-6-framework-comparison)
- [Key Findings & Recommendations](#key-findings--recommendations)

---

## Project Overview

After observing the rapid adoption of AI tools across the organization — including AI-assisted content generation, automated scheduling, and vendor-provided ML-driven analytics — I identified a gap: **no governance structure existed to evaluate whether these tools were safe, compliant, or aligned with organizational risk tolerance.**

This project simulates what a GRC or Security Architect would do to close that gap, from framework selection through policy implementation.

---

## Step 1) NIST AI RMF — Core Functions
<img width="1408" height="768" alt="NIST AI RMF" src="https://github.com/user-attachments/assets/2cd8abb4-9a5d-49a3-9a56-73b819939ad0" />

The **NIST AI Risk Management Framework (AI RMF 1.0)** provides a voluntary, non-prescriptive approach to managing AI risk across four core functions. I used this as the organizational backbone of the governance program.

### GOVERN
Establishes the policies, accountability structures, and organizational culture required to manage AI risk.

Key actions taken:
- Defined organizational AI risk appetite: *"AI tools may be used to augment human decision-making but may not be used as the sole decision-maker for outcomes that materially affect employees, customers, or business operations."*
- Assigned an AI Risk Owner role (maps to CISO/GRC function)
- Created an AI Acceptable Use Policy covering tool onboarding, vendor review, and disclosure obligations

### MAP
Identifies and categorizes AI systems in use and the context in which they operate.

Key actions taken:
- Completed an **AI System Inventory** of all tools currently in use across departments
- Documented data inputs, outputs, affected populations, and decision types for each system
- Mapped each system to an EU AI Act risk tier (see Step 2)

### MEASURE
Analyzes, assesses, and tracks identified AI risks using quantitative and qualitative methods.

Key actions taken:
- Developed evaluation criteria across six AI trustworthiness dimensions: Validity & Reliability, Safety, Explainability, Privacy, Fairness, and Security
- Created a vendor AI risk questionnaire for third-party AI tool procurement
- Established model monitoring checkpoints for drift and accuracy degradation

### MANAGE
Prioritizes and addresses AI risks through response plans and ongoing monitoring.

Key actions taken:
- Tiered AI systems into risk bands (High / Medium / Low) with corresponding review cadences
- Documented a decommission protocol for AI systems that exceed acceptable risk thresholds
- Integrated AI risk reviews into the existing Change Advisory Board (CAB) process

---

## Step 2) EU AI Act — Risk Tier Classification
<img width="1408" height="768" alt="NIST AI AMF Image" src="https://github.com/user-attachments/assets/b32fd4ba-2d3a-45ae-be2a-91d667b05b46" />

The **EU AI Act** (effective August 2024, phased enforcement through 2027) establishes a risk-based classification system. Even organizations outside the EU must comply if they deploy AI systems that affect EU residents.

### Tier 1 — Unacceptable Risk (Prohibited)
AI applications that pose a clear threat to fundamental rights. **Outright banned** with no compliance pathway.

Examples: Social scoring systems, real-time biometric surveillance in public spaces, subliminal manipulation, exploitation of vulnerable groups.

> **Organizational posture:** Prohibited systems will not be considered under any circumstances. Any vendor proposing such capabilities will be immediately disqualified during procurement review.

### Tier 2 — High Risk (Strictly Regulated)
AI systems used in critical sectors or that significantly impact people's rights and safety. **Mandatory requirements** include conformity assessments, human oversight, bias testing, and registration in the EU AI database.

High-Risk domains: Employment/HR tools, credit scoring, medical devices, law enforcement, education, critical infrastructure.

> **Organizational posture:** Any high-risk AI system requires security/GRC review, legal sign-off, and documented human oversight procedures before deployment.

### Tier 3 — Limited Risk (Transparency Required)
AI systems that interact with humans must disclose they are AI. Users must be notified when interacting with a chatbot, AI-generated content, or emotion recognition system.

> **Organizational posture:** All customer-facing AI tools include mandatory AI disclosure language. All AI-generated content is labeled prior to publication.

### Tier 4 — Minimal Risk (Voluntary Standards)
The majority of AI systems. No mandatory EU AI Act obligations, though voluntary codes of conduct apply. Standard data protection and security rules (GDPR, CCPA) still apply.

> **Organizational posture:** Minimal-risk AI tools follow standard IT procurement process with abbreviated AI risk questionnaire.

---

## Step 3) AI System Inventory & Risk Assessment

The following AI systems were identified across the organization and classified:

| AI System | Department | EU AI Act Tier | NIST Risk Level | Human Oversight Required |
|---|---|---|---|---|
| AI Content Generator (marketing copy) | Marketing | Limited (Tier 3) | Low | No — review before publish |
| AI-Assisted SEO Analysis | Marketing | Minimal (Tier 4) | Low | No |
| Automated Scheduling / Calendar AI | Operations | Minimal (Tier 4) | Low | No |
| Vendor Credit Risk Scoring (3rd party) | Finance | High (Tier 2) | High | Yes — human review required |
| AI-Powered HR Screening Tool (vendor) | HR | High (Tier 2) | High | Yes — human review required |
| Customer Service Chatbot | Customer Success | Limited (Tier 3) | Low | No — but AI must be disclosed |
| Anomaly Detection (Sentinel / Defender) | Security | Minimal (Tier 4) | Medium | Yes — analyst reviews alerts |

**Key finding:** Two vendor-provided tools (HR screening, credit risk scoring) fall under **EU AI Act High Risk** classification and require immediate conformity review and documented human oversight procedures.

---

## Step 4) Governance Policy Development
<img width="1408" height="768" alt="Firefly_Gemini Flash_I want a sleak Human hand AND robot AI collaboration to show the HITL  Something futu 964978" src="https://github.com/user-attachments/assets/81a7791a-6d43-407e-8c75-fe42c1e26937" />


The following policy documents were developed as outputs of this program:

**AI Acceptable Use Policy**
- Defines permitted and prohibited uses of AI across the organization
- Establishes disclosure requirements for customer-facing AI
- Sets approval thresholds for new AI tool adoption by risk tier

**AI Vendor Risk Questionnaire**
- 28-question assessment covering model transparency, bias testing, data handling, and compliance certifications
- Required for any vendor providing AI/ML capabilities as part of their product
- Maps to NIST AI RMF Measure function and EU AI Act conformity assessment requirements

**AI Incident Response Procedure**
- Defines what constitutes an "AI incident" (harmful output, discriminatory decision, model failure)
- Escalation path from operational team → GRC → Legal
- Integrates with existing security incident response workflow

---

## Step 5) Conditional Controls by Risk Tier

| Control | Minimal Risk | Limited Risk | High Risk | Unacceptable |
|---|---|---|---|---|
| AI System Inventory Entry | ✅ Required | ✅ Required | ✅ Required | ❌ Prohibited |
| Vendor AI Risk Questionnaire | Abbreviated | Standard | Full | N/A |
| GRC/Security Review | ❌ Not required | Recommended | ✅ Required | N/A |
| Legal Sign-Off | ❌ Not required | ❌ Not required | ✅ Required | N/A |
| Human Oversight Procedure | ❌ Not required | Recommended | ✅ Required | N/A |
| AI Disclosure to Users | ❌ Not required | ✅ Required | ✅ Required | N/A |
| Bias / Fairness Testing | Voluntary | Voluntary | ✅ Required | N/A |
| Annual Compliance Review | Voluntary | Voluntary | ✅ Required | N/A |
| EU AI Database Registration | ❌ Not required | ❌ Not required | ✅ Required | N/A |

---

## Step 6) Framework Comparison

| Dimension | NIST AI RMF | EU AI Act | ISO/IEC 42001 |
|---|---|---|---|
| **Mandatory?** | No — voluntary | Yes — binding law | No — voluntary certification |
| **Penalties?** | None | Up to €35M or 7% global revenue | None (certification loss) |
| **Scope** | US-focused, global applicability | EU + extraterritorial reach | Global |
| **Approach** | Process-based lifecycle | Prescriptive risk tiers | Management system standard |
| **Best used for** | Internal AI risk program design | Legal compliance for EU market | Demonstrating AI governance maturity |
| **Overlap** | Maps to ISO 42001 clauses | Can use NIST to implement | Aligns with NIST + EU Act |

> **Practical note:** For a US-based organization with EU customers, the optimal approach is to use **NIST AI RMF as the program backbone**, **EU AI Act as the compliance overlay**, and pursue **ISO/IEC 42001 certification** to demonstrate governance maturity to enterprise clients and regulators.

---

## Key Findings & Recommendations

| Priority | Finding | Recommendation |
|---|---|---|
| 🔴 High | HR screening vendor not assessed for EU AI Act High-Risk compliance | Initiate conformity assessment; require vendor documentation within 30 days |
| 🔴 High | No AI disclosure language on customer-facing chatbot | Add required EU AI Act Tier 3 disclosure before next sprint release |
| 🟡 Medium | No formal AI system inventory existed prior to this project | Maintain inventory in GRC tool; review quarterly |
| 🟡 Medium | No AI vendor risk questionnaire in procurement process | Integrate into vendor onboarding workflow immediately |
| 🟢 Low | AI content generation used without labeling policy | Implement AI-generated content labeling standard for all published material |

---

## Ongoing AI Governance Activities
<img width="1408" height="768" alt="Firefly_Gemini Flash_-A small cute robot wearing a tiny graduation cap and a business suit, proudly holdin 964978" src="https://github.com/user-attachments/assets/175b1ffe-ee84-44db-b9aa-64cee372bbd1" />

- **Quarterly AI inventory reviews** — identify new tools adopted by business units
- **Annual framework refresh** — track updates to EU AI Act enforcement timeline and NIST AI RMF guidance
- **AI vendor reassessments** — re-evaluate high-risk vendors annually or upon major product changes
- **Workforce awareness** — deliver AI literacy training covering responsible use, bias awareness, and disclosure obligations
- **Regulatory monitoring** — track US state AI legislation, FTC AI guidance, and SEC AI disclosure requirements

---

*Part of an ongoing Microsoft Security Stack and GRC implementation at Pursue SEO Marketing. See also:*
*[Vulnerability Management Program](https://github.com/JoshuaBleechington/Vulnerability-management-program) · [Entra ID Login Monitoring](https://github.com/JoshuaBleechington/Entra-ID-LOGIN-Monitoring)*
