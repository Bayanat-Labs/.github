# Bayanat Labs .github

This repository holds two things for the [Bayanat Labs](https://github.com/Bayanat-Labs) GitHub organization.

1. **The organization profile.** `profile/README.md` is the page shown at [github.com/Bayanat-Labs](https://github.com/Bayanat-Labs). The two logo files next to it are used by that page, one for light themes and one for dark themes.
2. **Default community files.** Any Bayanat Labs repository that does not have its own copy uses these:
   - [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)
   - [CONTRIBUTING.md](CONTRIBUTING.md)
   - [SECURITY.md](SECURITY.md)
   - [SUPPORT.md](SUPPORT.md)
   - [.github/ISSUE_TEMPLATE/](.github/ISSUE_TEMPLATE/) with the issue forms and contact links
   - [.github/pull_request_template.md](.github/pull_request_template.md)

## Notes for maintainers

- A repository with its own `.github/ISSUE_TEMPLATE/` folder ignores every default issue form here.
- Licenses cannot be shared this way. Every repository needs its own LICENSE file.
- The issue forms only use GitHub's default labels (`bug`, `enhancement`, `question`), so they work in any new repository.
- The profile README loads its logos from `raw.githubusercontent.com` on the `main` branch. Update those URLs if the branch is ever renamed.

The Bayanat Labs name and logo are not licensed for reuse. The Code of Conduct is adapted from the [Contributor Covenant](https://www.contributor-covenant.org), version 2.1.

Questions: [hello@bayanatlabs.com](mailto:hello@bayanatlabs.com)
