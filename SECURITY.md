# Security policy

Thank you for helping keep our players and our studio safe.

## Scope

This policy covers:

- Our games, including demos and test builds we distribute
- [severedsignal.com](https://severedsignal.com)
- Severed Signal Studios accounts and repositories on GitHub

If a problem lies in a store, platform, engine or other third-party service and
not in our work, please report it to that service.

We're a small studio and don't run a bug bounty program, so we can't offer
payment for reports.

## Reporting a security problem

**Don't report security problems in public issues, on community platforms or
on social media.**

Report them privately in either of these ways:

- **Email** [security@severedsignal.com](mailto:security@severedsignal.com) and start
  the subject line with "Security". You don't need a GitHub account.
- **GitHub private report.** Open the
  [security page](https://github.com/Severed-Signal-Studios/.github/security)
  of our public `.github` repository and select **Report a vulnerability**. You
  need a GitHub account. Our code is private, so reports about our games and
  website go there too.

Please include as much of this as you can:

- The affected product and version, and where you got it
- Your operating system and hardware, if relevant
- Step-by-step instructions to reproduce the problem
- A minimal proof of concept, if you have one
- The impact, and how an attacker might use it
- Any known workaround
- Whether you've shared the details with anyone else

Use test data where possible. Don't send passwords, personal data or other
sensitive information unless we ask for it through a channel we've agreed on.

## What counts as a security problem

In a game, for example:

- Running code through a crafted save file, settings file or other file the
  game reads
- The game reading, changing or deleting files outside its own folders
- The game exposing personal data
- A compromised build or update distributed through our channels

On the website, anything that lets someone change its content or attack its
visitors.

These are not security problems:

- Editing your own saves or settings to change your own game
- Cheats and exploits that only affect your own single-player game
- Crashes caused by a damaged file, unless you think a crafted file could do
  more than crash the game

We still want to hear about ordinary crashes and bugs. Report them in the
[issue tracker](https://github.com/Severed-Signal-Studios/.github/issues/new/choose).
If a crash comes from a file you crafted, report it privately instead, and
don't post the file in public.

## What to expect

We acknowledge your report as soon as we can and keep you informed as we
investigate. If we confirm the problem, we work on a fix and agree with you on
when to make it public. With your permission, we credit you when we do.

Please give us reasonable time to fix the problem before you publish details.
We can't promise a particular response time.

## Responsible research

When you investigate a possible security problem:

- Test only on systems, accounts, devices and files that you own or have
  permission to use.
- Avoid privacy violations, data loss and service disruption.
- Stop and tell us if you come across personal data, credentials or other
  sensitive information.
- Don't use social engineering, phishing, denial-of-service attacks or physical
  attacks.
- Collect only the information you need to show the problem, and delete it
  when you no longer need it.

## Safe harbor

If you follow this policy in good faith, we consider your research authorized.
We don't take or support legal action against you for it, and if someone else
does, we tell them you had our permission. This covers examining your own
copies of our games, including their files, and testing severedsignal.com
within the rules above. It doesn't let you share our code or assets, and we
can't give permission for systems we don't own, such as our web host, game
stores, community platforms or code hosting services.
