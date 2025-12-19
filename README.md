# copilot-review-playground

A tiny sandbox repo for trying GitHub Copilot review behaviors and PR templates.

## What this repo is for
- Practice PR review comments, status changes, and template usage
- Test Copilot PR review prompts without touching production code
- Share examples of "Related Issue" wording and closing keywords

## Quick start
1. Clone the repo.
2. Create a branch: `git checkout -b sample-change`.
3. Make a small edit (README や .github 配下など) and open a PR. If you have an Issue, link it with `close #<issue-number>` in the PR description.
4. Ask Copilot to review and cross-check `.github/copilot-instructions.md` for expected reviewer behavior.

## Notes
- The repository intentionally has minimal app code; add tiny changes as needed to test review behavior.
- Keep PRs small so Copilot feedback is easy to read and iterate on.
