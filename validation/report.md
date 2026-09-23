# Question bank validation report

Bank v0.4: 750 questions in 32 batch files.

## Result: PASS

- Hard failures: 0
- Warnings: 0

## Progress toward v1.0 targets

Informational only; shortfalls are not failures.

| Domain | Questions | Easy | Medium | Hard |
|---|---|---|---|---|
| D1 Security and Risk Management | 120/160 | 36/48 | 54/72 | 30/40 |
| D2 Asset Security | 75/100 | 22/30 | 34/45 | 19/25 |
| D3 Security Architecture and Engineering | 98/130 | 30/39 | 43/59 | 25/32 |
| D4 Communication and Network Security | 98/130 | 30/39 | 43/59 | 25/32 |
| D5 Identity and Access Management | 97/130 | 30/39 | 43/59 | 24/32 |
| D6 Security Assessment and Testing | 90/120 | 27/36 | 40/54 | 23/30 |
| D7 Security Operations | 97/130 | 30/39 | 43/59 | 24/32 |
| D8 Software Development Security | 75/100 | 22/30 | 34/45 | 19/25 |
| **Total** | **750/1000** | | | |

### Next milestone: v1.0 (1000 questions)

| Domain | Have | Share of milestone | Still needed |
|---|---|---|---|
| D1 | 120 | 160 | 40 |
| D2 | 75 | 100 | 25 |
| D3 | 98 | 130 | 32 |
| D4 | 98 | 130 | 32 |
| D5 | 97 | 130 | 33 |
| D6 | 90 | 120 | 30 |
| D7 | 97 | 130 | 33 |
| D8 | 75 | 100 | 25 |

## Question types

| Domain | Knowledge | Application | Managerial | Managerial share |
|---|---|---|---|---|
| D1 | 39 | 33 | 48 | 40% |
| D2 | 22 | 24 | 29 | 39% |
| D3 | 29 | 30 | 39 | 40% |
| D4 | 30 | 31 | 37 | 38% |
| D5 | 28 | 30 | 39 | 40% |
| D6 | 26 | 29 | 35 | 39% |
| D7 | 30 | 27 | 40 | 41% |
| D8 | 22 | 22 | 31 | 41% |

Overall managerial share: 39.7% (target at least 35%).

## Answer-letter distribution

Allowed range 20%-30% per letter (checked).

| A | B | C | D |
|---|---|---|---|
| 187 (25%) | 187 (25%) | 186 (25%) | 190 (25%) |

## Length bias

Correct answer is the longest option (ties count) in 181/750 questions (24%); warning above 35%, and below 15% once the bank has 200 questions.
Correct answer is the shortest option in 203/750 (27%).

| Domain | Longest | Shortest |
|---|---|---|
| D1 | 23/120 (19%) | 33/120 (28%) |
| D2 | 15/75 (20%) | 19/75 (25%) |
| D3 | 30/98 (31%) | 26/98 (27%) |
| D4 | 25/98 (26%) | 21/98 (21%) |
| D5 | 22/97 (23%) | 13/97 (13%) |
| D6 | 23/90 (26%) | 29/90 (32%) |
| D7 | 25/97 (26%) | 29/97 (30%) |
| D8 | 18/75 (24%) | 33/75 (44%) |

## Most similar stems

Pairs above 0.85 fail validation. Top pairs at or above 0.50:

- D1-0042 / D1-0093: 0.78
- D1-0010 / D1-0039: 0.69
- D4-0005 / D4-0044: 0.68
- D6-0006 / D6-0036: 0.68
- D1-0056 / D2-0061: 0.67
- D2-0036 / D2-0068: 0.65
- D3-0045 / D3-0059: 0.63
- D1-0041 / D1-0081: 0.59
- D5-0041 / D4-0069: 0.59
- D5-0028 / D5-0095: 0.59

## Subtopic coverage

- **D1** 16/16 covered. Professional ethics 8, Security concepts 8, Security governance and roles 8, Due care and due diligence 5, Legal, regulatory, and contractual compliance 9, Privacy and transborder data flow 9, Intellectual property and licensing 6, Investigation types 7, Policies, standards, procedures, and guidelines 7, Business continuity and BIA 9, Personnel security 7, Risk assessment and analysis 9, Risk response and control selection 8, Threat modeling 6, Supply chain risk management 7, Security awareness, education, and training 7.
- **D2** 11/11 covered. Data classification 7, Asset inventory and ownership 7, Data roles 7, Data lifecycle and collection 7, Data retention 7, Data remanence and destruction 7, Data states and protection 6, Scoping, tailoring, and baselines 7, DLP, DRM, and CASB 7, Asset handling and labeling 7, End-of-life assets 6.
- **D3** 15/15 covered. Secure design principles 6, Zero trust and secure access architecture 6, Security models 8, Evaluation and certification 6, Hardware security capabilities 6, Virtualization, containers, and serverless 6, Cloud and distributed systems 7, ICS, IoT, and embedded systems 6, Database and web architecture vulnerabilities 6, Symmetric and asymmetric cryptography 9, Hashing, signatures, and integrity 6, PKI and key management 8, Cryptanalytic attacks 7, Site and facility design 6, Environmental and physical controls 5.
- **D4** 14/14 covered. OSI and TCP/IP models 7, IP networking and addressing 7, Secure protocols 8, Converged and multilayer protocols 7, Network segmentation 7, Wireless networks 8, Cellular and satellite 7, SDN, SD-WAN, and virtual networks 6, Network devices and NAC 9, Transmission media 5, Remote access and VPN 6, Voice, video, and collaboration 5, Network attacks 9, CDN and edge networks 7.
- **D5** 13/13 covered. Physical and logical access control 6, Identification and authentication 8, Multi-factor and passwordless authentication 7, Session management 7, Identity proofing and registration 7, Federation and SSO 11, Authorization models 9, Access policy enforcement 7, Provisioning lifecycle 7, Access reviews 5, Privileged and service accounts 8, Authentication protocols 10, Just-in-time access 5.
- **D6** 13/13 covered. Assessment strategy 7, Vulnerability assessment 8, Penetration testing 9, Log review 8, Synthetic transactions and RUM 5, Code review and testing 6, Misuse cases and coverage analysis 7, Interface testing 6, Breach and attack simulation 6, Security process data and metrics 7, Backup and recovery verification 6, Reporting and remediation 7, Audits and SOC reports 8.
- **D7** 16/16 covered. Investigations and evidence 6, Digital forensics 5, Logging and monitoring 6, SIEM, SOAR, and threat intelligence 8, Configuration management 7, Foundational security operations 6, Resource and media protection 5, Incident management 7, Detective and preventive controls 6, Patch and vulnerability management 7, Change management 5, Backup and recovery strategies 7, Disaster recovery 5, DR plan testing 5, Physical security operations 7, Personnel safety 5.
- **D8** 12/12 covered. SDLC integration 5, Development methodologies 6, Software maturity models 5, Development ecosystem security 5, CI/CD and pipeline security 6, Application security testing 6, Software composition and supply chain 7, Acquired software security 6, Secure coding practices 8, Source code weaknesses 9, API security 6, Change and release management 6.
