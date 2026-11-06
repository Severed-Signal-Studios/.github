# Support

## Before you ask

1. Restart the game and check whether the problem happens again.
2. Make sure you have the latest version.
3. Search the [existing issues](https://github.com/Severed-Signal-Studios/.github/issues?q=is%3Aissue).
4. Note the game version, your operating system and the exact text of any
   error.

## Where to ask

- **Bugs, accessibility barriers and feedback:** [open an issue](https://github.com/Severed-Signal-Studios/.github/issues/new/choose).
- **Questions, help and conversation:** join our [Discord](https://discord.gg/jRH8Rv5b5y).
- **Purchases and refunds:** contact the store you bought the game from.
- **Anything private:** email [info@severedsignal.com](mailto:info@severedsignal.com).
- **Security problems:** follow the [security policy](SECURITY.md). Don't open
  an issue.

Please don't use an unrelated issue as a support thread. Our
[code of conduct](CODE_OF_CONDUCT.md) applies in all these spaces.

## Logs and saves

On Windows, the game keeps its files here:

| What | Folder |
|---|---|
| Logs | `%APPDATA%\Godot\app_userdata\Unaccounted\logs` |
| Saves | `%APPDATA%\Unaccounted` |
| Settings | `%APPDATA%\Godot\app_userdata\Unaccounted` |

Paste a folder path into the File Explorer address bar to open it.

- `godot.log` is the log of the latest session. Quit the game before you copy
  it, since some lines are written only when the game closes. Each launch
  renames the previous log to `godot` followed by a date and time, and the game
  keeps the five newest logs. If you've started the game since the problem,
  attach the newest dated log too.
- Each save is a `.save` file, and the matching `.bak` file is the version it
  replaced.
- `settings.cfg` holds your settings and key bindings.

On Steam Deck and Linux, the Windows build runs through Proton or Wine. The
same folders sit inside its prefix, under `drive_c/users/<user>/AppData/Roaming`.

- With Steam, the prefix is `steamapps/compatdata/<app ID>/pfx` in the Steam
  library that holds the game, usually `~/.local/share/Steam`. The user is
  `steamuser`, and the app ID is the number in the game's Steam store address.
- With Wine, the prefix is `~/.wine` or your `WINEPREFIX`, and the user is your
  own user name.

Before you attach anything to an issue:

- Issues and their attachments are public. Anyone with the link can open an
  attachment without signing in.
- Logs can include your Windows user name in file paths, and that name is often
  part of your real name or email address. You can replace it with `USER`
  before uploading.
- Screenshots and videos can show other windows, notifications and account
  names, and recordings can pick up your microphone or voice chat. Check them
  before you post.
- Zip a save or settings file before you upload it, because GitHub doesn't
  accept `.save` or `.cfg` files.

## Writing a useful report

Describe what you did, what you expected and what happened instead. Copy the
exact error text into the report so others can search for it, and add
screenshots or a short video if they help.

We're a small studio and answer as soon as we can.
