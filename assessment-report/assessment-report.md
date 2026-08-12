# NIS2 Gap Assessment Report
**Author:** Jaden Mascarenhas  
**Role:** Cybersecurity Analyst (SOC/IR · GRC · OT/ICS)  
**Date:** 12 August 2026  

---

## 1. Executive Summary
This report presents a NIS2 Directive Gap Assessment for a simulated organisation operating essential digital services. The assessment evaluates the organisation’s cybersecurity posture against NIS2 requirements, identifying gaps in governance, risk management, operational security, incident response, and supply chain security.

Key gaps identified include:
- Lack of formal cybersecurity governance and accountability structures.
- Insufficient risk management processes and documentation.
- Missing technical and organisational controls required under NIS2 Article 21.
- Limited incident detection and response capabilities.
- No supplier risk management or contractual security requirements.
- Absence of business continuity and crisis management planning.

---

## 2. Scope of Assessment
### In-Scope
- Governance & Accountability  
- Risk Management  
- Technical Controls  
- Incident Response  
- Business Continuity  
- Supply Chain Security  

### Out-of-Scope
- Physical security  
- HR policies  
- Financial audit controls  

---

## 3. Methodology
- Review of organisational policies  
- Technical inspection of systems  
- Mapping controls to NIS2 Articles  
- Gap identification and prioritisation  
- Risk scoring (Likelihood × Impact)  

Frameworks referenced:
- NIS2 Directive  
- ISO 27001  
- NIST CSF  
- ENISA Guidelines  

---

## 4. Architecture Overview

```mermaid
flowchart TD

    A[Organisation] --> B[Governance & Accountability]
    A --> C[Risk Management]
    A --> D[Technical Controls]
    A --> E[Incident Response]
    A --> F[Supply Chain Security]

    D --> G[Logging & Monitoring]
    D --> H[Vulnerability Management]
    D --> I[Access Control]

    E --> J[Detection]
    E --> K[Response]
    E --> L[Reporting]

    F --> M[Vendor Assessment]
    F --> N[Contractual Requirements]
