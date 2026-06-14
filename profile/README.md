# Code Mower

Code Mower is the fastest way to create an AI peer-programmer and reviewer
system around the top coding agents and review tools.

It helps teams move from plan to merge at maximum safe velocity while
preserving code quality, architecture, and deployment confidence. It also
creates a quality, speed, and cost benchmark loop on your actual product:
which AI builders and reviewers produce useful results on your codebase, at
what cost, and under which review policy.

## Start Here

- Open-source core: [codemower-ai/code-mower](https://github.com/codemower-ai/code-mower)
- Website and dashboard: [codemower.com](https://codemower.com)
- Product updates: [@CodeMowerAI](https://x.com/CodeMowerAI)

## What Code Mower Does

- Sets up AI reviewer lanes for real GitHub pull requests.
- Keeps lanes head-bound, structured, and auditable.
- Measures reviewer usefulness, false positives, latency, and cost.
- Supports prompt lenses and calibration corpora so teams can test what works
  on their codebase.
- Provides optional cloud reporting with privacy-first metadata sharing.

## Privacy Posture

Code Mower is local-first. The OSS tool works without CodeMower.com.

Optional cloud sharing is designed to upload sanitized metadata, not source
code, raw diffs, raw transcripts, raw auth output, or secrets by default.

## Current Status

Code Mower is in early alpha. It is ready for friendly pilots where users can
install from GitHub, run `code-mower init --easy`, run `code-mower doctor
--v05`, generate a first local value report, and optionally connect a
CodeMower.com team token.

Start with the 10-minute guide:

[Try Code Mower In 10 Minutes](https://github.com/codemower-ai/code-mower/blob/main/docs/try-in-10-minutes.md)
