# My GitHub Stats

This repository is used to collect and store my GitHub statistics. The data is collected daily via a GitHub Actions workflow.

## Workflow

The workflow is defined in [`.github/workflows/gh_stats.yml`](./.github/workflows/gh_stats.yml). It uses the following actions:

- [LukeHagar/stats-action](https://github.com/LukeHagar/stats-action) to collect the stats.
- [stefanzweifel/git-auto-commit-action](https://github.com/stefanzweifel/git-auto-commit-action) to commit the updated stats file.

The stats are saved in the `handika-gh-stats.json` file.
