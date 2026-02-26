# Projects

Project-specific work should live in `projects/<project-slug>/` so context, research, and decisions stay grouped.

## Why
- Prevents project context from being scattered across `memory/`, `intel/`, and agent working files
- Makes handoffs easier between coordinator, research, copywriter, and dev-agent
- Keeps durable project history in one place

## Folder Rules
- One folder per active project: `projects/<project-slug>/`
- Use kebab-case slugs (e.g. `projects/interior-software-content-series/`)
- Keep project-local research and drafts inside the project folder
- Put cross-project durable knowledge in `shared/` or `intel/`

## Suggested Workflow
1. Create project from `_template/`
2. Fill `PROJECT.md` (brief + success criteria)
3. Add tasks in `TASKS.md`
4. Collect research in `research/`
5. Record decisions in `DECISIONS.md`
6. Store drafts/specs/artifacts in `deliverables/`

## Status Convention
- `active`
- `blocked`
- `waiting`
- `done`
- `archived`
