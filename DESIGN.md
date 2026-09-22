# DESIGN.md

# LLMRC Design

## Boundary

LLMRC is a portable personal behavioral layer for language models. README.md tells users which file to adopt; the LLMRC documents define the actual contract.

## Core decisions

- Separate stable behavioral preferences from domain, project, task, and conversation context. This prevents a personal interaction contract from becoming a dump of project-specific facts.
- Use plain Markdown so the same material can travel across chat interfaces, coding agents, local models, and API workflows.
- Maintain a full and a lite form. The full document supports richer co-thinking; the lite version is sized for coding-agent context budgets.
- Favor explicit epistemic labeling, auditability, and reusable artifacts over tool-vendor-specific behavior.

## Constraints

LLMRC guides behavior; it does not replace repository instructions, domain policies, or task-specific requirements. Keep personal identity narrative separate from the stable behavioral layer.


