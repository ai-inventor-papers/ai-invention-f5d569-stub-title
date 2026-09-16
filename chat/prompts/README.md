# Prompts

Complete, auto-generated record of **every prompt the AI Inventor system gave each agent** across this run — generated at repository-upload time so it captures all steps. For the full conversation (assistant turns, thinking, tool calls and results) see the sibling `../messages/` folder.

- Run: `run_MDfGzum4NSNc` — [stub] title

Each prompt is labelled by type and timestamped, with its full untruncated body:

- **SYSTEM-USER** — the pipeline-generated role/instruction prompt placed in the user slot.
- **HUMAN-USER** — the task / human-typed message into the agent stream.
- **SKILL-INPUT** — a skill the agent loaded; its `SKILL.md` instructions, verbatim.

Layout mirrors the run's module tree: one folder per high-level phase, a `round_N/` per iteration where the phase iterates, then each module — a single-task module is one `.md` file, a parallel module (gen_plan / gen_art / gen_viz / gen_demo_art) is a folder with one `.md` per task.

## Index

- **1. create_idea** — `hypo_loop`
  - round_1
    - `chat/prompts/1_create_idea/round_1/1_gen_hypo.md` — 2 prompts
    - `chat/prompts/1_create_idea/round_1/2_review_hypo.md` — 2 prompts
  - round_2
    - `chat/prompts/1_create_idea/round_2/1_gen_hypo.md` — 2 prompts
    - `chat/prompts/1_create_idea/round_2/2_review_hypo.md` — 2 prompts
