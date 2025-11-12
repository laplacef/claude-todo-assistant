# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

An Obsidian vault used as a personal productivity system — managing tasks, daily notes, and meeting notes. There is no build system, test suite, or application code. Content is plain Markdown files organized into folders.

## Structure

- `tasks.md` — Central task list
- `scratchpad.md` — Scratch space for quick notes and drafts
- `daily-notes/` — Daily journal entries
- `meetings/` — Meeting notes
- `.obsidian/` — Obsidian vault configuration (do not modify unless asked)

## Custom Claude Commands

Located in `.claude/commands/`:
- `/start` — Morning standup: review tasks, check memory, prioritize the day
- `/sync` — Process loose notes: file scratchpad items, summarize meetings, update tasks
- `/wrap-up` — End-of-day: process remaining notes, update tasks, write daily summary, save context to memory

## Working With This Vault

- All content files are Markdown. Use Obsidian-compatible syntax (wiki-links `[[like this]]`, tags, checkboxes `- [ ]`).
- When creating daily notes, use the filename format `YYYY-MM-DD.md` inside `daily-notes/`.
- Tasks use Markdown checkbox format: `- [ ]` for incomplete, `- [x]` for complete.
- The `.gitignore` excludes Python artifacts and virtual environments — this vault may have Python tooling added alongside it.
