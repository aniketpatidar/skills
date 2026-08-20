# skills

My personal collection of agent skills for any agent that supports `SKILL.md`.

## Skills

| Skill | Description |
|-------|-------------|
| [daily-log](daily-log/SKILL.md) | Maintain a personal daily work log in plain simple English, one file per day. |

## Install

```bash
git clone https://github.com/aniketpatidar/skills.git
cp -r skills/daily-log /path/to/agent/skills/
```

Or symlink it so updates pull in automatically (assuming you are inside the cloned repo):

```bash
ln -s "$(pwd)/daily-log" /path/to/agent/skills/daily-log
```
