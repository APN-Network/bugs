# APN Bug Reports

APN is a VPN service with a native Android client.
This repository is where we collect bug reports from testers and users.
Found something broken?
Please [open an issue][issues].

## Where to Get the App

The Android app is published on [Google Play][play], which is where
  you start testing.

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

- App version (build number) and platform (e.g. Android 14).
- Steps to reproduce, numbered.
- Expected behaviour versus what actually happened.
- Screenshots or a screen recording when the bug is visual.
- The server or country involved, if the bug is connection-related.
- App logs when the bug involves a connection drop, a reconnection failure,
  or a suspected leak: `adb logcat` output on Android.

Before opening an issue, please search the [tracker][issues] to avoid
  duplicates.

## Rewards

We pay $10, $25, or $50 for every accepted bug, depending on its severity.
Once a bug is accepted, we attach a reward label to its issue.
A label means the reporter may claim the bonus.
To claim, email [bugs@apn.tech](mailto:bugs@apn.tech) from the address
  tied to your report, and include your USDT (ERC-20 on Ethereum mainnet)
  wallet address.

[issues]: https://github.com/APN-Network/bugs/issues
[play]: https://play.google.com/store/apps/details?id=tech.apn
