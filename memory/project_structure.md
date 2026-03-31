---
name: Project Structure
description: Workspace and repo structure for the stockBetaContext project
type: project
---

One VS Code workspace, two repos:

1. `E:\Development\ideas\stockBetaContext` — main project repo (StockBeta app)
2. `E:\Development\claude-config` — separate repo for Claude and Gemini agent definitions

**Why:** Agents are managed independently so they can be reused across projects. Symlinks connect `~/.claude/agents/` and `~/.gemini/agents/` to `claude-config`.

**How to apply:** When working in this workspace, changes to agents go in `claude-config`, not in the project repo's `.claude/agents/` or `.gemini/agents/` folders.
