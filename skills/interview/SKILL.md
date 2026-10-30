---
name: interview
description: Interview the user in depth about a task or project, then write a detailed spec to a file. Use when a task has unclear requirements or the user asks to be interviewed first.
allowed-tools: AskUserQuestion, Write, Agent
---

> **Credit:** based on the "interview me" spec prompt shared by Thariq (Anthropic) on X: https://x.com/trq212/status/2005315275026260309. Packaged as a skill; not original work of this repository's owner.

Follow the user instructions and interview me in detail using the AskUserQuestionTool about literally anything: technical implementation, UI & UX, concerns, tradeoffs, etc. but make sure the questions are not obvious. be very in-depth and continue interviewing me continually until it's complete. then, write the spec to a file.

Save location: `<cwd>/.plans/<relevant-name>.md`

- `<cwd>` = the current working directory — the project you are actually working in. Specs live with the code they describe so they are easy to find, open in an editor, and commit alongside the work.
- `<relevant-name>` = a short kebab-case slug describing the spec topic, ending in `-spec.md` (e.g. `friends-tab-redesign-spec.md`).
- Create the `.plans/` directory if it does not exist — the Write tool creates parent directories automatically.
- Always resolve and write the absolute path, and state the path you wrote to in your reply.
- Do not save specs under `~/.claude/` — they become impossible to find there.

<instructions>$ARGUMENTS</instructions>