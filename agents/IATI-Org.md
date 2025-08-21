# IATI-Org Agent

The **IATI Org Agent** is an open source agent designed to help organizations expose and share rich organizational data contained in their IATI (International Aid Transparency Initiative) Org XML files. This agent makes it easy for organizations to provide machine-readable, standards-based information to the public, partners, and other agents or systems, enhancing transparency and discoverability in the international development and humanitarian sectors.

## 🌍 What is IATI Org Data?

The **IATI Org XML** file is a core part of the IATI standard, containing structured details about an organization’s identity, registration, classification, locations, and more. Publishing this data enables interoperability, trust, and automation in aid and development information systems.

## 🤖 What Does the IATI Org Agent Do?

- **Parses organization’s official IATI Org XML file**
- Responds to requests for specific fields (e.g., name, identifier, countries, registration, types, contact info, etc.)
- Delivers structured responses via API or local queries
- Designed for composability—can be integrated with an Orchestration Agent and other org agents

## 💡 Example Use Cases

- Powering organization profile widgets on websites or dashboards
- Enabling federated discovery portals for aid agencies
- Answering automated or human queries about registered IATI organizations
- Supporting transparency, compliance, and data-sharing commitments

## 🛠️ API Endpoints

| Endpoint           | Method | Description                                    |
|--------------------|--------|------------------------------------------------|
| `/org`             | GET    | Returns core organizational identity info      |
| `/org/contacts`    | GET    | Returns all available contact information      |
| `/org/locations`   | GET    | Lists registered countries/regions             |
| `/org/registration`| GET    | Provides registration and identifier details   |
| `/org/raw`         | GET    | Returns the full raw Org XML (optional)        |

_All responses are JSON unless otherwise specified._

## 👩‍💻 How it Works

- Loads and parses your IATI Org XML file at startup.
- Matches incoming requests to the proper fields/data in the XML.
- Provides standardized, precise answers drawn directly from your official data.
- Easily embeddable in larger agent architectures via an Orchestration Agent.

## 🧠 Learn More

- [IATI Official Documentation](https://iatistandard.org)
- [IATI Org XML Schema](https://iatistandard.org/en/iati-standard/203/activity-standard/iati-activities/iati-organisation/)
