# Project Operations (Workspace Convention)

## Where project context goes
- Project-local brief, tasks, decisions, and research belong in `projects/<project-slug>/`
- Cross-project reusable knowledge belongs in `shared/` or `intel/`
- Daily activity/incidents still go to `memory/YYYY-MM-DD.md`

## Delegation pattern by project folder
- `research-agent` -> `projects/<slug>/research/`
- `copywriter` -> `projects/<slug>/deliverables/copy/` or draft into `WORKING.md` and copy final versions here
- `dev-agent` -> implementation notes/specs in `projects/<slug>/deliverables/specs/`
- `main` -> keeps `PROJECT.md`, `PLAN.md`, and `TASKS.md` coherent

## Public-facing rule
Drafts can be prepared in project folders without approval. Publishing/sending still requires human confirmation.
