# APN Bug Reports

APN is a VPN service with native clients for Android, iOS, and macOS.
This repository is where we collect bug reports from testers and users.
Found something broken?
Please [open an issue][issues].

## Where to Get the App

The Android app is published on [Google Play][play], which is the easiest
  place to start testing.
We also ship native clients for iOS and macOS that share the same behaviour,
  so a bug found on one platform is worth checking on the others.

## What to Test

Install the app, sign in, connect to a few servers, and try to break things.
The areas we care about most:

- Connection — establishing, holding, and tearing down the VPN tunnel, and
  reconnecting after the network changes (Wi-Fi to cellular, sleep, wake,
  airplane mode).
- Server switching — picking a country, switching between servers, and how
  long a switch takes to settle.
- Subscriptions and billing — purchase, restore, renewal, and the state of
  the app once a subscription lapses.
- Leaks — DNS, IPv6, or any traffic that escapes the tunnel while connected
  or mid-reconnect.
- Kill switch — whether traffic is blocked when the tunnel drops unexpectedly.
- Battery and data — unexpected drain or background traffic.
- UI — layout glitches, wrong labels, broken navigation, and anything that
  looks off across phone sizes, tablets, and dark mode.

## What Makes a Good Report

One bug per issue, with enough detail for us to reproduce it:

- App version (build number) and platform (e.g. Android 14, iOS 17, macOS 14).
- Steps to reproduce, numbered.
- Expected behaviour versus what actually happened.
- Screenshots or a screen recording when the bug is visual.
- The server or country involved, if the bug is connection-related.

Before opening an issue, please search the [tracker][issues] to avoid
  duplicates.

## Rewards

We pay $10, $25, or $50 for every accepted bug, depending on its severity.
Once a bug is accepted, we attach a reward label to its issue.
A label means the reporter may claim the bonus.
To claim, email [bugs@apn.tech](mailto:bugs@apn.tech) with your USDT (ERC-20)
  wallet address.

[issues]: https://github.com/APN-Network/bugs/issues
[play]: https://play.google.com/store/apps/details?id=
