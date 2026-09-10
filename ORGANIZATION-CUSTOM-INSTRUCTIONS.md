# TBHRC FolderDesk — GitHub Organization Custom Instructions

**Purpose:** Versioned source for the text configured in **GitHub Organization Settings → Copilot → Custom instructions**. This file is not a second FolderDesk master prompt; it is the native GitHub ingress pointer to the canonical owner.

**Canonical master prompt:** [FolderDesk Master Prompt](https://github.com/tbhrc/skills/blob/main/governance/folderdesk-master-prompt.md)

**Current GitHub support reference:** [Organization custom instructions](https://docs.github.com/en/copilot/how-tos/copilot-on-github/customize-copilot/add-custom-instructions/add-organization-instructions) · [Custom-instruction support matrix](https://docs.github.com/en/copilot/reference/custom-instructions-support)

## Exact organization custom-instruction text

```text
TBHRC uses FolderDesk as its agentic-first operating harness. For work in the tbhrc organization, load and follow the current canonical FolderDesk Master Prompt from tbhrc/skills/governance/folderdesk-master-prompt.md.

After that baseline is available, once the target repository is known, read that repository's root AGENTS.md Router before task search, Issue lookup, other repository file reads or mutations. Then follow the routed Skills-first workflow and controlling-Issue requirements.

GitHub main is authoritative for editable operational canon. Keep durable work in its canonical owner, do not maintain duplicate master-prompt copies, and use descriptive clickable GitHub links in founder-facing output when stable URLs exist.
```

## Deployment contract

- Configure the text above once in the TBHRC organization Copilot custom-instructions setting when that feature is available to the organization plan.
- Treat GitHub's organization setting as an **injection/delivery surface**, not editable business canon; edit the source here and the full operating rules in the canonical FolderDesk Master Prompt.
- Repository/path instructions and `AGENTS.md` may specialise behavior; avoid conflicting duplicates.
- As verified 10 September 2026, GitHub organization custom instructions currently cover Copilot Chat on GitHub.com, Copilot code review on GitHub.com, and Copilot cloud agent on GitHub.com. They do not currently provide universal coverage for Copilot CLI or arbitrary external AI clients.
- Unsupported runtimes may use the smallest stable compatibility pointer required to load the canonical FolderDesk master-prompt runtime block. Never maintain a separate full prompt copy.
