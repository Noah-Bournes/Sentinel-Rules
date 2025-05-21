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


=======
This repository contains custom and community-driven **Microsoft Sentinel Analytics Rules** designed to enhance threat detection, investigation, and response across your environment.

## 📌 Overview

Microsoft Sentinel uses Analytics Rules to proactively identify suspicious behavior and potential threats. This repo provides:

- **KQL-based detection rules** tailored for specific data sources (e.g., Azure AD, Defender, Intune, etc.)
- **Scheduled rules** with customizable thresholds and frequency
- **Behavioral and anomaly detections**
- Rules aligned with frameworks like **MITRE ATT&CK** and **NIST**

## 🔍 What's Inside

- `ScheduledRules/`: Rules that run on a recurring schedule
- `FusionRules/`: Rules leveraging Microsoft's built-in machine learning
- `NRT/`: Near-real-time rules for high-priority detections
- `Templates/`: JSON rule templates for easy deployment via ARM or API

>>>>>>> f78053a9222b50462db6e66d52cc838fa6e458fe
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

## 🤝 Contributing

We welcome contributions! If you have detection rules that improve security visibility, feel free to:
- Fork the repo
- Create a feature branch
- Submit a pull request

Please follow our contribution guidelines and include references, descriptions, and test validation notes with your rules.

## 📄 License

This repository is licensed under the MIT License.

