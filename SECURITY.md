# Security

Thanks for helping make Capgo safe for everyone.

Capgo takes the security of our software seriously, including all open-source repositories in the Cap-go GitHub organization:
https://github.com/Cap-go

## Reporting a vulnerability

Do not report, discuss, or disclose security issues on Discord, GitHub Issues, or any public forum.

All security reports must be submitted through GitHub Security Advisories for the relevant repository:
- https://github.com/Cap-go/capgo.app/security/advisories/new (primary backend/product repo)
- https://github.com/Cap-go/CLI/security/advisories/new
- https://github.com/Cap-go/capacitor-updater/security/advisories/new

Please include:
- a clear description of the issue and its impact
- reproducible steps, proof of concept, and environment details
- the exact file path and line numbers where the issue exists
- any suggested fix (optional)

Do not publish details in any repository content until we coordinate disclosure.

For bug bounty details and payout rules, see:
https://capgo.app/bug-bounty/

## Bug bounty payouts

Capgo is a small, bootstrapped team. Payments are issued only after the fix is **released** and you have **verified** that the fix works for you. Linking or opening a pull request alone is not enough for payout.

This process typically takes a few days to a few weeks depending on release timing and verification. Please do not send messages like "to get paid"; payment happens only once the release is live and you have tested and validated the fix.

## Out of scope / will be closed

The following are not treated as vulnerabilities and reports will be closed:

- Unauthenticated `channel_self` set, and the designed no-API-key behavior for `/updates` and `/stats`, are intentional product design — do not re-report.
- Uploader mislabeling encryption on `external_url` bundles is not a Capgo vulnerability.
- Duplicate reports, reports already fixed on `main` without a new exploit path, and mistaken or incomplete drafts.

For the full out-of-scope list, see https://capgo.app/security/. For bounty amounts and rules, see https://capgo.app/bug-bounty/.

## After you report

- We may close mistaken or duplicate drafts.
- If we open an intentional fix PR, the advisory stays open and linked until release and disclosure coordination.
- Side-effect fixes may close the advisory as resolved without a dedicated advisory publish.

## Embargo policy

Security information must be shared only within the Capgo Core and Security teams on a need-to-know basis. Do not make the information public, share it externally, or hint at it without explicit prior approval. This holds until the agreed public disclosure date and time.

As a clarifying example, this policy forbids sharing security details with employers unless prior arrangements have been made.

If information leaks, you must urgently inform the Capgo Security Team with exactly what was shared, with whom, and what steps will prevent future leaks.

Repeated offenses may lead to removal from the Security or Capgo team.
