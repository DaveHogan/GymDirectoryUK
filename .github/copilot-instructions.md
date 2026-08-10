# Copilot PR Review Instructions

Applies to pull requests in **GymDirectoryUK**.

This repository is deliberately different from the rest of the estate, so it does **not** carry the
shared review block used by the application repos. Two reasons: it contains no application code, and
it is public, accepting community contributions.

## Context

Public repository for [Gym Directory UK](https://gymdirectory.co.uk) — feature requests, bug reports,
gym submissions and published data sets. The website source is closed and lives elsewhere. Nothing in
a review here should describe or depend on that private implementation.

Contributions arrive from people outside the project. Reviews should read as welcoming to a
first-time contributor.

## Line endings

**This repo is LF and has no `.gitattributes` or `.editorconfig`.** That is deliberate and is the
opposite of the workspace default. Never suggest CRLF, and never flag LF here. A PR that normalises
existing files to CRLF should be rejected on those grounds alone, because it rewrites every line of
every file it touches.

## What to look for

- **Data quality over style.** Duplicate rows, inconsistent casing in a controlled vocabulary, and
  entries that differ only by punctuation matter far more than formatting.
- **Schema stability.** Columns here are consumed by an importer downstream. Renaming, reordering or
  removing a column is a breaking change even though nothing in this repo fails.
- **Licensing is a condition, not a courtesy.** Data sourced under an attribution licence (Sport
  England Active Places is CC BY 4.0) must keep its credit intact. Check that a PR adding rows also
  records where they came from.
- **No personal data.** Gym submissions should carry business contact details, never an individual's
  personal phone number, home address or email.
- **No secrets, tokens or internal URLs**, including in issue templates and workflow files.

## What not to raise

- Formatting or line endings, per the section above.
- Requests to restructure the data sets to suit a consumer. That coupling belongs on the consumer
  side, not here.
