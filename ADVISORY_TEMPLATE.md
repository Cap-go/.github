# Capgo private advisory checklist

Use this when opening a GitHub Security Advisory for a Cap-go repository. Paste the filled sections into the advisory description.

Do not report, discuss, or disclose security issues on Discord, GitHub Issues, or any public forum.

## Required

- [ ] I read https://capgo.app/security/ (out of scope) and https://capgo.app/bug-bounty/ (payout rules)
- [ ] This is not an intentional product behavior, a duplicate, or a report already fixed on `main` without a new exploit path

### Summary
One sentence: what breaks and who is affected.

### Impact
What an attacker can do. Severity rationale (no unpublished exploit marketing).

### Affected component
- Repository:
- Package / path:
- Version(s) tested:
- Platform (iOS / Android / web / CLI / backend):

### Exact location
- File path:
- Line number(s):
- Function / method:

### Steps to reproduce
Numbered steps a maintainer can follow. Include environment and config that matter.

### Proof of concept
Minimal PoC (commands, request/response, or short snippet). Redact secrets.

### Suggested fix (optional)
High-level only. No need for a full patch.

## Out of scope reminders (will be closed)

- Unauthenticated `channel_self` set, and designed no-API-key behavior for `/updates` and `/stats`
- Uploader mislabeling encryption on `external_url` bundles (not a Capgo vulnerability)
- Duplicates, reports already fixed on `main` without a new exploit path, incomplete drafts

Full list: https://capgo.app/security/

## Bounty note

Payout (when eligible) only after the fix is **released** and you have **verified** it. Opening or linking a PR alone is not enough. Details: https://capgo.app/bug-bounty/
