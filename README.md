# FlowForge AI

FlowForge AI is a multi-agent research automation workflow built with **n8n** and **Google Gemini**. The system uses specialized AI agents to independently analyze a topic and synthesize their outputs into a structured Markdown report.

## Features

* Multi-agent architecture
* Parallel execution of expert agents
* Automated report synthesis
* Markdown report generation
* Workflow orchestration using n8n
* Powered by Google Gemini

## Architecture

```
                     Topic
                       ↓
                  Edit Fields
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
Overview Expert Challenges Expert Future Trends Expert
        └──────────────┼──────────────┘
                       ↓
                     Merge
                       ↓
              Final Report Editor
                       ↓
                Convert to File
                       ↓
                 Markdown Report
```

## Repository Structure

```
flowforge-ai/
│
├── workflows/
│     FlowForge AI.json
│
├── examples/
│     report.md
│
├── screenshots/
│      architecture.png
│
├── README.md
└── .gitignore
```

## Tech Stack

* n8n
* Google Gemini
* Agentic AI
* Multi-Agent Systems
* Prompt Engineering
* Workflow Automation
* Markdown

## Example Use Cases

* AI research reports
* Technology trend analysis
* Knowledge synthesis
* Content generation workflows

## Future Improvements

* Query Planner Agent
* Web Search Tool Integration
* Tavily Search
* Retrieval-Augmented Generation (RAG)
* Memory and state management

## License

This project is licensed under the MIT License.
