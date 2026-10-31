# Security policy

This policy covers every public repository in the [FynePDF organization](https://github.com/fynepdf) that doesn't have its own.

## Reporting a vulnerability

Please don't report security problems in public issues, pull requests or discussions.

Report them privately instead, either way:

1. **On GitHub:** open the repository's **Security** tab and choose **Report a vulnerability**. Only the maintainers see the report.
2. **By email:** write to [support@fynepdf.com](mailto:support@fynepdf.com) with "Security" in the subject.

Please include:

- the project and version (for npm packages, `npm ls <package>` shows it)
- what an attacker could do, and how to reproduce it
- a file that triggers the problem, if one does and you can share it

We'll confirm we received your report, keep you updated while we work on a fix, and credit you in the release notes unless you'd rather stay anonymous. Please give us a reasonable chance to release a fix before you talk about the problem publicly.

## Supported versions

Fixes go into the latest release of each project. Upgrade to the newest version before reporting, in case the problem is already fixed.

## Things that count as security problems

For the PDF libraries (fynepdf-pdfa, fynepdf-grayscale), we especially want to hear about crashes, hangs or memory exhaustion caused by a crafted PDF, and anything that reads or writes files outside the ones you passed in. For wrapguard, we want to hear about anything that leaks secrets from CI or runs code it shouldn't.

## fynepdf.com and the FynePDF apps

To report a vulnerability in the website, the API or the desktop app, email [support@fynepdf.com](mailto:support@fynepdf.com) with "Security" in the subject. Please don't test against other people's accounts or data.
