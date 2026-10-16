<!-- markdownlint-disable MD033 MD041 -->

<div align="center">

[中文](./CONTRIBUTING.md) | English

</div>

# Contributing to Project Hazelita

Thank you for taking the time to contribute to Project Hazelita.

A contribution does not have to begin with a Pull Request. A useful bug report, a thoughtful question, a documentation improvement, a translation, a design suggestion, a code review, or even a small idea shared at the right moment can help make Project Hazelita better.

If you are new here, it is perfectly fine to start small.

## Before You Begin

This document describes the default contribution guidelines shared across Project Hazelita projects. Different projects may use different programming languages, tools, development workflows, and release processes. If the repository you are contributing to has its own `CONTRIBUTING.md`, development documentation, or other project-specific instructions, please follow that project's rules first.

When participating in Project Hazelita projects, please also follow our [Code of Conduct](./CODE_OF_CONDUCT-en.md) and the [Project Hazelita Community Guidelines](https://github.com/ProjectHazelita/community-guidelines).

## Issues

Before opening a new Issue, we recommend searching existing Issues to see whether the same problem or topic has already been reported or discussed.

### Reporting Bugs

If you find a bug, please provide enough information for others to understand and reproduce it.

Helpful information usually includes:

- What actually happened;
- What you expected to happen;
- Steps to reproduce the problem;
- The affected version or commit;
- Your operating system, runtime environment, or relevant dependency versions;
- Logs, screenshots, or error messages that may help identify the cause.

Before sharing logs, screenshots, or configuration files publicly, please remove passwords, tokens, personal information, and other sensitive data. If the issue may involve a security vulnerability, do not open a public Issue. Instead, report it privately by following the project's `SECURITY.md` or Project Hazelita's default [Security Policy](https://github.com/ProjectHazelita/.github/blob/main/SECURITY.md).

### Feature Suggestions

We welcome feature suggestions. A helpful suggestion usually begins by explaining "what problem you are trying to solve," rather than only "which implementation you want us to adopt."

Please try to describe the specific use case, the limitations of existing features or alternatives, and the outcome you hope to achieve. If you have relevant examples, screenshots, or reference materials, feel free to include them. You do not need to come with a complete design or implementation plan; for suggestions with a broad scope or potential effects on architecture or existing behavior, it is usually more helpful to discuss requirements and trade-offs before starting implementation.

## Pull Requests

Each Pull Request should focus on a clear purpose. Before submitting one, please do your best to confirm the following, as appropriate for the project:

- The project builds or runs in your environment;
- You have run the relevant tests, linters, and formatters provided by the project;
- If behavior has changed, the corresponding documentation has also been updated;
- The changes do not include large-scale formatting or refactoring unrelated to the purpose of the Pull Request;
- The Pull Request explains what changed and why the change is needed.

In general, small, focused Pull Requests are easier to understand, review, and maintain than submissions containing many unrelated changes.

## Commits

Project Hazelita generally follows [Conventional Commits](https://www.conventionalcommits.org/zh-hans/v1.0.0/), with a [gitmoji](https://gitmoji.dev/) added after the commit message's type to describe the change. We use the following commit message template:

```text
<type>[optional scope]: <gitmoji> <description>

[optional body]

[optional footer(s)]
```

The `scope`, `body`, and `footer(s)` are all optional. For example, the following commit message follows our format and includes a `scope`, but no `body` or `footer(s)`:

```text
fix(docker): :bug: build memory images via buildx bake to grant host networking
```

Different projects may use different commit conventions. If a repository does not specify a particular format, please follow the convention above and try to keep commit messages concise and clear about the purpose of each change.

A clear Git history is valuable, but we do not expect contributors to spend an unreasonable amount of time repeatedly reorganizing local commits just to submit a Pull Request.

Depending on the project's merge strategy, maintainers may squash, rebase, or otherwise reorganize commits when merging.

## Code Review

Code review is about the contribution itself, not a judgment of the contributor.

When reviewing someone else's work, please try to:

- Explain why a change is needed;
- Distinguish between required changes and suggestions, preferences, or optional improvements;
- Be patient with contributors who are unfamiliar with the project or the relevant technology;
- Interpret others' words in good faith where reasonable;
- Focus criticism on code, design, documentation, and specific behavior, rather than on the contributor personally.

When receiving review feedback, you are welcome to ask questions or disagree. If you do not understand why a change is needed, you can ask the reviewer directly.

## AI-Assisted Contributions

Project Hazelita welcomes responsible use of AI-assisted development tools. We accept the use of AI tools for programming, debugging, writing documentation, translation, organizing information, research, and exploring possible implementations. However, the person submitting a contribution remains responsible for it.

Before submitting AI-generated or AI-modified content, please make a reasonable effort to confirm that:

- You understand what the code or text you are submitting does;
- It actually solves the intended problem;
- It has been tested where appropriate;
- It does not contain obvious errors, fabricated information, or unverified assumptions;
- It does not accidentally include passwords, tokens, personal information, or other secrets;
- It does not introduce third-party code, text, images, or other materials that you are not entitled to use or whose licenses are incompatible with the project;
- You can explain, discuss, and revise the contribution in response to feedback during review.

Please do not submit large amounts of unchecked generated content and expect maintainers to perform all the verification for you. If AI assistance played a substantial role in a contribution, and explaining that role would help maintainers understand how the content was produced or verified, we welcome that context in the Pull Request.

## Security Issues

Please **do not report security vulnerabilities through public Issues, Discussions, or Pull Requests**.

If you discover a potential security issue, consult the affected repository's `SECURITY.md`. If the project does not provide its own security policy, follow Project Hazelita's default [Security Policy](https://github.com/ProjectHazelita/.github/blob/main/SECURITY.md). If you are unsure whether an issue has security implications, reporting it privately first is usually the safer choice.

## Licensing and Third-Party Content

By contributing to a Project Hazelita repository, you agree that your contribution may be distributed under that repository's license, unless the project explicitly states otherwise.

Please submit only content you have the right to contribute. If your contribution includes third-party code, assets, text, or other materials, make sure their licenses, attribution requirements, and other conditions of use are compatible with the target project. Different Project Hazelita projects may use different licenses, so refer to the license files in the specific repository.

## Not Sure Where to Start?

That is okay. You can:

- Browse existing Issues;
- Look for documentation that is unclear or could be improved;
- Start or join a discussion;
- Help test a project;
- Share an idea that is not fully formed yet;
- Or join the Project Hazelita community and talk with us there.

---

<div align="center">

Thank you for helping Project Hazelita grow, little by little,\
through an Issue, a patch, an idea, a review, or a conversation.🌱

</div>
