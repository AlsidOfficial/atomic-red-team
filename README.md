<p><img src="https://redcanary.com/wp-content/uploads/Atomic-Red-Team-Logo.png" width="150px" /></p>

# Atomic Red Team
[![CircleCI](https://circleci.com/gh/redcanaryco/atomic-red-team.svg?style=svg)](https://circleci.com/gh/redcanaryco/atomic-red-team)

Atomic Red Team allows every security team to test their controls by executing simple
"atomic tests" that exercise the same techniques used by adversaries (all mapped to
[Mitre's ATT&CK](https://attack.mitre.org)).

## Philosophy

Atomic Red Team is a library of simple tests that every security team can execute to test their controls. Tests are
focused, have few dependencies, and are defined in a structured format that can be used by automation frameworks.

Three key beliefs made up the Atomic Red Team charter:
- **Teams need to be able to test everything from specific technical controls to outcomes.**
  Our security teams do not want to operate with a “hopes and prayers” attitude toward detection. We need to know
  what our controls and program can detect, and what it cannot. We don’t have to detect every adversary, but we
  do believe in knowing our blind spots.

- **We should be able to run a test in less than five minutes.**
  Most security tests and automation tools take a tremendous amount of time to install, configure, and execute.
  We coined the term "atomic tests" because we felt there was a simple way to decompose tests so most could be
  run in a few minutes.

  The best test is the one you actually run.

- **We need to keep learning how adversaries are operating.**
  Most security teams don’t have the benefit of seeing a wide variety of adversary types and techniques crossing
  their desk every day. Even we at Red Canary only come across a fraction of the possible techniques being used,
  which makes the community working together essential to making us all better.

See: https://atomicredteam.io

## Having trouble?

Join the community on Slack at [https://atomicredteam.slack.com](https://atomicredteam.slack.com)

## Getting Started

* [Getting Started With Atomic Red Team](https://github.com/redcanaryco/atomic-red-team/wiki/About-Atomic-Red-Team)
* Automated Test Execution with the [Execution Frameworks](https://github.com/redcanaryco/atomic-red-team/wiki/Executing-Atomic-Tests#execute-an-atomic-test-with-an-execution-framework)
* Peruse the Complete list of Atomic Tests ([md](atomics/Indexes/Indexes-Markdown/index.md), [csv](atomics/Indexes/Indexes-CSV/index.csv)) and the [ATT&CK Matrix](atomics/Indexes/Matrices/matrix.md)
  - Windows [Matrix](atomics/Indexes/Matrices/windows-matrix.md) and tests by tactic ([md](atomics/Indexes/Indexes-Markdown/windows-index.md), [csv](atomics/Indexes/Indexes-CSV/windows-index.csv))
  - MacOS [Matrix](atomics/Indexes/Matrices/macos-matrix.md) and tests by tactic ([md](atomics/Indexes/Indexes-Markdown/macos-index.md), [csv](atomics/Indexes/Indexes-CSV/macos-index.csv))
  - Linux [Matrix](atomics/Indexes/Matrices/linux-matrix.md) and tests by tactic ([md](atomics/Indexes/Indexes-Markdown/linux-index.md), [csv](atomics/Indexes/Indexes-CSV/linux-index.csv))
* Using [ATT&CK Navigator](https://github.com/mitre-attack/attack-navigator)? Check out our coverage layers ([All](atomics/Indexes/Attack-Navigator-Layers/art-navigator-layer.json), [Windows](atomics/Indexes/Attack-Navigator-Layers/art-navigator-layer-windows.json), [MacOS](atomics/Indexes/Attack-Navigator-Layers/art-navigator-layer-macos.json), [Linux](atomics/Indexes/Attack-Navigator-Layers/art-navigator-layer-linux.json))
* [Fork](https://github.com/redcanaryco/atomic-red-team/fork) and [Contribute](https://github.com/redcanaryco/atomic-red-team/wiki/Contributing) your own modifications
* Have questions? Join the community on Slack at [https://atomicredteam.slack.com](https://atomicredteam.slack.com)
    * Need a Slack invitation? Submit an invite request via this [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSc3oMtugGy--6kcYiY52ZJQQ-iOaEy-UpxfSA37IlA5wCMV0A/viewform?usp=sf_link)

## Code of Conduct

In order to have a more open and welcoming community, Atomic Red Team adheres to a
[code of conduct](CODE_OF_CONDUCT.md).

## License

See the [LICENSE](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt) file.
