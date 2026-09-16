# TBHRC — GitHub Organization Custom Instructions

**Purpose:** Versioned source for the text configured in **GitHub Organization Settings → Copilot → Custom instructions**. This file is a delivery pointer, not a second organisation instruction system.

**Canonical master router:** [Workspace AGENTS.md](https://github.com/tbhrc/workspace/blob/main/AGENTS.md)

**Canonical Skill Bank:** [Workspace `.folderdesk/skills/`](https://github.com/tbhrc/workspace/tree/main/.folderdesk/skills)

**Current GitHub support reference:** [Organization custom instructions](https://docs.github.com/en/copilot/how-tos/copilot-on-github/customize-copilot/add-custom-instructions/add-organization-instructions) · [Custom-instruction support matrix](https://docs.github.com/en/copilot/reference/custom-instructions-support)

## Exact organization custom-instruction text

```text
For work in the tbhrc organization, load and follow the current organisation master router at tbhrc/workspace/AGENTS.md unless the active repository hierarchy has already supplied it.

Once the target repository is known, read that repository's root AGENTS.md overlay when one exists. When reusable specialist HOW is required, use the canonical Skill Bank at tbhrc/workspace/.folderdesk/skills through the authorised skills-mcp path rather than an installed or copied Skill body.

GitHub main is authoritative for editable operational canon. Read across owners; write to the canonical owner. Do not use tbhrc/skills as editable truth; it is retired provenance/compatibility only.
```

## Deployment contract

- Configure the text above once in the TBHRC organization Copilot custom-instructions setting when that feature is available to the organization plan.
- Treat GitHub's organization setting as an injection/delivery surface, not editable business canon; organisation-wide policy remains in Workspace `AGENTS.md` and reusable HOW remains in Workspace `.folderdesk/skills/`.
- Repository/path instructions and repository `AGENTS.md` overlays may specialise behavior; avoid conflicting duplicates.
- Unsupported runtimes may use the smallest stable compatibility pointer needed to load the Workspace master router and selected canonical Skill. Never maintain a separate full policy or Skill copy.
