# Agentic AI InsightVoyager

## Overview
* Agentic AI InsightVoyager is a **privacy-first autonomous research and content generation pipeline** powered by CrewAI.  
* It uses **Google Gemini** for reasoning and **DuckDuckGo** for search, enabling AI-driven research with a focus on **privacy-friendly data retrieval**.

## Key Features
- **Multi-Agent Orchestration**: Research + content creation powered by Gemini.
- **Privacy-Friendly Search**: Uses DuckDuckGo for minimal tracking.
- **Automated Insight Generation**: Turns research into clear, structured reports or articles.
- **Sequential Workflow**: Ensures consistent, high-quality outputs.

## Tech Stack
- **Python**
- **CrewAI**
- **Google Gemini API**
- **DuckDuckGo Search**
- **Process.sequential** execution

## Architecture
1. **Researcher Agent** → Uses DuckDuckGo to find reliable sources.
2. **Writer Agent** → Creates content from research findings.
3. **Crew Orchestration** → Manages agents for smooth sequential execution.

## Example Use Cases
- Research for privacy-conscious organizations
- AI-assisted journalism
- Market analysis with anonymized data gathering

## Setup & Installation
```bash
pip install crewai
pip install langchain_google_genai
```

## Environment Variables
```bash
export GOOGLE_API_KEY="your_gemini_key"
```

## Run
```bash
python main.py
```

---
## Thank You
---
