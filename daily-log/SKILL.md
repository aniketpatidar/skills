---
name: daily-log
description: Maintain a personal daily work log in plain simple English, one file per day. Use when the user asks to log progress, update the daily log, start a new day's log, or mentions writing up what was done today.
---

# Daily Log

Keep a plain-English record of work done each day. The log lives outside the repo, in a dedicated directory, so it is not shared with teammates and never committed.

## Rules

- One file per day at `<daily-log-directory>/<DD-Mon-YYYY>.md` (e.g. `3-aug-2026.md`).
- Write in plain simple English — short bullet points, no jargon. Say what was done and why it helps (e.g. "Reduced image size before sending it to Gemini, making requests smaller and quicker.").
- Group entries under `## [<branch>] <issue title>` using the actual branch name and issue title.
- One section per issue. Working on several issues the same day means several sections in the same file.
- Append to today's file if it exists; create it if not.
- Do not log internal process details (branch renames, commit cleanup, PR descriptions).
- Do not commit the log and do not add anything to AGENTS.md for this.

## Workflow

1. Read today's file if it exists.
2. Append a new section for each issue worked on, or extend an existing section for that issue.
3. Keep bullets to one line each where possible.
