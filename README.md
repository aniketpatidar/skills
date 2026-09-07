# Agent Skills

My personal collection of agent skills for any agent that supports `SKILL.md`. These skills help guide AI agents to write better code, log daily progress, and follow best practices.

## Features

- **Standardized Format**: Works with any agent supporting the `SKILL.md` format.
- **Easy Updates**: Symlink directly into your agent's skills directory.
- **Growing Collection**: Includes skills for coding practices, daily logging, and business planning.

| Skill | Description |
|-------|-------------|
| [code-like-aniket](code-like-aniket/SKILL.md) | Implement with clear orchestration, strong interfaces, and happy-path-first design |
| [daily-log](daily-log/SKILL.md) | Maintain a personal daily work log in plain simple English, one file per day. |

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/aniketpatidar/skills.git
```

Then copy or symlink the skills you want to your agent's skills directory. 
Symlinking is recommended so updates pull in automatically:

```bash
cd skills
ln -s "$(pwd)/daily-log" /path/to/agent/skills/daily-log
```

## Usage

To use a skill, simply ask your agent to load or invoke it by referencing the skill folder.

Example usage with a conversational agent:

```bash
# In your agent's chat interface or CLI:
$ "Hey Agent, please invoke the daily-log skill."
```

Or run an agent with a specific skill attached directly:

```bash
$ agent-cli --skill /path/to/agent/skills/daily-log "Write my daily log for today"
```

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request if you want to add a new helpful agent skill.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
