# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Claude Code skill package for product management. It provides expert guidance for feature planning, user stories, PRDs, roadmaps, prioritization, and product decisions.

## Repository Structure

```
.claude/
  skills/product-aio/     # Main skill definition (SKILL.md)
  commands/               # Custom slash commands (if any)
.claude-plugin/
  marketplace.json        # Skill marketplace metadata
```

## Key Conventions

- **Language**: Write all product documents in Vietnamese (English for technical terms only)
- **Storage**: All product documents go in the `spec/` folder
- **Prioritization**: Use RICE scoring framework
- **User Stories**: Follow the epic/story structure with proper naming conventions

## Custom Commands

- None yet - add custom commands to `.claude/commands/` as needed
