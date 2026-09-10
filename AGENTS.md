# AGENTS.md — TBHRC GitHub Platform Defaults Router

**Structural class:** H — GitHub organisation metadata/defaults. See [TBHRC GitHub Repository Pre-Structure](https://github.com/tbhrc/org/blob/main/700-architecture/organisation-pre-structure.md).

Repository purpose: inherited GitHub organisation profile, community-health defaults, shared issue/PR templates, versioned sources for organisation-level GitHub/Copilot delivery settings, and related GitHub-platform defaults.

## Route

- Organisation Chart / Business Structure / Repository Map / Repository Pre-Structure → [`tbhrc/org`](https://github.com/tbhrc/org).
- Reusable HOW / lifecycle method / canonical FolderDesk operating instructions → [`tbhrc/skills`](https://github.com/tbhrc/skills).
- GitHub organisation profile, default issue/PR templates, CODEOWNERS/community-health defaults, organisation-level Copilot/custom-instruction delivery source, and organisation custom-agent distribution surfaces → stay here.
- Current organisation custom-instruction source → [`ORGANIZATION-CUSTOM-INSTRUCTIONS.md`](ORGANIZATION-CUSTOM-INSTRUCTIONS.md); it points to the canonical [FolderDesk Master Prompt](https://github.com/tbhrc/skills/blob/main/governance/folderdesk-master-prompt.md) rather than duplicating it.
- Repository-specific override → owning repository only when a real local difference is required.

## Rule

**Own inherited GitHub defaults once; do not copy them across repositories.** Treat GitHub organisation settings and `.github` distribution surfaces as delivery/inheritance layers, not second editable canon. Reusable operating logic remains in `tbhrc/skills`; this repository owns the GitHub-platform mechanism that distributes or applies it where supported.

**Fast links:** [FolderDesk organisation instructions](ORGANIZATION-CUSTOM-INSTRUCTIONS.md) · [FolderDesk Master Prompt](https://github.com/tbhrc/skills/blob/main/governance/folderdesk-master-prompt.md) · [TBHRC Organisation Chart](https://github.com/tbhrc/org/blob/main/300-governance/organisation-chart.md) · [TBHRC GitHub Repository Map](https://github.com/tbhrc/org/blob/main/300-governance/repository-map.md) · [Operating Structure Vocabulary](https://github.com/tbhrc/org/blob/main/300-governance/operating-structure-vocabulary.md) · [Skills](https://github.com/tbhrc/skills)
