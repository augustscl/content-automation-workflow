# Content Automation Workflow

An OpenClaw master skill for building and running content creation automation pipelines.

## What this repository contains

This repository currently focuses on one master skill:
- `skills/content-automation-workflow/`

It is designed as a controller layer for content systems, not just a single writing prompt.

## Core idea

The skill organizes content automation into five layers:

1. **Input**
   - collect raw material from links, articles, notes, audio, video, docs, or prior context
2. **Processing**
   - summarize, extract key points, identify audience and angles
3. **Production**
   - generate long-form articles, short posts, slides, images, or other assets
4. **Distribution**
   - prepare channel-specific drafts or publishing outputs
5. **Deposition**
   - store reusable knowledge, summaries, and generated assets for later reuse

## What it is good for

- building a content factory
- designing a repeatable publishing workflow
- turning one source into multiple content outputs
- coordinating article, social, slide, image, and deposition tasks
- serving as the orchestration layer above more specific content skills

## Repository structure

```text
README.md
skills/
  content-automation-workflow/
    SKILL.md
    README.md
    VERSION.md
    examples/
    references/
```

## Included references

- workflow templates
- MVP routes
- output contracts
- deposition schema
- channel recipes
- example mapping for an AI news briefing workflow

## Example use cases

- build a WeChat-centered content pipeline
- create a one-source-many-outputs workflow
- automate AI news briefings
- design a content production MVP before scaling into a larger system

## Notes

This repository is intended to be a clean standalone package for the master workflow skill.
Specific vertical content skills can live in separate repositories and plug into this controller layer.
