# Claude Agents Collection

A focused collection of Claude-compatible subagents designed to extend software, product, and growth workflows using specialized expertise.

## Overview

This workspace includes **24 expert agents**, each scoped to a specific domain: engineering, analytics, product, growth, and support. They follow Claude-compatible `.md` format and are ready to use for orchestration or explicit invocation.

## Available Agents

### Development & Architecture
- **[AI Engineer](ai-engineer.md)**
- **[Architect Review](architect-review.md)**
- **[Backend Architect](backend-architect.md)**
- **[Experimentation Engineer](experimentation-engineer.md)**
- **[Performance Engineer](performance-engineer.md)**
- **[Prompt Engineer](prompt-engineer.md)**
- **[Release Engineer](release-engineer.md)**
- **[SwiftUI Engineer](swiftui-engineer.md)**

### Quality & Research
- **[Business Analyst](business-analyst.md)**
- **[Code Reviewer](code-reviewer.md)**
- **[Competitor Intelligence Analyst](competitor-intelligence-analyst.md)**
- **[User Researcher](user-researcher.md)**

### Community & Communication
- **[Community Growth Manager](community-growth-manager.md)**
- **[Context Manager](context-manager.md)**
- **[Customer Support](customer-support.md)**
- **[Dev Rel Content Manager](dev-rel-content-manager.md)**
- **[Partnership Outreach Manager](partnership-outreach-manager.md)**

### Data & Infrastructure
- **[Analytics Telemetry Agent](analytics-telemetry-agent.md)**
- **[API Documenter](api-documenter.md)**
- **[Data Pipeline Specialist](data-pipeline-specialist.md)**
- **[Debugger](debugger.md)**

### Business & Compliance
- **[Legal Advisor](legal-advisor.md)**
- **[Pricing Specialist](pricing-specialist.md)**
- **[Product Feature Designer](product-feature-designer.md)**

## Usage

Place these files in your `.claude/agents/` directory or load them manually via your orchestration logic.

Each file defines the agent’s role, expected input/output, and best practices.

Use natural language or explicit commands to trigger the correct agent, for example:

```
Use the pricing-specialist to create a SaaS pricing page
Ask the user-researcher to summarize survey insights
Let the swiftui-engineer implement this onboarding flow
```

## Contributions

To add an agent, duplicate an existing `.md` file and follow the same structure.

✅ Keep prompts concise, focused, and goal-oriented.  
✅ Stick to a single area of expertise per agent.  
✅ Use markdown sections (`## Focus Areas`, `## Output`, etc.) for structure.
