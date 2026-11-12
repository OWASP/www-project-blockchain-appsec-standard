# Contributing Guidelines

Thank you for your interest in contributing to an OWASP project. We welcome all
contributions and appreciate your efforts to improve our projects.

## Getting Started

To get started with contributing to any OWASP project, please follow these
steps:

1. [Join](http://owasp.org/slack/invite) the
   [OWASP Slack workspace](https://owasp.slack.com) to connect with the OWASP
   community and get help with any questions you may have.

2. Visit the project's
   [repository](https://github.com/OWASP/www-project-blockchain-appsec-standard)
   to familiarize yourself with the project goals and objectives.

3. Choose a [guide][ref-1] to which you would like to contribute, or decide on a
   guide on an additional topic if it does not yet exist.

4. Fork the repository and clone it to your local machine.

5. Install any necessary dependencies and set up your development environment.

6. Make your changes and test them locally to ensure they work as expected.
   Run the
   [Markdown Formatting Validation](.github/workflows/markdown-linter.yml)
   check against Markdown files:

   ```bash
   npx --yes markdownlint-cli2 "**/*.md" "**/*.markdown"
   ```

7. Submit a pull request with your changes.

## Pull Request Guidelines

Before submitting a pull request, please make sure:

1. Your changes are consistent with the project's goals and objectives.

2. Your changes are well-documented and follow the project's coding standards.
   Markdown files must pass
   [Markdown Formatting Validation](.github/workflows/markdown-linter.yml).

3. Your changes do not introduce new bugs or break existing functionality.

4. Your changes are accompanied by tests, if applicable. Pull requests run
   these CI checks when the matching files change:
   [Markdown Formatting Validation](.github/workflows/markdown-linter.yml)
   for Markdown, and
   [Validate OWASP entity metadata][owasp-metadata]
   for OWASP metadata files.

5. Your pull request includes a clear and concise description of the changes you
   have made. Follow the
   [pull request template](.github/pull_request_template.md)
   that GitHub shows when you open a pull request.

## Code of Conduct

We ask that all contributors to OWASP projects abide by our
[Code of Conduct](https://owasp.org/www-policy/operational/code-of-conduct).
This code outlines our expectations for behavior within the project community
and helps us maintain a welcoming and inclusive environment for all
contributors.

Thank you for your interest in contributing to the OWASP Blockchain AppSec
Standard. We appreciate your efforts to help us improve and grow our project.

[ref-1]:
https://github.com/OWASP/www-project-blockchain-appsec-standard/tree/main/guides

[owasp-metadata]: .github/workflows/validate-owasp-metadata.yaml
