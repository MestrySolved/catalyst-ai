# Project Catalyst: Agentic GKE Migration & Governance 🚀
**Powered by Gemini Enterprise Agent Platform (Vertex AI)**

## 📖 The Origin Story
During a large-scale enterprise cloud migration in the **Mumbai (asia-south1)** region, I managed the transition of complex workloads across 5 critical namespaces. While the migration was successful, the process was heavily reliant on manual "check-and-verify" steps, static Terraform scripts, and constant monitoring of infrastructure drift. 

Recognizing that manual orchestration is the bottleneck of modern scaling, I built **Project Catalyst**. It transforms the "boring," error-prone manual steps of migration into an autonomous, reasoning-based workflow.

Project Catalyst is a code-first, multi-agent framework designed to automate and govern large-scale enterprise migrations in the **GCP Mumbai (asia-south1)** region. It moves beyond static scripts into **Autonomous SRE**, where agents reason through infrastructure state to perform self-healing and automated deployments.

## 🌟 Key Pillars
* **Autonomous Orchestration:** Uses Gemini 1.5 Pro via the **Agent Development Kit (ADK)** to triage migration requests.
* **Self-Healing Infrastructure:** Integrated with **Dynatrace SLIs** to trigger autonomous remediation for latency and availability breaches.
* **Enterprise Governance:** Implements a "Human-in-the-Loop" (HiTL) Interactive Hub via Jupyter for safe, governed execution.
* **Regional Optimization:** Purpose-built for the high-demand Mumbai region, ensuring low-latency and localized compliance.

## 🛠️ Technology Stack
* **Orchestration:** Gemini Enterprise Agent Platform (ADK).
* **Cloud:** Google Kubernetes Engine (GKE) & Google Cloud Platform.
* **CI/CD:** Codefresh Parameterized Pipelines.
* **Observability:** Dynatrace Performance Monitoring.

## 📂 Architecture Overview
- `/agents`: Role-based definitions for Root, Technical, and SRE Agents.
- `/blueprints`: Parameterized K8s and Codefresh templates.
- `/metadata`: Enterprise-grade network and environment configuration.
- `/notebooks`: The 'Migration Hub' — your interactive command center.
