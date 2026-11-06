# Contributing to PALAD Technology

PALAD is run by one human owner with a team of AI agents. These rules apply to everyone - human or agent.

## Workflow

1. **Every change starts from an issue.** Use the Bug, Feature or Task form. The acceptance criteria are the definition of done.
2. **Work on a branch, never on `main`.** Name it `type/issue-number-short-description`, e.g. `feat/42-rate-alerts`, `fix/57-chart-crash`.
3. **Open a pull request** using the template. Link the issue with `Closes #N`.
4. **Checks must pass** before review.
5. **The owner approves and merges.** Agents do not merge their own PRs.

## Commits

Use [Conventional Commits](https://www.conventionalcommits.org): `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`. Keep each commit focused on one change.

## Rules for AI agents

- Read the repo's `CLAUDE.md` before starting. It overrides anything general here.
- Stay inside the issue's scope. If you find something else worth fixing, open a new issue rather than widening the PR.
- Never commit secrets, API keys or credentials. Use the repo's secrets store.
- Never force-push to shared branches, rewrite history on `main`, or disable checks.
- Don't add new dependencies without saying why in the PR.
- If a task is ambiguous or blocked, stop and ask in the issue rather than guess.
- Say honestly in the PR what was and wasn't tested.
