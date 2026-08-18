# Contributing to Awesome Banking

Thanks for helping keep this guide useful. Corrections and removals are as welcome as additions.

## What belongs here

This list is **production-first**. An entry should be something a banking team would realistically deploy, operate, or study.

**Accepted:**

- Actively maintained banking, payments, security, compliance, and fintech platforms
- Standards, regulatory frameworks, and standards bodies
- Substantive learning resources (courses, books, talks, engineering writeups)
- Real banking-domain knowledge and mental models (the "domain primer" sections)
- Open-source projects used in banking

**Not accepted:**

- Abandoned projects (no meaningful activity in ~12 months, or archived)
- Thin wrappers with no distinct value over what they wrap
- Marketing pages, waitlists, and unreleased products
- Paid-only content behind a signup wall with no substance
- Duplicate entries already listed under another section

## Entry checklist

Before opening a pull request, confirm your entry:

1. **Is production-relevant** — something a real banking team would use
2. **Is actively maintained** — recent commits, releases, or doc updates
3. **Is not already listed** — search the README first
4. **Uses the canonical link** — the project repository or official docs, never an aggregator, redirect, or referral link
5. **Follows the table format** of the section you're adding to
6. **Has a one-line, non-marketing description** — say what it does and who it's for
7. **Sits in the most specific applicable section** — don't add a new section for a single entry

## Domain-knowledge sections

If your contribution is knowledge rather than a tool, prefer to strengthen an existing **Key concepts** list or **domain primer** over adding prose bloat. Keep every claim accurate and jurisdiction-aware — banking rules differ wildly by country, so label the region (EU, US, UK, GCC, etc.) where it matters.

## Format

Every section uses Markdown tables. Match the columns of the section you are editing exactly.

```markdown
| [Project Name](https://github.com/org/repo) ⭐ 🔓 | What it does, in one line, no hype |
```

**Badge legend** (apply only where genuinely true):

| Badge | Meaning |
|---|---|
| ⭐ | Widely adopted default for its category |
| 🔓 | Open source |
| 💰 | Commercial / paid tier required |
| ☁️ | Managed / hosted service |
| 🆓 | Free to use |

Use ⭐ sparingly — it means "if you don't have an opinion, pick this one." Roughly one to three per section.

### Description style

- One line, no trailing period needed for fragments
- Describe capability, not adjectives: "API-first core for deposits, lending, and payments" beats "blazing fast and powerful"
- Avoid copying the project's own tagline verbatim if it's pure marketing
- Prefer an em dash to separate name-clarification from purpose

## Ordering

Within a section, follow whatever ordering is already there. Most tables are ordered roughly by adoption and relevance rather than alphabetically — put your entry where a reader would expect to find it, not automatically at the end.

## Submitting

```bash
git clone https://github.com/<your-username>/awesome-banking.git
cd awesome-banking
git checkout -b add-tool-or-section
# edit README.md
git commit -am "Add <Tool> to <Section>"
git push origin add-tool-or-section
```

### Automated checks

Every pull request runs a [lychee](https://github.com/lycheeverse/lychee) link check over the Markdown. If it fails, your link is unreachable — fix the URL rather than working around the check.

To run it before pushing:

```bash
# macOS
brew install lychee
# or: cargo install lychee

lychee --config lychee.toml --no-progress .
```

A handful of hosts (LinkedIn, X, iso.org, salesforce.com, oracle.com, bloomberg.com) block automated traffic and are listed in `.lycheeignore`. Add to that file only when a link genuinely works in a browser but cannot be verified by a bot — never to hide a dead link.

Then open a pull request. In the description, include:

- A link to the project
- One or two sentences on why it belongs here
- Any disclosure of affiliation (see below)

**One entry per pull request** where practical — it keeps review fast.

## Self-promotion and affiliation

You may submit your own project. **Disclose the affiliation in the pull request.** Self-submitted entries are held to the same bar as everything else, and "actively maintained" is checked more carefully for projects with few external users.

## Reporting problems

[Open an issue](https://github.com/seyhunak/awesome-banking/issues/new) for:

- Dead or redirected links
- Projects that have been archived, acquired, or deprecated
- Descriptions that are no longer accurate
- A ⭐ that no longer reflects reality
- Regulatory facts that are outdated or jurisdictionally wrong

These are high-value contributions. A curated guide decays quietly, and corrections are what keep it trustworthy.

## Code of Conduct

Participation is governed by the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

By contributing, you agree that your contributions are licensed under the [MIT License](LICENSE).