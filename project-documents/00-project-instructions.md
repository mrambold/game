# Project Instructions

The standing instructions for Claude on this project. They are copied by hand into the Claude app's project instructions and kept in sync with this file, which is the master copy. They are sent with every message, so they stay short. They hold working rules, conventions and pointers to the other documents, never the design details themselves.

**Copy everything below the line into the Claude app.**

---

## Project
A 2D roguelike deckbuilder for PC, built in Godot 4 with C#. The player plays rounds with their deck against rising score targets. Easy to learn, hard to master, rewards synergies and combos, strong "one more run" pull. Hobby project, possible Steam release. Theme not decided yet.

## About me
Experienced .NET/C# developer, new to Godot. Explain Godot-specific concepts briefly when they come up. Don't explain general C# or .NET.

## Git: hard rule
Never commit, push, create branches, tag or open pull requests. I do all check-ins myself. Leave changes in the working tree. Read-only git commands (status, diff, log) are fine.

## Where things live
- Paths are relative to the repo root, whose location differs between my machines. Source code is in `src/`, design docs in `project-documents/`.
- The repo is the only master copy, so don't duplicate docs in the Claude project.
- Read only the docs the current task needs, not all of them.
- Check `11-decision-log.md` before reopening a question. Settled decisions stand unless I reopen them.
- Judge features against the pillars in `01-vision-pillars-and-theme.md`.

## How we work
- One topic per chat. When a topic is done, propose the updates to the affected docs plus a decision-log entry, and write them once I agree.
- Docs hold decisions and rules in compact form (bullets, tables), not long prose.
- Design direction, scope and taste are my call: ask. Weigh in when you think one of my decisions could be better.
- Routine technical details are yours: decide and mention them in a line.
- Don't paste whole files or docs into the chat. Refer to paths and show only the relevant excerpts or diffs.

## Language and formatting
- Docs and code are English only.
- The game ships in English first but must be ready for translation: no player-facing text hard-coded in code.
- All files use CRLF line endings.

## Code
- Conventions and architecture: see `09-technical-architecture.md` (not defined yet).
- Before reporting a task as done, build and run the tests. Prefer automated tests over screenshots to verify.

## Token efficiency
- Keep answers short. No recaps of what was already said. I'll ask when I want more detail.
- Use targeted reads (search, line ranges) rather than reading whole files.
- When a chat gets long or the topic changes, suggest starting a new one.
