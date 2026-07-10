# OrchiCyb AI ATTACK 🌸 

### Adaptive Cybersecurity Intelligence (ACI)

An AI-powered Cyber Threat Intelligence platform built around the MITRE ATT&CK® framework to help security professionals understand, analyze, and respond to modern cyber threats.

### Live Demo

**https://orchicyb-ai-attack.lovable.app**

---

## Overview

OrchiCyb AI ATTACK is an experimental AI-native cybersecurity platform designed to transform the way analysts interact with cyber threat intelligence.

Instead of navigating static databases, users can explore MITRE ATT&CK through an intelligent interface that combines:

- Artificial Intelligence
- Knowledge Graphs
- Threat Intelligence
- Detection Engineering
- Threat Hunting
- Interactive Attack Visualization

The project explores the concept of **Adaptive Cybersecurity Intelligence (ACI)** - an approach where cyber defense continuously evolves through contextual intelligence and AI-assisted decision making.

---

## Features

- AI-assisted MITRE ATT&CK exploration
- Interactive Attack Graphs
- AI-powered Threat Intelligence
- Detection Engineering workspace
- Natural language search
- AI recommendations
- Threat relationship visualization
- Adaptive cybersecurity workflows

---

## Threat Intelligence Dashboard

<img width="2048" height="1135" alt="image" src="https://github.com/user-attachments/assets/a31877c0-7d4f-408b-9920-ea0d97596cfe" />

The Threat Intelligence Dashboard serves as the operational entry point to the OrchiCyb AI ATTACK platform, providing a centralized overview of the current cyber threat landscape. Rather than displaying isolated metrics, the dashboard aggregates intelligence from the underlying knowledge graph and presents it as actionable operational awareness.

Security analysts can instantly monitor the total number of entities, relationships, active threat actors, and critical findings while tracking attack trends over time. Interactive visualizations provide insight into how threat activity evolves, enabling faster identification of dominant attack techniques and emerging adversary behaviors.

The dashboard also measures framework coverage across industry standards such as MITRE ATT&CK, NIST CSF, and CIS Controls, helping organizations understand the maturity of their security posture. Combined with AI-powered recommendations, this workspace is designed to reduce investigation time and support faster, data-driven decision making within Security Operations Centers (SOCs), Threat Intelligence teams, and Detection Engineering workflows.


## Knowledge Graph

<img width="2047" height="1137" alt="image" src="https://github.com/user-attachments/assets/6caccffe-69b1-4ffb-b2bc-25405625245b" />


The Knowledge Graph represents the core intelligence engine of OrchiCyb AI ATTACK. Instead of storing cybersecurity information as disconnected records, every entity is modeled as part of a continuously evolving graph where techniques, threat actors, malware, campaigns, vulnerabilities, mitigations, defensive controls, and security frameworks are interconnected through meaningful relationships.

Analysts can visually explore adversary behavior, discover hidden correlations, and identify complex attack paths that are difficult to recognize using traditional databases or spreadsheets. The graph supports interactive filtering, shortest-path analysis, relationship exploration, and contextual investigation, allowing users to understand how different entities influence one another throughout the attack lifecycle.

This graph-based approach enables AI to reason over the entire cybersecurity knowledge base, making it possible to generate contextual recommendations, explain relationships, predict attacker behavior, and support advanced threat hunting scenarios.


## Threat Explorer

<img width="2048" height="1135" alt="image" src="https://github.com/user-attachments/assets/2a6b1e2d-a1bd-4ed0-bbfd-09357d0bda18" />


Threat Explorer provides a unified interface for navigating the cybersecurity knowledge graph. Every entity—including MITRE ATT&CK techniques, threat actors, malware families, campaigns, vulnerabilities, defensive controls, and detection rules—can be searched, filtered, and analyzed within a single workspace.

Selecting an entity immediately reveals detailed contextual information, including descriptions, severity, industries affected, related entities, and graph relationships. This allows analysts to move naturally between different parts of the intelligence model without manually searching multiple external resources.

By combining structured cybersecurity knowledge with intuitive exploration, Threat Explorer transforms large collections of threat intelligence into an accessible investigative environment where defenders can rapidly understand adversary capabilities and operational context.



## Detection Engineering

<img width="2048" height="1134" alt="image" src="https://github.com/user-attachments/assets/924e8212-51d3-481c-aa91-d0830c15bc71" />

The Detection Engineering module assists defenders in creating production-ready detection logic directly mapped to the MITRE ATT&CK framework. Rather than generating simple code snippets, the platform produces complete detection documentation that includes detection purpose, ATT&CK mappings, telemetry requirements, expected false positives, implementation considerations, and detection limitations.

Users can generate detections across multiple technologies, including Sigma, YARA, Microsoft Sentinel KQL, Splunk SPL, Elastic DSL, CrowdStrike, Microsoft Defender XDR, Suricata, Snort, Falco, Sysmon, and OSQuery. Additional contextual information can be provided to tailor generated detections to specific environments or organizational requirements.

By combining AI reasoning with cybersecurity best practices, the module accelerates detection development while promoting consistency, maintainability, and framework-aligned detection engineering workflows.


## Cyber Insights

<img width="2048" height="1133" alt="image" src="https://github.com/user-attachments/assets/65eb5836-0d03-4190-ae01-260d4324d9a1" />


Cyber Insights transforms raw relationships within the intelligence graph into contextual intelligence that helps analysts understand the broader security picture. Instead of requiring users to manually interpret thousands of graph connections, the platform continuously analyzes entity relationships and generates human-readable observations describing correlations, attacker behavior, mitigation opportunities, exposure risks, coverage gaps, and emerging trends.

Each generated insight links directly back to the knowledge graph, allowing analysts to investigate the underlying evidence supporting every recommendation. This creates a transparent AI-assisted investigation workflow where conclusions remain explainable and traceable to their original intelligence sources.

The goal of Cyber Insights is to reduce cognitive overload by automatically surfacing meaningful information that would otherwise remain hidden within complex interconnected cybersecurity datasets.


## Graph Analytics

<img width="2048" height="1127" alt="image" src="https://github.com/user-attachments/assets/3b6034a8-3aae-4f9e-a5db-870c2bef2ead" />

Graph Analytics provides quantitative insights into the overall structure and health of the cybersecurity knowledge graph. Rather than focusing solely on threats, this module measures how intelligence itself is connected, enabling analysts to identify highly referenced techniques, influential threat actors, relationship density, and areas where intelligence coverage may be incomplete.

Structural metrics help security teams evaluate the completeness of their intelligence model while revealing which entities serve as central nodes within the threat ecosystem. Highly connected techniques often indicate frequently abused attacker behaviors and may deserve increased detection coverage or prioritization during threat hunting activities.

These analytics provide a complementary perspective to traditional dashboards by measuring the intelligence model itself instead of only operational security events.


## MITRE ATT&CK Import

<img width="2048" height="1137" alt="image" src="https://github.com/user-attachments/assets/5ff7ff82-87d3-4bb1-b634-731c12a586af" />


The MITRE ATT&CK Import module enables organizations to ingest the public ATT&CK knowledge base directly into the graph engine. During import, ATT&CK objects are transformed into interconnected graph entities while preserving relationships between techniques, tactics, threat groups, malware, software, mitigations, and defensive controls.

Users can customize the import process by selecting domains, limiting entity counts, including or excluding sub-techniques, and previewing the resulting graph structure before ingestion begins. This flexible import pipeline makes it possible to build lightweight demonstration environments or large-scale enterprise knowledge graphs depending on organizational needs.

By representing MITRE ATT&CK as a graph instead of a traditional relational dataset, the platform unlocks advanced graph analytics, AI reasoning, and contextual relationship discovery across the entire threat intelligence ecosystem.


## OrchiCyb AI Copilot

<img width="2048" height="1142" alt="image" src="https://github.com/user-attachments/assets/4994d5c9-3df2-41d6-a990-790e4a5d0c1b" />

OrchiCyb AI Copilot is an AI-native cybersecurity assistant designed to reason over the complete intelligence graph rather than isolated documents. Leveraging relationships between MITRE ATT&CK techniques, threat actors, malware, campaigns, vulnerabilities, and defensive controls, the Copilot can answer complex cybersecurity questions using contextual knowledge rather than keyword matching.

Analysts can request attack chain generation, explain adversary behavior, identify detection opportunities, recommend mitigations, generate investigation plans, and summarize complex threat intelligence directly within the platform. Every response is grounded in the underlying graph model, allowing AI to produce recommendations that reflect the relationships between entities instead of treating each object independently.

The long-term vision of the Copilot is to become an intelligent cyber operations assistant capable of supporting Security Operations Centers, Threat Hunters, Detection Engineers, Incident Responders, and Cyber Threat Intelligence analysts throughout every stage of the defensive workflow.

---

## Technology

This project explores the combination of:

- Artificial Intelligence
- MITRE ATT&CK®
- Cyber Threat Intelligence (CTI)
- Knowledge Graphs
- Detection Engineering
- Threat Hunting
- Modern UX for Security Operations

---

## Roadmap

- Initial AI ATT&CK platform
- Interactive intelligence dashboards
- AI Copilot
- Knowledge Graph engine
- Detection rule generation
- IOC Analyzer
- Threat Hunting workspace
- Incident Response assistant
- AI-generated security reports

---

## Vision

The long-term vision is to build an AI-native Cyber Threat Intelligence platform where security professionals can interact with cyber knowledge using natural language, intelligent recommendations, and interconnected threat intelligence.

---

## Disclaimer

OrchiCyb AI ATTACK is an independent research project intended for educational, research, and cybersecurity innovation purposes.
MITRE ATT&CK® is a registered trademark of The MITRE Corporation.

---

## License


