# Agent Instructions — Workspace: agent-lab-dotnet

## Mandatory development checklist (must pass before PR)
1. Lint: `dotnet format` — fail the change if it produces edits.
2. Build: `dotnet build --configuration Release` from repo root.
3. Test: `dotnet test` (all test projects).

---

## Quick context
- Root: `C:\Users\mehul\source\repos\themicrosoftguy\agent-lab-dotnet`
- Target: .NET 10
- Preferred shell: `powershell.exe`
- IDE: __Visual Studio__

---

## Workflow rules (short)
- Run the mandatory checklist after changes and before opening PRs.
- Create an isolated branch: `agent/<short-task>-<timestamp>` or a git worktree for background tasks.
- Keep commits small and single-responsibility. Include unit tests for logic changes.
- PR title: `[agent] <short-summary>`. PR must list commands run and their results.

---

## Safety & escalation
- Do not commit secrets or credentials. Stop and report if found.
- Ask a human when:
  - Multiple startup projects exist and target unclear.
  - Changes affect production config, deployment, or secrets.
  - Tests fail nondeterministically after repeated attempts.

---

## Useful commands
- Find solutions: `Get-ChildItem -Path . -Filter *.sln -Recurse`
- Build: `dotnet build`
- Run project: `dotnet run --project <path>`
- Test: `dotnet test`
- Format: `dotnet format`
- Create worktree: `git worktree add ../worktree-<branch> -b <branch>`

--- 

Keep changes minimal, verifiable, and documented in the PR description.