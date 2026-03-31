# claude-config

Personal AI agent definitions for Claude and Gemini, version controlled and shared across projects.

## Structure

```
claude-config/
  claude/
    agents/       # Claude Code agent definitions (~/.claude/agents/)
  gemini/
    agents/       # Gemini CLI agent definitions (~/.gemini/agents/)
```

## Setup

Create symlinks so agents are available globally:

```cmd
mklink /D "C:\Users\<you>\.claude\agents" "E:\Development\claude-config\claude\agents"
mklink /D "C:\Users\<you>\.gemini\agents" "E:\Development\claude-config\gemini\agents"
```

## Agents

| Agent | Description |
|---|---|
| `bob` | Senior software craftsman modeled after Robert C. Martin (Uncle Bob). Code reviews, refactoring, SOLID principles. |
| `aswath` | Valuation and corporate finance expert modeled after Professor Aswath Damodaran. |
