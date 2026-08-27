# NIST CSF 2.0 Risk Assessment — Home Network

## Overview
This project applies the NIST Cybersecurity Framework (CSF) 2.0 to a real-world 
environment: my own home network. I conducted a full gap analysis, built a scored 
risk register, and produced a prioritized remediation roadmap — the same 
methodology used in professional GRC and risk analyst work.

## Why I Built This
I wanted hands-on experience applying a governance framework end-to-end, not just 
studying it. Using my own network kept the findings honest and specific instead of 
theoretical.

## Methodology
1. Defined the scope — a household network on a basic ISP router, shared by 
   multiple family members, occasionally used for sensitive tasks.
2. Assessed current-state controls against all 6 CSF functions: Govern, Identify, 
   Protect, Detect, Respond, Recover.
3. Scored each identified gap as a risk (Likelihood × Impact, 1–5 scale) in a 
   risk register.
4. Built a phased remediation roadmap (Quick Wins / Short-Term / Long-Term).

## Key Findings
- **Highest risk:** router admin credentials were still factory default — a 
  common, easily searchable vulnerability.
- **Second highest:** inconsistent password practices across household members.
- Both were also the **lowest-effort fixes**, so they were prioritized first — 
  the same risk-reduction-per-effort logic used in professional risk 
  prioritization.
- Strengths identified: automatic firmware updates and existing cloud backups.

## Files
- `Home_Network_Gap_Analysis_Report.docx` — full report (executive summary, 
  findings by function, roadmap)
- `Home_Network_Risk_Register.xlsx` — scored risk register with remediation 
  tracking

## Skills Demonstrated
NIST CSF 2.0 · Risk Assessment & Scoring · Gap Analysis · Control Mapping · 
Remediation Planning · Executive Reporting
