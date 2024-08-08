# Intro to Cyber Threat Intel — Walkthrough

## Task 1: Introduction

### Learning Objectives
- Understand the basics of Cyber Threat Intelligence (CTI) and its classifications.
- Learn the lifecycle for deploying and using intelligence in threat investigations.
- Explore frameworks and standards used for distributing intelligence.

### Cyber Threat Intelligence Module
This module includes the following rooms:
- Threat Intelligence Tools
- YARA
- OpenCTI
- MISP

---

## Task 2: Cyber Threat Intelligence

Cyber Threat Intelligence (CTI) is evidence-based knowledge about adversaries, including their indicators, tactics, motivations, and actionable advice against them. CTI helps in protecting critical assets and informs cybersecurity teams and management business decisions.

### Key Concepts:
- **Data:** Discrete indicators associated with an adversary (e.g., IP addresses, URLs, hashes).
- **Information:** A combination of multiple data points (e.g., "How many times have employees accessed tryhackme.com within the month?").
- **Intelligence:** The correlation of data and information to extract patterns based on contextual analysis.

### CTI Questions to Address:
- Who’s attacking you?
- What are their motivations?
- What are their capabilities?
- What artefacts and indicators of compromise (IOCs) should you look out for?

### Threat Intelligence Classifications:
- **Strategic Intel:** High-level intel mapping out the threat landscape.
- **Technical Intel:** Evidence and artefacts of attack used by an adversary.
- **Tactical Intel:** Adversaries’ tactics, techniques, and procedures (TTPs).
- **Operational Intel:** Specific motives and intents of an adversary.

**Q:** What does CTI stand for?  
**A:** Cyber Threat Intelligence

**Q:** IP addresses, Hashes and other threat artefacts fall under which classification?  
**A:** Technical Intel

---

## Task 3: CTI Lifecycle

The CTI lifecycle is a process that transforms raw data into contextualized, actionable insights for triaging security incidents. It consists of six phases:

1. **Direction:** Define objectives and goals, including information assets, potential impacts, data sources, and tools required.
2. **Collection:** Gather data from various sources to address defined objectives.
3. **Processing:** Convert raw data into usable formats through sorting, organizing, correlation, and presentation.
4. **Analysis:** Derive insights and make decisions based on the aggregated information.
5. **Dissemination:** Distribute intelligence in varying formats to different organizational stakeholders.
6. **Feedback:** Regular interaction between teams to improve the threat intelligence process.

![CTI](https://github.com/Shruti1533/TryHackMe-Intro-to-Cyber-Threat-Intel-/blob/main/cti%20lifecycle.png)

**Q:** At which phase is data converted into usable formats?  
**A:** Processing

**Q:** During which phase do analysts define the questions for investigating incidents?  
**A:** Direction

---

## Task 4: CTI Standards & Frameworks

Standards and frameworks rationalize the distribution and use of threat intel across industries.

### Key Frameworks:
- **MITRE ATT&CK:** A knowledge base of adversary behavior focusing on indicators and tactics.
  ![MITRE ATTACK](https://github.com/Shruti1533/TryHackMe-Intro-to-Cyber-Threat-Intel-/blob/main/mitre.png)
- **TAXII:** Protocol for securely exchanging threat intel, supporting two models: Collection and Channel.
- **STIX:** Language for specifying, capturing, and communicating standardized cyber threat information.
- **Cyber Kill Chain:** Breaks down adversary actions into steps to help analysts identify activities during an attack.
![CYBER KILL CHAIN](https://github.com/Shruti1533/TryHackMe-Intro-to-Cyber-Threat-Intel-/blob/main/kill%20chain.png)
- **The Diamond Model:** Focuses on four key areas: Adversary, Victim, Infrastructure, and Capabilities.

  ![DIAMOND MODEL](https://github.com/Shruti1533/TryHackMe-Intro-to-Cyber-Threat-Intel-/blob/main/diamond%20model.png)

**Q:** What sharing models are supported by TAXII?  
**A:** Collection and Channel

**Q:** When an adversary extracts data, what phase of the kill chain are they in?  
**A:** Actions on Objectives

---

## Task 5: Practical Analysis

During the dissemination phase, CTI is distributed through published threat reports from technology and security companies like Mandiant, Recorded Future, and AT&TCybersecurity.

### Key Findings:
- **Source email address:** `vipivillain@badbank.com`
- **Downloaded file name:** `flbpfuh.exe`
- **Threat profile message:** `THM{NOW_I_CAN_CTI}`
- **Extraction IP address:** `91.185.23.222`
- **Threat actor's email address:** `vipivillain@badbank.com`
- **Extraction software tool:** `flbpfuh.exe`
- **Logged in user account:** `Administrator`
- **Targeted victim:** `John Doe`
