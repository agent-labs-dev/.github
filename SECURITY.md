# Security policy

## Reporting a vulnerability

Report a vulnerability privately, never in a public issue, pull request or discussion.

Open the affected repository's **Security** tab and choose **Report a vulnerability**. The report
becomes a private GitHub security advisory that only the maintainers and you can see. Where a repository
does not offer that button, open an issue titled "Private contact request" with no details, and a
maintainer will reply with a private channel.

Include:

- the repository and the version or commit you tested
- what an attacker could do
- the steps or input that reproduce it, when you can share them safely
- any mitigation you know of

Do not include real secrets or other people's data.

We aim to acknowledge a report within five working days, and to publish the fix and an advisory
together. Reporters are credited in the advisory unless they ask not to be.

## Scope

In scope is the code in the repository, its CI workflows and release packaging, and the packages
published from it. A repository's own `SECURITY.md`, where it has one, defines its scope in more
detail.

Out of scope are the third-party services and sites a project talks to, and the model providers it
calls. Report those to their owners.

## Supported versions

Only the latest release of each project receives security fixes. Check that the problem reproduces on
the latest release before reporting it.
