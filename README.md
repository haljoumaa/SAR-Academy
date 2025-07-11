# SAR Academy

**AI-Based Training Platform for Search & Rescue Operations**  
**Public Technical Summary Report (v1.0)**  
**Prepared by:** Mohammad Hareth Hasan Al-Jomaa, Co-Founder & Technical Lead  
**Date Created:** 09.04.2025  
**Last Updated:** 08.07.2025  

> **Disclosure**: This project is fully independent. No formal financial or institutional support has been granted by any of the entities mentioned. See [Disclosure](#disclosure) section below.
> 
> _This report is a public technical summary. All sensitive data, source code, and internal documentation are under binding NDA and contributor agreement. Unauthorized disclosure is prohibited._
---

## Executive Summary

SAR Academy is a pre-MVP, interdisciplinary R&D initiative focused on developing an AI-enhanced training platform for search-and-rescue (SAR) operations. Initiated within the context of ING303 at the Western Norway University of Applied Sciences, the project progressed through technical, legal, academic, institutional, and market validation phases. Development is currently paused (as of April 2025), with plans to resume in Q4 2026.

The core system leverages convolutional neural networks (CNNs) to analyze thermal and GPS-based input data, supporting SAR dog handlers in optimizing field training.

---

## Project Genesis and Institutional Alignment

The project began in Autumn 2024 as part of ING303: _Systems Thinking and Innovation for Engineers_ at the Western Norway University of Applied Sciences (HVL). During a classroom pitch, an advisor from Innovation Norway gave positive feedback and expressed initial interest. This helped initiate follow-up discussions with HVL faculty and staff, who supported the team in taking the project further.

The team was later introduced to StartupLab Bergen through HVL, establishing direct contact with their leadership and gaining access to mentorship and advisory resources.

From the beginning, the team followed structured project management routines, including regular meetings and detailed progress tracking. During the pre-MVP phase, regular status reports were shared with relevant connections, covering technical updates, challenges, and key decisions. Ensuring transparency and clear communication throughout development.

---

## Legal and Administrative Structure

The project is governed by a 10-page contributor agreement drafted by the technical lead. Key clauses include:

- IP allocation and retention rights  
- Confidentiality and NDA provisions  
- Scope of contribution definitions  
- Arbitration and dissolution protocols  

No source code, datasets, or internal documents may be disclosed without written mutual consent.

---

## Technical Architecture

### Data Ingestion
- GPS log parser with time-aligned trajectory mapping for post-training analysis  
- Thermal imaging input handler (format-agnostic; optimized for recorded sessions)
- Integrated session logging for both real-time and post-training phases, with checkpointing to support model evaluation and iterative refinement

### Signal Processing
- TensorFlow-based CNN model to classify sensor patterns  
- Preprocessing pipeline: bounding-box isolation + multi-frame motion tracking  
- Synthetic dataset generation simulating dog motion and environmental noise

### User Interface
- Figma-based UI, optimized for SAR field training environments  
- Deployment target: mobile and rugged tablet platforms  
- Displays: confidence overlays, spatial maps, and feedback zones for handler review

---

## Development Timeline and Status

| Phase                      | Timeline         | Status     |
|---------------------------|------------------|------------|
| Course Project (ING303)   | Aug–Dec 2024     |  Completed |
| Legal Structuring         | Dec 2024         |  Completed |
| UI/UX Architecture        | Dec–Apr 2025     |  Paused    |
| Backend Prototyping       | Dec–Apr 2025     |  Paused    |
| Targeted Resumption       | Oct 2026         |  Planned   |

---

## Governance and Team Operations

SAR Academy operated with an Agile-style development cycle between Dec 2024 and Apr 2025.  
Meetings were held up to twice daily for code reviews and integration discussions. Roles were contractually defined and tracked via Git-based versioning in a private repository. No public code has been released as of this report.

---

## Market Alignment and Stakeholder Mapping

The team conducted comprehensive market validation:

- Budget forecasting and financial modeling  
- Business model exploration (B2G and institutional licensing)  
- Cost-efficiency analysis for SAR training deployment  

A SAR practitioner on the team conducted 50+ interviews with public and private sector trainers, operators, and leaders.  
Meetings with the Norwegian Armed Forces and Police stakeholders confirmed institutional interest and a willingness to stay informed on future iterations.

> These findings confirmed strong demand for AI-supported SAR training, revealed inefficiencies in existing training workflows, and underscored the platform’s potential for national-scale institutional deployment.

---

## Public Commitments and Disclosure Policy

SAR Academy commits to the following public deliverables:

- **Q1 2026**: Release of design whitepaper (non-sensitive version)  
- **Q2 2026**: GitHub publication of frontend interface skeleton  
- **Q4 2026**: Internal MVP test using synthetic datasets  
- **Q1 2027**: Outreach to SAR institutions for pilot collaboration

---

## Contact and Collaboration

**Academic, research, or incubator-related inquiries:**  
📧 harethaljomaa@saracademy.no / harethaljomaa@saracademy.net  

**General inquiries:**  
📧 post@saracademy.no / post@saracademy.net  

**Registered domains:**  
🌐 [saracademy.no](http://saracademy.no) / [saracademy.net](http://saracademy.net)

**For legal, institutional, or strategic collaboration:**  
Please use the contact channels above. A formal inquiry form will be released with the Q1 2026 whitepaper.

---

## Disclosure

SAR Academy has **not received formal funding, institutional grants, or financial sponsorship** from any of the organizations mentioned. All engagements with Innovation Norway, HVL, Norwegian Armed Forces, Police Departments and StartupLab Bergen have been informal, advisory, or academic in nature. The project remains fully independent and pre-commercial.

---

> _This report is a public technical summary. All sensitive data, source code, and internal documentation are under binding NDA and contributor agreement. Unauthorized disclosure is prohibited._
