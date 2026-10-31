<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fynepdf/.github/main/profile/assets/fynepdf-logo-dark.svg">
  <img src="https://raw.githubusercontent.com/fynepdf/.github/main/profile/assets/fynepdf-logo.svg" alt="FynePDF" width="160" height="36">
</picture>

**FynePDF is an AI PDF workspace.** Edit PDFs by hand or by prompt, merge, convert, compress and sign them, run workflows, and let 15 AI agents review contracts, résumés and citations. Every tool is free to start, with no sign-up: **[fynepdf.com](https://fynepdf.com)**

This is where we open-source the parts of FynePDF that are useful on their own. Everything here is MIT licensed and released from GitHub with npm provenance.

## Open source

**[fynepdf-pdfa](https://github.com/fynepdf/fynepdf-pdfa)** &nbsp; `npm i fynepdf-pdfa`<br>
Turns PDFs into valid **PDF/A** by fixing them in place instead of rebuilding them. 99.3% of 2,053 test files come out valid PDF/A-2b in veraPDF, and a file it can't fix is never labelled PDF/A. C++17 library and command line on qpdf, no Ghostscript.

**[fynepdf-grayscale](https://github.com/fynepdf/fynepdf-grayscale)** &nbsp; `npm i fynepdf-grayscale`<br>
Converts PDFs to **grayscale** in place: text stays text and nothing is redrawn. On 1,067 real PDFs it lost no text, links or form fields, and ran 13× faster than Ghostscript. C++17 library and command line on qpdf.

**[wrapguard](https://github.com/fynepdf/wrapguard)** &nbsp; `npm i -D wrapguard`<br>
Fails CI when text wraps onto more lines at any screen width. It counts the lines of every heading, paragraph, link and button per breakpoint instead of comparing screenshots. CLI and GitHub Action.

We built the PDF/A and grayscale converters for fynepdf.com and the FynePDF desktop app, as an open-source alternative to Ghostscript for both jobs.

## FynePDF API and MCP server

The same tools as a REST API and a remote MCP server, for your apps and for AI agents, with plugins for Claude, ChatGPT, Muse and Grok. The waitlist is open at **[fynepdf.com/developers](https://fynepdf.com/developers)**.

## Get in touch

- **A bug in one of these projects:** open an issue in its repository.
- **A security problem:** please report it privately, as our [security policy](https://github.com/fynepdf/.github/blob/main/SECURITY.md) explains.
- **Help with fynepdf.com or the desktop app:** [support@fynepdf.com](mailto:support@fynepdf.com)

[Website](https://fynepdf.com) · [X](https://x.com/fynepdf) · [LinkedIn](https://www.linkedin.com/company/fynepdf) · [Reddit](https://www.reddit.com/r/fynepdf/) · [Instagram](https://www.instagram.com/fynepdf/)

<sub>Made in Bharatpur, Nepal.</sub>
