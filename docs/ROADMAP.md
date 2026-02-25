# 🗺️ ODefender Community — Roadmap

> Living document. Updated as priorities evolve.

---

## 🟢 Released

### MDE ServerTags — `v2.2.0` *(Feb 2025)*
- ✅ Automated server classification by Azure subscription
- ✅ Lifecycle tags: Inactive (7d/40d), Ephemeral, Duplicate
- ✅ 4-level subscription auto-discovery
- ✅ Interactive Setup Wizard
- ✅ End-to-End validation (10 stages)
- ✅ Azure Policy integration
- ✅ Email notifications
- ✅ Windows Scheduled Task automation

---

## 🟡 In Progress

### MDE ServerTags — AI Agents *(Q3 2025)*
**Goal**: Autonomous agents that act on classification results.

| Agent | Function | Status |
|-------|----------|--------|
| 🤖 Cleanup Agent | Auto-offboard `DUPLICADA_EXCLUIR` machines after validation | 🔄 Design |
| 🤖 Lifecycle Agent | Investigate `INATIVO_40D`, escalate or offboard | 🔄 Design |
| 🤖 Fleet Agent | Manage ephemeral server lifecycle, auto-tag VMSS | 📋 Planned |
| 🤖 Group Agent | Auto-create/update MDE Device Groups via Graph API | 📋 Planned |

**Architecture**: Built on top of current classification engine, using AI to make decisions that currently require human judgment.

---

## 🔵 Planned

### Sentinel Analytics Pack *(Q3 2025)*
- KQL query library with MITRE ATT&CK mapping
- Auto-generated executive reports (HTML)
- PCI-DSS and NIST compliance correlation
- Threat hunting query packs

### Defender Third-Party Bridge *(Q4 2025)*
- Integration patterns for multi-vendor environments
- CrowdStrike ↔ Sentinel connector templates
- SentinelOne ↔ MDE alert correlation
- Palo Alto ↔ Sentinel data ingestion
- Unified dashboard templates

### Security Posture Baseline *(Q4 2025)*
- Automated CIS Benchmark assessment
- Remediation playbooks (GPO/Intune)
- Compliance drift detection
- Before/after posture scoring

### Endpoint Hardening Pack *(2026)*
- GPO and Intune templates
- Attack Surface Reduction (ASR) rule packs
- Validation scripts with rollback support
- Hardening score calculator

---

## 💭 Exploring

*Ideas we're evaluating. No commitment yet.*

- 🔍 MDE Threat Hunting automation library
- 📊 Security Operations KPI dashboard
- 🎓 Security automation learning path / lab
- 🔗 ServiceNow ↔ Defender integration templates
- 📱 Teams bot for security alerts and approvals

---

## How to Influence the Roadmap

1. ⭐ **Star** projects you use — it helps us prioritize
2. 💡 **Open an Issue** with `[Feature Request]` for new ideas
3. 📢 **Share** what pain points you face in your security operations
4. 🔧 **Contribute** — PRs that align with the roadmap get fast reviews

---

*Last updated: February 2025*
