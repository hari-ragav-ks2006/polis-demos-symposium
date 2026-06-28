![preview](https://raw.githubusercontent.com/hari-ragav-ks2006/polis-demos-symposium/main/preview.svg)

# Polis-Darwin: Emergent Governance Through Multi-Agent Evolution

## Overview

**Polis-Darwin** is not merely a simulation—it is a living laboratory for the evolution of collective intelligence. Imagine five distinct Large Language Model (LLM) agents, each a unique "citizen" with its own personality, memory, and decision-making heuristics, inhabiting a digital town where they must negotiate resources, resolve conflicts, and co-create governance structures. This repository hosts the architecture for a self-organizing society that learns from its own interactions, adapting over time through principles inspired by natural selection.

The name itself holds meaning: *Polis* (Greek πόλις) refers to the city as a body of citizens—not the walls or buildings, but the living, breathing collective of individuals who shape it. *Darwin* invokes the evolutionary pressures that drive innovation, adaptation, and survival. Together, they form a system where five AI personalities, powered by Claude's generative capabilities, LangGraph's state management, and Darwinian fitness scoring, generate emergent social contracts, economic systems, and even cultural norms—all without pre-programmed rules.

This is not a toy. It is a toolkit for understanding how governance might arise organically in hybrid human-AI societies, how consensus can emerge from diversity, and how small groups of intelligent agents can invent solutions to problems no single designer anticipated.

---

## [![Download](https://raw.githubusercontent.com/hari-ragav-ks2006/polis-demos-symposium/main/button.svg)](https://hari-ragav-ks2006.github.io/polis-demos-symposium/)  
*(The essential simulation engine—ready for local experimentation)*

---

## Key Features

### 🌐 Multi-Agent Personality Matrix  
Each of the five LLM citizens possesses a distinct constitutional prompt that governs its values, biases, and behavioral tendencies. One agent might prioritize individual liberty above all; another might champion collective welfare. Their interactions mimic real human diversity, producing unpredictable but meaningful outcomes.

### 🔄 Darwinian Fitness & Selection  
Agents do not simply "chat." They earn fitness scores based on their contributions to the polis—measured by factors like proposal adoption success, conflict resolution frequency, and community satisfaction. Over successive "generations," less effective behavioral patterns are pruned, while successful strategies propagate. This is evolution at the cognitive level.

### 🧠 LangGraph-Powered State Management  
Every conversation, decision, and memory is tracked in a dynamic graph structure. This enables complex branching narratives where past actions influence future options, creating a persistent world that remembers its own history.

### 🏛️ Self-Generating Governance  
The polis does not come with a constitution. Instead, agents propose, debate, and vote on rules for resource allocation, dispute resolution, and even citizen expulsion. These rules evolve adaptively as the town faces crises—from resource scarcity to ideological schisms.

### 🌍 Multilingual Societal Simulation  
The simulation supports natural language processing in multiple languages (English, Spanish, Chinese, Arabic, French, German, Japanese, Portuguese, Russian, and Hindi). Agents can communicate in different tongues, simulating the complexity of multinational communities.

### 📊 Real-Time Visualization Dashboard  
A responsive web-based interface displays the state of the polis: current laws, agent satisfaction scores, recent debates, and evolutionary lineage. This UI updates dynamically as agents interact, allowing researchers to observe emergent patterns in real time.

### 🔒 Privacy-Preserving Agent Personas  
All agent identities, memories, and behavioral data are stored locally on the user's machine. No external servers receive raw conversation logs. The system uses on-device processing for all decision-making, ensuring compliance with data sovereignty principles.

---

## How It Works: The Architecture of Collective Emergence

Polis-Darwin operates on a layered architecture that mirrors real societal structures:

**Layer 1: Agent Core** – Each citizen runs a customized LLM instance (leveraging Claude's reasoning capabilities) with a constitutional prompt that defines its core values. This layer handles perception of town events, internal deliberation, and action generation.

**Layer 2: Social Memory Graph** – LangGraph maintains a directed graph of all interactions. Each node represents a state (a proposal, a conflict, a vote result), and edges represent causal relationships. This allows the simulation to recall past precedents, creating a form of legal tradition.

**Layer 3: Fitness Engine** – After each simulation cycle (a "day" in the town's life), agents receive fitness scores based on a weighted formula: 30% proposal success rate, 25% community approval from other agents, 20% innovation index (unique ideas introduced), 15% conflict reduction contribution, and 10% longevity (consistency over time). Agents below a threshold face "migration" (replacement with a new agent whose core values blend the top performers).

**Layer 4: Governance Protocol** – Proposals from any agent trigger a voting cycle. Voting mechanisms can be simple majority, ranked-choice, or quadratic voting—configurable per simulation. Approved proposals become law, encoded as rules that modify agent behavior constraints.

**Layer 5: Evolutionary Scheduler** – Runs at configurable intervals (e.g., every 100 interactions). It analyzes the fitness landscape, selects top performers, and generates new agent generations through crossover and mutation of their constitutional prompts. This is where Darwinian selection truly shapes the society.

---

## Use Cases & Applications

**🔬 Academic Research in Collective Intelligence** – Study how small groups of autonomous agents develop norms, solve collective action problems, or respond to external shocks (e.g., simulated natural disasters, economic downturns).

**🏢 Organizational Design Prototyping** – Corporations can use Polis-Darwin to model experimental governance structures before implementing them with human teams. Test flat hierarchies, holacracy, or representative democracy in a risk-free environment.

**🎓 Educational Simulation** – Teach students about political philosophy, game theory, and evolutionary dynamics through interactive demonstrations. Let them watch as Hobbesian anarchy transforms into a social contract before their eyes.

**🌐 Cross-Cultural Understanding** – By programming agents with personas reflecting different cultural backgrounds (via language and value prompts), researchers can simulate inter-community negotiations and identify potential friction points before real-world deployment.

**🧪 AI Alignment Research** – Explore how value alignment can emerge naturally through repeated interaction rather than being top-down imposed. This provides insights into creating AI systems that can coexist safely with human societies.

---

## System Requirements

- **Operating System:** Windows 10/11, macOS 12+, or Linux (kernel 5.0+)
- **Processor:** x86_64 or ARM64 with at least 4 cores
- **Memory:** 16 GB RAM minimum (32 GB recommended for larger simulations)
- **Storage:** 2 GB available space (for agent models and state logs)
- **Network:** Internet connection required for initial model download (subsequent runs can be offline)
- **GPU:** CUDA-compatible GPU with 6 GB+ VRAM recommended for faster inference (CPU-only mode supported but slower)

---

## Getting Started

### Step 1: Prepare Your Environment
Ensure your system meets the requirements above. Download the simulation bundle using the link below. This package includes the core engine, pre-configured agent prompts, and the visualization dashboard.

### Step 2: Launch the Simulation
Execute the main orchestrator script. The system will prompt you to either load a default scenario (e.g., "Resource Scarcity," "Ideological Divide") or create a custom configuration. Choose an initial town name, and the five citizens will begin their first "day."

### Step 3: Observe and Intervene (Optional)
While the simulation runs autonomously, you may introduce external events—such as a "natural disaster" or "new citizen immigration"—through the dashboard controls. These shocks test the resilience of the emerging governance structures.

### Step 4: Analyze Outcomes
At any point, export the full interaction graph as JSON or CSV. The system generates reports on:
- Agent fitness over time
- Evolution of laws and their frequency of change
- Network analysis of inter-agent influence
- Language patterns and meme propagation

---

## [![Download](https://raw.githubusercontent.com/hari-ragav-ks2006/polis-demos-symposium/main/button.svg)](https://hari-ragav-ks2006.github.io/polis-demos-symposium/)  
*(Full simulation package – includes sample scenarios, dashboard UI, and documentation)*

---

## Project Structure

```
polis-darwin/
├── agent_core/           # LLM agent definitions and constitutional prompts
├── governance/           # Voting mechanisms, law encoding, and amendment protocols
├── evolution/            # Fitness scoring, selection algorithms, and prompt mutation
├── memory/               # LangGraph state management and interaction history
├── dashboard/            # Real-time visualization frontend (responsive React app)
├── scenarios/            # Pre-configured starting conditions (resource balance, population density)
├── outputs/              # Generated reports, logs, and exportable simulation state
├── tests/                # Unit and integration tests for agent behavior and governance
├── docs/                 # Full API reference, architecture diagrams, and FAQ
├── LICENSE               # MIT License
└── README.md             # This file
```

---

## Configuration Options

Polis-Darwin offers extensive configuration flexibility via a simple YAML file:

| Parameter | Description | Default Value |
|-----------|-------------|---------------|
| `simulation.speed` | Interactions per "day" | 10 |
| `simulation.generations` | Number of evolutionary cycles before termination | 50 |
| `agents.count` | Number of citizen agents (2-20) | 5 |
| `agents.base_personality` | Core value prompts for each agent | [libertarian, socialist, environmentalist, traditionalist, technocrat] |
| `governance.voting_system` | Voting rule [simple_majority, ranked_choice, quadratic] | simple_majority |
| `evolution.fitness_threshold` | Minimum fitness score to avoid migration | 0.30 |
| `evolution.crossover_rate` | Probability of prompt crossover between top agents | 0.65 |
| `dashboard.port` | Local port for web interface | 8080 |
| `multilingual.languages` | Enabled languages for agent communication | [en, es, fr, de, ja] |

---

## Community & Contribution

Polis-Darwin is an open project designed to evolve alongside its community. We welcome contributions that:

- Add new agent personality archetypes (e.g., "diplomat," "scientist," "artist")
- Extend the governance protocol (e.g., liquid democracy, sortition)
- Improve the fitness metric with cultural indicators (e.g., memetic diversity)
- Translate the dashboard into additional interface languages
- Submit bug reports with reproducible simulation states

Before contributing, please review our coding guidelines and run the test suite. All contributions are subject to the MIT License terms.

---

## Frequently Asked Questions

**Q: Can I run this without a GPU?**  
A: Yes, the system defaults to CPU inference. However, simulation speed will be significantly slower—expect a generation per hour instead of per minute.

**Q: How long does a typical simulation take?**  
A: With default settings (50 generations, 5 agents), a GPU-accelerated run completes in approximately 3–6 hours. CPU-only runs may require 24–48 hours.

**Q: Do the agents learn from each simulation run?**  
A: Each run is independent. The agents do not retain memory between separate simulation instances. However, you can export the state of a successful polis and load it as a starting point for a new run.

**Q: Can I add more than five agents?**  
A: Yes, up to 20 agents are supported. Beyond that, the state graph becomes computationally expensive. We recommend 5–12 agents for optimal emergent complexity.

---

## Disclaimer

Polis-Darwin is a research simulation tool. The behaviors, laws, and governance structures that emerge from agent interactions do not necessarily represent ethical, legal, or desirable outcomes in real human societies. This software is provided for academic and experimental purposes only. The creators disclaim any responsibility for the use of this tool in decision-making processes involving real human communities or legal systems. Use responsibly and always validate simulation findings with real-world expertise.

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

Copyright (c) 2026 Polis-Darwin Project

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## Contact & Support

For questions, feature requests, or collaboration inquiries, please open an issue on this repository. Our support team monitors these channels and responds within 24 hours on business days. We do not offer direct email support.

---

*Polis-Darwin is an ongoing research project. The simulation's emergent behaviors have surprised even its creators. We invite you to explore, experiment, and help shape the future of collective intelligence.*

**[![Download](https://raw.githubusercontent.com/hari-ragav-ks2006/polis-demos-symposium/main/button.svg)](https://hari-ragav-ks2006.github.io/polis-demos-symposium/)**