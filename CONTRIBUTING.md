# Contributing

Thanks for taking the time to contribute. KindStack maintains a mix of iOS/Swift apps, static websites, and small command-line utilities, so this guide stays deliberately general.

> **Individual repositories may include their own `CONTRIBUTING.md`.** When they do, it takes precedence over this org-wide default — especially for build steps, toolchain versions, and testing.

## Before you start

For anything more than a small fix, **open an issue first**. It is disappointing for everyone when a well-built pull request has to be turned down because it goes in a direction the project wasn't heading. A short conversation up front avoids that.

Small, obvious fixes — a typo, a broken link, a clearly wrong value — can go straight to a pull request.

## Filing issues

Use the issue templates. They exist so that reports arrive with the information needed to act on them.

A good bug report includes:

- What you expected to happen.
- What actually happened.
- Exact steps to reproduce it.
- Your environment — OS and version, device or simulator, language runtime, browser, whichever apply.
- Relevant logs or error output, as text rather than a screenshot where possible.

Please search existing issues before opening a new one. If you find a matching issue, adding your environment details to it is more useful than opening a duplicate.

**Never include passwords, API keys, tokens, or personal data in an issue.** If a log contains one, redact it. For security vulnerabilities, do not open an issue at all — see [SECURITY.md](SECURITY.md).

## Branches

Work on a branch off the default branch. Name it with a short prefix and a description:

```
feat/outbound-whitelist
fix/ofx-date-parsing
docs/readme-install-steps
chore/bump-dependencies
```

Common prefixes: `feat/`, `fix/`, `docs/`, `refactor/`, `test/`, `chore/`.

## Commit messages

Write a short imperative subject line under about 72 characters, describing what the commit does:

```
Add whitelist check for outbound calls
Fix crash when OFX file has no TRNUID field
```

Not `Fixed stuff` or `updates`.

If the change needs explanation, leave a blank line and add a body covering **why** the change was made. The diff already shows what changed; the reasoning is what gets lost.

Reference issues where relevant — `Fixes #12` will close the issue when the pull request merges.

We do not require [Conventional Commits](https://www.conventionalcommits.org/), but a repository is free to adopt them and will say so in its own contributing guide.

## Pull requests

- Keep each pull request to a single logical change. Several unrelated fixes in one branch are much harder to review, and one problem blocks all of them.
- Fill in the pull request template.
- Explain how you tested the change. "Built and ran on iPhone 15 simulator, iOS 17" tells a reviewer far more than "tested".
- Update the README or other docs if your change affects how someone uses the project.
- Make sure any existing tests, linters, or builds still pass.
- Do not commit generated files, build artifacts, local configuration, or anything containing credentials. If a project ships an `.env.example`, update that rather than committing a real `.env`.
- Match the existing style of the code you are editing. Consistency within a file beats personal preference.
- Draft pull requests are welcome if you want early feedback on work in progress.

Review is done by a small team, largely in spare time, so please be patient. We will get to it.

## Code of Conduct

Participation in KindStack projects is covered by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it. We take it seriously and it applies to issues, pull requests, and code review just as much as anywhere else.

## Licensing

Each repository carries its own licence. By contributing, you agree that your contribution is licensed under the licence of the repository you are contributing to.

## Questions

If you are unsure about anything, see [SUPPORT.md](SUPPORT.md), or email [hello@codekind.net](mailto:hello@codekind.net). Asking is always fine.
