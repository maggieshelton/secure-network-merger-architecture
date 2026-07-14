# secure-network-merger-architecture
Secure network architecture design, risk assessment, and compliance framework integration for an enterprise network merger.


**View the full technical document:** [Shelton_Secure_Network_Design_APA.pdf](https://github.com/user-attachments/files/30021155/Shelton_Secure_Network_Design_APA.pdf) 


Project Overview
This engineering project designs and documents a secure network architecture to safely merge two distinct corporate networks under a strict **$50,000 budgetary constraint**. The project encompasses comprehensive threat modeling, architectural risk analysis of End-of-Life (EOL) assets, regulatory compliance validation, and a high-availability cloud migration plan.


**Core Engineering Deliverables**

Technologies & Security Solutions Implemented
*   **Edge & Security Architecture:** SD-WAN, Fortinet 60F & 40F Firewalls, FortiSASE Services
*   **Core Compliance Frameworks:** HIPAA (Health Insurance Portability and Accountability Act), PCI-DSS (Payment Card Industry Data Security Standard)
*   **Framework Methodologies:** Defense-in-Depth, Network Segmentation, Principle of Least Privilege, Zero Trust Architecture (ZTA)

Risk Analysis & Threat Modeling
Identified and assessed critical security and infrastructure vulnerabilities across both companies prior to migration. Core findings neutralized include:
*   **Authentication Flaws:** Exposure of 8-character un-enforced password policies and excessive root-level/admin privilege assignments.
*   **Legacy Protocols:** Mitigation of cleartext data transmission risks resulting from active Rexec, Rlogin, and Rsh services.
*   **Perimeter Risks:** Vulnerability mapping of exposed internet-facing PostgreSQL database configurations and unprotected RDP (Port 3389) interfaces.

Regulatory Compliance Integration
Engineered the unified network layout to satisfy rigorous statutory demands:
*   **HIPAA Zone:** Isolated Protected Health Information (PHI) within an encrypted, strictly governed database zone (VLAN 100) enforced via Multi-Factor Authentication (MFA).
*   **PCI-DSS Zone:** Segmented all cardholder data and Personally Identifiable Information (PII) into an isolated storage cluster (VLAN 200) protected by granular Access Control Lists (ACLs).

Financial Optimization & Budgetary Strategy
Successfully executed a comprehensive cost-benefit analysis to completely rebuild the perimeter infrastructure within the allotted **$50,000 cap**. Allocated **$32,633.16** toward localized SASE software licensing and high-availability hardware leasing, repurposing core internal infrastructure to maximize project value.

<img width="1765" height="1011" alt="NetworkTopMerger drawio" src="https://github.com/user-attachments/assets/eb774a7f-ac05-45b3-a605-cbb7dedcd7f9" />
