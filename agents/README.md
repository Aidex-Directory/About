# Agentic Systems Sandbox: Agents for Transparent, Interoperable, and Collaborative Organizations

Welcome to the **Agentic Systems Sandbox**! This repository contains a suite of open source agents designed to help organizations, from small NGOs to large networks, experiment with safe, composable, and transparent agentic systems. Here, organizations can start small, build practical knowhow, and prepare for a future shaped by collaborative AI.

## 🤖 Overview: The Suite of Agents

### 1. About Agent
- **Function:** Acts as the organization’s digital ambassador, answering questions based on the official mission statement and publicly available information.
- **Purpose:** Provides an easy, low-risk entry point for experimenting with agent technology.

### 2. Orchestrator Agent
- **Function:** Serves as the central coordinator. Receives incoming requests and routes them to the appropriate specialized agent (About Agent, IATI Org Agent, IATI Activities Agent, Micro-Payments Agent, etc.).
- **Purpose:** Enables modular system design, allowing organizations to add or upgrade services without restructuring their agent setup.

### 3. IATI Org Agent
- **Function:** Returns detailed organizational information by parsing the IATI Org XML file submitted by the organization to the International Aid Transparency Initiative (IATI).
- **Purpose:** Promotes transparency and data interoperability using a key sector standard.

### 4. IATI Activities Agent
- **Function:** Exposes comprehensive project or activity information based on the organization’s IATI Activity XML files.
- **Purpose:** Makes project portfolios discoverable and machine-readable—enabling evidence-based analysis and reporting.

### 5. Micro-Payments Agent
- **Function:** Facilitates micro-transactions—enabling agents to charge for certain services/data and pay other agents or organizations for theirs.
- **Purpose:** Lets organizations prototype agent-powered, pay-per-use models and incentivize open contributions safely.

## 🕸️ How the Agents Work Together

These agents are designed for **modularity and interoperability**, making it easy for organizations to test any agent by itself or combine them into more complex workflows using the Orchestration Agent.

**Example flow:**
1. A user queries the Orchestration Agent about the organization’s mission and most recent project.
2. The Orchestration Agent routes “mission” to the About Agent and “project info” to the IATI Activities Agent.
3. The user requests a premium report—the Orchestration Agent invokes the Micro-Payments Agent to handle billing before releasing the data.

This architecture promotes **composability**: new features, data sources, or payment models can be added as new agents or modules.

## 🚀 Why Start with These Agents?

- **Safe & Simplified:**  
  Each agent is small, focused, and low risk—perfect for organizations new to agentic systems.

- **Transparency & Trust:**  
  Built on open data sources (like IATI) and clear rules, fostering organizational transparency and sector interoperability.

- **Flexible Experimentation:**  
  Organizations can start small—pick just one agent—and grow as their comfort and needs evolve.

- **Capacity Building:**  
  By testing these systems, staff and volunteers learn the foundations of agentic AI, setting the stage for more ambitious digital transformation.

## 🤝 Collaboration and Volunteer Engagement

This project is also a **hub for collaborative learning and co-creation**:
- Organizations can **work with volunteers** from the open source and humanitarian tech community to deploy, customize, or extend agents.
- The modular codebase ensures easy onboarding for new contributors and fast experimentation for organizations of all sizes.
- Contributions are welcome—from bug fixes to new agent ideas and documentation.

## 🧩 Getting Started

1. Clone this repository and browse each agent’s README for setup instructions.
2. Deploy an agent locally or in the cloud; start with the About Agent for the simplest on-ramp.
3. Experiment! Chain together agents using the Orchestration Agent. Explore making and receiving micro-payments.  
4. Engage with the community—open issues, suggest features, and connect with like-minded organizations and volunteers.

---

*Build, Learn, Collaborate—welcome to the Agentic Systems Playground, where organizations and volunteers shape the future of transparent, interoperable, and agent-powered public good!*
