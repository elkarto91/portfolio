# 🧩 MoSCoW Prioritization – TrustBridge MVP

This matrix outlines which features are **Must Have**, **Should Have**, **Could Have**, and **Won’t Have** for the first release of TrustBridge — based on impact, feasibility, and user value.

---

## ✅ Must Have (MVP-critical)

| Feature | Reason |
|--------|--------|
| CLI-based Data Transfer Tracker | Entry point for developer workflows; non-intrusive |
| SHA256 Hash Generator | Ensures fingerprinting of every data object |
| Blockchain Write Module | Core to the product's value – tamper-proof audit trail |
| Policy-Driven Access Event Capture | Enforces Zero Trust principles |
| JSON Receipt Export | Needed for audit and forensic use cases |

---

## 🟡 Should Have (Adds value but not critical for pilot)

| Feature | Reason |
|--------|--------|
| API Webhook Integration | Enables automated system-to-system logging |
| Dashboard UI | Great for compliance and execs; not needed by CLI users |
| Role-Based Access Controls (RBAC) | Helpful for large orgs; CLI can be tied to SSO for now |
| Retry Mechanism for Ledger Failures | Improves reliability; manual fallback can suffice initially |

---

## 🔵 Could Have (Nice to include in roadmap)

| Feature | Reason |
|--------|--------|
| Visual Lineage Graph | Powerful storytelling and trace visualization |
| Transfer Alerting System | Adds real-time defense signals |
| Plugin for GitHub Actions / GitLab CI | Makes adoption easier for platform teams |
| Ledger Sync Analytics | Helps with performance tuning and optimization |

---

## ❌ Won’t Have (Deprioritized for MVP)

| Feature | Reason |
|--------|--------|
| Tokenized SLA Smart Contracts | Adds complexity, legal risk, and is futuristic in nature |
| Cross-ledger Federation | Required for consortium use, not needed for early pilots |
| Data Redaction & Anonymization | Security must focus on transparency, not suppression |
| Public Blockchain Anchoring | Adds cost and exposure; private ledger sufficient for now |

---

> TrustBridge focuses on clarity, compliance, and chain-of-custody first. Complexity can wait.
