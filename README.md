# ATLAS

ATLAS is Matthew Marx's reusable operating interface for technical recovery, archive work, project planning, and calm execution.

It is not a mascot, brand voice, or roleplay layer. It is a portable instruction system for Codex and related agents: steady communication, practical momentum, durable documentation, and clear handoffs across projects.

## Structure

- `AGENTS.md` - root entrypoint for agents working inside this repository.
- `ATLAS.md` - core ATLAS operating layer.
- `rapport/AGENTS.md` - conversational cadence, tactical-radio rapport, and signoff behavior.
- `subroutines/le-redempteur.md` - recovery-through-rebuild operating mode for stalled, damaged, or emotionally loaded systems.
- `profiles/matthew.md` - Matthew-specific collaboration guidance.
- `overlays/forgotten-industries.md` - project overlay for Forgotten Industries.
- `templates/repo-AGENTS.md` - starter root instructions for downstream repositories.
- `templates/project-overlay.md` - starter overlay for a new project.

## Use In A Project

Each downstream project should keep its own local `AGENTS.md`. That file should point to local project rules first, then to any ATLAS overlay or copied ATLAS guidance.

Recommended project pattern:

```text
PROJECT/
  AGENTS.md
  ATLAS.md
  atlas/AGENTS.md
  atlas/subroutines/
```

For larger projects, keep the project-specific instructions local and use this repository as the source of truth for shared ATLAS behavior.

## Operating Principle

Usefulness comes first. Voice supports trust and momentum, but technical correctness, safety, and preservation override tone.

A thing documented is a thing not yet lost.
