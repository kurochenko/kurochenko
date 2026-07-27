# Andrej Kurochenko

Senior developer & wannabe builder.

## Projects

[**Mend**](https://github.com/kurochenko/mend) — Autonomous merge-request review for GitLab. Runs on your own machine, reviews MRs with your coding agent of choice, and posts structured findings back as draft notes.

[**cookt.io**](https://cookt.io) — Recipe organizer with AI. Paste any recipe format, get structured ingredients, steps, and chat with your recipes.

[**skillbook.dev**](https://github.com/kurochenko/skillbook) — CLI tool for managing AI skills across projects and teams. Centralized library that works with any AI harness (OpenCode, Cursor, Claude Code).

[**pi.nvim**](https://github.com/kurochenko/pi.nvim) — Neovim plugin that integrates the [Pi](https://pi.dev) coding agent into a side panel. Select code, send it to Pi with a keypress, and get responses back — with context placeholders, an action picker, and built-in prompts for explain, review, fix, test, and more.

[**living-spec**](https://github.com/kurochenko/living-spec) — Stop your AI from making things up. Framework that captures hidden project knowledge — invariants, decisions, rules — in a format your LLM reads before it writes code. Catch contradictions early, auto-generate tests from specs, and make tribal knowledge explicit.

## What I Do

Help teams integrate AI into their development workflow:
- Automating bug fixing and code review pipelines  
- Streamlining development processes
- Building tools that let developers focus on what matters

## Case Studies

### Production Incident Response: From Hours to Minutes

**Problem:** Production incidents required manual investigation across multiple systems — checking logs in CloudWatch, querying ALB logs in Athena, reviewing exceptions in Sentry, finding relevant code, and figuring out fixes. This took hours of senior engineer time.

**Solution:** Built AI agents that connect monitoring tools (CloudWatch, Sentry) to code repositories (GitLab). When an alert fires, the AI automatically pulls relevant logs, identifies the root cause, and creates a merge request with a proposed fix.

**Result:** What used to take hours of manual investigation now takes 5 minutes. Engineers review the AI-generated MR instead of hunting for the problem.

[Read article →](https://medium.com/@andrejkurocenko/from-hours-to-minutes-how-ai-agents-handle-our-production-issues-94cf8a85eab8)

### Code Review Automation

AI pipeline that analyzes PRs, suggests fixes, and auto-generates merge requests for common issues.

## Background

Started with backend (JVM, Node), moved through frontend web (React) and mobile (React Native), then cloud/serverless, Linux, and DevOps.

**Lately:** TypeScript for everything — backend, frontend, terminal UIs.


