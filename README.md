# 🇮🇷 Iran Cyber Threat Actor Matrix

## Overview

This project provides a structured analytical model of Iranian cyber threat actors mapped across operational phases. It is designed to simulate how different categories of actors (state-sponsored APTs, contractors, and proxy groups) behave during periods of geopolitical escalation.

The matrix organizes activity into time-based phases and links each phase to likely cyber behaviors, objectives, and actor types.

---

## 🎯 Objectives

* Model Iranian cyber operations across conflict phases
* Map threat actors to behaviors and intent
* Support threat hunting and detection engineering
* Provide a scenario-based framework for cyber defense planning

---

## 🧩 Framework Structure

The matrix is divided into three primary phases:

### 1. Pre-Positioning Phase

**Timeframe:** Long-term (months to years before escalation)

**Objectives:**

* Establish persistence
* Conduct espionage
* Pre-position access for future operations

**Common Activities:**

* Spear phishing campaigns
* Credential harvesting
* Web shell deployment
* Supply chain compromise

**Example Actors:**

* APT33 (Holmium)
* APT34 (OilRig)
* APT35 (Charming Kitten)
* MuddyWater

---

### 2. Shock & Disruption Phase

**Timeframe:** Day 0 (initial escalation event)

**Objectives:**

* Disrupt critical infrastructure
* Degrade communications
* Create psychological and operational impact

**Common Activities:**

* Wiper malware deployment
* Distributed Denial-of-Service (DDoS)
* ICS/SCADA targeting
* Command-and-control (C2) activation

**Example Actors:**

* Agrius
* State-aligned offensive cyber units

---

### 3. Retaliation / Sustained Operations Phase

**Timeframe:** Days to weeks after initial disruption

**Objectives:**

* Maintain pressure on adversaries
* Conduct opportunistic attacks
* Amplify geopolitical messaging

**Common Activities:**

* Ransomware operations
* Data leaks and hack-and-leak campaigns
* Website defacement
* Influence operations

**Example Actors:**

* Proxy hacktivist groups
* Contractor-linked cyber units

---

## 🛠 MITRE ATT&CK Mapping (Example)

| Tactic            | Technique                      | ID    |
| ----------------- | ------------------------------ | ----- |
| Initial Access    | Phishing                       | T1566 |
| Persistence       | Web Shell                      | T1505 |
| Credential Access | Credential Dumping             | T1003 |
| Command & Control | Web Services (e.g., GitHub C2) | T1102 |
| Impact            | Data Destruction (Wipers)      | T1485 |

---

## 🔎 Use Cases

* Threat intelligence analysis
* Red team scenario planning
* Detection engineering
* Security operations simulations

---

## ⚠️ Disclaimer

This project is a **conceptual and analytical model** based on publicly available threat intelligence and known behavioral patterns of Iranian cyber operations. It is intended for educational and research purposes only.

---

## 🚀 Future Improvements

* Add detailed actor profiles
* Expand MITRE ATT&CK coverage
* Include real-world campaign references
* Provide detection queries (Sigma, KQL)
* Visualize matrix as heatmap or dashboard

---

## 👤 Author

Akoparna B

---

## 📚 Sources

* MITRE ATT&CK Framework ([https://attack.mitre.org](https://attack.mitre.org))
* CISA Advisory: Iranian Government-Sponsored APT Activity
* Microsoft Threat Intelligence reports on Iranian actors
* Mandiant (Google Cloud) Threat Intelligence reports
* CrowdStrike Global Threat Report
* Palo Alto Unit 42 research on Iranian threat groups
* Recorded Future threat intelligence reports
* Open-source reporting on APT33, APT34 (OilRig), APT35 (Charming Kitten), MuddyWater, and Agrius

---

## 📄 License

This project is open-source and available under the MIT License.
