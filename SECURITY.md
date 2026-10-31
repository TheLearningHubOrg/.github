# Security Policy

This policy covers every repository in the
[TheLearningHubOrg](https://github.com/TheLearningHubOrg) organization unless a
repository has its own SECURITY file.

## Supported Versions

The guides are maintained on their default branch. Security fixes are made on
`main` only. Older tags and releases are not patched.

| Version             | Supported |
| ------------------- | --------- |
| `main` (latest)     | Yes       |
| Older tags/releases | No        |

## Reporting a Vulnerability

Please do not report security problems through public issues, discussions or
pull requests.

Use GitHub private vulnerability reporting instead:

1. Go to the affected repository.
2. Open the **Security** tab.
3. Click **Report a vulnerability**.
4. Describe the problem and how to reproduce it.

Helpful details include:

- The repository, file and line, or the workflow or Docker image affected.
- Steps to reproduce, or a proof of concept.
- What an attacker could do with it.
- Any fix you would suggest.

If the **Report a vulnerability** button is not shown for a repository, open an
issue that asks a maintainer to contact you, without including any details of
the problem.

## What to Expect

- An acknowledgement within 7 days.
- A decision on whether the report is accepted within 14 days.
- If accepted, a fix on `main` and a security advisory crediting you, unless
  you prefer to stay anonymous.
- If declined, an explanation of why.

## Scope

In scope: code samples, example apps, Dockerfiles, GitHub Actions workflows and
published images in these repositories.

Out of scope: vulnerabilities in the third-party tools and libraries that the
guides teach. Report those to the upstream project.
