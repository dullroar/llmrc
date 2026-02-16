# llmrc
An "LLMRC" file, inspired by .vimrc and similar.

## Instructions

Fork. Edit. Upload to any LLM convo where you have cross-session memory turned on and tell it
to remember the contents as preferred interaction style.

## Why This Is Behavioral-First

* **Portability Across Models** – Behavioral interaction contracts transfer cleanly between ChatGPT, Claude, Copilot, and future models; narrative persona layers often do not.

* **Token Discipline** – Stable behavioral rules are compact and efficient, whereas biographical or philosophical context tends to bloat and degrade signal-to-noise.

* **Governance & Auditability** – Behavioral constraints (e.g., admit uncertainty, structure reasoning, avoid fabrication) are traceable and defensible in regulated or professional environments.

* **Layered Architecture** – A small, invariant personal core can be cleanly overlaid with domain- and project-specific context without creating a monolithic prompt blob.

* **Reduced Drift** – Behavioral expectations stabilize interaction style over time, while narrative-heavy prompts can cause overfitting or persona distortion.

* **Reproducibility** – Outputs can be meaningfully associated with a specific version of the behavioral layer, enabling reproducible “cognitive builds.”

* **Vendor Neutrality** – Behavioral rules describe how to think and communicate, not which platform to optimize for, minimizing lock-in.

* **Separation of Identity and Operation** – Narrative identity belongs in domain or project overlays; the core remains an operational contract for productive collaboration.

## Why Markdown?

Easy to understand and edit by the user, easy to parse and condense by the LLM.
