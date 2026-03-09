# 🐝 Opencode Swarm Multi-Agent

> *Because one AI is cool… but a whole AI team is cooler.*

Welcome to **Opencode Swarm Multi-Agent**, a swarm of specialized AI agents designed to collaborate like a real software team, powered by [OpenCode AI](https://opencode.ai).

Instead of asking one AI to do everything (and panic halfway through), this project organizes **multiple agents with clear responsibilities**.

Your AI team includes:

🧠 Research
📦 Product
🏗 Architecture
🎨 Design
💻 Engineering (Frontend, Backend, Flutter)
🔍 QA
🚀 DevOps

All coordinated by an **Orchestrator agent** that keeps everyone focused.

Think of it as **an AI startup team living inside your terminal**.

---

## ✨ Why This Exists

Most AI coding workflows look like this:

```
User → AI → Chaos → Hope it works
```

This project proposes something better:

```
User → Orchestrator → Specialized Agents → Structured Output
```

Each agent has **a clearly defined role**.

No confusion.
No "AI trying to do everything".

Just **organized AI teamwork**.

---

## 🧠 The Swarm

Your AI team consists of 10 specialized agents.

| Role            | Agent         | Description                                                                                               |
| --------------- | ------------- | --------------------------------------------------------------------------------------------------------- |
| 🎮 Orchestrator | `orchestrator` | AI Project Manager. Transforms user requests into structured multi-agent execution workflows              |
| 🧠 Research     | `research`     | Senior Technical Researcher. Evaluates technologies, produces comparison tables and recommendations      |
| 📦 Product      | `product`      | Senior Product Manager. Transforms ideas into features, user stories, and acceptance criteria            |
| 🏗 Architecture | `architect`    | Senior Software Architect. Designs system architecture, data flows, scalability and security strategies  |
| 🎨 Design       | `ux-ui`        | Senior UX/UI Designer. Designs user journeys, wireframes, UI components and design systems               |
| 💻 Frontend     | `frontend`     | Senior Angular Developer. Generates components, services, routing and state management (NgRx/RxJS)       |
| 💻 Backend      | `backend`      | Senior Backend Engineer. Generates REST/GraphQL APIs, database schemas and authentication mechanisms     |
| 📱 Mobile       | `flutter`      | Senior Flutter Developer. Generates Flutter apps with clean architecture and Riverpod state management   |
| 🚀 DevOps       | `devops`       | DevOps Engineer. Generates Dockerfiles, docker-compose, CI/CD pipelines and Ansible playbooks            |
| 🔍 QA           | `qa`           | Quality Assurance Engineer. Validates outputs, defines testing strategies and triggers improvement loops |

---

## 📂 Repository Structure

```
opencode-swarm-multi-agent/
├── agents/
│   ├── orchestrator.md    # Primary agent - coordinates the swarm
│   ├── architect.md       # System architecture design
│   ├── backend.md         # Backend/API development
│   ├── devops.md          # Infrastructure & CI/CD
│   ├── flutter.md         # Mobile app development
│   ├── frontend.md        # Web frontend development
│   ├── product.md         # Product management
│   ├── qa.md              # Quality assurance
│   ├── research.md        # Technical research
│   └── ux-ui.md           # UX/UI design
├── opencode.json          # OpenCode AI configuration
├── package.json           # Dependencies
└── README.md
```

---

## 🧬 How the Swarm Works

A typical development workflow looks like this:

1️⃣ **Research Agent**
"Let's understand the problem first."

2️⃣ **Product Agent**
"What are we actually building?"

3️⃣ **Architect Agent**
"Here's the system design."

4️⃣ **UX/UI Agent**
"Let's make it usable by humans."

5️⃣ **Engineering Agents** (Frontend, Backend, Flutter)
"Time to write code."

6️⃣ **QA Agent**
"Did anyone test this?"

7️⃣ **DevOps Agent**
"Let's deploy this thing."

All coordinated by the **Orchestrator Agent**.

---

## 📚 Required Project Context

Before producing any output, **agents must check if the project contains a `context/` folder.**

If present, agents **must read the following files**:

```
context/project.md
context/stack.md
context/architecture.md
context/coding-rules.md
```

These files define:

* Project purpose
* Selected technology stack
* Architecture constraints
* Coding standards

Agents **must adapt their outputs to this information**.

If context files are missing, the agent **must inform the Orchestrator**.

Agents must **never invent project constraints**.

In short:

> No hallucinated architecture.
> No imaginary tech stack.
> No "I think the project uses Kubernetes".

Only what the context says.

---

## 🕹 How To Use

### Prerequisites

- [OpenCode AI](https://opencode.ai) installed
- Node.js / Bun runtime

### Installation

Clone the repository:

```bash
git clone https://github.com/aives81/opencode-swarm-multi-agent.git
cd opencode-swarm-multi-agent
```

Install dependencies:

```bash
bun install
# or
npm install
```

### Usage

1️⃣ Start OpenCode in your project directory
2️⃣ The **Orchestrator agent** is the primary agent and will coordinate the swarm
3️⃣ Provide a project goal
4️⃣ Let the swarm collaborate 🐝

Example prompt:

```
Build a SaaS project management platform for indie developers.
```

The orchestrator will then **delegate work to the appropriate agents**.

### Agent Tools

Each agent has access to specific tools defined in `opencode.json`:

| Tool       | Description                          |
| ---------- | ------------------------------------ |
| `write`    | Create new files                     |
| `edit`     | Modify existing files                |
| `bash`     | Execute shell commands               |
| `glob`     | Search files by pattern              |
| `grep`     | Search content in files              |
| `read`     | Read file contents                   |
| `task`     | Delegate to other agents             |
| `webfetch` | Fetch web resources (Research only)  |

---

## 🧩 Customizing the Swarm

You can extend the swarm by adding new agents.

1. Create a new agent file in `agents/` (e.g., `security.md`)
2. Add the agent configuration to `opencode.json`

Example ideas:

```
agents/security.md
agents/ai.md
agents/data-science.md
agents/growth.md
```

Because every team eventually needs:

🛡 A security expert
📊 A data nerd
📈 A growth hacker

---

## 🧠 Philosophy

This project follows a simple idea:

> AI should collaborate like humans do.

Specialization beats generalization.

Even AI should **stay in its lane**.

---

## 🚀 Use Cases

This swarm is perfect for:

✅ AI coding workflows
✅ Multi-agent experimentation
✅ Autonomous development teams
✅ Structured prompt engineering
✅ AI-driven software architecture

Or simply because **you like watching AI argue about architecture**.

---

## 🤝 Contributing

Contributions are welcome!

Ideas include:

* New agents
* Improved workflows
* Swarm orchestration experiments
* Integrations with AI frameworks

Pull requests are welcome.

Even weird ones.

Especially weird ones.

---

## 📜 License

MIT License

Do whatever you want with it.

Just don't blame the swarm if it becomes self-aware and starts scheduling sprint meetings without you 🤖
