# elements-of-style

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An agent skill that helps Claude Code, Gemini/Antigravity, and other AI assistants write and edit clear prose. It restates the principles of Strunk & White's *The Elements of Style* (4th ed., 2000), adapted for documentation, issue trackers, coursework, and game text.

The skill contains no text from the book. Every rule is restated in original wording with original examples. Rule tags such as R14 or V8 point to the matching rule in the book for anyone who owns a copy.

## Files

| File | Contents |
| --- | --- |
| [`SKILL.md`](./SKILL.md) | The plan, draft, revise, and proofread steps; how to edit someone else's draft; the composition rules (Chapter II) and style reminders (Chapter V). |
| [`USAGE.md`](./USAGE.md) | The proofreading pass: punctuation and grammar (Chapter I), matters of form (Chapter III), and a table of commonly misused words (Chapter IV), plus the places this skill departs from the book. |
| [`evals/`](./evals) | Test prompts, input files, and checks for comparing runs with and without the skill. |

## When it triggers

The agent loads the skill when it writes or revises text people will read: server guides, READMEs, docs, GitHub issues and PRs, release notes, in-game text, and player explanations. It also loads when asked to edit, tighten, or proofread a draft. You can call it by name with `/elements-of-style`.

## Installation

Clone it into your shared skills folder, then link it into each agent's skills folder.

```powershell
git clone https://github.com/GV-Server-Mods/elements-of-style.git "$env:USERPROFILE\.agents\skills\elements-of-style"

# Claude Code
New-Item -ItemType Junction -Path "$env:USERPROFILE\.claude\skills\elements-of-style" -Target "$env:USERPROFILE\.agents\skills\elements-of-style"
```

Gemini/Antigravity reads `~/.gemini/config/skills`. If that folder is not already linked to `~/.agents/skills`, clone or link the skill there too.

To update, run `git pull` in the clone.

## Versioning

Releases follow Semantic Versioning: patch for wording fixes, minor for new rules or coverage, major for renamed or moved files.

## License

MIT. See [LICENSE](./LICENSE).
