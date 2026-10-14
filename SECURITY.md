# Security policy

This policy covers every repository in the [Bayanat Labs](https://github.com/Bayanat-Labs) GitHub organization.

## How to report

Please do not open a public issue for a security problem.

Email [hello@bayanatlabs.com](mailto:hello@bayanatlabs.com) with "Security" in the subject line. If the repository's **Security** tab shows a **Report a vulnerability** button, you can use that instead. It sends a private report to the maintainers.

Include the repository, the version or commit, the steps to reproduce, and what an attacker could do with the problem. A short proof of concept helps.

## In scope

- Code, scripts, packages and GitHub Actions workflows in Bayanat Labs repositories
- Secrets, tokens or credentials published by mistake in our repositories or releases
- Personal or confidential data that should not be in a published file
- Release files that do not match their published checksums

Problems with www.bayanatlabs.com can be sent to the same email address.

## Out of scope

- Vulnerabilities in third-party dependencies that do not affect how we use them. Please report those to the upstream project.
- Reports from automated scanners with no demonstrated impact
- Denial-of-service or load testing, social engineering, and physical attacks
- Mistakes in data or labels that are not a security or privacy problem. Please open a regular issue for those.

## What to expect

We will acknowledge your report, keep you updated while we investigate, and tell you when a fix is released. We are happy to credit you in the release notes if you would like that.

Please give us a reasonable chance to fix the problem before you disclose it publicly. We welcome good-faith research that follows this policy, avoids privacy violations and data destruction, and does only what is needed to show the problem.

## Supported versions

We fix security problems in the latest release of each repository.
