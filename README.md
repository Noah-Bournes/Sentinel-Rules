# Demo Sentinel Analytics Rules 

This repository contains custom and community-driven **Microsoft Sentinel Analytics Rules** designed to enhance threat detection, investigation, and response across your environment.

## 📌 Overview

Microsoft Sentinel uses Analytics Rules to proactively identify suspicious behavior and potential threats. This repo provides:

- **KQL-based detection rules** tailored for specific data sources (e.g., Azure AD, Defender, Intune, etc.)
- **Scheduled rules** with customizable thresholds and frequency
- **Behavioral and anomaly detections**
- Rules aligned with frameworks like **MITRE ATT&CK** and **NIST**

## 🔍 What's Inside

- `MediumSeverityRules/`: Medium Severity Rules that run on a recurring schedule
- `HighSeverityRules/`: High severity Rules that run on a recurring schedule
- DefenderXDR
- Entra ID
- Azure Activity
- MS 365

## 🛠️ Usage

These rules can be imported into Sentinel using:
- Microsoft Sentinel UI
- ARM templates
- Azure Resource Graph Explorer
- PowerShell / Azure CLI
- GitHub Actions or CI/CD pipelines

## ✅ Requirements

- Active Microsoft Sentinel Workspace
- Properly connected data connectors (e.g., Microsoft Defender, Entra ID, Office 365)
- Contributor or higher permissions on the Sentinel Workspace

