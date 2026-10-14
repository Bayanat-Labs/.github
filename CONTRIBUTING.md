# Contributing to Bayanat Labs projects

Thank you for helping. This guide applies to every repository in the [Bayanat Labs](https://github.com/Bayanat-Labs) organization unless a repository has its own CONTRIBUTING file.

## Start with an issue

For anything bigger than a typo, please open an issue before you write code. Tell us what you want to change and why. We will reply on the issue, and once we agree on the approach you can open a pull request. This saves you from building something we cannot merge.

## Good first contributions

- Bug reports with a small example that reproduces the problem
- Fixes for bugs that already have an issue
- Tests, especially Arabic edge cases such as diacritics, hamza and alef forms, tatweel, Arabic-Indic digits, and mixed Arabic and English text
- Documentation fixes and clearer examples

## Rules for data

These rules protect you, the people in the data, and the projects.

- **No large or third-party datasets in git.** Large data stays at its original source or on a separate data host. Repositories hold code, small fixtures that are synthetic or written by the contributor, and scripts that download or rebuild data.
- **Keep files small.** Keep each file under 10 MB. GitHub rejects files over 100 MiB.
- **Only data you can share.** Add Arabic text, audio or images only if you wrote them yourself, they are clearly synthetic, or their license allows redistribution. Name the source and its license in your pull request.
- **No personal data.** Do not put real names, phone numbers, national ID or Iqama numbers, IBANs, email addresses or street addresses in code, tests, issues or pull requests. Use made-up values and say that they are made up.
- **Keep fixture text as written.** Do not change diacritics, letter forms or digits in test data unless the test is about normalization.
- **No secrets.** Never commit API keys, tokens or `.env` files.

## Pull requests

- Keep each pull request focused on one change.
- Run the tests before you push. Each repository README explains how.
- Describe what changed, why, and how you tested it. The pull request template lists what we need.
- Update the README or docs when behavior changes.
- Do not add performance claims or benchmark numbers to a README unless they come from a run that anyone can reproduce with the repository.

By submitting a pull request, you agree that your contribution is licensed under that repository's license.

## Citing our work

Each project repository has a `CITATION.cff` file. Use the "Cite this repository" button on GitHub to get APA or BibTeX. When a release has a Zenodo DOI, please cite the DOI.

## Conduct and security

Everyone taking part follows our [Code of Conduct](https://github.com/Bayanat-Labs/.github/blob/main/CODE_OF_CONDUCT.md). Please report security problems privately, as described in our [security policy](https://github.com/Bayanat-Labs/.github/blob/main/SECURITY.md), and not in a public issue.

## Questions

See [SUPPORT.md](https://github.com/Bayanat-Labs/.github/blob/main/SUPPORT.md), or email [hello@bayanatlabs.com](mailto:hello@bayanatlabs.com).
