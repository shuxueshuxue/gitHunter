# GitHub Hunter

An autonomous AI agent that hunts for contribution opportunities on GitHub 24/7.

## Vision

GitHub Hunter is a Claude Code-powered agent that automatically:
- 🔍 Searches GitHub for interesting open source projects
- 🐛 Identifies fixable issues
- 🔧 Attempts to fix them autonomously
- 📬 Submits pull requests
- 🎯 Helps open source newcomers find "soft targets" to contribute to

## Use Cases

### 1. Autonomous Contribution Bot
Runs 24/7, expanding your GitHub network by making meaningful contributions across the ecosystem.

### 2. Newcomer Assistant
Helps open source beginners by:
- Finding projects with good first issues
- Identifying easy wins
- Demonstrating how to approach contributions
- Building confidence through successful PRs

## Architecture

Built on top of **PolyCLI** infrastructure:
- Persistent Claude Code sessions
- AgentTalk coordination
- Automated workflow execution
- Resource management (utilizing idle API quota)

## Agent Identity

**AgentTalk Agent Name**: github_hunter
**Channels**: general, github_hunter_ops
**Base Infrastructure**: PolyCLI + Claude Code

## Philosophy

> "Now that Opus became Sonnet, I have max $200/month I can't use up - might as well use the idle quota for hunting!"

Turn unused API quota into ecosystem value. Every successful PR is:
- A contribution to open source
- A learning opportunity documented
- A connection in the developer network
- A demonstration of AI-human collaboration

## Status

🚧 **Project in early planning stage**

Created: 2025-11-07
Creator: server_manager (via ubuntu_0)
Next: Launch dedicated Claude Code instance for development

## Development Plan

1. GitHub API integration (search, issues, PRs)
2. Issue analysis and difficulty scoring
3. Autonomous fix attempt workflow
4. PR generation and submission
5. Success/failure tracking
6. Newcomer recommendation system
7. 24/7 operation with PolyCLI

---

*Part of the autonomous agent ecosystem coordinated through AgentTalk*
