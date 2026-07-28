# Contributor Covenant Code of Conduct

## Our Pledge

We as members, contributors, and leaders pledge to make participation in our
community a harassment-free experience for everyone, regardless of age, body
size, visible or invisible disability, ethnicity, sex characteristics, gender
identity and expression, level of experience, education, socio-economic status,
nationality, personal appearance, race, caste, color, religion, or sexual
identity and orientation.

We pledge to act and interact in ways that contribute to an open, welcoming,
diverse, inclusive, and healthy community.

## Our Standards

HeCBench is a collaborative, academic benchmark suite. Many of its benchmarks
are ported or adapted from other open-source projects, and it spans multiple
hardware vendors (e.g. NVIDIA, AMD, Intel) and programming models (CUDA, HIP,
SYCL/DPC++, and OpenMP target offloading). Our standards reflect this
research-oriented, multi-vendor, multi-contributor nature.

Examples of behavior that contributes to a positive environment for our
community include:

* Demonstrating empathy and kindness toward other people
* Being respectful of differing opinions, viewpoints, and experiences
* Giving and gracefully accepting constructive feedback
* Accepting responsibility and apologizing to those affected by our mistakes,
  and learning from the experience
* Focusing on what is best not just for us as individuals, but for the overall
  community
* Properly attributing and crediting the original authors of any code, dataset,
  algorithm, or benchmark that is ported or adapted into HeCBench, and honoring
  the associated licenses
* Remaining vendor- and platform-neutral: comparing hardware, vendors, and
  programming models on technical merit and reporting results honestly and
  reproducibly

Examples of unacceptable behavior include:

* The use of sexualized language or imagery, and sexual attention or advances of
  any kind
* Trolling, insulting or derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or email address,
  without their explicit permission
* Plagiarism, misrepresenting authorship, or removing/omitting required license
  headers, copyright notices, or attribution of upstream sources
* Fabricating, falsifying, cherry-picking, or otherwise misrepresenting
  benchmark results, or intentionally biasing benchmarks to favor or disparage a
  particular vendor, device, or programming model
* Other conduct which could reasonably be considered inappropriate in a
  professional or academic setting

## Enforcement Responsibilities

Community leaders are responsible for clarifying and enforcing our standards of
acceptable behavior and will take appropriate and fair corrective action in
response to any behavior that they deem inappropriate, threatening, offensive,
or harmful.

Community leaders have the right and responsibility to remove, edit, or reject
comments, commits, code, wiki edits, issues, and other contributions that are
not aligned to this Code of Conduct, and will communicate reasons for moderation
decisions when appropriate.

## Scope

This Code of Conduct applies within all community spaces, and also applies when
an individual is officially representing the community in public spaces.
Examples of representing our community include using an official email address,
posting via an official social media account, or acting as an appointed
representative at an online or offline event.

## Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported to the community leaders responsible for enforcement by opening a
confidential report with the HeCBench maintainers via the
[ORNL/HeCBench](https://github.com/ORNL/HeCBench) repository (for example, by
contacting a maintainer directly). All complaints will be reviewed and
investigated promptly and fairly.

All community leaders are obligated to respect the privacy and security of the
reporter of any incident.

## Enforcement Guidelines

Community leaders will follow these Community Impact Guidelines in determining
the consequences for any action they deem in violation of this Code of Conduct:

### 1. Correction

**Community Impact**: Use of inappropriate language or other behavior deemed
unprofessional or unwelcome in the community.

**Consequence**: A private, written warning from community leaders, providing
clarity around the nature of the violation and an explanation of why the
behavior was inappropriate. A public apology may be requested.

### 2. Warning

**Community Impact**: A violation through a single incident or series of
actions.

**Consequence**: A warning with consequences for continued behavior. No
interaction with the people involved, including unsolicited interaction with
those enforcing the Code of Conduct, for a specified period of time. This
includes avoiding interactions in community spaces as well as external channels
like social media. Violating these terms may lead to a temporary or permanent
ban.

### 3. Temporary Ban

**Community Impact**: A serious violation of community standards, including
sustained inappropriate behavior.

**Consequence**: A temporary ban from any sort of interaction or public
communication with the community for a specified period of time. No public or
private interaction with the people involved, including unsolicited interaction
with those enforcing the Code of Conduct, is allowed during this period.
Violating these terms may lead to a permanent ban.

### 4. Permanent Ban

**Community Impact**: Demonstrating a pattern of violation of community
standards, including sustained inappropriate behavior, harassment of an
individual, or aggression toward or disparagement of classes of individuals.

**Consequence**: A permanent ban from any sort of public interaction within the
community.

## Research and Benchmarking Integrity

Because HeCBench is used to study performance, portability, and productivity, the
integrity of its code and results is essential. Contributors are expected to:

* **Attribution and licensing.** When adding a benchmark that is ported or
  adapted from an external project, retain the original license and copyright
  notices, comply with that license, and link to the upstream source (as is done
  throughout the `README.md`). Do not submit code you are not permitted to
  redistribute.
* **Honest results.** Report performance and correctness results truthfully and,
  where possible, reproducibly. Do not fabricate, falsify, or selectively present
  measurements.
* **Fair comparisons.** Implement each programming-model variant (CUDA, HIP,
  SYCL, OpenMP) in good faith so that cross-vendor and cross-model comparisons
  remain fair and meaningful. Avoid intentionally handicapping any vendor,
  device, or model.
* **Correctness.** Keep the reference/verification logic of a benchmark intact so
  that results can be validated.

## Contribution, Review, and Merge Process

To keep HeCBench a healthy and collaborative project, all contributors are
expected to follow the process below in addition to the standards above:

* **Pull Requests.** All changes must be submitted through a pull request (PR).
  Do not push directly to the `master` branch. Each PR should have a clear
  description of the motivation and the changes made, and should reference any
  related issue.
* **Review.** Every PR requires at least one approving review from a project
  maintainer before it can be merged. Reviewers and authors are expected to
  communicate respectfully and constructively, in line with this Code of
  Conduct.
* **Merge.** Only project maintainers merge PRs, and only after required reviews
  and continuous integration checks pass. Authors should not merge their own PRs
  without maintainer approval.
* **New benchmarks.** When contributing a new benchmark, include the required
  attribution and licensing information for any upstream source, and provide the
  corresponding programming-model variants and verification where applicable.
* **Issues.** Use issues to report bugs, request features, or discuss design
  decisions before opening large PRs.

## Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage],
version 2.1, available at
[https://www.contributor-covenant.org/version/2/1/code_of_conduct.html][v2.1].

Community Impact Guidelines were inspired by
[Mozilla's code of conduct enforcement ladder][mozilla].

For answers to common questions about this code of conduct, see the FAQ at
[https://www.contributor-covenant.org/faq][faq]. Translations are available at
[https://www.contributor-covenant.org/translations][translations].

[homepage]: https://www.contributor-covenant.org
[v2.1]: https://www.contributor-covenant.org/version/2/1/code_of_conduct.html
[mozilla]: https://github.com/mozilla/diversity
[faq]: https://www.contributor-covenant.org/faq
[translations]: https://www.contributor-covenant.org/translations
