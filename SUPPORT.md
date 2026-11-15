# Support

This guide is also on our website, at
[severedsignal.com/support](https://severedsignal.com/support).

## Before you ask

1. Restart the game and check whether the problem happens again.
2. Make sure you have the latest version.
3. Search the [existing issues](https://github.com/Severed-Signal-Studios/.github/issues?q=is%3Aissue).
4. Note the game version, your operating system and the exact text of any
   error.

## Where to ask

- **Bugs, accessibility barriers and feedback:** [open an issue](https://github.com/Severed-Signal-Studios/.github/issues/new/choose).
  If you don't have a GitHub account, report a bug or barrier by email to
  [support@severedsignal.com](mailto:support@severedsignal.com) or on Discord,
  and we add it to the issues for you without your personal details. We keep
  the original message and any attached files only as long as needed to handle
  the report, then delete them.
- **Questions, help and conversation:** join our [Discord](https://discord.gg/nz9bkGb2Fv).
- **Purchases and refunds:** contact the store you bought the game from.
- **Anything private:** email [support@severedsignal.com](mailto:support@severedsignal.com).
- **Security problems:** follow the [security policy](SECURITY.md). Don't open
  an issue.

Please don't use an unrelated issue as a support thread. Our
[code of conduct](CODE_OF_CONDUCT.md) applies in all these spaces.

Our [accessibility statement](ACCESSIBILITY.md) says what we aim for and what
to tell us when you report a barrier.

## Logs and saves

*Unaccounted* stores its files in different folders depending on your system.

### Windows

Paste a folder path into the File Explorer address bar to open it.

| What | Folder |
|---|---|
| Logs | `%APPDATA%\Godot\app_userdata\Unaccounted\logs` |
| Saves | `%APPDATA%\Unaccounted` |
| Settings | `%APPDATA%\Godot\app_userdata\Unaccounted` |

### macOS

In Finder, open the Go menu, select Go to Folder, and paste a folder path.

| What | Folder |
|---|---|
| Logs | `~/Library/Application Support/Godot/app_userdata/Unaccounted/logs` |
| Saves | `~/Library/Application Support/Unaccounted` |
| Settings | `~/Library/Application Support/Godot/app_userdata/Unaccounted` |

### Linux and Steam Deck

On Steam Deck, switch to Desktop Mode first. `.local` is a hidden folder, so
enable hidden files in your file manager, often with Ctrl+H. If you have set
`XDG_DATA_HOME`, the folders are there instead of in `~/.local/share`.

| What | Folder |
|---|---|
| Logs | `~/.local/share/godot/app_userdata/Unaccounted/logs` |
| Saves | `~/.local/share/Unaccounted` |
| Settings | `~/.local/share/godot/app_userdata/Unaccounted` |

### Proton or Wine

If you play the Windows version through Proton or Wine, its Windows folders are
inside the prefix, under `drive_c/users/<user>/AppData/Roaming`.

- With Steam, the prefix is `steamapps/compatdata/747010/pfx` in the Steam
  library that holds the game, usually `~/.local/share/Steam`. The user is
  `steamuser`.
- With Wine, the prefix is `~/.wine` or your `WINEPREFIX`, and the user is your
  own username.

### Which files to send

- `godot.log` is the log for the latest session. Quit the game before copying
  it, as some lines are written only when the game closes. Each launch renames
  the previous log to `godot` with a date and time, and the game keeps the five
  most recent logs. If you have started the game since the problem occurred,
  please also send the newest dated log.
- Each save is a `.save` file, and the matching `.bak` file is the version it
  replaced.
- `settings.cfg` holds your settings and key bindings.
- Compress save or settings files before attaching them to an issue, as GitHub
  does not accept `.save` or `.cfg` files.

## Before you share files

- Issues and attachments on GitHub are public. Anyone with the link can access
  an attachment without signing in. To send a file privately, please email it
  to [support@severedsignal.com](mailto:support@severedsignal.com). We keep
  emailed files only as long as needed to handle the issue, then delete them.
- Logs may include your username in file paths, which can be part of your real
  name or email address. You can replace it with `USER` before sharing the log.
- Screenshots and videos may display other windows, notifications, or account
  names. Recordings may capture your microphone or voice chat. Please review
  them before posting.

The [privacy policy](https://severedsignal.com/privacy) explains how we handle
what you send us.

## Writing a useful report

Describe what you did, what you expected and what happened instead. Copy the
exact error text into the report so others can search for it, and add
screenshots or a short video if they help.

We're a small studio and answer as soon as we can.
