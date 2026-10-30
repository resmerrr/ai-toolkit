# Claude Skills

> **Claude only.** Skills are a Claude feature. They do not work in ChatGPT.

A skill is a folder with instructions (a `SKILL.md` file) that Claude loads when it needs them. Once installed, a skill works in every chat. Some skills start automatically when they fit the task; others start when you type their name, such as `/i-have-adhd`.

## Available skills

| Skill | What it does | Author |
|---|---|---|
| [class-notes-style](class-notes-style/SKILL.md) | Formats explanations as compact class notes: small headings, bold key points, arrows, examples and a TL;DR | Resmer |
| [i-have-adhd](i-have-adhd/SKILL.md) | Shapes answers for ADHD readers: next action first, numbered steps, no tangents. Start with `/i-have-adhd`, stop with "stop adhd mode" | [Ayoub Ghriss (ayghri)](https://github.com/ayghri/i-have-adhd), MIT License |
| [interview](interview/SKILL.md) | Interviews you in depth about a task, then writes a detailed spec to a file. Best suited to coding projects | Based on a prompt shared by [Thariq (Anthropic)](https://x.com/trq212/status/2005315275026260309) |

## How to install a skill in Claude

**Before you start:** skills need file creation turned on. Open **Settings → Capabilities** and turn on **Code execution and file creation** (in the newer layout: **Create and edit files**).

1. Open the [`zips`](zips) folder and click the skill you want, for example `class-notes-style.zip`.
2. Click the **download button** (the arrow icon on the right) to save the zip file.
3. In Claude, open **Customize → Skills**.
4. Click **+**, then **+ Create skill**, then **Upload a skill**.
5. Choose the zip file you downloaded.
6. Make sure the skill's **toggle is on**.

*Do not unzip the file before uploading. Claude expects the zip with the skill folder inside.*

Settings names in Claude change from time to time. If a step looks different, see the official guide: [Use skills in Claude](https://support.claude.com/en/articles/12512180-use-skills-in-claude).
