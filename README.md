# PALAD Technology - org defaults

This is the organisation's special `.github` repository. GitHub applies the files here to every repository in `palad-technology` that doesn't have its own version.

| Path | What it does |
|---|---|
| `profile/README.md` | Public profile shown on github.com/palad-technology |
| `ISSUE_TEMPLATE/` | Default issue forms (bug, feature, task) |
| `PULL_REQUEST_TEMPLATE.md` | Default PR description |
| `CONTRIBUTING.md` | How work flows from task to merge - for humans and AI agents |
| `SECURITY.md` | How to report a vulnerability |

This repo is public by necessity - GitHub only applies defaults from a public `.github` repo. Nothing confidential belongs here.

Things that are **not** inherited from this repo and must be set elsewhere:
- Branch protection and rulesets - Org settings > Repository > Rulesets
- `CODEOWNERS` - each repo needs its own
- Dependabot config - each repo needs its own `.github/dependabot.yml`
