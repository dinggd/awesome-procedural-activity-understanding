# Contributing

Thank you for helping keep this list complete and accurate.

## How the README is built

`README.md` is generated from the survey sources by `tools/build_readme.py`.
Hand-curated parts (news, quick start, hall of fame, trends, key ideas, code
links) live in `tools/curated.py`. Please edit those files rather than the
README directly when possible.

## Adding a paper

Open a pull request that adds a row to the relevant section, using the existing format:

```
| 🆕 | **[Paper Title](link)** — FirstAuthor et al.<br><sub>One-line key idea.</sub> | Venue Year | [![Code](https://img.shields.io/badge/Code-GitHub-blue)](code-link) |
```

- Use 🆕 for papers not covered in the survey; 🟢 is reserved for papers discussed in it.
- Place benchmarks under **Benchmarks** and models under **Methods**.
- Link to the official publication or the arXiv page.
- Keep entries sorted by year (newest first).

Sections follow the survey's taxonomy:
- **§2.1 Parsing:** step recognition, temporal parsing (segmentation, detection, step localization, online), step grounding, activity and goal recognition.
- **§2.2 Predicting:** action anticipation, procedure planning.
- **§2.3 Assessing:** progress monitoring, mistake detection, skill assessment.
- **§2.4 Supporting:** captioning, retrieval, question answering and dialogue, demonstration generation.

## Adding code links or corrections

Add the code URL to `CODE` in `tools/curated.py`, or open an issue with the correction.
