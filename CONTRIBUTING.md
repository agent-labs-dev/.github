# Contributing

Thanks for helping with an Agent Labs project. This guide covers every repository that has no
`CONTRIBUTING.md` of its own. Agent-assisted contributions are welcome and follow the same rules.

## Before you start

- Read the repository's `README.md`, and its `AGENTS.md` where there is one: it lists the setup,
  check and release commands, and the conventions no linter enforces.
- Open an issue before starting a feature, so the idea is agreed before code is written. A small bug
  fix can go straight to a pull request.
- Report security problems privately, as [SECURITY.md](https://github.com/agent-labs-dev/.github/blob/main/SECURITY.md)
  describes, never in a public issue or pull request.

## Making a change

- Branch from the default branch and keep each pull request to one change.
- Run the repository's checks before pushing: its formatter, linter, type checker and tests, with the
  commands in `AGENTS.md` or `README.md`. CI runs the same commands and must pass before a merge.
- Add or update tests for the behaviour you change.
- If a file says it is generated, change its generator and regenerate it instead of editing it.
- In a repository with a `CHANGELOG.md`, add one line under `## [Unreleased]` for any change a user
  would notice.
- Never commit secrets, tokens, `.env` files or private data, even expired or in a test.

## Commits and pull requests

- Sign your commits (`git commit -S`). The default branch accepts signed commits only.
- Write commit messages and pull request titles as [Conventional Commits](https://www.conventionalcommits.org/),
  for example `fix(cli): keep the exit code when output is piped`. Pull requests are squash merged, so
  the title and description become the commit on the default branch.
- Fill in the pull request template: why, what changed, and the checks you ran with their results. Link
  each issue the pull request resolves with its own `Closes #123` line.
- Every review thread is resolved before a merge. Reply in the thread with what you changed or why it
  does not apply.

## Licence

By contributing you agree that your contribution is licensed under the repository's licence, as given in
its `LICENSE` file, and that you have the right to submit it.

## Conduct

Everyone taking part follows the [code of conduct](https://github.com/agent-labs-dev/.github/blob/main/CODE_OF_CONDUCT.md).
