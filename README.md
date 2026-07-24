# OrchiCyb AI ATTACK 🌸 

## Overview

OrchiCyb AI ATTACK is an experimental AI-native Adaptive Cybersecurity Intelligence (ACI) platform designed to help to understand cyber threats through relationships rather than isolated data. Instead of treating MITRE ATT&CK techniques, threat actors, vulnerabilities and security frameworks as separate entities, the platform connects them into a single knowledge graph enriched with AI-assisted reasoning, governance context and interactive security simulations. The project explores how artificial intelligence can support cyber threat intelligence by explaining relationships between attacks, security controls, governance frameworks and organizational risk - not simply displaying more information.


The project explores the concept of **Adaptive Cybersecurity Intelligence (ACI)** - an approach where cyber defense continuously evolves through contextual intelligence and AI-assisted decision making.

---


### Try the latest version: 

**https://orchicyb-ai-attack.lovable.app**

---

## Supported Frameworks

- MITRE ATT&CK®
- MITRE D3FEND™
- MITRE ATLAS™
- NIST Cybersecurity Framework
- ISO/IEC 27001
- NIST AI RMF
- DORA

---

## Features

- AI-assisted Cyber Threat Intelligence
- Interactive Knowledge Graph
- MITRE ATT&CK, MITRE ATLAS & MITRE D3FEND integration
- What-if Analysis simulator
- Governance Context
- Live Intelligence Center
- AI-generated intelligence reports
- Research Workspace
- Detection Engineering
- Natural language investigation
- AI recommendations
- Threat relationship visualization

---


## Adaptive Cybersecurity Intelligence Pipeline


```mermaid
flowchart LR

    A[MITRE ATT&CK]
    B[MITRE D3FEND]
    C[MITRE ATLAS]
    D[External Threat Intelligence]

    A --> KG
    B --> KG
    C --> KG
    D --> KG

    KG[(Knowledge Graph)]

    KG --> TE[Threat Explorer]
    KG --> GC[Governance Context]
    KG --> WA[What-if Analysis]
    KG --> RW[Research Workspace]
    KG --> AI[AI Reasoning]

    AI --> IR[Intelligence Reports]
    AI --> LIC[Live Intelligence Center]
    AI --> DE[Detection Engineering]

    IR --> DS[Adaptive Cybersecurity Intelligence]
    LIC --> DS
    DE --> DS
    GC --> DS
    WA --> DS
```


---


## What-if Analysis

<img width="1389" height="773" alt="Zrzut ekranu 2026-07-24 o 13 45 57" src="https://github.com/user-attachments/assets/e7564b01-e2b2-4119-8853-5ca00feb99ea" />

The What-if Analysis module allows analysts to simulate how different security controls influence cyber risk. Instead of providing static recommendations, users can enable or disable controls such as MFA, EDR, SIEM or Network Segmentation and immediately observe how they affect likelihood, residual risk, governance exposure and defensive coverage. The objective is to help analysts understand the operational impact of security decisions before implementing them.


## Governance Context

<img width="1389" height="776" alt="Zrzut ekranu 2026-07-24 o 13 47 20" src="https://github.com/user-attachments/assets/9747e3c7-7d26-4f13-bcd9-e7739e889562" />

Governance Context extends traditional ATT&CK mappings by explaining the relationship between cyber threats, security controls and governance requirements.

Rather than simply listing that a technique maps to ISO 27001, NIST CSF or DORA, the platform attempts to explain:
- why a specific threat makes certain controls important,
- how those controls contribute to reducing organizational risk,
- how governance frameworks relate to defensive strategies.

The goal is to bridge Cyber Threat Intelligence with governance through contextual explanations instead of static compliance mappings.



## Live Intelligence Center

The Threat Intelligence Dashboard serves as the operational entry point to the OrchiCyb AI ATTACK platform, providing a centralized overview of the current cyber threat landscape. Rather than displaying isolated metrics, the dashboard aggregates intelligence from the underlying knowledge graph and presents it as actionable operational awareness.

```mermaid
flowchart LR

Collect --> Connect --> Understand --> Simulate --> Explain --> Adapt

Collect["Collect Intelligence"]
Connect["Build Knowledge Graph"]
Understand["AI-assisted Reasoning"]
Simulate["What-if Analysis"]
Explain["Intelligence Reports"]
Adapt["Adaptive Cybersecurity Intelligence"]
```


<img width="1387" height="774" alt="Zrzut ekranu 2026-07-24 o 13 48 13" src="https://github.com/user-attachments/assets/669e73e1-cd9c-4511-a6a0-d891d1967206" />

<img width="1387" height="772" alt="Zrzut ekranu 2026-07-24 o 13 56 27" src="https://github.com/user-attachments/assets/0ec701c2-8b1b-4158-852e-ab65a6b5e46b" />

<img width="1386" height="776" alt="Zrzut ekranu 2026-07-24 o 13 57 03" src="https://github.com/user-attachments/assets/a118bb45-bba2-41a0-a39a-0643de647c9f" />


The Live Intelligence Center aggregates multiple intelligence sources into a single operational workspace.
Current capabilities include:
- CISA Known Exploited Vulnerabilities (KEV)
- AI-generated intelligence briefings
- Weak Signal monitoring
- Emerging threat overview

The objective is to combine structured threat intelligence with continuously updated situational awareness.


## Research Workspace

<img width="1391" height="775" alt="Zrzut ekranu 2026-07-24 o 13 48 52" src="https://github.com/user-attachments/assets/362b3660-239f-44be-924c-aa93ec456ac1" />

The Research Workspace provides an environment for exploring intelligence, organizing investigations and generating AI-assisted reports. Instead of acting as a document repository, the workspace supports an intelligence-driven workflow where analysts can move naturally between graph exploration, threat analysis and report generation.



## Knowledge Graph

<img width="1391" height="776" alt="Zrzut ekranu 2026-07-24 o 13 52 30" src="https://github.com/user-attachments/assets/d0be195a-068c-4332-bff8-7b224db67fb9" />

The Knowledge Graph is the intelligence core of OrchiCyb AI ATTACK. Instead of representing cyber threat intelligence as isolated records, the platform models relationships between MITRE ATT&CK techniques, threat actors, malware, campaigns, vulnerabilities, security controls, governance frameworks and defensive technologies within a single interconnected graph. Analysts can visually explore attack paths, discover hidden relationships and understand how different entities influence one another across the cyber threat landscape. The graph is also designed to support AI-assisted reasoning, allowing the platform to explain why entities are connected, identify potential investigation paths and provide contextual intelligence instead of isolated indicators.


```mermaid
graph TD

ThreatActor["Threat Actor"]
Campaign["Campaign"]
Technique["MITRE Technique"]
Malware["Malware"]
Vulnerability["Vulnerability"]
Control["Security Control"]
Governance["Governance Context"]
Detection["Detection Rule"]
Report["Intelligence Report"]

ThreatActor --> Campaign
Campaign --> Technique
Technique --> Malware
Technique --> Vulnerability
Technique --> Control
Control --> Detection
Control --> Governance

Technique --> Report
Governance --> Report
Detection --> Report
```


## Threat Explorer

<img width="1387" height="773" alt="Zrzut ekranu 2026-07-24 o 14 00 08" src="https://github.com/user-attachments/assets/1e1f2768-0f9e-4ee6-9dc8-7ba8769bdd63" />

The Threat Explorer provides a unified workspace for investigating cyber threats through contextual relationships rather than individual records. Each entity—including ATT&CK techniques, threat actors, malware, campaigns, vulnerabilities, mitigations and security controls—contains rich contextual information connected directly to the underlying knowledge graph. Beyond traditional threat intelligence, the explorer introduces Governance Context, helping analysts understand how specific threats relate to security controls, governance frameworks and organizational risk. Instead of simply listing mappings, the platform explains why particular controls matter, how they reduce exposure and how governance requirements support defensive strategies


## Intelligence Reports

<img width="1389" height="773" alt="Zrzut ekranu 2026-07-24 o 17 45 45" src="https://github.com/user-attachments/assets/8bed9fa3-b958-4779-a3e3-9c118038ee67" />

The Intelligence Reports module transforms investigation results into structured, AI-assisted intelligence reports. Rather than exporting raw data, the platform generates reports that summarize cyber threats, explain relationships between entities, highlight governance considerations and provide actionable recommendations for security teams. Reports can include attack techniques, threat actor profiles, security controls, governance context, AI-generated observations and visual knowledge graph snapshots, making them suitable for research, threat intelligence sharing and executive briefings. The goal is to reduce manual reporting while improving consistency, explainability and decision support throughout the investigation process.


<img width="509" height="641" alt="Zrzut ekranu 2026-07-24 o 18 26 30" src="https://github.com/user-attachments/assets/11279b58-3c81-4745-8829-2f153c6ac882" />




## Detection Engineering

<img width="1391" height="769" alt="Zrzut ekranu 2026-07-24 o 14 01 39" src="https://github.com/user-attachments/assets/3de5b0c2-f720-414e-a5ac-25ed4390bd3f" />

The Detection Engineering module assists defenders in creating production-ready detection logic directly mapped to the MITRE ATT&CK framework. Rather than generating simple code snippets, the platform produces complete detection documentation that includes detection purpose, ATT&CK mappings, telemetry requirements, expected false positives, implementation considerations, and detection limitations. Users can generate detections across multiple technologies, including Sigma, YARA, Microsoft Sentinel KQL, Splunk SPL, Elastic DSL, CrowdStrike, Microsoft Defender XDR, Suricata, Snort, Falco, Sysmon, and OSQuery. Additional contextual information can be provided to tailor generated detections to specific environments or organizational requirements. By combining AI reasoning with cybersecurity best practices, the module accelerates detection development while promoting consistency, maintainability, and framework-aligned detection engineering workflows.


## Cyber Insights

<img width="1390" height="779" alt="Zrzut ekranu 2026-07-24 o 14 03 02" src="https://github.com/user-attachments/assets/8b87afd7-c3e8-47ba-9359-4acf40dd5785" />

Cyber Insights transforms raw relationships within the intelligence graph into contextual intelligence that helps analysts understand the broader security picture. Instead of requiring users to manually interpret thousands of graph connections, the platform continuously analyzes entity relationships and generates human-readable observations describing correlations, attacker behavior, mitigation opportunities, exposure risks, coverage gaps, and emerging trends. Each generated insight links directly back to the knowledge graph, allowing analysts to investigate the underlying evidence supporting every recommendation. This creates a transparent AI-assisted investigation workflow where conclusions remain explainable and traceable to their original intelligence sources. The goal of Cyber Insights is to reduce cognitive overload by automatically surfacing meaningful information that would otherwise remain hidden within complex interconnected cybersecurity datasets.


## Graph Analytics

<img width="1389" height="779" alt="Zrzut ekranu 2026-07-24 o 14 03 36" src="https://github.com/user-attachments/assets/96fea405-ce36-4508-b59e-3164c17f288b" />

Graph Analytics provides quantitative insights into the overall structure and health of the cybersecurity knowledge graph. Rather than focusing solely on threats, this module measures how intelligence itself is connected, enabling analysts to identify highly referenced techniques, influential threat actors, relationship density, and areas where intelligence coverage may be incomplete.

Structural metrics help security teams evaluate the completeness of their intelligence model while revealing which entities serve as central nodes within the threat ecosystem. Highly connected techniques often indicate frequently abused attacker behaviors and may deserve increased detection coverage or prioritization during threat hunting activities.

These analytics provide a complementary perspective to traditional dashboards by measuring the intelligence model itself instead of only operational security events.


## MITRE ATT&CK Import

<img width="1384" height="783" alt="Zrzut ekranu 2026-07-24 o 14 04 13" src="https://github.com/user-attachments/assets/be52ec15-d777-4e31-890d-2005c441c2c5" />

The MITRE Framework Import module enables organizations to import multiple MITRE knowledge bases directly into the OrchiCyb knowledge graph.

Currently, the platform supports importing:
- MITRE ATT&CK® – adversary tactics, techniques, software, groups, mitigations and data sources
- MITRE D3FEND™ – defensive techniques and countermeasures
- MITRE ATLAS™ – adversarial AI tactics and techniques

During the import process, each framework is transformed into interconnected graph entities while preserving their original relationships. This creates a unified cybersecurity knowledge graph where offensive techniques, defensive controls and AI-specific attack patterns can be explored together instead of remaining isolated within separate frameworks. By combining multiple MITRE frameworks into a single intelligence model, OrchiCyb enables richer relationship analysis, AI-assisted reasoning and contextual investigations that span both traditional cybersecurity and emerging AI security threats.


## OrchiCyb AI Copilot

<img width="1393" height="775" alt="Zrzut ekranu 2026-07-24 o 14 05 23" src="https://github.com/user-attachments/assets/398b531d-b50c-490c-b6c2-298af735a211" />

OrchiCyb AI Copilot is an AI-native cybersecurity assistant designed to reason over the complete intelligence graph rather than isolated documents. Leveraging relationships between MITRE ATT&CK techniques, threat actors, malware, campaigns, vulnerabilities, and defensive controls, the Copilot can answer complex cybersecurity questions using contextual knowledge rather than keyword matching. Analysts can request attack chain generation, explain adversary behavior, identify detection opportunities, recommend mitigations, generate investigation plans, and summarize complex threat intelligence directly within the platform. Every response is grounded in the underlying graph model, allowing AI to produce recommendations that reflect the relationships between entities instead of treating each object independently. The long-term vision of the Copilot is to become an intelligent cyber operations assistant capable of supporting Security Operations Centers, Threat Hunters, Detection Engineers, Incident Responders, and Cyber Threat Intelligence analysts throughout every stage of the defensive workflow.

---

## Technology

OrchiCyb AI ATTACK combines modern cybersecurity concepts with AI-native intelligence workflows, including:

- Artificial Intelligence (AI)
- Adaptive Cybersecurity Intelligence (ACI)
- Cyber Threat Intelligence (CTI)
- Knowledge Graphs
- MITRE ATT&CK®
- MITRE D3FEND™
- MITRE ATLAS™
- Detection Engineering
- Threat Hunting
- Governance Context
- AI-assisted Security Reasoning
- Interactive Threat Visualization
- Live Threat Intelligence
- Modern UX for Security Operations

  
```mermaid
flowchart TD

    subgraph Data Sources
        ATTACK[MITRE ATT&CK]
        D3FEND[MITRE D3FEND]
        ATLAS[MITRE ATLAS]
        CTI[Threat Intelligence Feeds]
    end

    subgraph Intelligence Layer
        IMPORT[MITRE Framework Import]
        KG[Knowledge Graph]
        AI[AI Reasoning Engine]
    end

    subgraph Investigation
        TE[Threat Explorer]
        GC[Governance Context]
        WA[What-if Analysis]
        RW[Research Workspace]
    end

    subgraph Outputs
        REPORTS[AI Intelligence Reports]
        LIVE[Live Intelligence Center]
        DETECTION[Detection Engineering]
    end

    ATTACK --> IMPORT
    D3FEND --> IMPORT
    ATLAS --> IMPORT
    CTI --> IMPORT

    IMPORT --> KG
    KG --> AI

    AI --> TE
    AI --> GC
    AI --> WA
    AI --> RW

    TE --> REPORTS
    GC --> REPORTS
    WA --> REPORTS
    RW --> REPORTS

    AI --> LIVE
    AI --> DETECTION
```


---

## Vision

The long-term vision of OrchiCyb AI ATTACK is to explore how Adaptive Cybersecurity Intelligence can transform cyber defense.
Rather than building another threat intelligence platform, the project investigates how AI, knowledge graphs and contextual reasoning can help security professionals understand relationships between cyber threats, security controls, governance frameworks and organizational risk. The goal is to make cyber intelligence more explainable, interconnected and actionable.

```mermaid
flowchart LR

Data["Cyber Data"] --> Intelligence["Threat Intelligence"]

Intelligence --> Graph["Knowledge Graph"]

Graph --> AI["AI Reasoning"]

AI --> Context["Context"]

Context --> Decisions["Security Decisions"]

Decisions --> Adaptation["Adaptive Cybersecurity Intelligence"]

style Adaptation fill:#f7d6ea,stroke:#b04b8d,color:#000
```



---

## Disclaimer

OrchiCyb AI ATTACK is an independent research project intended for educational, research, and cybersecurity innovation purposes.
MITRE ATT&CK® is a registered trademark of The MITRE Corporation.

---

## License
Copyright (c) 2026 OrchiCyb Dominika Jakubek

All rights reserved.
This repository contains documentation and public information about the project.
No part of this repository may be copied, modified, distributed, or used to create derivative works without prior written permission from the copyright holder.
