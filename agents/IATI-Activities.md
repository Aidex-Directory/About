# IATI Activities Agent

The **IATI Activities Agent** is an open source AI agent that enables organizations to expose and share comprehensive data from their IATI (International Aid Transparency Initiative) Activity XML files. This agent provides structured, standards-compliant access to the details of an organization’s aid activities—improving transparency, discoverability, and data interoperability across the humanitarian and development sectors.

## 🌍 What is IATI Activity Data?

**IATI Activity XML** files are the heart of IATI reporting, containing rich, structured information about an organization’s individual aid and development projects—including objectives, sectors, budgets, participating organizations, results, locations, and timelines. Publishing this data supports global transparency, project coordination, and evidence-based decision-making.

## 🤖 What Does the IATI Activities Agent Do?

- Parses an organization’s official IATI Activity XML files
- Responds to detailed queries about projects, timelines, objectives, locations, finances, results, and more
- Delivers structured, machine-readable outputs via API or local queries
- Integrates seamlessly with other agents (such as an Orchestration Agent or IATI Org Agent)

## 💡 Example Use Cases

- Powering public dashboards displaying active aid or development projects
- Supporting data aggregation and analysis for consortia or donors
- Enabling automated, up-to-date project listings on organizational websites
- Providing detailed answers about where and how aid is being delivered

## 🛠️ API Endpoints

| Endpoint                | Method | Description                                      |
|-------------------------|--------|--------------------------------------------------|
| `/activities`           | GET    | Returns a list of all activities/projects        |
| `/activities/{id}`      | GET    | Returns full details for a specific activity     |
| `/activities/sectors`   | GET    | Lists sectors/themes covered by all activities   |
| `/activities/locations` | GET    | Lists locations of activities                    |
| `/activities/results`   | GET    | Provides high-level results/outcomes data        |
| `/activities/raw`       | GET    | Returns the raw Activity XML (optional)          |

_All responses are in JSON unless otherwise specified._

## 👩‍💻 How it Works

- Loads and parses one or many IATI Activity XML files at startup or on request
- Extracts key fields like project titles, descriptions, budgets, timelines, sectors, outcomes, locations, and more
- Answers detailed, standards-based queries about an organization’s activities
- Designed for easy inclusion in a wider agent ecosystem, managed via an Orchestration Agent

## 🧠 Learn More

- [IATI Official Documentation](https://iatistandard.org)
- [IATI Activity XML Schema](https://iatistandard.org/en/iati-standard/203/activity-standard/iati-activities/iati-activity/)

---

*The IATI Activities Agent empowers organizations to share the story and impact of their work—openly, clearly, and in alignment with global transparency standards.*
