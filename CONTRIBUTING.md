# Contributing to SwiftUI Specialist

Thanks for your interest in improving this skill! The SwiftUI guidance here is Apple-sourced, so most contributions fall into one of three buckets:

1. **Packaging / tooling** — README, install paths, agent-skill compatibility, scripts.
2. **Curation** — new entries in `references/soft-deprecated-apis.md` as Apple ships new APIs, corrections to references when Apple updates guidance.
3. **Ergonomics** — clearer wording, cross-references between files, examples.

## Before you start

- Open an issue first for anything beyond a typo or a small curation entry. This avoids duplicate work and lets us align on direction.
- Search existing issues and PRs before filing a new one.

## What we won't accept

- **Rewording Apple's guidance in a way that changes its meaning.** If you believe a reference misrepresents Apple's intent, open an issue with the source and we'll fix it together.
- **Speculative best practices** that aren't grounded in Apple's published material. This repo's value is "authoritative"; we keep it that way.
- **Large reorganizations** of the `references/` tree without prior discussion.

## How to contribute a change

1. Fork the repo and create a branch:
   ```bash
   git checkout -b docs/add-soft-deprecated-entry
   ```
2. Make your change. Keep edits focused — one topic per PR is ideal.
3. If you touch a `references/*.md` file, make sure the corresponding line in `SKILL.md` still accurately describes it.
4. Test it: if you use Cursor, install the updated skill locally and verify it loads and is consulted as expected.
5. Open a PR with a clear description of **what** changed and **why**, linking any related issue.

## Good first issues

Issues labeled [`good first issue`](https://github.com/trmquang93/swiftui-specialist-skill/labels/good%20first%20issue) are scoped for newcomers — typically a single new entry in `references/soft-deprecated-apis.md` or a small README improvement. If you start one, comment on the issue so it's assigned to you.

## Style notes

- Markdown files use a leading `#` title and `##` subsections.
- Keep lines under ~100 chars where reasonable.
- Inline code in backticks for API names; fenced blocks for code samples.
- No emojis in the reference files.

## Reporting problems with the guidance

If you find a place where the guidance here conflicts with Apple's current documentation, open an issue with:
- The file and line you're questioning.
- A link to the Apple source you're citing.
- What you believe the correct guidance should be.

## Licensing

By contributing, you agree that your contributions will be licensed under the [MIT License](./LICENSE).
