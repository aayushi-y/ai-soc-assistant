# ai-soc-assistant

# 🤖 AI-Augmented SOC Assistant

## 📌 Overview

This project demonstrates an AI-assisted Security Operations Center (SOC) workflow using Microsoft Sentinel, KQL, and AI-based alert analysis.

The system detects suspicious activities (e.g., failed logins, impossible travel), analyzes alerts using AI, and classifies them by severity.

---

## ⚙️ Tech Stack

* Microsoft Sentinel (SIEM)
* KQL (Detection queries)
* Microsoft Entra ID (Login logs)
* Microsoft Defender for Endpoint (Device telemetry)
* ChatGPT (AI-based alert analysis)

---

## 🧠 Features

* Custom KQL detection rules
* AI-based alert classification (High/Medium/Low)
* Simulated attack scenarios
* Optional automated response using Playbooks

---

## 🔄 Workflow

1. Logs ingested into Microsoft Sentinel
2. KQL analytics rule detects anomaly
3. Alert generated
4. Alert sent to AI model
5. AI classifies severity + suggests action
6. (Optional) Playbook triggers response

---

## 🚨 Sample Use Cases

* Multiple failed login attempts
* Impossible travel detection
* Suspicious PowerShell execution

---

## 🎯 Outcome

* Reduced alert fatigue
* Faster triage using AI
* Improved incident prioritization

---

## 📸 Demo

(Screenshots in /demo folder)

---

## 🚀 Future Improvements

* Integrate real API-based AI processing
* Add automated response workflows
* Expand detection rules


