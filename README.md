# Cyber Incident Investigation Portfolio Dashboard

## Project Overview
This repository contains the complete `Source Code` configuration for an interactive cyber incident response dashboard built inside **Splunk Dashboard Studio**. The project maps and visualizes parsed event timelines to help security analysts reconstruct an active threat scenario efficiently.

## Core Features
- **Incident Summary Monitoring:** Highlights an active tracking profile for a Credential Compromise event originating from a TOR exit node.
- **MITRE ATT&CK Mapping:** Converts raw logging flags directly into distinct attacker tactics utilizing custom Splunk Processing Language (SPL).
- **Chronological Timeline Reconstruction:** Integrates epoch time parsing (`strptime`) to automatically establish structural event orders.

## Files Included
- `cyber_incident_dashboard.json`: The foundational layout definitions, coordinate mapping parameters, data sources, and structural configurations.

## How to Deploy This Dashboard
1. Copy the raw contents of the `cyber_incident_dashboard.json` file in this repository.
2. Open your Splunk Enterprise or Cloud instance.
3. Create a new dashboard inside **Dashboard Studio** using an **Absolute Layout**.
4. Click on the **Source Editor** icon (brackets icon `</>`) in the top menu toolbar.
5. Select and delete all existing placeholder code, paste the copied JSON text, and hit **Apply**.
