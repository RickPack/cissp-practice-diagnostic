# Question bank validation report

Bank v0.3: 500 questions in 24 batch files.

## Result: PASS

- Hard failures: 0
- Warnings: 0

## Progress toward v1.0 targets

Informational only; shortfalls are not failures.

| Domain | Questions | Easy | Medium | Hard |
|---|---|---|---|---|
| D1 Security and Risk Management | 80/160 | 24/48 | 36/72 | 20/40 |
| D2 Asset Security | 50/100 | 15/30 | 22/45 | 13/25 |
| D3 Security Architecture and Engineering | 65/130 | 20/39 | 28/59 | 17/32 |
| D4 Communication and Network Security | 65/130 | 20/39 | 28/59 | 17/32 |
| D5 Identity and Access Management | 65/130 | 20/39 | 29/59 | 16/32 |
| D6 Security Assessment and Testing | 60/120 | 18/36 | 27/54 | 15/30 |
| D7 Security Operations | 65/130 | 20/39 | 29/59 | 16/32 |
| D8 Software Development Security | 50/100 | 15/30 | 22/45 | 13/25 |
| **Total** | **500/1000** | | | |

### Next milestone: v0.4 (750 questions)

| Domain | Have | Share of milestone | Still needed |
|---|---|---|---|
| D1 | 80 | 120 | 40 |
| D2 | 50 | 75 | 25 |
| D3 | 65 | 98 | 33 |
| D4 | 65 | 98 | 33 |
| D5 | 65 | 97 | 32 |
| D6 | 60 | 90 | 30 |
| D7 | 65 | 97 | 32 |
| D8 | 50 | 75 | 25 |

## Question types

| Domain | Knowledge | Application | Managerial | Managerial share |
|---|---|---|---|---|
| D1 | 26 | 22 | 32 | 40% |
| D2 | 14 | 15 | 21 | 42% |
| D3 | 18 | 22 | 25 | 38% |
| D4 | 18 | 22 | 25 | 38% |
| D5 | 19 | 20 | 26 | 40% |
| D6 | 18 | 19 | 23 | 38% |
| D7 | 19 | 19 | 27 | 42% |
| D8 | 14 | 15 | 21 | 42% |

Overall managerial share: 40.0% (target at least 35%).

## Answer-letter distribution

Allowed range 20%-30% per letter (checked).

| A | B | C | D |
|---|---|---|---|
| 125 (25%) | 126 (25%) | 124 (25%) | 125 (25%) |

## Length bias

Correct answer is the longest option (ties count) in 117/500 questions (23%); warning above 35%, and below 15% once the bank has 200 questions.
Correct answer is the shortest option in 124/500 (25%).

| Domain | Longest | Shortest |
|---|---|---|
| D1 | 12/80 (15%) | 16/80 (20%) |
| D2 | 9/50 (18%) | 8/50 (16%) |
| D3 | 22/65 (34%) | 11/65 (17%) |
| D4 | 17/65 (26%) | 14/65 (22%) |
| D5 | 14/65 (22%) | 4/65 (6%) |
| D6 | 15/60 (25%) | 23/60 (38%) |
| D7 | 16/65 (25%) | 26/65 (40%) |
| D8 | 12/50 (24%) | 22/50 (44%) |

## Most similar stems

Pairs above 0.85 fail validation. Top pairs at or above 0.50:

- D1-0010 / D1-0039: 0.69
- D4-0005 / D4-0044: 0.69
- D6-0006 / D6-0036: 0.68
- D3-0045 / D3-0059: 0.62
- D2-0035 / D7-0047: 0.51
- D4-0030 / D4-0060: 0.51

## Subtopic coverage

- **D1** 16/16 covered. Professional ethics 5, Security concepts 5, Security governance and roles 5, Due care and due diligence 3, Legal, regulatory, and contractual compliance 6, Privacy and transborder data flow 6, Intellectual property and licensing 4, Investigation types 5, Policies, standards, procedures, and guidelines 4, Business continuity and BIA 7, Personnel security 5, Risk assessment and analysis 6, Risk response and control selection 5, Threat modeling 4, Supply chain risk management 5, Security awareness, education, and training 5.
- **D2** 11/11 covered. Data classification 4, Asset inventory and ownership 5, Data roles 5, Data lifecycle and collection 4, Data retention 5, Data remanence and destruction 5, Data states and protection 4, Scoping, tailoring, and baselines 5, DLP, DRM, and CASB 4, Asset handling and labeling 5, End-of-life assets 4.
- **D3** 15/15 covered. Secure design principles 4, Zero trust and secure access architecture 4, Security models 5, Evaluation and certification 4, Hardware security capabilities 4, Virtualization, containers, and serverless 4, Cloud and distributed systems 5, ICS, IoT, and embedded systems 4, Database and web architecture vulnerabilities 4, Symmetric and asymmetric cryptography 6, Hashing, signatures, and integrity 4, PKI and key management 5, Cryptanalytic attacks 5, Site and facility design 4, Environmental and physical controls 3.
- **D4** 14/14 covered. OSI and TCP/IP models 4, IP networking and addressing 5, Secure protocols 5, Converged and multilayer protocols 5, Network segmentation 4, Wireless networks 6, Cellular and satellite 5, SDN, SD-WAN, and virtual networks 4, Network devices and NAC 6, Transmission media 3, Remote access and VPN 4, Voice, video, and collaboration 3, Network attacks 6, CDN and edge networks 5.
- **D5** 13/13 covered. Physical and logical access control 4, Identification and authentication 5, Multi-factor and passwordless authentication 5, Session management 5, Identity proofing and registration 5, Federation and SSO 8, Authorization models 7, Access policy enforcement 4, Provisioning lifecycle 4, Access reviews 3, Privileged and service accounts 5, Authentication protocols 7, Just-in-time access 3.
- **D6** 13/13 covered. Assessment strategy 4, Vulnerability assessment 6, Penetration testing 6, Log review 6, Synthetic transactions and RUM 3, Code review and testing 4, Misuse cases and coverage analysis 5, Interface testing 4, Breach and attack simulation 4, Security process data and metrics 4, Backup and recovery verification 4, Reporting and remediation 4, Audits and SOC reports 6.
- **D7** 16/16 covered. Investigations and evidence 4, Digital forensics 3, Logging and monitoring 4, SIEM, SOAR, and threat intelligence 6, Configuration management 5, Foundational security operations 4, Resource and media protection 3, Incident management 5, Detective and preventive controls 4, Patch and vulnerability management 5, Change management 3, Backup and recovery strategies 5, Disaster recovery 3, DR plan testing 3, Physical security operations 5, Personnel safety 3.
- **D8** 12/12 covered. SDLC integration 3, Development methodologies 4, Software maturity models 3, Development ecosystem security 3, CI/CD and pipeline security 4, Application security testing 4, Software composition and supply chain 4, Acquired software security 4, Secure coding practices 6, Source code weaknesses 7, API security 4, Change and release management 4.
