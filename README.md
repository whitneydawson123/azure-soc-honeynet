<h1>Implementing a Live SOC & Honeynet: Attacking and Remediating It!</h1>
In Progress

<h2>Introduction</h2>
<p>This project involves setting up a honeynet on Microsoft Azure to attract cyber attackers, track and analyze malicious traffic, conduct incident response, and implement security measures to strengthen the environment.</p>

<h2>Objectives</h2>
<p>The primary goal of this project is to deploy a honeynet that enables real-time analysis of cyberattacks, faciliates incident response, and allows for in-depth investigation of security alerts. The secondary goal is to transition this vulnerable environment into a secure one by refining firewall configurations, optimizing Network Security Groups (NSG), and enforcing security best practices in alignmnent with NIST 800-52 and Microsoft Defender for Cloud recommendations.</p>

<h2>Before and After Hardening</h2>

- Before: The system is intentionally left exposed to attackers.


- After: Security controls are implemented to protect the environment.

<h2>Technologies, Regulations, and Azure Components Used:</h2>

- Networking & Security: Virtual Network (VNet), Network Security Group (NSG)
- Compute Resources: Two Windows and one Linux virtual machine
- Logging & Monitoring: Log Analytics Workspace for Kusto Query Language (KQL) data filtering
- Security & Compliance:
  - Azure Key Vault - Secure storage for sensitive information
  - Azure Storage Account - Data storage
  - Microsoft Sentinel - Security Information and Event Management (SIEM)
  - Microsoft Defender for Cloud - Resource monitoring and log ingestion
- Attack Simulation & Access:
  - PowerShell - Used for conducting simulated attacks
  - Command Line Interface (CLI) - Connection verification
  - Windows Remote Desktop - Remove VM access
- Regulatory Frameworks:
  - NIST SP 800-53 Revision 4 - Security control guidelines
  - NIST SP 800-61 Revision 2 - Incident response guidance
  - PCI DSS 3.2.1
 
<h2>Deploying the Honeynet</h2>

<h2>Logging & Monitoring</h2>

<h2>Analzing Log Collection</h2>

<h2>Remediation & Hardening</h2>

<h2>Metrics</h2>

<h2>Reflection</h2>

<h2>Conculsion</h2>

