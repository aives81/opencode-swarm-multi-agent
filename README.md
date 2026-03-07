# 🐝 Opencode Swarm Multi-Agent

> *Because one AI is cool… but a whole AI team is cooler.*

Welcome to **Opencode Swarm Multi-Agent**, a swarm of specialized AI agents designed to collaborate like a real software team.

Instead of asking one AI to do everything (and panic halfway through), this project organizes **multiple agents with clear responsibilities**.

Your AI team includes:

🧠 research
📦 product
🏗 architecture
🎨 design
💻 engineering
🔍 QA
🚀 DevOps

All coordinated by an **Orchestrator agent** that keeps everyone focused.

Think of it as **an AI startup team living inside your prompts**.

---

# ✨ Why This Exists

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

# 🧠 The Swarm

Your AI team consists of multiple specialized agents.

| Role            | Agent             | What they do                                     |
| --------------- | ----------------- | ------------------------------------------------ |
| 🧠 Research     | `research-agent`  | Investigates technologies, tools and competitors |
| 📦 Product      | `product-agent`   | Defines product goals, features and scope        |
| 🏗 Architecture | `architect-agent` | Designs system architecture                      |
| 🎨 Design       | `ux-ui-agent`     | Creates UX flows and UI ideas                    |
| 💻 Engineering  | `frontend-agent`  | Builds web interfaces                            |
| 💻 Engineering  | `backend-agent`   | Builds APIs and backend systems                  |
| 📱 Engineering  | `flutter-agent`   | Builds cross-platform mobile apps                |
| 🚀 DevOps       | `devops-agent`    | Infrastructure, CI/CD and deployment             |
| 🔍 QA           | `qa-agent`        | Testing and quality control                      |
| 🎮 Orchestrator | `agent.md`        | Coordinates the entire swarm                     |

---

# 📂 Repository Structure

```
opencode-swarm-multi-agent
│
├── swarm
│   ├── core-agents
│   │   ├── architect-agent.md
│   │   ├── product-agent.md
│   │   └── research-agent.md
│   │
│   ├── design-agents
│   │   └── ux-ui-agent.md
│   │
│   ├── engineering-agents
│   │   ├── backend-agent.md
│   │   ├── devops-agent.md
│   │   ├── flutter-agent.md
│   │   └── frontend-agent.md
│   │
│   ├── orchestrator
│   │   └── agent.md
│   │
│   └── quality-agents
│       └── qa-agent.md
│
└── system
    └── swarm-rules.md
```

---

# 🧬 How the Swarm Works

A typical development workflow looks like this:

1️⃣ **Research Agent**
"Let's understand the problem first."

2️⃣ **Product Agent**
"What are we actually building?"

3️⃣ **Architect Agent**
"Here's the system design."

4️⃣ **UX/UI Agent**
"Let's make it usable by humans."

5️⃣ **Engineering Agents**
"Time to write code."

6️⃣ **QA Agent**
"Did anyone test this?"

7️⃣ **DevOps Agent**
"Let's deploy this thing."

All coordinated by the **Orchestrator Agent**.

---

# 📚 Required Project Context

Before producing any output, **agents must check if the project contains a `context/` folder.**

If present, agents **must read the following files**:

```
context/project.md
context/stack.md
context/architecture.md
context/coding-rules.md
```

These files define:

* project purpose
* selected technology stack
* architecture constraints
* coding standards

Agents **must adapt their outputs to this information**.

If context files are missing, the agent **must inform the Orchestrator**.

Agents must **never invent project constraints**.

In short:

> No hallucinated architecture.
> No imaginary tech stack.
> No "I think the project uses Kubernetes".

Only what the context says.

---

# 🕹 How To Use

Clone the repository:

```bash
git clone https://github.com/your-username/opencode-swarm-multi-agent.git
```

Then:

1️⃣ Load the agents into your AI orchestration system
2️⃣ Start with the **Orchestrator agent**
3️⃣ Provide a project goal
4️⃣ Let the swarm collaborate 🐝

Example prompt:

```
Build a SaaS project management platform for indie developers.
```

The orchestrator will then **delegate work to the appropriate agents**.

---

# 🧩 Customizing the Swarm

You can extend the swarm by adding new agents.

Example ideas:

```
security-agent.md
ai-agent.md
data-science-agent.md
growth-agent.md
```

Because every team eventually needs:

🛡 a security expert
📊 a data nerd
📈 a growth hacker

---

# 🧠 Philosophy

This project follows a simple idea:

> AI should collaborate like humans do.

Specialization beats generalization.

Even AI should **stay in its lane**.

---

# ⚠️ Important Rule

All agents must follow the swarm rules defined here:

```
system/swarm-rules.md
```

This file defines:

* collaboration rules
* agent responsibilities
* workflow constraints

Breaking the swarm rules may result in:

🐝 angry bees
💥 architectural chaos
☕ the orchestrator needing coffee

---

# 🚀 Use Cases

This swarm is perfect for:

✅ AI coding workflows
✅ multi-agent experimentation
✅ autonomous development teams
✅ structured prompt engineering
✅ AI-driven software architecture

Or simply because **you like watching AI argue about architecture**.

---

# 🤝 Contributing

Contributions are welcome!

Ideas include:

* new agents
* improved workflows
* swarm orchestration experiments
* integrations with AI frameworks

Pull requests are welcome.

Even weird ones.

Especially weird ones.

---

# 📜 License

MIT License

Do whatever you want with it.

Just don't blame the swarm if it becomes self-aware and starts scheduling sprint meetings without you 🤖
