# Decision Log

A dated record of every significant decision, with the reasoning and the alternatives we rejected. It keeps us from reopening settled questions and lets a new conversation catch up quickly without rereading old chats.

| # | Date | Decision | Reason | Alternatives rejected |
|---|---|---|---|---|
| 1 | 2026-10-24 | Fresh concept. The theme is chosen as part of the vision work. | Start without assumptions. The earlier "Service Line" kitchen concept is not carried over. | Continue the kitchen concept |
| 2 | 2026-10-24 | Hobby project with a possible Steam release. Light market research only, no marketing. | Keeps scope realistic, while research keeps the hook distinct. | Full commercial plan with marketing |
| 3 | 2026-10-24 | Engine: Godot 4 with C#. | Owner is an experienced .NET/C# developer. | GDScript, other engines |
| 4 | 2026-10-24 | Placeholder art first. Final art later, either commissioned or generated with ComfyUI. | Gameplay gets proven before money or time goes into art. | Final art from the start |
| 5 | 2026-10-24 | Docs and code in English only. The game ships in English first and is built ready for translation. | One working language. Translation stays possible without rework. | German docs, hard-coded text |
| 6 | 2026-10-24 | All files use CRLF line endings, enforced with `.gitattributes`. | Matches the owner's git setup on every machine. | LF, relying on per-machine git config |
| 7 | 2026-10-24 | Claude never commits, pushes, branches, tags or opens pull requests. The owner does all check-ins. Read-only git commands are allowed. | Owner keeps full control over version history. | Claude commits work in progress |
| 8 | 2026-10-24 | The repo is the only master copy of the docs. Project instructions are copied by hand into the Claude app. A `CLAUDE.md` file is added when coding starts. | One source of truth, no drift between copies. | Docs also stored in the Claude project |
