![NANDA Sub-directory](https://github.com/Aidex-Directory/About/blob/main/media/AidExchange1000.png)

The **Aid Exchange Directory** ([aidex.directory](https://aidex.directory/)) is an experimental NANDA Index sub-directory specifically developed for humanitarian aid organizations and their partners to use to register their AI agents. The sub-directory is designed to be a primary gateway for aid organizations to interface with the broader Project NANDA ecosystem. The gateway also enables aid organizations to get involved in project NANDA as a working group. 

## Project NANDA

> "Project [NANDA](https://nanda.media.mit.edu/) (Networked Agents and Decentralized AI) is an ambitious MIT initiative developing the foundational infrastructure for a true "Internet of AI Agents." Just as the early web required DNS and HTTP protocols to scale, NANDA is creating the essential building blocks to support trillions of autonomous AI agents that can discover, verify, and collaborate in real-time across decentralized networks. The project envisions specialized AI agents collaborating across a decentralized architecture, where each agent performs discrete functions while communicating seamlessly, navigating autonomously, socializing, learning, earning and transacting on our behalf."

[Source: MIT NANDA: Algorithms to Unlock The Internet of AI Agents](https://www.media.mit.edu/projects/mit-nanda/overview/)

NANDA's technical architecture establishes a comprehensive infrastructure for distributed agent intelligence, leveraging and extending existing frameworks like Anthropic's Model Context Protocol (MCP) and Google's Agent2Agent (A2A) protocol. At its core, the system features a decentralized registry that functions as a DNS for agents, facilitating their discovery, authentication, and verifiable interactions across the entire network. This is complemented by advanced agent-to-agent communication protocols that not only provide the foundational language for AI interaction but also include sophisticated mechanisms for agents to locate one another within the network. Furthermore, these protocols enable the querying of distributed knowledge spread across different agent networks, creating a seamless web of interconnected intelligence.

To ensure the integrity and trustworthiness of the agent network, NANDA incorporates robust security and verification protocols. These measures are designed to create a secure environment for all agent interactions by implementing verifiable agent-to-agent exchange accountability. This includes native systems for identity, traceability, and the recording of behavioral patterns, which together ensure that all interactions are transparent and reliable. Supporting this secure framework is a comprehensive developer ecosystem, which provides the necessary tools and services for building upon the NANDA platform. This ecosystem includes a registry of agents, access to various resources and tools, a database of agentic interactions for analysis and learning, and third-party integrations facilitated by both client and server software development kits (SDKs).

## NANDA Index

The **NANDA Index** is an open agent registry for discovering and managing autonomous agents. Agent owner/developers use the registry to publish agent JSON facts files and agent metadata facilitating agent-to-agent discovery, authentication and interaction. Project NANDA's vision is a decentralized agentic web linking AI agents and interoperable public and private agent fact registries, each established and managed by different organizations and initiatives.

## Aid Exchange Directory

![Aidex Logo](https://github.com/Aidex-Directory/About/blob/main/media/Aidex_Right_Small.png)

The **aidex.directory** is a NANDA Index sub-directory that is being built specifically to address the needs of the global humanitarian aid community. It establishes a dedicated NANDA Indext sub-directory for humanitarian organizations and their partners.

Project NANDA leverages and extends existing frameworks like Anthropic's Model Context Protocol (MCP) and Google's Agent2Agent (A2A) protocol. "The aidex.directory initiative will enable members to integrate concepts and standards from these and other projects, notably project [LOKA](https://arxiv.org/abs/2504.10915) affiliated with Carnegie Mellon University, directly into their agents and agent documentation.

This initiative provides a tailored platform for these organizations to register their specialized AI agents, incorporating additional metadata fields critical for the humanitarian context, such as operational sector (e.g., health, logistics, protection), geographic focus, language capabilities, and adherence to humanitarian principles and data privacy standards. Beyond simply acting as a registry, this sub-directory is designed to be the primary gateway for aid organizations to interface with the broader Project NANDA ecosystem. It offers a structured on-ramp for them to connect their agents, collaborate on shared challenges, and actively contribute to the development of a distributed AI infrastructure that is safe, effective, and ethically aligned with the mission of serving vulnerable populations.

### List39

The aidex.directory builds on the NANDA Index and on [List39](https://list39.org/) which is another registry. **List39** is a vendor-neutral registry enabling agent discovery, capability declaration, and trust establishment in distributed agentic systems. For reference, the List's fields are as follows:

| List39 Fields  | Description |
| ------------- | ------------- |
| Username  | This will be your agent's public URL: /@username.json  |
| Agent Name  | My AI agent  |
| Label  | My AI agent  |
| Description  | Describe what your agent does  |
| Version  | Version number  |
| Jurisdiction  | Country  |
| Document URL  | https://... address  |
| Document Template  | https://... address  |
| Provider Name  | Your organization  |
| Provider URL  | https://... address  |
| Static endpoints  | API endpoints  |

Aid organizations involved in the aidex.directory initiative will disscuss and collaboratively develop agent metadata fields and agent fact sheet templates for organizations to use. Information fields will incorporate lessons learned from humanitarian open data sharing initiatives such as [IATI](https://iatistandard.org/en/), managed by the International Aid Transparency Initiative.

### File Registry and Storage

To enhance collaboration, the aidex.directory uniquely provides integrated storage for both public and private data files. This shared repository enables organizations to more easily conduct foundational, collaborative tests on core functions like agent-to-agent interaction and knowledge exchange.

## Research Projects

Initially, the Aid Exchange project will focus on helping aid organizations develop rudamentary agents, register these through the NANDA Index via the aidex.directory and experiment with agent-to-agent interaction. Follow-up research will examine critical facets of agentic systems, focusing on three key areas: the internal logic of an agent (reflection and reasoning, identity, and wallets); the external dynamics of collaboration, human interaction, and coordination protocols; and the overarching ethical considerations that guide development.

### Basic Projects

* HTML Parsing Agent: Aid organizations rely on website information to inform AI search engines about their organizations, missions and operations. The project will guide organizations through generating facts files on their organizations and setting up their first agents able to parse and relay this html information to other agents. The project would help organizations campare AI search engine outputs to AI agent outputs and carry out comparative testing and A/B testing.
* XML Data Parsing Agent: Aid organizations commonly use open data sharing frameworks to make granular information about their organizations and activities accessible to machine applications. The project will guide organizations through generating informational XML files and setting up agents able to parse and relay information found in XML files to other agents. 
* Transaction Agent: The project will help organizations set up simplified agents able to make and receive micro-transactions. 
* XML Reporting Agent: The project will help organizations set up agents able to generate transaction logs and report transactions in XML.

## Get Involve

A host of private secotr technology companies, academic institutions, investors and open source communities are involved in project NANDA. For humanitarina aid organizations wishing to get involved or following the initiative contact: team(at)humanitarianai.org
