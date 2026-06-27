# Cyber Incident Investigation Dashboard
##**Enterprise SOC Investigation & Detection Engineering with Splunk**

## Executive Summary
Security Operations Centers (SOCs) generate thousands of security events every day. Without effective visualization and correlation, analysts can spend valuable time manually piecing together attacker activity.

This project demonstrates how Splunk Dashboard Studio can transform raw security telemetry into an interactive investigation platform that accelerates incident triage, improves situational awareness, and supports evidence-based decision making.

The dashboard was designed to help analysts quickly identify malicious activity, reconstruct attack timelines, map adversary behavior to the MITRE ATT&CK framework, and prioritize response actions.

## Business Problem
Traditional SIEM dashboards often present large volumes of isolated alerts with limited context. During active investigations, analysts must correlate multiple log sources, identify relationships between events, and determine attack progression under time pressure.

This project addresses that challenge by presenting correlated security events through a single investigation dashboard that enables faster analysis and more informed incident response.

## Objectives
The primary objectives of this project were to:

- Improve visibility into security incidents through centralized visualization.
- Reduce investigation time by correlating related security events.
- Provide analysts with an intuitive attack timeline.
- Translate raw log data into meaningful security intelligence.
- Demonstrate practical SIEM engineering using Splunk Dashboard Studio.

## Solution Overview
The dashboard combines multiple investigation components into a unified operational view.

### Incident Overview

Provides analysts with an immediate understanding of the active investigation, including incident classification, priority level, and current investigation status.

### Timeline Reconstruction

Security events are automatically organized into chronological order using timestamp normalization, allowing investigators to understand the sequence of attacker activity from initial access through post-compromise actions.

### MITRE ATT&CK Mapping

Relevant events are mapped against MITRE ATT&CK tactics and techniques to help analysts understand attacker objectives and identify gaps in detection coverage.

### Security Event Correlation

Multiple event sources are correlated using Splunk Search Processing Language (SPL), enabling analysts to connect authentication events, endpoint activity, and suspicious behavior within a single investigation workflow.

### Investigation Dashboard

The final dashboard provides an operational view designed to support:

- Incident Triage
- Threat Hunting
- Root Cause Analysis
- Executive Reporting
- SOC Investigations

## Technologies Used
Technology	Purpose
Splunk Enterprise	Security Information & Event Management (SIEM)
Splunk Dashboard Studio	Interactive Dashboard Development
Splunk SPL	Event Correlation & Search Logic
MITRE ATT&CK	Adversary Behavior Mapping
JSON	Dashboard Configuration
Security Event Logs	Investigation Data Source

## Skills Demonstrated

This project demonstrates practical experience in:

Security Operations Center (SOC) Monitoring
Incident Investigation
Detection Engineering
SIEM Dashboard Development
Splunk Search Processing Language (SPL)
Security Event Correlation
Threat Hunting
MITRE ATT&CK Mapping
Security Reporting
Data Visualization

## Key Takeaways

This project demonstrates how effective dashboard engineering can improve the speed and quality of cyber incident investigations by transforming raw telemetry into actionable intelligence.

Rather than presenting isolated alerts, the solution emphasizes context, attacker behavior, and investigative workflow—principles that are fundamental to modern Security Operations Centers.

## Author

**Dakang Victor Ladat**

Cyber Defense Analyst | Security Operations | Threat Hunting | Incident Response | Digital Forensics | Detection Engineering
