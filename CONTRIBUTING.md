# Contributing to DependencyGuard

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to DependencyGuard.
These are mostly guidelines, not rules.
Use your best judgment, and feel free to propose changes to this document in a
pull request.

# Code of Conduct

This project and everyone participating in it is governed by the
[Code of Conduct](CODE_OF_CONDUCT.md).

By participating, you are expected to uphold this code.
Please report unacceptable behavior to [mediact@github.com](mailto:mediact@github.com).

# How Can I Contribute?

## Reporting Bugs

This section guides you through submitting a bug report.
Following these guidelines helps maintainers and the community understand your
report :pencil:, reproduce the behavior :computer: :computer:, and find related
reports :mag_right:.

> **Note:** If you find a **Closed** issue that seems like it is the same thing
that you're experiencing, open a new issue and include a link to the original
issue in the body of your new one.

Please use the following as guidelines to write a bug report:

### Please describe the found bug
A clear and concise description of what the problem is.

> I'm always frustrated when [...]

### Describe the solution you'd like
A clear and concise description of what you want to happen.

> I would like the following changes to be made, in order to achieve [...]

### Describe alternatives you've considered

A clear and concise description of any alternative solutions or features you've considered.

> I have considered using **X** with **Y**, yet [...]

### Additional context

Add any other context or screenshots about the feature request here.

![Dependency Guard: JSON format](docs/composer-dependency-guard-json.png)

## Pull Requests

* Do not include issue numbers in the pull request title.
* Include screenshots and animated GIFs in your pull request whenever possible.
* Follow the style guides in this document.
* Add two of the following reviewers:
  * Ashoka de Wit
  * Jan-Marten de Boer
* Ensure Scrutinizer CI runs successfully.
  [![Build Status](https://scrutinizer-ci.com/g/mediact/dependency-guard/badges/build.png?b=master)](https://scrutinizer-ci.com/g/mediact/dependency-guard/build-status/master)
* Ensure code coverage stays the same or increases.
  [![Code Coverage](https://scrutinizer-ci.com/g/mediact/dependency-guard/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/mediact/dependency-guard/?branch=master)
* Ensure code quality stays the same or improves.
  [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/mediact/dependency-guard/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/mediact/dependency-guard/?branch=master)


## Styleguides

### PHP

The package
[`mediact/testing-suite`](https://packagist.org/packages/mediact/testing-suite)
is installed, ensuring code style and standards, as well as quality.

To locally test using the testing suite, use the following:

```
vendor/bin/grumphp run
```

This will run GrumPHP using the tests set by the testing suite.

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
