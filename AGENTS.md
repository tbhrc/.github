# AGENTS.md — TBHRC GitHub Platform Defaults Router

Repository purpose: inherited GitHub organisation profile, community-health defaults, shared issue/PR templates, versioned sources for organisation-level GitHub/Copilot delivery settings, and related GitHub-platform defaults.

## Route

- Organisation structure / business map / repository navigation → [`tbhrc/workspace`](https://github.com/tbhrc/workspace).
- Organisation-wide operating instructions → [`tbhrc/workspace/AGENTS.md`](https://github.com/tbhrc/workspace/blob/main/AGENTS.md).
- Reusable HOW / lifecycle method / canonical FolderDesk operating instructions → [`tbhrc/workspace/.folderdesk/skills`](https://github.com/tbhrc/workspace/tree/main/.folderdesk/skills), through the Workspace master router's mandatory LS1-backed `skills-mcp.find_skill(actual task)` path for each new bounded task; manual/Fast-Link discovery is fallback only when `find_skill` reports a fallback state.
- GitHub organisation profile, default issue/PR templates, community-health defaults, organisation-level Copilot/custom-instruction delivery source, and organisation custom-agent distribution surfaces → stay here.
- Current organisation custom-instruction source → [`ORGANIZATION-CUSTOM-INSTRUCTIONS.md`](ORGANIZATION-CUSTOM-INSTRUCTIONS.md); it points to the Workspace master router rather than duplicating organisation policy.
- Repository-specific override → owning repository only when a real local difference is required.

## Rule

**Own inherited GitHub defaults once; do not copy them across repositories.** Treat GitHub organisation settings and `.github` distribution surfaces as delivery/inheritance layers, not second editable canon. Organisation-wide structure and routing are owned by `tbhrc/workspace`; reusable operating HOW is owned by `tbhrc/workspace/.folderdesk/skills/`. `tbhrc/skills` is retired provenance/compatibility only.

**Fast links:** [Organisation instructions](ORGANIZATION-CUSTOM-INSTRUCTIONS.md) · [Workspace master router](https://github.com/tbhrc/workspace/blob/main/AGENTS.md) · [Workspace](https://github.com/tbhrc/workspace) · [Workspace migration plan](https://github.com/tbhrc/workspace/blob/main/MIGRATION-PLAN.md) · [Skill Bank](https://github.com/tbhrc/workspace/tree/main/.folderdesk/skills)
