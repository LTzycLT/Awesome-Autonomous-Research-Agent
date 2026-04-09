# Contributing Guidelines

Thank you for contributing to Awesome Autonomous Research Agent. Please read the rules below before submitting a pull request.

---

## Scope

This list collects systems that autonomously perform research tasks — hypothesis generation, experiment design/execution, result analysis, and/or paper writing — with minimal human intervention. General-purpose coding agents are in scope if they are widely used as execution backbones for research agents.

When in doubt, ask: does this system make autonomous research decisions, or is it a tool that humans use to conduct research manually? Only the former belongs here.

---

## Entry Format

All entries go in the single **Entries** table with columns:

`Name | Description | Code | Paper | Organization | Released | Stars`

### Name

- If a GitHub repository exists, use the repository name
- Otherwise, use the paper title
- Rendered as bold plain text (no link; links are in Code and Paper columns)

### Description

- If a paper exists: use the paper title minus the project name prefix (e.g., for "AIDE: AI-Driven Exploration in the Space of Code", use "AI-Driven Exploration in the Space of Code")
- If no paper exists: paraphrase a one-line description from the project README in a style similar to a paper subtitle
- Must be taken verbatim or paraphrased directly from the source; no editorial judgment

### Code

- If a public GitHub repository exists: `[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github)](URL)`
- Otherwise: `—`

### Paper

- If a public paper exists: `[![arXiv](https://img.shields.io/badge/arXiv-ID-b31b1b?logo=arxiv)](URL)`
- Otherwise: `—`

### Organization

- If a paper exists: use the institution of the first or corresponding author(s)
- If no paper exists: use the GitHub repository owner account name

### Released

- If a GitHub repository exists: month of first commit (`YYYY-MM`)
- If no repository exists: month of paper first submission (`YYYY-MM`)

### Stars

- If a GitHub repository exists: rendered as a colored badge, rounded to nearest 0.1k
  - `> 10k` → gold (`FFD700`)
  - `1k – 10k` → blue (`4A90D9`)
  - `< 1k` → grey (`aaaaaa`)
  - Badge format: `![](https://img.shields.io/badge/★_Xk-COLOR?style=flat-square)`
- Otherwise: `—`

---

## Content Rules

### Source discipline (strictly enforced)

- Descriptions must be taken verbatim or paraphrased directly from the paper abstract or project README
- Do not add interpretation, analysis, or editorial context
- Do not claim "best", "first", "state-of-the-art", or any superlative unless the paper itself makes that specific claim in writing

### Public link requirement

Every entry must have at least one publicly accessible link (GitHub repository or paper page). Entries without a verifiable public URL will not be accepted.

### Date format

All dates use `YYYY-MM`. Do not use relative terms like "recent" or "latest".

### Stars

Stars are a snapshot at time of entry. Do not update star counts in follow-up PRs unless you are also updating other fields for that entry. Stale star counts are acceptable.

---

## Adding an Entry

1. Fork the repository and create a new branch
2. Add your entry to the Entries table, sorted by release date (descending)
3. Verify that all links are accessible
4. Open a pull request with a brief description of what you are adding and why it is in scope

---

## What Does Not Belong Here

- Systems that require continuous human direction for each step
- Pure AutoML tools without autonomous planning or reasoning
- General-purpose LLM APIs or frameworks not specifically designed for research automation
- Entries with no public code or paper (pre-publication, internal-only systems)
