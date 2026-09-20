# Agent Forge

A version-controlled library of reusable AI agent skills, engineering standards, workflows, and project templates.

## Skills

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

## Install

Install the website skill globally from this repository:

```bash
npx skills add https://github.com/nipungoel24/agent-forge --skill production-website -g --agent '*' --copy
```

Project-local installation:

```bash
npx skills add https://github.com/nipungoel24/agent-forge --skill production-website --copy
```

## Repository philosophy

GitHub is the canonical source of truth. Improve the skill here as new failures, techniques, and standards are discovered. Projects should contain their own PRD, Architecture, Rules, Phases, Design, and Memory files; the reusable skill provides the methodology and templates.

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
