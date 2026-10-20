# Awesome-Diagramming-Flowcharts

## Top Diagramming & Flowcharts Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Code-to-Diagram Generation, Real-Time Collaboration & Local-First Editing*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Diagramming & Flowcharts**. These tools enable teams to map processes, design architectures, and sketch ideas visually—from code-first tools that render diagrams from plain text to canvas-based editors that work entirely offline.



**Examples** include draw.io, Mermaid, Excalidraw, OpenFlowKit, LibreOffice Draw, Dia, yEd, Pencil Project, PlantUML, and Graphviz (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, text-to-diagram generation, and open canvas infrastructure—ideal for developers, architects, and organizations seeking transparent, vendor-independent diagramming.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Starting Paid Pricing | Free Tier / Trial Limits | Description & Best For |
| :--- | :--- | :--- | :--- | :--- |
| **Microsoft Visio** | ~$3.95 Trillion (Market Cap) | **$5.00 / user / month** (Visio Plan 1, billed annually) | **30-day free trial** (Plan 1/Plan 2; requires business login/card); lightweight web view/edit included with Microsoft 365 commercial plans | **Enterprise diagramming** integrated with Microsoft 365. Fully proprietary and cloud-hosted. No self-hosting. Deep integration with Excel data linking and SharePoint. **Best for**: organizations already committed to the Microsoft ecosystem. |
| **Lucidchart** | ~$3.0 Billion - $4.5 Billion (Valuation) / ~$144M ARR | **$9.00 / month** (Individual plan, billed annually) | **Free forever plan**: Up to 3 active editable documents, max 60 shapes per document, and 100 basic templates | **The centralized standard for collaborative diagramming**. Fully proprietary and cloud-hosted. Free plan caps documents, shapes, and canvas space. No self-hosting, no offline mode. **Best for**: teams prioritizing polished real-time collaboration over data sovereignty. |
| **Miro** | ~$1.79 Billion (Acquisition Valuation by Bending Spoons) / ~$600M ARR | **$8.00 / member / month** (Starter plan, billed annually, min 2 seats) or $10/mo monthly | **Free forever plan**: Up to 3 active editable boards, unlimited team members (all boards public to workspace), and 10 AI credits/mo | **Collaborative whiteboard platform** with diagramming templates. Fully proprietary and cloud-hosted. No self-hosting. **Best for**: teams wanting brainstorming and diagramming in one infinite canvas. |
| **SmartDraw** | ~$7 Million - $10.3 Million (Estimated Annual Revenue) | **$9.95 / month** (Individual plan, billed annually at ~$119.40/yr) | **7-day free trial** with full feature access for internal evaluation; no permanent free tier | **Automated diagramming software** with built-in templates and data-linked visuals. Fully proprietary and cloud-hosted. No self-hosting. **Best for**: business users creating org charts and process diagrams. |
| **Creately** | ~$5.1 Million (Estimated Annual Revenue) | **$5.00 / editor / month** (Starter plan, billed annually) or $8/mo monthly | **Free forever plan**: 3 workspaces, capped at 45 items per workspace, 1 folder, and basic export formats | **Diagramming and visual collaboration platform** with templates and real-time collaboration. Fully proprietary and cloud-hosted. No self-hosting. **Best for**: teams wanting a managed diagramming experience without technical setup. |

## Open-Source GitHub Projects



- **draw.io (diagrams.net)**

  **Client-side JavaScript diagramming application** (Apache-2.0) — **the most widely adopted open-source diagramming tool** . **Fully offline-capable**—runs in browser or desktop, saves to local storage or integrated cloud drives (Google Drive, OneDrive, Dropbox) . **Rich shape libraries** covering UML, flowcharts, org charts, network diagrams, and more. **Zero cost, zero account required**. **Exports**: PNG, JPEG, SVG, PDF . **The trade-offs**: **lacks built-in team collaboration** (threaded comments, version control)—you collaborate by sharing files . **The reference implementation for general-purpose open-source diagramming**—**choose when you want a complete, free tool that works offline and integrates with your existing cloud storage**.



- **Mermaid**

  **JavaScript-based diagramming tool that generates diagrams from text** (MIT) — **the code-first standard** . **Write Markdown-like syntax and get rendered flowcharts, sequence diagrams, Gantt charts, class diagrams, state diagrams, ER diagrams, mind maps, and more** . **Native support across GitHub, GitLab, Notion, Obsidian, and VS Code**—diagrams embed directly in READMEs and wikis . **The speed advantage**: no dragging, no aligning, no context-switching—you type the logic and the tool handles layout . **The trade-offs**: **requires syntax knowledge** (steep learning curve initially) and **no pixel-perfect control**—if you need precise positioning, use a canvas tool . **The reference implementation for text-to-diagram**—**choose when you want diagrams that live in version control alongside code**.



- **Excalidraw**

  **Virtual whiteboard for sketching hand-drawn-like diagrams** (MIT) — **the hand-drawn choice** . **Infinite canvas-based whiteboard** with a distinctive sketch aesthetic. **End-to-end encryption** for real-time collaboration. **Local-first support** (autosaves to browser). **Export to PNG, SVG, and `.excalidraw` JSON**. **Shape libraries, dark mode, image support** . **Self-hostable via Docker** with a build that keeps **links, collaboration, and fonts on your own server**—the browser never contacts external services . **The trade-offs**: **not a design-system tool**—component management and structured diagrams are limited. **The reference implementation for whiteboarding and ideation**—**choose when you want a fast, collaborative canvas for sketches and early-stage wireframes**.



- **OpenFlowKit**

  **Free, open-source diagram canvas with code-to-diagram and AI integration** (MIT) — **the AI-native choice** . **Bidirectional text conversion**: paste **Mermaid, Structurizr DSL, or D2** onto the canvas and it converts; **Copy as Mermaid** exports flowcharts and sequence diagrams for READMEs . **AI assistant** via `⌘J`—pick Claude, OpenAI, Gemini, Groq, Mistral, Cerebras, NVIDIA, OpenRouter, Ollama, or any OpenAI-compatible endpoint; the key stays in your browser . **MCP server** lets Claude Code edit diagrams live . **CLI for CI**: `npx openflowkit render`, `validate`, `convert`, `discover` . **PR diagrams Action** comments on pull requests with diagram changes and drift detection . **Local-first, no account**. **The reference implementation for agent-native diagramming**—**choose when you want AI to draft and edit diagrams from natural language or code**.



- **LibreOffice Draw**

  **Open-source vector graphics editor** (MPL-2.0) — **the offline suite choice** . **Part of LibreOffice**—if you already use the suite, diagrams embed directly in Writer documents and Calc spreadsheets . **Node editing, Bézier curves, smart connectors, custom shapes**. **Exports**: ODG, SVG, PDF . **The trade-offs**: **not flowchart-optimized**—interface feels less polished than dedicated tools, and collaboration is weak . **The reference implementation for offline, integrated diagramming**—**choose when you're already in LibreOffice and want diagrams without installing another app**.



- **Dia**

  **Classic open-source diagram editor** (GPL-2.0) — **the lightweight legacy choice** . **Simple interface with basic shapes and connectors**. **Exports**: PNG, SVG, EPS. **Custom shape libraries via XML**. **Low resource footprint**—opens instantly on old hardware . **The trade-offs**: **dated UI and usability**—no real-time collaboration, no modern conveniences . **Best for**: simple flowcharts on constrained systems where a modern editor won't run.



- **yEd Graph Editor**

  **Powerful diagram editor with automatic layout algorithms** (yEd license) — **the auto-layout choice** . **Import external data and auto-arrange large graphs with one click**—manual diagramming is fast, but automatic layout is the differentiator . **Best for**: large graphs, network diagrams, and org charts where automatic arrangement saves hours.



- **Pencil Project**

  **Standalone diagramming and UI mockup tool** — **the lightweight prototyping choice** . **Built-in templates and interface components**. **Exports**: PNG, PDF, SVG. **Multi-page diagrams, object linking (hyperlinks for interactive prototypes)** . **The trade-offs**: **not suitable for large complex process modeling**, and **collaboration is limited** . **Best for**: quick UI flows and wireframe sketches without the overhead of a full design tool.



### Additional Strong Open-Source Options



- **PlantUML** — **Text-based UML diagram generator** (open-source) — **the UML specialist**. **Write plain text, get UML diagrams**—class, sequence, activity, use case, component, state, and deployment diagrams. **Integrates with IDEs and documentation tools**. **Best for**: software architects needing **standard UML diagrams from code**.

- **Graphviz** — **Open-source graph visualization software** (EPL) — **the DOT language standard**. **Define graphs in DOT syntax, render with automatic layout engines** (dot, neato, fdp, circo, twopi). **PanGraphic** provides a real-time visual Graphviz editor with Monaco code view and multiple layout engines . **Interactive Graphviz** provides a private, client-side DOT viewer with live editing and WebAssembly rendering . **Best for**: **programmatic graph generation** and **network/flow diagrams from data**.

- **Agentic Mermaid** — **Open-source Mermaid toolkit for AI agents** (open-source) — **the agent-native Mermaid renderer** . **SVG, PNG, ASCII, Unicode, JSON output** from one source. **Composable styles** (watercolor, blueprint, hand-drawn, publication-figure) and **custom palettes** . **CLI, MCP, and library interfaces** . **Best for**: teams wanting **AI-generated Mermaid diagrams with brand-consistent styling**.

- **DocuShark** — **Page-based document editor with built-in diagramming and MCP server** (AGPL-3.0) — **the document-integrated choice** . **Prose and canvas in one document**—write text, drop in a flowchart, attach files. **Import from Mermaid, draw.io, and Excalidraw**. **Real-time collaboration via CRDT (Yjs)** with self-hostable relay. **MCP server** lets AI agents read and write documents . **Best for**: teams wanting **diagrams embedded in living documents** with AI agent access.

- Community **n8n** workflows for diagram export automation and documentation pipeline integration.



**Frameworks for building custom systems**: Combine **draw.io** for general-purpose offline diagramming with **Mermaid** for code-first diagrams in version control, **Excalidraw** for collaborative whiteboarding, **OpenFlowKit** for AI-assisted drafting, and **Graphviz** for programmatic graph generation—creating a comprehensive diagramming stack matched to each use case.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Diagramming tools handling proprietary architecture and process documentation must be evaluated for **self-hosting capability**, **file format portability** (open formats like SVG vs. proprietary JSON), and **collaboration features**.

- **The "canvas vs. code" distinction drives workflow.** **Canvas tools** (draw.io, Excalidraw, OpenFlowKit) let you drag shapes and arrange visually—**fast for brainstorming, but the diagram lives in a binary or JSON file** that's hard to review in a pull request. **Code tools** (Mermaid, PlantUML, Graphviz) generate diagrams from text—**diagrams live in version control, diffs are readable, and layout is automatic** . **Choose based on whether you want to draw or describe.**

- **draw.io is the complete free canvas, but collaboration is its gap.** **Rich shape libraries, offline mode, cloud drive integration**—it covers almost everything Lucidchart does without the subscription . **But threaded comments and version control are missing**—you collaborate by sharing files, not by editing together in real time . **For teams that need real-time multiplayer, Excalidraw or a SaaS tool fills that gap.**

- **Mermaid's trade-off is control for speed.** **No pixel-perfect positioning**—if you need precise placement, use a canvas tool . **But for flowcharts, sequence diagrams, and Gantt charts that live in READMEs and wikis**, Mermaid's automatic layout and version-control-friendly text format are unmatched . **Native GitHub and GitLab support mean your diagrams render wherever your code lives.**

- **AI-native diagramming is the emerging frontier.** **OpenFlowKit** converts Mermaid, D2, and Structurizr bidirectionally, lets AI models draft diagrams from natural language, and exposes an MCP server for Claude Code to edit live . **Agentic Mermaid** provides styled Mermaid output for agents . **DocuShark** embeds diagramming in documents with MCP access . **The diagram is becoming a tool that AI agents can create and modify, not just a file humans edit.**

- **Self-hosted open-source solutions require proper backup strategies and version control.** **Diagrams are documentation**—if they only exist in a proprietary cloud, they're one subscription cancellation away from loss. **Open formats and local-first tools protect against that.**



---



**Made for developers, architects, and organizations building transparent diagramming solutions.**  

Let's make Diagramming & Flowcharts more open, data-driven, and code-first.
