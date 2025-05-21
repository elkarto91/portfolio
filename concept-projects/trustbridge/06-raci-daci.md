# 🧠 RACI & DACI Matrices – TrustBridge

Clear responsibility assignment is critical in a zero-trust product. This matrix outlines cross-functional roles in planning, building, launching, and governing TrustBridge.

---

## 📊 RACI Matrix

| Activity | Product Manager | CISO | Security Architect | Data Engineer | Infra Ops | Legal & Compliance | QA |
|----------|------------------|------|---------------------|----------------|------------|----------------------|----|
| Requirements Gathering | R | A | C | C | I | C | I |
| CLI + Webhook Design | A | I | R | C | C | I | I |
| Policy Enforcement Model | C | A | R | I | I | C | I |
| Blockchain Integration | R | I | A | C | C | I | I |
| Legal Data Retention Review | I | C | I | I | I | A | I |
| Test Plan Creation | C | I | I | I | I | I | A |
| Pilot Program Planning | R | C | C | C | C | A | C |
| Audit Preparation & Receipt Format | A | C | C | I | I | R | I |

> R = Responsible, A = Accountable, C = Consulted, I = Informed

---

## 👤 DACI Matrix

| Decision Area | Driver | Approver | Contributors | Informed |
|---------------|--------|----------|--------------|----------|
| MVP Scope & Features | Product Manager | CTO / CISO | Security Arch, Legal, Data Eng | QA, Infra |
| Ledger Stack Selection | Security Architect | CTO | Product, Data Eng | Legal |
| Partner API Governance | Product + Legal | CEO | Security, Infra | Compliance |
| Consent & Privacy Policy | Legal Lead | CEO | Product, Security | QA |
| Audit Submission Format | Product + Legal | Compliance Lead | Security, Data Eng | Infra, QA |

---

## 💬 Notes

- TrustBridge involves deeply cross-functional accountability — especially between **Security** and **Legal** teams.
- Product and Security jointly drive roadmap and MVP scope, but all launches must pass **legal sign-off** for data privacy and retention models.
- Future DACI will include external partners (marketplaces, auditors, etc.) once multi-org ledger mode is piloted.

> In trust infrastructure, design and compliance must co-own the product. Speed without sign-off is risk.
