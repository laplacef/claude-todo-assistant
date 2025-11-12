# claude-todo-assistant

A personal productivity system powered by an Obsidian vault and Claude Code. Manages tasks, daily notes, meetings, and scratch notes through a set of conversational commands.

## Structure

```
tasks.md            # Central task board
scratchpad.md       # Quick-capture scratch space
daily-notes/        # Daily journal entries (YYYY-MM-DD.md)
meetings/           # Meeting notes and transcripts
```

## Claude Code Commands

| Command | What it does |
|---------|-------------|
| `/start` | Morning standup — reviews tasks, checks context from previous sessions, helps prioritize the day |
| `/sync` | Processes scratchpad and meeting notes, updates the task board and daily note |
| `/wrap-up` | End-of-day close-out — files remaining notes, updates tasks, saves context for tomorrow |

## How It Works

Claude Code acts as a personal assistant across sessions. Context is carried over via `.claude/memory.md`, so follow-ups and priorities persist between conversations. The three commands map to a daily workflow: start the day, sync throughout, wrap up at the end.

## Credits

The idea for this setup was inspired by Nori Nishigaya's [Obsidian + Claude Code is Beyond Useful](https://emergentinsights.substack.com/p/obsidian-claude-code-is-beyond-useful) on Substack, which explores pairing an Obsidian vault with Claude Code as a daily productivity system.
