# Question bank validation report

Bank v0.1: 80 questions in 8 batch files.

## Result: PASS

- Hard failures: 0
- Warnings: 0

## Progress toward v1.0 targets

Informational only; shortfalls are not failures.

| Domain | Questions | Easy | Medium | Hard |
|---|---|---|---|---|
| D1 Security and Risk Management | 10/160 | 3/48 | 4/72 | 3/40 |
| D2 Asset Security | 10/100 | 3/30 | 4/45 | 3/25 |
| D3 Security Architecture and Engineering | 10/130 | 3/39 | 4/59 | 3/32 |
| D4 Communication and Network Security | 10/130 | 3/39 | 4/59 | 3/32 |
| D5 Identity and Access Management | 10/130 | 3/39 | 4/59 | 3/32 |
| D6 Security Assessment and Testing | 10/120 | 3/36 | 4/54 | 3/30 |
| D7 Security Operations | 10/130 | 3/39 | 4/59 | 3/32 |
| D8 Software Development Security | 10/100 | 3/30 | 4/45 | 3/25 |
| **Total** | **80/1000** | | | |

### Next milestone: v0.2 (250 questions)

| Domain | Have | Share of milestone | Still needed |
|---|---|---|---|
| D1 | 10 | 40 | 30 |
| D2 | 10 | 25 | 15 |
| D3 | 10 | 33 | 23 |
| D4 | 10 | 33 | 23 |
| D5 | 10 | 32 | 22 |
| D6 | 10 | 30 | 20 |
| D7 | 10 | 32 | 22 |
| D8 | 10 | 25 | 15 |

## Question types

| Domain | Knowledge | Application | Managerial | Managerial share |
|---|---|---|---|---|
| D1 | 3 | 3 | 4 | 40% |
| D2 | 3 | 3 | 4 | 40% |
| D3 | 3 | 3 | 4 | 40% |
| D4 | 3 | 3 | 4 | 40% |
| D5 | 3 | 3 | 4 | 40% |
| D6 | 3 | 3 | 4 | 40% |
| D7 | 3 | 3 | 4 | 40% |
| D8 | 3 | 3 | 4 | 40% |

Overall managerial share: 40.0% (target at least 35%).

## Answer-letter distribution

Allowed range 20%-30% per letter (not enforced until the bank has 200 questions).

| A | B | C | D |
|---|---|---|---|
| 20 (25%) | 20 (25%) | 20 (25%) | 20 (25%) |

## Length bias

Correct answer is the longest option (ties count) in 12/80 questions (15%); limit 35%.
Correct answer is the shortest option in 17/80 (21%).

| Domain | Longest | Shortest |
|---|---|---|
| D1 | 0/10 (0%) | 2/10 (20%) |
| D2 | 3/10 (30%) | 2/10 (20%) |
| D3 | 3/10 (30%) | 0/10 (0%) |
| D4 | 2/10 (20%) | 4/10 (40%) |
| D5 | 1/10 (10%) | 0/10 (0%) |
| D6 | 0/10 (0%) | 3/10 (30%) |
| D7 | 1/10 (10%) | 3/10 (30%) |
| D8 | 2/10 (20%) | 3/10 (30%) |

## Most similar stems

Pairs above 0.85 fail validation. Top pairs at or above 0.50:

- none

## Subtopic coverage

- **D1** 10/16 covered. Professional ethics 1, Security concepts 1, Security governance and roles 1, Due care and due diligence 1, Policies, standards, procedures, and guidelines 1, Business continuity and BIA 1, Risk assessment and analysis 1, Risk response and control selection 1, Threat modeling 1, Supply chain risk management 1.
  - Not yet covered: Legal, regulatory, and contractual compliance, Privacy and transborder data flow, Intellectual property and licensing, Investigation types, Personnel security, Security awareness, education, and training
- **D2** 9/11 covered. Data classification 1, Data roles 2, Data lifecycle and collection 1, Data retention 1, Data remanence and destruction 1, Data states and protection 1, Scoping, tailoring, and baselines 1, DLP, DRM, and CASB 1, End-of-life assets 1.
  - Not yet covered: Asset inventory and ownership, Asset handling and labeling
- **D3** 10/15 covered. Secure design principles 1, Zero trust and secure access architecture 1, Security models 1, Virtualization, containers, and serverless 1, ICS, IoT, and embedded systems 1, Symmetric and asymmetric cryptography 1, Hashing, signatures, and integrity 1, PKI and key management 1, Cryptanalytic attacks 1, Environmental and physical controls 1.
  - Not yet covered: Evaluation and certification, Hardware security capabilities, Cloud and distributed systems, Database and web architecture vulnerabilities, Site and facility design
- **D4** 10/14 covered. OSI and TCP/IP models 1, IP networking and addressing 1, Secure protocols 1, Converged and multilayer protocols 1, Network segmentation 1, Wireless networks 1, SDN, SD-WAN, and virtual networks 1, Remote access and VPN 1, Voice, video, and collaboration 1, Network attacks 1.
  - Not yet covered: Cellular and satellite, Network devices and NAC, Transmission media, CDN and edge networks
- **D5** 10/13 covered. Identification and authentication 1, Multi-factor and passwordless authentication 1, Session management 1, Federation and SSO 1, Authorization models 1, Provisioning lifecycle 1, Access reviews 1, Privileged and service accounts 1, Authentication protocols 1, Just-in-time access 1.
  - Not yet covered: Physical and logical access control, Identity proofing and registration, Access policy enforcement
- **D6** 10/13 covered. Assessment strategy 1, Vulnerability assessment 1, Penetration testing 1, Log review 1, Synthetic transactions and RUM 1, Code review and testing 1, Security process data and metrics 1, Backup and recovery verification 1, Reporting and remediation 1, Audits and SOC reports 1.
  - Not yet covered: Misuse cases and coverage analysis, Interface testing, Breach and attack simulation
- **D7** 10/16 covered. Investigations and evidence 1, Digital forensics 1, Logging and monitoring 1, Incident management 1, Detective and preventive controls 1, Change management 1, Backup and recovery strategies 1, Disaster recovery 1, DR plan testing 1, Personnel safety 1.
  - Not yet covered: SIEM, SOAR, and threat intelligence, Configuration management, Foundational security operations, Resource and media protection, Patch and vulnerability management, Physical security operations
- **D8** 10/12 covered. SDLC integration 1, Development methodologies 1, Software maturity models 1, Development ecosystem security 1, CI/CD and pipeline security 1, Software composition and supply chain 1, Acquired software security 1, Secure coding practices 1, Source code weaknesses 1, API security 1.
  - Not yet covered: Application security testing, Change and release management
