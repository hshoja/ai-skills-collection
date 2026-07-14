# ai-skills-collection

Personal Claude Code skills - reusable workflows and automation tools.

## What are skills?

Skills are reference guides that Claude Code loads on demand to apply proven techniques. Drop any skill folder into `~/.claude/skills/` and invoke it with `/skill-name`.

## Skills

| Skill | Description |
|-------|-------------|
| [macos-disk-cleanup](./macos-disk-cleanup/SKILL.md) | Full macOS disk audit - scans all major dirs including hidden dot dirs, outputs prioritized cleanup table with exact commands |

## Installation

```bash
# Clone and symlink, or copy individual skills:
cp -r macos-disk-cleanup ~/.claude/skills/
```

Then in Claude Code: `/macos-disk-cleanup`
