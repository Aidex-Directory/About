# About-Org Agent

About Agent: Open Source AI For Organizational Mission Sharing

The **About Agent** is an open source project that enables humanitarian, nonprofit, and mission-driven organizations to share their mission statements and core information via lightweight, safe, and composable AI agents. These agents can explain what an organization does—acting as digital ambassadors that provide clear, trustworthy facts to humans or other agents. The About Agent can be deployed as a simple API, a cached script, or a component in multi-agent systems.

## 🚀 Why About Agent?

Many organizations want to experiment with agentic AI but lack safe, practical starting points. The About Agent is:

- **Minimal and Safe:**  
  It only shares public, pre-approved information about the organization (e.g., mission statement, programs). No risky actions, no sensitive data, and no autonomy beyond explanation.

- **Composable and Extensible:**  
  Each About Agent instance can interoperate in a broader network—enabling federated directories, automated matching of services, and more.

- **Open and Accessible:**  
  Designed for simplicity—deploy as a cloud API, a local script, or even as a chatbot extension. Minimal setup, maximum transparency.

## 💡 Example Use Cases

- **Humanitarian Coordination:**  
  Agents exchange mission data to help map out “who does what, where.”
- **Volunteer Platforms:**  
  Automate organization profiling and onboarding in discovery portals.
- **Federated Search:**  
  Networked About Agents enable distributed, up-to-date directories of nonprofit activities.

## 🛠️ API Endpoints

| Endpoint      | Method | Description                     |
|---------------|--------|---------------------------------|
| `/about`      | GET    | Get the organization's mission  |
| `/contact`    | GET    | Get contact information         |
| `/leadership` | GET    | List leadership profiles (optional) |

_All responses are JSON._

## 👩‍💻 How it Works

- Reads your mission and contact info from YAML or your website
- Responds to queries with plain explanations—no internet needed (cached) or via REST API (hosted)
- Plug-and-play: drop in your org info and launch your own About Agent

## 🌍 Networked Mode

Deploy About Agents across many organizations to create a distributed, interoperable knowledge network—organizations own their information, but anyone (or any agent) can find out who does what, instantly and reliably.

## 🧠 Learn More

Under construction

---

*The About Agent project brings trustworthy, transparent AI into the hands of organizations working for good everywhere. Simple, safe, open source, and built for collaboration.*
