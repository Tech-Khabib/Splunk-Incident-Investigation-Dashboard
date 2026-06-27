# Cyber Incident Investigation Dashboard
### Enterprise SOC Investigation & Detection Engineering with Splunk

## Executive Summary
Modern Security Operations Centers (SOCs) process thousands of security events every day. During an active cyber incident, analysts must rapidly determine what happened, when it happened, how the attacker progressed through the environment, and what actions should be taken next.

Traditional SIEM dashboards often present isolated alerts that require analysts to manually correlate events across multiple data sources, increasing investigation time and the likelihood of overlooking critical evidence.

This project demonstrates how Splunk Dashboard Studio can be used to transform raw security telemetry into an interactive investigation platform that improves analyst efficiency, accelerates incident triage, and enhances security visibility.

The solution consolidates investigation data into a single operational dashboard that enables analysts to reconstruct attacker activity, visualize attack progression, correlate related security events, and map adversary behavior to the MITRE ATT&CK Framework.

## Solution Architecture
<img width="757" height="412" alt="image" src="https://github.com/user-attachments/assets/73c63670-4523-49ba-be49-9d5916ea358e" />

## Project Preview

<img width="1918" height="785" alt="Screenshot 2026-06-27 193443" src="https://github.com/user-attachments/assets/e1a7fc42-a253-464f-b3a4-de5068a1fe10" />
<img width="1911" height="805" alt="Screenshot 2026-06-27 193515" src="https://github.com/user-attachments/assets/c91978e9-08ab-486d-9e2c-e091896c76ca" />
<img width="1916" height="881" alt="Screenshot 2026-06-27 193538" src="https://github.com/user-attachments/assets/e32fc722-f975-43df-adac-210e443d2285" />


## Business Problem
During security investigations, analysts must rapidly answer several critical questions:

- What attack occurred?
- Which systems were affected?
- How did the attacker gain access?
- What actions occurred after initial compromise?
- Which MITRE ATT&CK techniques were observed?
- What should the incident response team do next?

Answering these questions manually often requires analysts to switch between multiple SIEM searches, dashboards, and raw event logs.

This project addresses that challenge by consolidating investigation workflows into a single operational dashboard that improves visibility, reduces investigation complexity, and supports evidence-based decision making.

## Objectives
This project was designed to:

- Centralize security investigation data into a single operational view.
- Reduce analyst investigation time through event correlation.
- Reconstruct attacker timelines using normalized timestamps.
- Map observed activity to the MITRE ATT&CK Framework.
- Improve SOC situational awareness.
- Demonstrate practical SIEM engineering using Splunk Dashboard Studio.
- Showcase enterprise dashboard engineering for security operations.

## Solution Overview
The dashboard follows the same investigative process used in mature Security Operations Centers.

1. Incident Overview

Provides analysts with an immediate understanding of the active incident, including:

- Incident classification
- Severity
- Investigation status
- Priority
- Initial triage information
  
2. Timeline Reconstruction

Normalizes timestamps and reconstructs attacker activity into chronological order, allowing investigators to understand the complete attack lifecycle.

Benefits include:

- Faster forensic analysis
- Clear attack progression
- Evidence preservation
- Improved investigation accuracy

3. Security Event Correlation

Correlates multiple security events using Splunk Search Processing Language (SPL).

Examples include:

- Authentication activity
- Endpoint events
- Security alerts
- User behavior
- Suspicious host activity

Correlation reduces manual analysis by connecting related events into a unified investigation timeline.

4. MITRE ATT&CK Mapping

Observed attacker behavior is mapped against the MITRE ATT&CK Framework to improve analyst understanding of adversary tactics and techniques.

Example techniques that may be represented include:

- Initial Access
- Execution
- Persistence
- Privilege Escalation
- Credential Access
- Discovery
- Lateral Movement
- Collection
- Exfiltration

This enables analysts to understand attacker objectives while identifying opportunities for future detection engineering.

5. Investigation Dashboard

The completed dashboard supports several SOC functions, including:

- Incident Triage
- Threat Hunting
- Root Cause Analysis
- Security Reporting
- Executive Briefings
- Detection Validation

## Technologies Used
The project demonstrates practical implementation of:

- Splunk Dashboard Studio
- Splunk Search Processing Language (SPL)
- Interactive dashboard engineering
- Timeline reconstruction
- Event normalization
- Event correlation
- Investigation visualization
- MITRE ATT&CK enrichment
- Dashboard filtering
- Security reporting

## Technologies Used
Technology	                              Purpose
Splunk Enterprise	        Security Information & Event Management (SIEM)
Splunk Dashboard Studio	          Dashboard Development
Splunk SPL	                 Event Correlation and Search Logic
MITRE ATT&CK                  	Adversary Behavior Mapping
JSON	                            Dashboard Configuration
Security Event Logs	            Investigation Data Source


## Skills Demonstrated

This project demonstrates practical experience in:

- Security Operations Center (SOC) Monitoring
- Incident Investigation
- Detection Engineering
- SIEM Dashboard Development
- Splunk Search Processing Language (SPL)
- Security Event Correlation
- Threat Hunting
- MITRE ATT&CK Mapping
- Security Reporting
- Data Visualization

## Business Value

This solution provides measurable operational value by:

- Improving analyst visibility during investigations.
- Reducing investigation complexity.
- Accelerating incident triage.
- Supporting evidence-based response decisions.
- Standardizing investigation workflows.
- Improving executive reporting through clear visualization.
- Enhancing SOC operational efficiency.

## Project Limitations
This project is intended as a portfolio demonstration and therefore has several limitations:

- Uses demonstration security data.
- Does not perform automated containment or response actions.
- Assumes normalized event timestamps.
- Detection quality depends on available log sources.
- Dashboard content can be extended for additional enterprise use cases.

Documenting these limitations reflects realistic engineering practice and demonstrates awareness of operational constraints.

## Future Enhancements
Potential future improvements include:

- SOAR integration for automated response.
- Risk scoring and incident prioritization.
- User and Entity Behavior Analytics (UEBA).
- Threat intelligence enrichment.
- Geolocation visualization.
- Automated investigation playbooks.
- Multi-dashboard SOC monitoring suite.
- Executive KPI reporting.

## Key Takeaways
This project demonstrates how effective dashboard engineering can transform large volumes of security telemetry into actionable intelligence for Security Operations Centers.

Rather than presenting isolated alerts, the dashboard emphasizes investigative context, attacker behavior, evidence correlation, and operational decision support, principles that underpin modern detection engineering and incident response.
## Author
### Dakang Victor Ladat

Cyber Defense Analyst | Security Operations | Threat Hunting | Incident Response | Digital Forensics | Detection Engineering
