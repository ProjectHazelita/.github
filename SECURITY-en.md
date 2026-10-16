<!-- markdownlint-disable MD033 MD041 -->

<div align="center">

[中文](./SECURITY.md) | English

</div>

# Security Policy

Thank you for helping keep Project Hazelita and its users safe. 🌌

If you discover a security vulnerability in a Project Hazelita project, please report it through a private channel first, and avoid disclosing the vulnerability details through public Issues, Discussions, Pull Requests, community messages, or other public means before the maintainers have had a chance to learn about and address the issue.

## Reporting Security Vulnerabilities

If the affected repository has GitHub's **Private Vulnerability Reporting** enabled, please use the **Report a vulnerability** feature on the repository's **Security** page as your first option.

If the repository provides its own `SECURITY.md` or other security reporting instructions, please follow that project's own policy first.

If none of the above options are available, you can:

- Contact the project's maintainers through the private contact details they have publicly provided;
- Create an ordinary Issue that contains no vulnerability details, asking only for an available private security contact channel.

Before establishing private contact, please do not publish vulnerability details, exploit code, sensitive logs, or other information that might help others reproduce the vulnerability in a public place.

A helpful vulnerability report can typically include:

- The affected repository, component, version, or commit;
- A brief description of the vulnerability;
- Steps to reproduce the issue or a minimal Proof of Concept;
- The security impact you believe it may have;
- Relevant logs, screenshots, requests, or other technical details;
- Possible mitigations or fix suggestions, if you have already identified any.

Reporting a security issue does not require you to be able to provide complete exploit code or a fix.

Before submitting, please make every effort to remove personal information, passwords, access tokens, private keys, and other secrets unrelated to the vulnerability.

## What Should Be Reported Privately?

If an issue could enable an attacker to do any of the following, please prioritize reporting it through a security channel:

- Execute unexpected code or commands;
- Bypass authentication or permission controls;
- Access, modify, or leak data without authorization;
- Escalate privileges;
- Obtain credentials, tokens, keys, or other secrets;
- Significantly disrupt the availability or integrity of a service;
- Attack other users through behavior they cannot reasonably expect;
- Otherwise affect the confidentiality, integrity, or availability of the project or its users.

If you are unsure whether an issue constitutes a security vulnerability, reporting it privately first is usually the safer choice. Ordinary bugs without an obvious security impact can be reported through the project's normal Issue Tracker.

## Coordinated Disclosure

Please give the maintainers a reasonable amount of time to investigate, confirm, and address the issue before publicizing the full technical details of a vulnerability.

When conditions allow, the maintainers of Project Hazelita will try to work with the reporter to:

- Confirm and understand the vulnerability;
- Determine the affected scope;
- Develop or coordinate a fix;
- Determine a reasonable disclosure timeline;
- Publish a Security Advisory where appropriate;
- Provide reasonable credit to the reporter.

The complexity, risk, and remediation cost of different vulnerabilities can vary widely, so this organization-level default policy does not promise fixed response or remediation timelines. The timing and manner of public disclosure should prioritize the safety of affected users while respecting the contributions made by security researchers.

## Good-Faith Security Research

Project Hazelita welcomes good-faith security research aimed at improving the security of its projects.

When conducting testing, please make reasonable efforts to:

- Not access data that is unrelated to verifying the vulnerability and does not belong to you;
- Not modify or delete other people's data;
- Not disrupt services or cause significant impact to other users;
- Use the minimum privileges and the lowest-impact approach necessary to demonstrate the issue;
- Stop promptly if continuing testing could cause harm;
- Report discovered issues through an appropriate private channel.

Vulnerability verification should be sufficient to demonstrate that a security issue exists, without causing unnecessary impact.

Unless a specific project explicitly states otherwise, Project Hazelita currently does not offer a Bug Bounty, monetary rewards, or other vulnerability reporting reward programs.

Reporting a vulnerability in good faith does not mean you are authorized to engage in behavior that may be illegal, disrupt services, or infringe on the rights of others.

## Fixes and Public Disclosure

For issues where premature public disclosure could expose users to additional risk, security fixes may be made privately.

After the issue has been properly addressed, the maintainers may publish a Security Advisory or other announcement describing:

- The affected versions or scope;
- The impact of the vulnerability;
- The fix or mitigation;
- Any necessary upgrade recommendations;
- Appropriate credit to the reporter.

## Scope of Support

This document is the organization-level security policy used by default across Project Hazelita projects.

Different projects may have different supported versions, threat models, deployment methods, security boundaries, vulnerability reporting channels, response and disclosure processes, and so on. If a specific repository has its own `SECURITY.md`, that repository's security policy takes precedence. In addition, the fact that a repository does not list supported versions separately does not mean that all historical versions will continue to receive security updates.

---

<div align="center">

The best companions of security research are curiosity and a sense of responsibility.\
Thank you for choosing to report vulnerabilities in a way that gives everyone a chance to fix the issue safely.

</div>
