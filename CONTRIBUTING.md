# Contributing

Thanks for helping. These notes apply to every public repository in the [FynePDF organization](https://github.com/fynepdf) that doesn't have its own. Each project's README explains how to build it and run its tests.

## Reporting a bug

Open an issue in the project's repository and include:

- the version, your operating system, and Node.js version if you use the npm package
- the exact command or code you ran, what you expected, and what happened instead
- for the PDF libraries, a file that shows the problem, **only if you can share it publicly**. Never attach confidential documents. A small file you made yourself that shows the same problem is ideal.

Security problems are different: please report them privately, as the [security policy](https://github.com/fynepdf/.github/blob/main/SECURITY.md) explains.

## Suggesting a change

For anything bigger than a small fix, open an issue first so we can agree on the approach before you spend time on code.

## Pull requests

- Keep each pull request to one change, and explain why it's needed.
- Add or update tests for what you change. The PDF libraries are tested on real files, and PDF/A output is checked with veraPDF, so a regression shows up there.
- Make sure CI passes.
- Update the README when behaviour or options change.

By contributing, you agree that your contribution is released under the project's licence (MIT).

## Code of conduct

Everyone taking part follows our [code of conduct](https://github.com/fynepdf/.github/blob/main/CODE_OF_CONDUCT.md).
