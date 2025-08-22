# Agentic Systems Sandbox: Transparent, Interoperable, and Collaborative Agents for Organizations

Welcome to the **Agentic Systems Sandbox**! This repository contains a suite of open source agents designed to help organizations, from small NGOs to large networks, experiment with safe, composable, and transparent agentic systems. Here, organizations can start small, build practical knowhow, and prepare for a future shaped by collaborative AI.

## 🤖 Overview: The Suite of Agents

### 1. [About Agent](https://github.com/Aidex-Directory/About/blob/main/agents/About-Org.md)
- **Function:** Acts as the organization’s digital ambassador, answering questions based on the official mission statement and publicly available information.
- **Purpose:** Provides an easy, low-risk entry point for experimenting with agent technology.

### 2. [Orchestrator Agent](https://github.com/Aidex-Directory/About/blob/main/agents/Orchestrator.md)
- **Function:** Serves as the central coordinator. Receives incoming requests and routes them to the appropriate specialized agent (About Agent, IATI Org Agent, IATI Activities Agent, Micro-Payments Agent, etc.).
- **Purpose:** Enables modular system design, allowing organizations to add or upgrade services without restructuring their agent setup.

### 3. [IATI Org Agent](https://github.com/Aidex-Directory/About/blob/main/agents/IATI-Org.md)
- **Function:** Returns detailed organizational information by parsing the IATI Org XML file submitted by the organization to the International Aid Transparency Initiative (IATI).
- **Purpose:** Promotes transparency and data interoperability using a key sector standard.

### 4. [IATI Activities Agent](https://github.com/Aidex-Directory/About/blob/main/agents/IATI-Activities.md)
- **Function:** Exposes comprehensive project or activity information based on the organization’s IATI Activity XML files.
- **Purpose:** Makes project portfolios discoverable and machine-readable, enabling evidence-based analysis and reporting.

### 5. [Micro-Payments Agent](https://github.com/Aidex-Directory/About/blob/main/agents/Micro-Payments.md)
- **Function:** Facilitates micro-transactions, enabling agents to charge for certain services/data and pay other agents or organizations for theirs.
- **Purpose:** Lets organizations prototype agent-powered, pay-per-use models and incentivize open contributions safely.

### 6. [Papers Parser Agent](https://github.com/Aidex-Directory/About/blob/main/agents/Papers-Parser.md)
- **Role:** Parses PDF documents and answers both standardized and custom questions about their content. Enables query monitoring and parser/model improvement.
- **Purpose:** Unlocks insights from reports and papers, supports custom document parsing, and advances transparency and knowledge management.

### 7. Search Visibility & Evaluation [AEO Agent](https://github.com/Aidex-Directory/About/blob/main/agents/AEO-Agent.md)
- **Role:** Monitors, tests, and optimizes how an organization’s content appears and is used by modern AI search engines; enables A/B testing and benchmarking of agentic vs. external search outputs.
- **Purpose:** Ensures accuracy, discoverability, and fidelity of information across the evolving AI-driven digital ecosystem.

## 🕸️ How the Agents Work Together

These agents are designed for **modularity and interoperability**, making it easy for organizations to test any agent by itself or combine them into more complex workflows using the Orchestration Agent.

**Example workflow:**
1. A user asks about the organization’s mission and current activities.
2. The Orchestration Agent sends the mission query to the About Agent, and project queries to the IATI Activities Agent.
3. If the user requests a detailed report from a research paper, the Orchestration Agent invokes the Papers Agent for answers.
4. Accessing premium analyses or reports? The Orchestration Agent and Micro-Payments Agent handle payment and release the requested information.
5. Employ the Search Visibility & Evaluation Agent to continually monitor how all outputs are represented online, fine-tuning web, agent, and content strategy over time.

This flexible design helps organizations move from simple experiments to production-grade, federated agentic systems.

This architecture promotes **composability**: new features, data sources, or payment models can be added as new agents or modules.

## 🚀 Why Start with These Agents?

- **Safe & Simplified:**  
  Each agent is small, focused, and low risk—perfect for organizations new to agentic systems.

- **Transparency & Trust:**  
  Built on open data sources (like IATI) and clear rules, fostering organizational transparency and sector interoperability.

- **Flexible Experimentation:**  
  Organizations can start small—pick just one agent—and grow as their comfort and needs evolve.

- **Real Organizational Value:**  
  Answer questions, serve data, manage papers, or facilitate payments—all automated.

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
