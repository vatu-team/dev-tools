# Dev Tools

**A collection of development tools for PHP/WordPress projects. Helping simplify and standardise your development process.**

[![Commit](https://github.com/vatu-team/dev-tools/actions/workflows/commit.yml/badge.svg)](https://github.com/vatu-team/dev-tools/actions/workflows/commit.yml)

## Project URLs

- [Readme](https://github.com/vatu-team/dev-tools/blob/trunk/readme.md)

## Supported Versions

PHP Dev Tools follows [Semantic Versioning](https://semver.org/) and supports the following PHP versions:

| PHP Version | Dev Tool v2.0 | Dev Tool v2.1 |
|-------------| :----:        | :----:        |
| PHP 8.5     |               | ✔             |
| PHP 8.4     | ✔             | ✔             |
| PHP 8.3     | ✔             | ✔             |
| PHP 8.2     | ✔             | ✔             |
| PHP 8.1     | ✔             | ✔             |
| PHP 8.0     | ✔             | ✔             |
| PHP 7.4     | ✔             | ✔             |

PHP version widening is considered MINOR releases. As this is backward compatible functionality.

PHP version deprecation is considered MINOR releases. These are not breaking changes. If your project requires a version
of PHP that is no longer supported you are not be able to update this package.

Security releases will be made as PATCH releases. For legacy MINOR versions of this package will be released when deemed beneficial.

## Installation

## Composer

We reccomend installing the tools seperatly to your project to avoid conflicts with other packages or PHP versions.

```bash
composer require vatu/dev-tools --working-dir=./tools
```

Tools can be access via:

```bash
./tools/vendor/bin/{tools}
```

## Reporting Issues

If you spot any issues please create a ticket via the project's Issue Tracker. Including the issue, the browser and operating system, and how to replicate it. If the issue is security related please use the contact information below.

## Coordinated Disclosure

Keeping user information safe and secure is a top priority, and we welcome the
contribution of external security researchers. If you believe you've found a
security issue in software that is maintained in this repository, please read
[SECURITY](https://github.com/vatu-team/dev-tools/blob/trunk/security.md) for instructions on submitting a vulnerability report.

## Contact

Vatu - [hello@vatu.dev](hello@vatu.dev)

## Copyright

© 2022-2025 Vatu Limited and licensed for use under the terms of the
MIT License (MIT). Please see [LICENSE](https://github.com/vatu-team/dev-tools/blob/trunk/license.txt) for more information.
