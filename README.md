# SAR-Academy

AI-Based Training Platform for Search & Rescue Operations
Public Technical Summary Report (v1.0)
Prepared by: Mohammad Hareth Hasan Al-Jomaa, Co-Founder & Technical Lead
Date Created: 09.04.2025
Last Updated: 08.07.2025

This report is a public technical summary. All sensitive data, source code, and internal documentation are
under binding NDA and contributor agreement. Unauthorized disclosure is prohibited

Executive Summary
SAR Academy is a pre-MVP; interdisciplinary R&D initiative focused on the development of an AI-enhanced
training platform for search-and-rescue (SAR) operations. Initiated within the context of ING303 at the Western
Norway University of Applied Sciences, the project has evolved through technical, legal, academic, institutional,
and market validation phases. It is currently in a paused state (as of April 2025) with plans to resume development in
Q4 2026.

The core system utilizes convolutional neural networks (CNNs) to analyze and classify thermal and GPS-based
input data in real time, assisting SAR handlers in identifying high-priority search zones. The platform is supported
through academic and institutional relationships including HVL, Innovation Norway, and StartupLab Bergen.

Project Genesis and Institutional Alignment

The concept originated during the Autumn 2024 semester as part of ING303: Systems Thinking and Innovation for
Engineers. Following a successful concept pitch to representatives from Innovation Norway, the project received
interest and recommendations for further development. Subsequent internal validation led to engagement with HVL
faculty, culminating in a formal introduction to StartupLab Bergen.
Regular strategic meetings were held with StartupLab leadership, and the project delivered weekly status updates.

Legal and Administrative Structure

SAR Academy is governed by a 10-page legally binding internal contributor agreement authored by the technical lead.
The contract includes:
• IP allocation and retention rights
• Confidentiality and non-disclosure provisions
• Contribution scope definitions
• Arbitration and dissolution clauses
The structure ensures long-term enforceability of team responsibilities, IP protection, and decision-making protocols.
No source code, training data, or internal communication artifacts may be disclosed without mutual written consent.


Technical Architecture

Data Ingestion
GPS log parser with time-aligned trajectory mapping for post-training analysis
Thermal imaging input handler (format-agnostic, optimized for recorded training footage)

Signal Processing
CNN-based classification model developed in TensorFlow to interpret sensor patterns
Preprocessing pipeline with bounding-box isolation and multi-frame motion tracking
Synthetic training dataset simulating K9 movement profiles and terrain-induced noise

User Interface
Figma-based UI tailored for SAR training environments with intuitive field feedback
Designed for deployment on mobile and rugged tablet devices used during exercises
Displays detection confidence, spatial overlays, and feedback zones to support training efficiency

Development Timeline and Current Status

Phase Timeline Status
Course Project (ING303) Aug–Dec 2024 Completed
Legal Structuring Dec 2024 Completed
UI/UX Architecture Dec-Apr 2025 Paused
Backend Prototyping Dec-Apr 2025 Paused
Project Paused Apr 2025 Paused
Targeted Resumption Oct 2026 Planned
Governance and Team Operations
SAR Academy operated under an internal Agile-like sprint structure between December 2024 and April 2025.
Meetings were held up to twice daily, focusing on code reviews, system integration discussions, and deliverable
tracking.
Team roles were defined explicitly within the legal contract. Delegation and accountability were maintained through
internal logging and Git-based revision management (private repository). No public code has been released to date.
3
This report is a public technical summary. All sensitive data, source code, and internal documentation are
under binding NDA and contributor agreement. Unauthorized disclosure is prohibited
Market Alignment and Stakeholder Mapping
SAR Academy conducted extensive market analysis including:
• Budget forecasting and early-stage financial modeling
• Business model design (B2G and institutional licensing)
• Cost-efficiency projections for SAR deployment scenarios
A core team member with operational SAR experience conducted over 50 structured interviews with strategic leads
across public and private SAR institutions.
Meetings were also held with the Norwegian Armed Forces (Forsvaret) and Police Department stakeholders, both of
whom expressed interest in the system’s future applications. Forsvaret requested ongoing updates and indicated
willingness to stay informed as development progresses
These findings validated the demand for AI-enhanced SAR training tools, highlighted inefficiencies in current
preparatory workflows, and reinforced the potential for institutional adoption at national scale.
Public Commitments and Disclosure Policy
All proprietary components remain under legal lock. However, SAR Academy commits to the following public
milestones:
• Q1 2026: Release of design whitepaper (non-sensitive version)
• Q2 2026: GitHub release of frontend interface skeleton
• Q4 2026: Internal MVP pilot using synthetic datasets
• Q1 2027: Initial outreach to SAR institutions for field testing
Contact and Collaboration
For academic, research, or incubator-related inquiries:
Contact: harethaljomaa@saracademy.no / harethaljomaa@saracademy.net
General inquiries: post@saracademy.no / post@saracademy.net
Registered domains: saracademy.no / saracademy.net
For legal, institutional, or strategic collaboration:
Please use the official contact channels above. A formal inquiry form will be published alongside the Q1 2026
whitepaper.
4
This report is a public technical summary. All sensitive data, source code, and internal documentation are
under binding NDA and contributor agreement. Unauthorized disclosure is prohibited

