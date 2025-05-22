# 🚗 Customer Testimonial – ADX-Pilot Project (Tier-1 Automotive Supplier)

## Challenges and Objectives

We were building a new generation of embedded software for ADAS and powertrain systems using modern C++.  
Our goal was to ensure long-term maintainability, strict compliance with MISRA and ISO 26262, and prevent architectural drift across releases.  
As a safety-critical project, we needed an analysis tool that could evolve with our codebase and provide real insight — not just a list of warnings.

---

## What made CppDepend stand out over other tools?

Unlike basic linters or security-focused checkers, CppDepend gave us native integration with Visual Studio and CMake, but also offered unmatched flexibility via CQLinq.  
The rule engine and interactive visualizations made it easy for both developers and architects to use — no long onboarding required.

---

## Most Appealing Feature

The ability to define architectural layering and dependency rules using CQLinq was a game changer.  
We could model our architecture visually and enforce it over time.  
Also, the depth of MISRA C++:2023 support, combined with custom rules, gave us confidence during ISO 26262 audits.

---

## How the Team Uses It

CppDepend is now fully integrated into our Jenkins CI/CD pipeline.  
It runs nightly and on every merge request.  
The XML output is parsed into custom dashboards and shared with leads.  
We primarily monitor dependency violations, MISRA rules, and technical debt evolution.

---

## Company Profile

- **Company:** [Confidential – Tier-1 Automotive Supplier]  
- Develops advanced embedded software for engine management, ADAS, and electrified powertrains  
- Supplies OEMs across Europe and Asia  
- Engineering offices across 3 continents  
- Uses MISRA, AUTOSAR, and ISO 26262 standards in daily development

---

## Goals & Tasks

- Maintain modularity and enforce defined software architecture  
- Detect and block violations of MISRA/AUTOSAR rules before they reach production  
- Track long-term technical debt and trend evolution  
- Automate compliance checks for audits

---

## Pain Points Before CppDepend

- Architecture drift happened unnoticed across releases  
- Manual rule checks were inconsistent and unscalable  
- Code complexity increased without clear ownership  
- Audit prep required days of effort

---

## 📊 Measurable Impact

| Metric                  | Before   | After 12 Weeks |
|-------------------------|----------|----------------|
| MISRA Violations        | 1,500    | 160            |
| Architecture Breaches   | 98       | 15             |
| Audit Prep Time         | 4 days   | < 4 hours      |
| Code Review Time        | 2.5 days | 1 day          |

---

## Most Impressive Aspects

The expressiveness of the CQLinq language.  
The ability to write domain-specific rules with real-time feedback.  
Built-in trend charts and dashboards.  
Friendly and fast technical support.

---

## Final Thoughts

CppDepend has become a strategic part of our development pipeline.  
It helps us go beyond just “clean code” and focus on long-term architectural health — which is critical for a safety-critical, high-complexity product lifecycle.

