# Security Policy

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues, pull requests, or discussions.** A public report tells everyone about the problem, including people who would misuse it, before there is a fix.

Instead, use **GitHub's private vulnerability reporting**:

1. Go to the affected repository on GitHub.
2. Open the **Security** tab.
3. Click **Report a vulnerability**.

This opens a private channel visible only to the maintainers of that repository. It requires no email address and no account beyond your normal GitHub login.

> **Note:** Private vulnerability reporting must be enabled per-repository. If you do not see a **Report a vulnerability** button under the Security tab of a KindStack repository, it is not yet enabled there. In that case, email **[hello@codekind.net](mailto:hello@codekind.net)** instead. Some projects list their own security contact in their README — where they do, use that address in preference to the general one.

## What to include

The more of this you can provide, the faster we can confirm and fix the issue:

- The type of issue (for example: credential exposure, injection, path traversal, privilege escalation).
- The affected repository, and the file paths or components involved.
- The commit, tag, or release you tested against.
- Step-by-step instructions to reproduce the issue.
- Any proof-of-concept code, along with the configuration needed to run it.
- What an attacker could achieve by exploiting it.

## What to expect

- We will acknowledge your report as soon as we reasonably can.
- We will confirm whether we can reproduce it and let you know our assessment.
- We will keep you informed as we work on a fix.
- We are happy to credit you when the fix is published — tell us how you would like to be named, or if you would rather stay anonymous.

Please give us a reasonable opportunity to address the issue before disclosing it publicly.

## Supported versions

KindStack maintains a number of small projects, most of which do not publish formal versioned releases. As a general rule:

**The supported version of any KindStack project is the latest commit on its default branch.**

Fixes land there. Older commits, tags, forks, and previously downloaded copies do not receive backported security patches. If a specific project maintains a different support window, it will say so in its own `SECURITY.md`, which takes precedence over this org-wide default.

## Scope

This policy covers the source code in KindStack repositories.

Third-party services and dependencies that our projects rely on — for example hosting providers, package registries, or upstream libraries — are outside our control. Please report those to the relevant vendor directly. If one of our projects uses such a service in a way that is itself insecure, that part is in scope and we would like to hear about it.
