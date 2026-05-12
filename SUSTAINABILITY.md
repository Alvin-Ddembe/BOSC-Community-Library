# BOSC Community Library - Sustainability & Funding Strategy

**Document Version:** 1.0 | **Date:** May 12, 2026 | **Author:** Alvin Ddembe

---

## Executive Summary

This document outlines a comprehensive sustainability strategy for the BOSC Community Library, comparing two primary open source funding models—Red Hat-style service-based and Foundation-driven—and recommends a hybrid approach optimized for a public-sector wireless communication library.

---

## 1. Comparative Analysis of Sustainability Models

### 1.1 Red Hat Service-Based Model

| Aspect | Description |
|--------|-------------|
| Core Concept | Software remains open source (Apache 2.0); revenue from support, training, enterprise features |
| Revenue Sources | Paid support subscriptions, SLA contracts, certification, consulting |
| Staffing | Core maintainers on company payroll; community contributors |
| Governance | Corporate-led with community advisory board |
| Examples | Red Hat (Linux), MongoDB (pre-SSPL), GitLab (open core) |

**Advantages for BOSC:**
- Fast decision-making and execution
- Clear profit motive drives development
- Enterprise customers prefer single accountable vendor
- Easier to hire dedicated developers
- Can offer paid SLAs to government agencies

**Disadvantages for BOSC:**
- Risk of prioritizing paying customers over community
- Single point of failure (company bankruptcy)
- Tension between open source values and profit
- Government entities may distrust corporate-controlled infrastructure

### 1.2 Foundation-Driven Model

| Aspect | Description |
|--------|-------------|
| Core Concept | Independent non-profit foundation governs the project |
| Revenue Sources | Corporate sponsorships, grants, donations, membership fees |
| Staffing | Foundation employees + community volunteers |
| Governance | Multi-stakeholder board (corporate, academic, individual) |
| Examples | Apache Foundation, Linux Foundation, Python Software Foundation |

**Advantages for BOSC:**
- Perceived neutrality ideal for public sector
- Multiple revenue sources reduce risk
- Democratic governance aligns with open source values
- Eligible for government and philanthropic grants
- Can accept tax-deductible donations

**Disadvantages for BOSC:**
- Slower decision-making (consensus-based)
- Higher administrative overhead
- Difficulty competing on salary with corporate jobs
- Requires significant upfront funding to establish

### 1.3 Direct Comparison Matrix

| Criterion | Red Hat Model | Foundation Model |
|-----------|---------------|------------------|
| Decision Speed | Fast | Slow |
| Public Sector Trust | Medium | High |
| Revenue Predictability | High | Medium |
| Community Control | Low | High |
| Funding Diversity | Low | High |
| Grant Eligibility | Limited | Strong |
| SLA Offering | Yes | Complex |
| Single Point of Failure | Yes | No |

---

## 2. Recommended Hybrid Model for BOSC

**Recommendation:** Foundation-led with commercial services arm

### 2.1 Structure

The BOSC Foundation (Non-Profit) would own trademark, domain, and infrastructure while managing core code. A separate BOSC Services LLC (for-profit subsidiary) would offer paid support, SLAs, and consulting, with profits funding the Foundation.

### 2.2 Revenue Streams (5-Year Projection)

| Revenue Source | Year 1 | Year 2 | Year 3 | Year 4 | Year 5 |
|----------------|--------|--------|--------|--------|--------|
| Government Grants | $50k | $75k | $100k | $150k | $200k |
| Corporate Sponsorships | $20k | $40k | $80k | $120k | $180k |
| Support Subscriptions | $10k | $30k | $75k | $150k | $250k |
| Training & Certification | $5k | $15k | $30k | $60k | $100k |
| Individual Donations | $5k | $8k | $12k | $20k | $30k |
| **Total** | **$90k** | **$168k** | **$297k** | **$500k** | **$760k** |

### 2.3 Expense Allocation

| Category | Percentage | Purpose |
|----------|------------|---------|
| Core Development | 40% | Maintainers, feature development |
| Security & Compliance | 20% | Audits, vulnerability response |
| Community Management | 15% | Events, documentation, support |
| Infrastructure | 10% | CI/CD, hosting, tooling |
| Legal & Administration | 10% | License compliance, operations |
| Reserve Fund | 5% | Emergency sustainability fund |

---

## 3. Implementation Roadmap

**Phase 1 (Months 0-6): Bootstrap**
- Incorporate as fiscally-sponsored project (e.g., Software Conservancy)
- Secure anchor sponsor (local telecom or SDR manufacturer)
- Launch GitHub Sponsors and Open Collective

**Phase 2 (Months 6-12): Growth**
- Transition to independent 501(c)(6) foundation
- Hire first full-time maintainer
- Establish paid support program
- Apply for NGI or EU Open Source grants

**Phase 3 (Months 12-24): Scale**
- Launch BOSC Services LLC for enterprise support
- Develop certification program
- Establish annual BOSC Summit conference

---

## 4. Risk Mitigation

| Risk | Mitigation |
|------|------------|
| Single sponsor withdraws | Cap any sponsor at less than 30% of budget |
| Foundation governance gridlock | Clear escalation and voting procedures |
| Commercial arm cannibalizes community | Strict separation: core code stays open |
| Grant funding dries up | Diversify across grants, sponsors, services |

---

## 5. Comparison with Similar Projects

| Project | Model | Annual Budget | Staff Size |
|---------|-------|---------------|------------|
| GNU Radio | University + Sponsors | ~$500k | 2-3 FTE |
| OpenSSL | Foundation + Corporate | ~$1M | 4-5 FTE |
| WireGuard | Foundation + Donations | ~$200k | 1-2 FTE |
| **BOSC (Target)** | **Hybrid** | **$300-500k** | **3-5 FTE** |

---

## References

- "Sustainable Open Source" by Nadia Eghbal (Ford Foundation)
- TODO Group Sustainability Guide
- Open Collective Foundation Documentation

**End of Document**