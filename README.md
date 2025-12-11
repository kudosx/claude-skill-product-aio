# Skill Product AIO

Claude skill for product management, feature planning, and documentation.

## Features

- Feature planning and analysis
- User stories with acceptance criteria
- PRD (Product Requirements Document) templates
- Roadmap and planning guidance
- RICE prioritization framework
- User research and competitive analysis templates

## Example Prompts

### Feature Planning

```
analyze this feature request and create a user story

create a PRD for adding dark mode

break down this epic into user stories
```

### User Stories

```
create a user story for user authentication

write acceptance criteria for the checkout flow

add technical notes to this story
```

### Prioritization

```
calculate RICE score for these features

compare these two features using RICE

which feature should we prioritize?
```

### Documentation

```
create an epic overview for user management

set up the spec folder structure

update the roadmap with Q1 priorities
```

## Documentation

- [SKILL.md](.claude/skills/product-aio/SKILL.md) - Main skill documentation with full templates and conventions

### Key Concepts

- **Epics** - Large features broken into user stories
- **User Stories** - Individual requirements with acceptance criteria
- **PRDs** - Product Requirements Documents for major features
- **RICE Scoring** - Reach, Impact, Confidence, Effort prioritization

### Folder Structure

All product documents are stored in the `spec/` folder:
- `spec/prd/` - Product Requirements Documents
- `spec/stories/` - User stories organized by epic
- `spec/roadmap/` - Roadmap and planning documents
- `spec/research/` - User research and competitive analysis
