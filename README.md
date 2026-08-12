# .github

This repository holds the **default community health files** for the [KindStack](https://github.com/kindstack) organization.

GitHub automatically applies the files here to every repository in the org that does not provide its own version. A file committed in an individual repository always overrides the default in this one.

## What's in here

| File | Purpose |
| --- | --- |
| [`profile/README.md`](profile/README.md) | The org's public landing page, shown at [github.com/kindstack](https://github.com/kindstack). This is the most visible file in the repository. |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | How to file issues, name branches, write commits, and open pull requests. Linked from the "Contributing guidelines" prompt when someone opens a PR. |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Short, plain-language conduct rules. Reports go to `hello@codekind.net`. |
| [`SECURITY.md`](SECURITY.md) | How to report a vulnerability. Surfaces as the "Security policy" link on the Security tab. |
| [`SUPPORT.md`](SUPPORT.md) | Where to go for help. Linked from the new-issue page. |
| [`FUNDING.yml`](FUNDING.yml) | Drives the **Sponsor** button, pointing at Codekind's PayPal Giving Fund page (0% fees). |
| [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) | Prefills the description box on new pull requests. |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) | Bug report and feature request forms, plus `config.yml`. |

## Notes for maintainers

- **`profile/README.md` is public and prominent.** It is the first thing most people see of KindStack. Treat edits to it accordingly.
- **Issue forms deliberately do not set `labels:`.** A form that references a label which doesn't exist in the target repository fails to work there. Since these forms inherit into every repo in the org, they stay label-free.
- **Not everything is inherited.** GitHub Actions workflows, `copilot-instructions.md`, and `LICENSE` files are *not* picked up by other repositories from this one. Licences must live in each individual repository.
- **`FUNDING.yml` is verified working** and inherits correctly across the org. Leave it alone unless the donation destination genuinely changes.

If a repository needs to differ from any of these defaults, add the file to that repository directly rather than weakening the org-wide version.

## Contact

- Web: [codekind.net](https://codekind.net)
- Email: [hello@codekind.net](mailto:hello@codekind.net)
