# Question bank validation report

Bank v0.2: 250 questions in 16 batch files.

## Result: PASS

- Hard failures: 0
- Warnings: 0

## Progress toward v1.0 targets

Informational only; shortfalls are not failures.

| Domain | Questions | Easy | Medium | Hard |
|---|---|---|---|---|
| D1 Security and Risk Management | 40/160 | 12/48 | 18/72 | 10/40 |
| D2 Asset Security | 25/100 | 7/30 | 11/45 | 7/25 |
| D3 Security Architecture and Engineering | 33/130 | 10/39 | 14/59 | 9/32 |
| D4 Communication and Network Security | 33/130 | 10/39 | 14/59 | 9/32 |
| D5 Identity and Access Management | 32/130 | 10/39 | 14/59 | 8/32 |
| D6 Security Assessment and Testing | 30/120 | 9/36 | 13/54 | 8/30 |
| D7 Security Operations | 32/130 | 10/39 | 14/59 | 8/32 |
| D8 Software Development Security | 25/100 | 7/30 | 11/45 | 7/25 |
| **Total** | **250/1000** | | | |

### Next milestone: v0.3 (500 questions)

| Domain | Have | Share of milestone | Still needed |
|---|---|---|---|
| D1 | 40 | 80 | 40 |
| D2 | 25 | 50 | 25 |
| D3 | 33 | 65 | 32 |
| D4 | 33 | 65 | 32 |
| D5 | 32 | 65 | 33 |
| D6 | 30 | 60 | 30 |
| D7 | 32 | 65 | 33 |
| D8 | 25 | 50 | 25 |

## Question types

| Domain | Knowledge | Application | Managerial | Managerial share |
|---|---|---|---|---|
| D1 | 13 | 11 | 16 | 40% |
| D2 | 7 | 7 | 11 | 44% |
| D3 | 9 | 11 | 13 | 39% |
| D4 | 9 | 11 | 13 | 39% |
| D5 | 9 | 11 | 12 | 38% |
| D6 | 8 | 10 | 12 | 40% |
| D7 | 10 | 9 | 13 | 41% |
| D8 | 7 | 8 | 10 | 40% |

Overall managerial share: 40.0% (target at least 35%).

## Answer-letter distribution

Allowed range 20%-30% per letter (checked).

| A | B | C | D |
|---|---|---|---|
| 63 (25%) | 63 (25%) | 62 (25%) | 62 (25%) |

## Length bias

Correct answer is the longest option (ties count) in 52/250 questions (21%); warning above 35%, and below 15% once the bank has 200 questions.
Correct answer is the shortest option in 47/250 (19%).

| Domain | Longest | Shortest |
|---|---|---|
| D1 | 2/40 (5%) | 11/40 (28%) |
| D2 | 3/25 (12%) | 4/25 (16%) |
| D3 | 11/33 (33%) | 7/33 (21%) |
| D4 | 9/33 (27%) | 8/33 (24%) |
| D5 | 6/32 (19%) | 1/32 (3%) |
| D6 | 7/30 (23%) | 7/30 (23%) |
| D7 | 8/32 (25%) | 5/32 (16%) |
| D8 | 6/25 (24%) | 4/25 (16%) |

## Most similar stems

Pairs above 0.85 fail validation. Top pairs at or above 0.50:

- D1-0010 / D1-0039: 0.69

## Subtopic coverage

- **D1** 16/16 covered. Professional ethics 2, Security concepts 3, Security governance and roles 2, Due care and due diligence 2, Legal, regulatory, and contractual compliance 3, Privacy and transborder data flow 3, Intellectual property and licensing 2, Investigation types 3, Policies, standards, procedures, and guidelines 2, Business continuity and BIA 3, Personnel security 3, Risk assessment and analysis 3, Risk response and control selection 3, Threat modeling 2, Supply chain risk management 2, Security awareness, education, and training 2.
- **D2** 11/11 covered. Data classification 3, Asset inventory and ownership 2, Data roles 3, Data lifecycle and collection 1, Data retention 2, Data remanence and destruction 2, Data states and protection 3, Scoping, tailoring, and baselines 2, DLP, DRM, and CASB 3, Asset handling and labeling 2, End-of-life assets 2.
- **D3** 15/15 covered. Secure design principles 2, Zero trust and secure access architecture 2, Security models 3, Evaluation and certification 2, Hardware security capabilities 2, Virtualization, containers, and serverless 2, Cloud and distributed systems 2, ICS, IoT, and embedded systems 2, Database and web architecture vulnerabilities 2, Symmetric and asymmetric cryptography 3, Hashing, signatures, and integrity 2, PKI and key management 3, Cryptanalytic attacks 3, Site and facility design 2, Environmental and physical controls 1.
- **D4** 14/14 covered. OSI and TCP/IP models 2, IP networking and addressing 2, Secure protocols 3, Converged and multilayer protocols 2, Network segmentation 2, Wireless networks 3, Cellular and satellite 3, SDN, SD-WAN, and virtual networks 2, Network devices and NAC 3, Transmission media 2, Remote access and VPN 2, Voice, video, and collaboration 1, Network attacks 3, CDN and edge networks 3.
- **D5** 13/13 covered. Physical and logical access control 2, Identification and authentication 2, Multi-factor and passwordless authentication 2, Session management 2, Identity proofing and registration 3, Federation and SSO 5, Authorization models 4, Access policy enforcement 2, Provisioning lifecycle 2, Access reviews 1, Privileged and service accounts 2, Authentication protocols 4, Just-in-time access 1.
- **D6** 13/13 covered. Assessment strategy 2, Vulnerability assessment 3, Penetration testing 3, Log review 3, Synthetic transactions and RUM 1, Code review and testing 2, Misuse cases and coverage analysis 3, Interface testing 2, Breach and attack simulation 2, Security process data and metrics 2, Backup and recovery verification 2, Reporting and remediation 2, Audits and SOC reports 3.
- **D7** 16/16 covered. Investigations and evidence 1, Digital forensics 1, Logging and monitoring 2, SIEM, SOAR, and threat intelligence 4, Configuration management 3, Foundational security operations 2, Resource and media protection 1, Incident management 3, Detective and preventive controls 2, Patch and vulnerability management 3, Change management 1, Backup and recovery strategies 3, Disaster recovery 1, DR plan testing 1, Physical security operations 3, Personnel safety 1.
- **D8** 12/12 covered. SDLC integration 1, Development methodologies 2, Software maturity models 1, Development ecosystem security 1, CI/CD and pipeline security 2, Application security testing 2, Software composition and supply chain 2, Acquired software security 2, Secure coding practices 3, Source code weaknesses 5, API security 2, Change and release management 2.
