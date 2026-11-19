# Thinking Partner

A Claude skill that interviews you to clarify, stress-test, and articulate an idea, decision, or plan, then writes the result up as a structured document.

## What it does

- Asks 2-3 related questions per round and adapts depth to the topic (business gets challenged more, personal decisions get a gentler touch).
- Rotates forward-looking, backward-looking, and introspective questions, and plays devil's advocate when it helps.
- Proposes closure when themes dry up or answers shorten, and checks a synthesis with you before writing.
- Produces a document with Overview, Key Themes, Decisions & Positions, Open Questions, and Constraints & Boundaries. It never includes a raw Q&A transcript.

## Install

Download `SKILL.md` (or the packaged `.skill` file from Releases) and add it as a skill in Claude. For Claude Code, place the folder at `~/.claude/skills/thinking-partner/`.

## Try it

- "Interview me about moving my consulting to fixed-price packages."
- "I can't decide between a full-time job and freelancing. Help me think this through."
- "I have an idea, grill me."

## Repo layout

- `SKILL.md`: the skill.
- `evals/`: three test cases (prompt, expected outcome, assertions). `evals/personas/` holds the scripted simulated-user answers used to run them.

## Test results

Across the three cases, this version passed 15 of 15 checks, against 11 of 15 for the original draft. These were single runs with scripted users, so treat them as a sanity check rather than a benchmark.
