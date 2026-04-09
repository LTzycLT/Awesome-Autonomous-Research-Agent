# Contributing Guidelines

Thank you for contributing to Awesome Autonomous Research Agent. Please read the rules below before submitting a pull request.

---

## Scope

This list collects systems that autonomously perform research tasks — hypothesis generation, experiment design/execution, result analysis, and/or paper writing — with minimal human intervention. General-purpose coding agents are in scope if they are widely used as execution backbones for research agents.

When in doubt, ask: does this system make autonomous research decisions, or is it a tool that humans use to conduct research manually? Only the former belongs here.

---

## Entry Format

### Projects & Codebases

Table columns: `Project Name | Organization | Released | Last Updated | Stars`

- **Project Name**: linked to the public GitHub repository
- **Organization**: team or company that maintains the project
- **Released**: month of first public release, in `YYYY-MM` format
- **Last Updated**: month of most recent substantive update, in `YYYY-MM` format; use `—` if unknown
- **Stars**: GitHub star count at time of entry, rounded to nearest 0.1k (e.g., `★ 1.2k`); use `—` if unavailable

Optionally, add a one-line description as a blockquote immediately below the table row:

```markdown
> Autonomous LLM research loop running continuously with a fixed 5-minute experiment budget per iteration.
```

### Papers

Table columns: `Paper Name | Organization | Published | Code`

- **Paper Name**: linked to arXiv or official paper page
- **Organization**: institution of the first or corresponding author(s)
- **Published**: arXiv first submission month (`YYYY-MM`); for conference/journal papers, use the acceptance/publication month
- **Code**: GitHub link if publicly available; `—` otherwise

---

## Content Rules

### Source discipline (strictly enforced)

- Descriptions must be taken verbatim or paraphrased directly from the paper abstract or project README
- Do not add interpretation, analysis, or editorial context
- Do not claim "best", "first", "state-of-the-art", or any superlative unless the paper itself makes that specific claim in writing

### Public link requirement

Every entry must have at least one publicly accessible link (GitHub repository or arXiv paper page). Entries without a verifiable public URL will not be accepted.

### Date format

All dates use `YYYY-MM`. Do not use relative terms like "recent" or "latest".

### Stars

Stars are a snapshot at time of entry. Do not update star counts in follow-up PRs unless you are also updating other fields for that entry. Stale star counts are acceptable.

---

## Adding an Entry

1. Fork the repository and create a new branch
2. Add your entry to the appropriate table, sorted by release date (ascending)
3. Verify that all links are accessible
4. Open a pull request with a brief description of what you are adding and why it is in scope

---

## What Does Not Belong Here

- Systems that require continuous human direction for each step
- Pure AutoML tools without autonomous planning or reasoning
- General-purpose LLM APIs or frameworks not specifically designed for research automation
- Entries with no public code or paper (pre-publication, internal-only systems)
