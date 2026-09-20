# Agent Forge

A version-controlled library of reusable AI agent skills, engineering standards, workflows, and project templates.

## Skills

### agent-forge-bootstrap
A universal loader skill for AI agents. It tells an agent to fetch the current relevant skill from this repository before starting project work.

Use this as the small, reusable skill you install into individual AI assistants/agents.

### production-website
A production website engineering and QA skill for building or improving websites without generic AI/vibe-coded patterns.

It covers:
- product discovery and project planning
- design systems and UI quality
- responsive/mobile behavior
- accessibility
- SEO and metadata
- structured data
- social sharing
- content integrity
- forms and interaction states
- performance
- browser QA
- deployment and launch verification

## The recommended model

Install `agent-forge-bootstrap` into an agent that supports reusable skills.

When that agent receives a project request, it should:
1. Identify the relevant Agent Forge skills.
2. Fetch/load the current skills from this GitHub repository.
3. Apply those skills to the project.
4. Continue using project-specific requirements as the source of truth.

For website work, the bootstrap skill loads `production-website`.

## Install

Install the bootstrap skill globally:

```bash
npx skills add https://github.com/nipungoel24/agent-forge --skill agent-forge-bootstrap -g --agent '*' --copy
```

Install the production website skill directly:

```bash
npx skills add https://github.com/nipungoel24/agent-forge --skill production-website -g --agent '*' --copy
```

Project-local installation:

```bash
npx skills add https://github.com/nipungoel24/agent-forge --skill production-website --copy
```

## Repository philosophy

GitHub is the canonical source of truth. Improve the skills here as new failures, techniques, and standards are discovered.

Projects should contain their own PRD, Architecture, Rules, Phases, Design, and Memory files; reusable skills provide the methodology and templates.

## Included ecosystem references

- ibelick/ui-skills
- emilkowalski/skills
- Morphicons
- theSVG
- shadcn/ui
- Google Search documentation
- Web Vitals guidance
- llms.txt specification

See `skills/production-website/references/` for the integration notes.