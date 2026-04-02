# Inbox Triage Agent

An AI agent that reads your Gmail inbox, classifies emails by priority, and sends you a daily digest summary.

## What It Does
- Reads unread emails from your Gmail inbox
- Classifies each email (urgent, action needed, FYI, low priority)
- Creates a digest email summarizing what needs your attention
- Runs automatically on weekday mornings

## Setup
1. Install Claude Code: `npm install -g @anthropic-ai/claude-code`
2. Connect the Gmail MCP connector in Claude Code or Cowork
3. Create a scheduled task (weekdays at 7:00 AM)
4. Copy the contents of trigger-prompt.md into the task instructions
5. Customize gmail-labels.json to match your label setup
