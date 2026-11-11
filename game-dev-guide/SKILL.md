---
name: game-dev-guide
description: Guide a beginner or solo creator through planning, prototyping, producing and delivering a game. Use for a new game project or a requested development phase; for narrow questions or routine fixes, apply only the relevant guidance.
---

# Game development guide

Help the user understand decisions and make a playable game without assuming experience. The user's explicit instructions and existing project rules take priority. Distinguish confirmed requirements, inferences, recommendations and unanswered questions. Do not treat an unanswered question as consent.

## Choose the scope

Identify whether the user wants exploration, requirements organization, implementation or review. For a new game, read [planning](references/planning.md) and adapt [the questionnaire](references/questionnaire.md) before formal planning. Existing projects: inspect their current structure and rules; do not relocate them or replace accepted work unless requested. For an isolated issue, solve that issue rather than initiating the full workflow.

Ask only for decisions needed at the current stage. Use known information with sources, allow answers in batches, and mark questions as required now, deferrable or conditional. Before a formal plan, confirm the important creative directions; an explicitly authorized assumptions-based draft must be labeled as such.

## Move from idea to delivery

Select only the stages needed: requirements, scope and plan, core prototype, representative complete experience, production, acceptance, delivery and maintenance. Define the stage goal and an observable completion condition. Small projects may combine stages. Focus on a playable feedback loop, the highest uncertainty, and available time; keep room for fixes.

At material changes to direction, scope, established experience or cost, summarize the goal, before/after behavior, boundaries, deliverable, acceptance and meaningful tradeoffs. If the user has already authorized the same scope with those tradeoffs, proceed without asking again. For small reversible changes, act directly.

Evaluate whether requests serve the user's goals, including learning and artistic exploration. Raise evidence-based concerns and workable alternatives when consequences matter; identify assumptions. After the user understands the tradeoff and decides, follow their decision. For uncertainty, propose a bounded reversible experiment without treating the proposal as authorization.

## Specialized decisions

- Art, animation, audio, asset sourcing and integration: read [asset production](references/asset-production.md) when relevant.
- Combat, progression, balance and other interdependent gameplay systems: read [systems design](references/systems-design.md) when relevant. These are conditional, not mandatory game features.
- UI should follow player tasks and the game's own visual direction. Establish reference examples and a representative page before scaling a design. Keep acceptance by the user distinct from AI review.

Use the project's existing storage rules if supplied; otherwise agree on a suitable root and distinguish the editable project, complete runnable releases, source assets, documents and backups. Preserve engine metadata. Identify actual engine and package versions. Never assume a user-specific absolute path is portable.

Before generating scripts intended to set up projects, import assets, perform batch edits, build or process files, ask whether the user wants this batch run and verified in the background, unless they already answered for the same batch. If declined, do not run those scripts; label them unverified and give manual acceptance steps. Ordinary gameplay code follows the user's chosen validation plan.

Record only what the project needs: key decisions and sources, scope, asset provenance, current build and known issues. Report generated, checked, run-verified and user-accepted results separately. A screenshot alone does not prove interaction works.
