# ai-skills-collection

Personal Claude Code skills - reusable workflows and automation tools.

## What are skills?

Skills are reference guides that Claude Code loads on demand to apply proven techniques. Drop any skill folder into `~/.claude/skills/` and invoke it with `/skill-name`.

## Skills

| Skill | Description |
|-------|-------------|
| [macos-disk-cleanup](./macos-disk-cleanup/SKILL.md) | Full macOS disk audit - scans all major dirs including hidden dot dirs, outputs prioritized cleanup table with exact commands |
| [macos-cpu-cooling](./macos-cpu-cooling/SKILL.md) | Interactive CPU hog hunt - renders a live process table (PID, CPU%, MEM%, category, plain-English description), asks per-process what to do, repeats until cool |

## Installation

```bash
# Copy individual skills:
cp -r macos-disk-cleanup ~/.claude/skills/
cp -r macos-cpu-cooling ~/.claude/skills/
```

Then in Claude Code: `/macos-disk-cleanup` or `/macos-cpu-cooling`
