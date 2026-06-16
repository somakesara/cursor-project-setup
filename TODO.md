# Project Setup TODO

Track what's done and what's next. Check items off as you go.

## Must do before first real task
- [ ] Fill PROJECT.md (what, stack, entry points, key flows, layout, setup)
- [ ] Fill .cursor/rules/stack.mdc (language, framework, versions)
- [ ] Fill .cursor/rules/conventions.mdc (naming, errors, tests — even 10 bullets)
- [ ] Run: `git init`
- [ ] Run: `git config user.email "your.real@email.com"`
- [ ] Run: `git config user.name "Your Name"`
- [ ] Run: `git config core.hooksPath .githooks`
- [ ] Edit .githooks/pre-commit — replace placeholder email with real one
- [ ] First commit via VS Code Source Control panel (not the agent)

## Needed when starting real work
- [ ] Write one docs/domain/<area>.md for the first task's area
- [ ] Add at least 5 terms to docs/glossary.md
- [ ] Confirm test runner works (`npm test` / `pytest` / etc.)
- [ ] Add .editorconfig for cross-editor consistency
- [ ] Create first feature branch (never work on main)

## For the 3-role workflow
- [ ] Three prompts saved in PROMPTS.md (Planner, Implementer, Reviewer)
- [ ] Decide: same chat tab reused per role, or 3 separate chats?
- [ ] Pick checkpoint discipline: human approval after plan, after diff, after review

## Safety hardening
- [ ] Server-side branch protection on main (require PR, block direct push)
- [ ] Decide on git worktree habit for agent sessions
- [ ] Decide on pre-session snapshot habit (`git stash push -u -m "pre-agent"`)
- [ ] Optional: install gitleaks or trufflehog for secret scanning

## Ongoing hygiene
- [ ] Weekly: triage .agent/followups.md
- [ ] Weekly: review LESSONS.md, update rules from real misbehaviors
- [ ] Monthly: prune and dedupe docs/domain/*.md
- [ ] Per task: capture corrected business rules back into domain docs

## Skip for now (revisit later)
- [ ] BDD/features/*.feature — only if BDD is already a practice
- [ ] More than 3 agent roles — adds coordination cost
- [ ] MCP servers, custom tools — graduate when hitting a ceiling
- [ ] Orchestration frameworks (LangGraph, CrewAI) — overkill for solo dev

## Done log
<!-- Move completed items here with a date, or just leave checked above. -->