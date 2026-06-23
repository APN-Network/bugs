# Contributing

Thank you for helping make APN better.
This guide explains how to report a bug, what the reward labels mean,
  and how to claim a reward once your report is accepted.

## Reporting a Bug

One bug per issue, with enough detail for us to reproduce it:

- App version (build number) and platform (e.g. Android 14, iOS 17, macOS 14).
- Steps to reproduce, numbered.
- Expected behaviour versus what actually happened.
- Screenshots or a screen recording when the bug is visual.
- The server or country involved, if the bug is connection-related.

Before opening an issue, please search the [tracker][issues] to avoid
  duplicates.
The first complete report of a given bug is the one we reward;
  later reports of the same bug are closed as duplicates.

## Reward Tiers

After we triage a report and confirm it, we attach one of three reward
  labels to the issue.
The label is the signal that the report has been accepted at that tier;
  an issue without a reward label has not yet qualified for one.
Not every valid bug earns a reward, and the tier is at our discretion.

| Label | Reward | What qualifies |
|-------|--------|----------------|
| `$10` | $10 | Minor UI glitches, wrong labels, or cosmetic issues with a clear reproduction path |
| `$25` | $25 | Functional bugs in core features: connection, server switching, subscriptions, or reconnection |
| `$50` | $50 | Critical bugs affecting security or privacy: traffic leaks, kill-switch failures, or data loss |

## Claiming a Reward

Once a reward label is on your issue, you may claim the bonus.
To claim, email [bugs@apn.tech](mailto:bugs@apn.tech) from the address
  tied to your report, and include your USDT (ERC-20 on Ethereum mainnet)
  wallet address.
Payment is processed after the bug is verified, and, where a fix is
  involved, after the fix is accepted.

## Rules

- You must be the original reporter of the bug to claim its reward.
- Reports without enough detail to reproduce the bug are closed as invalid.
- Security-sensitive bugs (traffic leaks, credential exposure, data loss)
  should be reported with care; contact us before any public disclosure,
  by email: security@apn.tech.
- Intentionally planting a bug to claim a reward is not allowed.
- We reserve the right to adjust a tier or decline a reward at our discretion.

[issues]: https://github.com/APN-Network/bugs/issues
