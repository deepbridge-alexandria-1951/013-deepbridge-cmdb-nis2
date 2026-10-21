# NIS 2 and CMDB: Cybersecurity Obligations and Governance Framework

## The Critical Starting Point: NIS 2 Is NOT Just a Cybersecurity Technical Standard

**Before diving into technical requirements, understand this: NIS 2 is fundamentally a business and legal framework that imposes mandatory cybersecurity governance obligations on organizations—not merely a set of technical controls or a checklist to hand to IT operations.** Many organizations treat NIS 2 compliance as a technical security problem: "Update firewalls, patch systems, and we're done." This is a dangerous misconception.

NIS 2 reshapes organizational accountability by requiring **executive-level governance, systematic risk management, supply chain oversight, and incident reporting obligations that reach into board-level decision-making.** For an organization deploying a **CMDB (Configuration Management Database)** as a critical IT system, NIS 2 means you must demonstrate that your CMDB infrastructure meets mandatory security requirements, and that you have processes to detect, respond to, and report security incidents.

The burden falls on the **operator** (your organization). If you operate an essential service or are a large digital service provider, NIS 2 applies to you **regardless of where your systems are deployed** (on-premise, cloud, hybrid). Non-compliance carries **substantial fines, reputational damage, and potential operational shutdowns ordered by authorities.**

---

## Overview of NIS 2

**NIS 2** is the revised **Network and Information Security Directive**, which entered into force in **January 2023** and has been transposed into national laws across the EU and EEA (with implementation deadlines in 2024-2025). NIS 2 is the EU's primary cybersecurity regulatory framework, setting mandatory security and incident reporting obligations for operators of essential services and large digital service providers.

### What Changed from NIS 1 to NIS 2?

NIS 2 significantly strengthened requirements compared to the original NIS Directive:

| Aspect | NIS 1 | NIS 2 |
|--------|-------|-------|
| **Scope** | Essential services operators (narrow list) | Expanded to include large digital service providers; broader definition of essential services |
| **Risk Management** | "Appropriate technical measures" (vague) | Mandatory risk-based approach; specific security measures required |
| **Incident Reporting** | Report only serious incidents (72-hour threshold unclear) | Mandatory reporting of all incidents within **24 hours** to authorities |
| **Supply Chain Security** | Limited requirements | Mandatory supply chain risk assessment; vendor security obligations |
| **Governance** | Minimal executive oversight | **Board-level responsibility** for cybersecurity; mandatory board reporting |
| **Penalties** | Up to €600,000 (per member state) | Up to **€10 million or 2% of turnover** (whichever is higher) for operators; **€15 million or 3% of turnover** for service providers |
| **Enforcement** | Passive regulatory approach | **Active, proactive enforcement**; regulatory audits and inspections |

**The shift is clear: NIS 2 moves cybersecurity from an IT function to a business-critical governance responsibility.**

---

## Scope and Applicability: Who Must Comply?

NIS 2 applies to two primary categories of organizations:

### 1. **Operators of Essential Services (OES)**

An organization is an **operator of essential services** if it operates infrastructure or provides services in designated critical sectors **and** those operations are essential to the functioning of society or economy. Essential services sectors include:

| Sector | Examples | CMDB Relevance |
|--------|----------|----------------|
| **Energy** | Power generation, distribution, gas supply | If your CMDB is used for energy infrastructure management |
| **Transport** | Railways, air traffic, maritime, road transport | If your CMDB manages transport systems |
| **Water and Waste Management** | Water supply, sewerage, waste disposal | If your CMDB is critical to water/waste operations |
| **Health** | Hospitals, healthcare providers, pharmaceutical supply | If your CMDB is critical to healthcare delivery |
| **Digital Infrastructure** | DNS, internet exchange points, cloud providers, data centers | If your CMDB is part of digital infrastructure |
| **Public Administration** | Government agencies, e-government services | If your CMDB supports public administration |
| **Finance** | Banks, payment systems, securities exchanges | If your CMDB is critical to financial operations |
| **Drinking Water Supply and Distribution** | Water utilities | If your CMDB manages water supply systems |
| **Postal Services** | Postal operators | If your CMDB is critical to postal operations |

**Critical for CMDB: If your organization operates essential services and your CMDB is critical to those operations (i.e., if the CMDB goes down, the essential service is disrupted), your CMDB infrastructure falls under NIS 2.**

### 2. **Digital Service Providers (Large)**

A **large digital service provider** is a digital service provider that meets certain size thresholds:

| Type | Size Criterion | Examples | CMDB Relevance |
|------|---|----------|----------------|
| **Large Online Marketplaces** | >€1.5 billion annual EU turnover | Amazon, eBay | If your organization is a large marketplace operator |
| **Large Online Search Engines** | >€1.5 billion annual EU turnover | Google, Bing | If your organization operates a major search engine |
| **Large Content Distribution Networks (CDN)** | >€1.5 billion annual EU turnover | Akamai, Cloudflare | If your organization operates a major CDN |
| **Large Cloud Service Providers** | >€1.5 billion annual EU turnover | AWS, Azure, Google Cloud | If your organization operates a major cloud service and your CMDB is critical to that service |
| **Large Social Media Platforms** | >€1.5 billion annual EU turnover | Meta (Facebook), TikTok, LinkedIn | If your organization operates a major social platform |
| **Large Communication Service Providers** | Defined by electronic communications market | Telecom operators, ISPs | If your organization provides telecom/ISP services and your CMDB is critical |

**Critical for CMDB: If your organization is a large digital service provider and your CMDB is used to manage critical infrastructure supporting that service, NIS 2 applies to your CMDB.**

### Critical Question: Does Your CMDB Fall Under NIS 2?

Ask yourself:

1. **Does my organization operate essential services** (energy, transport, water, health, digital infrastructure, finance, public administration, postal)?
   - **YES** → If the CMDB is critical to those operations, **NIS 2 applies**.
   - **NO** → Continue to question 2.

2. **Is my organization a large digital service provider** (cloud, CDN, marketplace, social media, telecom) with >€1.5 billion EU turnover?
   - **YES** → If the CMDB is critical infrastructure for that service, **NIS 2 applies**.
   - **NO** → Continue to question 3.

3. **Is my organization designated as a critical supplier** to operators of essential services or large digital service providers?
   - **YES** → **NIS 2 applies** (supply chain security obligations).
   - **NO** → NIS 2 may not directly apply, though other cybersecurity laws may.

**If you answered YES to any of these, your CMDB falls under NIS 2 and you must comply with all mandatory requirements.**

---

## Core Obligations Under NIS 2

If NIS 2 applies to your CMDB environment, you must satisfy the following mandatory obligations:

### 1. Risk Management Framework (Mandatory)

NIS 2 requires a **systematic, risk-based approach to cybersecurity.** You must:

#### Establish a Risk Management System
- Identify assets, data, and systems critical to your essential services or digital services (including your CMDB)
- Identify threats, vulnerabilities, and potential impacts
- Assess the likelihood and impact of security incidents
- Prioritize risks based on potential harm to essential services, individuals, or the organization
- Document the risk assessment process and results

#### Implement Proportionate Security Measures
- Based on your risk assessment, implement technical and organizational measures to mitigate identified risks
- NIS 2 does not prescribe specific tools or techniques (unlike older standards), but requires a **risk-based, proportionate approach**
- Measures must be appropriate to the identified risks; excessive measures for low-risk elements are not required, but critical systems must be heavily protected

#### Measure and Monitor Risk
- Regularly assess the effectiveness of security measures
- Monitor for new threats and vulnerabilities
- Adjust measures based on changes in the threat landscape
- Document monitoring activities and adjust controls as needed

#### Key Requirements for CMDB Specifically
- Identify CMDB as a critical asset if it supports essential services or digital service delivery
- Assess risks to CMDB availability, integrity, and confidentiality
- Implement controls appropriate to the criticality of the CMDB (encryption, access control, redundancy, backup, disaster recovery)
- Test CMDB security regularly (penetration testing, vulnerability scanning)

### 2. Incident Management and Reporting (Mandatory)

NIS 2 imposes strict incident reporting obligations. This is a major shift and often the most disruptive requirement:

#### Incident Detection and Response
- Establish procedures to detect security incidents affecting your CMDB or other critical systems
- Respond to incidents promptly; establish incident response plans
- Investigate incidents to understand what happened and why
- Document incident details, timeline, and remediation actions
- Recover from incidents and restore normal operations

#### Mandatory Reporting Timeline
- **24-hour initial report**: Notify the competent authority (national NIS authority) within **24 hours** of detecting a security incident that impacts the confidentiality, integrity, or availability of CMDB or critical systems
- **72-hour detailed report**: Provide detailed incident information within **72 hours** of initial report (some member states allow extension to 7 days for complex incidents)
- **Follow-up reporting**: Provide updates as the incident investigation progresses

#### What Must Be Reported?

You must report incidents that:
- Affect the confidentiality, integrity, or availability of your CMDB or critical IT infrastructure
- Have a significant impact on the provision of essential services or digital services
- Meet certain severity thresholds (significant operational or security impact)

**Examples that trigger reporting:**
- CMDB is compromised by malware and integrity cannot be assured
- CMDB is rendered unavailable due to ransomware or DDoS attack
- Sensitive configuration data in CMDB is exfiltrated by attackers
- Unauthorized changes are made to CMDB data affecting service delivery
- Supply chain attack compromises CMDB security (e.g., malicious update from vendor)

#### Notification to Affected Parties
- If an incident affects personal data, you must also notify affected individuals (GDPR obligation applies in parallel)
- Notify customers and stakeholders if services they depend on are affected
- Communicate clearly and promptly about the incident and remediation steps

#### Incident Report Content (Required Information)
| Information | Description |
|-------------|-------------|
| **Time of discovery** | When was the incident first detected? |
| **Time of occurrence** | When did the incident actually happen (if different from discovery)? |
| **Attack vector** | How did attackers gain access? (e.g., phishing, vulnerability exploitation, insider threat) |
| **Affected systems** | Which systems were impacted? (e.g., CMDB, databases, networks) |
| **Affected data** | What data was accessed, modified, or exfiltrated? |
| **Impact assessment** | What is the business impact? (service downtime, data loss, etc.) |
| **Mitigation measures** | What steps were taken to respond and recover? |
| **Root cause** | What caused the incident? (preliminary assessment) |
| **Remediation plan** | What will be done to prevent recurrence? |

### 3. Supply Chain Security (Mandatory for High-Risk)

NIS 2 explicitly addresses supply chain risk. You must:

#### Identify Critical Suppliers
- Identify vendors and suppliers whose products, services, or infrastructure are critical to your CMDB or essential services
- Examples: software providers, hosting providers, managed service providers, security tool vendors, cloud providers

#### Assess Supplier Security
- Evaluate security controls of critical suppliers
- Conduct due diligence on their cybersecurity practices
- Verify they have incident detection, response, and reporting capabilities
- Assess their own supply chain security (vendors of vendors)

#### Contractual Requirements
- Include mandatory security requirements in vendor contracts
- Require vendors to notify you of security incidents within a specified timeframe (typically 24-48 hours)
- Include audit rights (right to inspect vendor security controls)
- Include incident reporting obligations (vendors must tell you of breaches affecting your data/systems)
- Define security incident thresholds and escalation procedures
- Include liability clauses for security failures

#### Manage Vendor Changes
- Monitor for changes in critical vendors (acquisition, bankruptcy, policy changes)
- Assess impact of vendor changes on your security posture
- Maintain contingency plans for vendor failure (alternative suppliers, backup systems)

#### Example for CMDB
If your CMDB is hosted by a cloud provider or managed by a managed service provider:
- Verify the provider meets NIS 2 requirements (if they are a large digital service provider, they must)
- Require SLAs guaranteeing incident response and reporting timelines
- Conduct regular audits of provider security controls
- Ensure you can recover your CMDB data if the provider fails

### 4. Cybersecurity Governance and Risk Management (Board-Level)

**NIS 2 explicitly requires executive and board-level cybersecurity governance.** This is not delegated to IT:

#### Board Responsibility
- The **board of directors** (or equivalent governing body) must oversee cybersecurity strategy and risk management
- The board must receive regular briefings on cybersecurity risks, incidents, and remediation
- The board must approve major cybersecurity investments and policies
- Board members are accountable for cybersecurity failures

#### Designate a Cybersecurity Lead
- Appoint a **chief information security officer (CISO)** or equivalent role with explicit responsibility for cybersecurity
- The CISO must have direct reporting line to senior leadership (ideally CEO or board)
- The CISO must have authority and budget to implement security measures
- The CISO must be involved in major business decisions affecting security

#### Cybersecurity Committee (Recommended)
- Establish a board-level committee focused on cybersecurity
- Meet regularly (at least quarterly) to review risks, incidents, and remediation
- Include external expertise (security consultants, auditors) as needed

#### Documentation and Governance Policies
- Document cybersecurity strategy, policies, and procedures
- Establish clear roles and responsibilities for security across the organization
- Create incident response procedures, communication plans, escalation paths
- Maintain records of security decisions and rationale

### 5. Technical and Organizational Security Measures

NIS 2 requires implementing security measures proportionate to identified risks. While the directive does not mandate specific tools, typical measures include:

| Measure | Purpose | CMDB Application |
|---------|---------|------------------|
| **Access Control** | Ensure only authorized users can access CMDB | Use role-based access control (RBAC); authenticate users; log all access |
| **Encryption** | Protect data confidentiality in transit and at rest | Encrypt sensitive CMDB data; use TLS 1.2+ for network communications |
| **Network Segmentation** | Isolate CMDB from less-trusted networks | Use firewalls, VLANs, zero-trust networking to restrict access to CMDB |
| **Vulnerability Management** | Identify and remediate security weaknesses | Regular vulnerability scans; patch management; security testing |
| **Malware Protection** | Detect and prevent malware infections | Endpoint detection and response (EDR); antivirus; threat intelligence |
| **Logging and Monitoring** | Detect security incidents | Comprehensive audit logs; security information and event management (SIEM); threat detection |
| **Business Continuity** | Ensure CMDB availability | Backup and disaster recovery; redundancy; failover capabilities |
| **Secure Development** | Prevent vulnerabilities in custom code | Code reviews, security testing, secure coding practices if you develop custom CMDB extensions |
| **Incident Response** | Respond to security incidents effectively | Incident response plan; regular drills; forensic capabilities; communication procedures |
| **Supplier Security** | Ensure supply chain security | Vendor assessments, contractual security requirements, monitoring |
| **Training and Awareness** | Reduce human security errors | Staff training on phishing, social engineering, CMDB security policies; awareness campaigns |
| **Penetration Testing and Red Team Exercises** | Identify real-world vulnerabilities | Annual penetration testing of CMDB infrastructure; simulated attack exercises |

### 6. Cryptographic Measures

NIS 2 explicitly requires appropriate use of cryptography:

- Use **strong encryption algorithms** (AES-256 for symmetric encryption; RSA-2048 or elliptic curve equivalents for asymmetric encryption)
- Use **TLS 1.2 or higher** for all network communications involving CMDB
- Protect cryptographic keys with key management systems
- Use **multi-factor authentication (MFA)** for access to CMDB
- Ensure encryption is appropriate to the sensitivity of data in CMDB

### 7. Transparency and Reporting to Authorities

- Maintain documentation of security
