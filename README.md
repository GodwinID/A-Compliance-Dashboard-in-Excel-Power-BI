# 📊 NovaStar Tech — GRC Compliance Dashboard

> A comprehensive, multi-tab Excel compliance dashboard consolidating risk register data, control maturity scores, SOC 2 TSC coverage, open actions, and trend analytics — all with color-coded status, conditional formatting, and embedded charts.

---

## 📋 Overview

This dashboard brings together all GRC programme data from the NovaStar Tech compliance projects into a single, executive-ready Excel workbook. It is designed to give the CISO and management team a real-time view of the company's compliance posture, open risk actions, and progress toward ISO 27001 and SOC 2 certification.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| [novastar_compliance_dashboard.xlsx](https://github.com/user-attachments/files/26393909/novastar_compliance_dashboard.xlsx) | Full 6-tab compliance dashboard with charts, KPIs, and conditional formatting |
| Full 6-tab compliance dashboard with charts, KPIs, and conditional formatting | <img width="1600" height="1140" alt="compliance_dashboard" src="https://github.com/user-attachments/assets/719fc98e-9168-40df-8fae-e7a172e00770" />

---

## 📊 Workbook — Tab Breakdown

### 🔵 Tab 1: Executive Dashboard
The main landing page — designed for CISO and executive reporting.

**8 KPI Cards:**
| KPI | Value | Status |
|-----|-------|--------|
| Overall Risk Level | MEDIUM | ↓ Improving |
| Controls Active | 48 / 60 | 80% implemented |
| High Risks | 7 | ↓ 5 residual = 0 |
| Avg Maturity | 3.1 / 5 | Target: 4.0 |
| SOC 2 Readiness | 90% | Type I ready |
| Open Actions | 14 | 6 overdue ⚠ |
| Compliance % | 68% | Target: 90% |
| Next Audit | Q1 2026 | ISO 27001 Stage 1 |

**6 Embedded Charts:**
1. 🥧 **Risk Distribution Pie** — High / Medium / Low breakdown
2. 🕸️ **Control Maturity Radar** — Current vs Target across 10 domains
3. 📊 **SOC 2 TSC Stacked Bar** — Implemented / Partial / Planned per CC1–CC9
4. 📈 **Risk Trend Line** — Open High + Medium risks over FY2025
5. 📉 **Compliance % Line** — Coverage trend: Jan 2025 → Oct 2025 (actual + projected)
6. 📊 **Maturity Bar Chart** — Current vs Target by domain

---

### 🔴 Tab 2: Risk Register
15 risks from the CloudNova risk assessment, imported and formatted:
- Risk ID, category, description, threat source
- Likelihood × Impact scoring with color-coded ratings 🔴🟡🟢
- Status: Implemented / In Progress / Planned
- Mitigation summary, owner, residual risk score
- Review dates

---

### 🔵 Tab 3: Control Matrix
20 ISO 27001 / NIST SP 800-53 controls:
- Dual framework mapping (ISO Annex A + NIST families)
- Status color-coded: Implemented / In Progress / Partial / Planned
- Maturity scores 1–5 with color coding
- Gap identification and remediation actions

---

### 🟠 Tab 4: Open Actions Tracker
14 open compliance actions with:
- Priority (CRITICAL / HIGH / MEDIUM / LOW) color-coded
- Days remaining — auto color: 🔴 Overdue / 🟡 Due ≤14 days / 🟢 On track
- Status (In Progress / Not Started / Overdue / Completed)
- % Complete with data bar formatting
- 6 overdue actions highlighted in red

---

### 🟢 Tab 5: SOC 2 Mapping
20 AWS controls mapped to SOC 2 TSC (CC1–CC9):
- AWS service implementing each control
- Implementation summary
- Evidence artifact filenames (SOC2_Artifacts/ folder)
- Gap identification and remediation

---

### 🟣 Tab 6: Compliance Trend
Monthly trend data (Jan–Oct 2025, actual + projected):
- Open high/medium risks per month
- Average control maturity per month
- % compliance coverage
- Controls implemented
- Embedded trend chart with actual vs projected

---

## 📈 Compliance Progress Summary

```
           Jan 2025    Jun 2025    Oct 2025 (target)
─────────────────────────────────────────────────────
Open High  12          7           1
Open Medium 8          5           2
Avg Maturity 1.8       3.1         4.1
% Compliant  42%       68%         90%
Controls     24        40          56
─────────────────────────────────────────────────────
```

---

## 🎨 Color Coding Legend

| Color | Meaning |
|-------|---------|
| 🔴 Red | High risk / Critical / Overdue / Not implemented |
| 🟡 Amber | Medium risk / In progress / Due soon / Partial |
| 🟢 Green | Low risk / Implemented / On track / Complete |
| 🔵 Blue | Informational / Projected / Data fields |
| 🟣 Purple | Planned items / Future milestones |

**Maturity Scale:**
| Score | Color | Meaning |
|-------|-------|---------|
| 1 | 🔴 Red | Not implemented |
| 2 | 🟠 Orange | Partially implemented, undocumented |
| 3 | 🟡 Amber | Implemented, not tested |
| 4 | 🔵 Blue | Implemented and tested |
| 5 | 🟢 Green | Optimized / continuously monitored |

---

## 🗺️ Roadmap to 90% Compliance

```
Jun 2025  →  68% — Baseline established; IR Plan + tabletop complete
Jul 2025  →  72% — PAM deployed; DMARC p=reject; phishing training
Aug 2025  →  78% — BCP/DRP; S3 DLP; UEBA
Sep 2025  →  84% — Internal audit; VRM programme launched
Oct 2025  →  90% — ISO 27001 Stage 1 readiness ← TARGET
Q1 2026   →       ISO 27001 Stage 1 audit
Q3 2026   →       SOC 2 Type II observation period begins
Q1 2027   →       SOC 2 Type II report issued
```

---

## 🧰 How to Use This Dashboard

1. **Open** [novastar_compliance_dashboard.xlsx](https://github.com/user-attachments/files/26393967/novastar_compliance_dashboard.xlsx) in Excel (works best in Excel 2016+)
2. **Start** on the Executive Dashboard tab for the overview
3. **Update** the Risk Register, Control Matrix, and SOC 2 tabs monthly as controls are implemented
4. **Update** the Open Actions tab weekly — mark completed actions and add new ones
5. **Add** monthly data to the Compliance Trend tab to extend the charts
6. **Export** the Executive Dashboard tab as a PDF for board/management reporting

---

## 📚 References

All data is consolidated from the NovaStar Tech GRC programme projects:
- CloudNova Risk Register (15 risks, risk scoring methodology)
- ISO 27001 / NIST Control Matrix (20 controls)
- SOC 2 AWS Controls Assessment (20 TSC-mapped controls)
- IR Plan & Tabletop Simulation (incident metrics)
- Vendor Assessment (Google Workspace, 48/50 score)

---

## ⚠️ Disclaimer

This is an educational GRC lab project using fictional company data. For real-world compliance programme management, consult a qualified GRC professional.

---

*Built by Godwin Iduye  |  © 2025*

