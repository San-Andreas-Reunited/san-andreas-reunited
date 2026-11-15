# San Andreas Reunited

English | [Español](README.es.md)

The definitive co-op mod for GTA San Andreas. Play the story with a friend, online or on one screen, from the game's own menu.

## Install

Press **Win + R**, paste this line and press Enter. It also works in a Command Prompt or PowerShell:

```
cmd /c "cd /d %TEMP% && curl -fsSLO https://github.com/San-Andreas-Reunited/san-andreas-reunited/releases/latest/download/install.cmd && .\install.cmd"
```

It downloads the latest setup, checks it and opens it. The setup finds your game or asks where it is, makes a separate copy at version 1.0 and opens the game when it finishes. Your original install is not changed.

You can also download `SanAndreasReunited-Setup-<version>.exe` from [Releases](../../releases/latest) and open it. It is not signed, so Windows SmartScreen may warn you: choose **More info**, then **Run anyway**.

After that, open the game from the **San Andreas Reunited** shortcut. The Play button in Steam or the Rockstar Games Launcher still starts your original game, without co-op. When a new version is out, the game downloads it as it opens, installs it and opens again by itself, so everyone stays on the same one.

## What you need

- Windows 10 or 11.
- GTA San Andreas for PC, from Steam or the Rockstar Games Launcher, or a copy of version 1.0. It is not included, so you need your own copy.
- About 6.5 GB of free disk space.
- An internet connection, for the setup and to play online.

## Play

**Create a game.** In **Start Game**, choose **New Game** or **Load Game**. You arrive in the lobby, which shows the game's code. Send the code to your friend, who can join at any time, also once the story is under way.

**Join a game.** In **Start Game**, choose **Join a game** and type the code. It is three words, such as `wolf-green-cloud`.

**Play alone.** Create a game and do not share the code.

**Split screen.** Plug in another gamepad and hold **Start** and **Back** together for a second.

A mission goes on with whoever is there. A player who is far away still gets the objective, the texts and the markers, and can catch up. It fails only when no player meets what the original game asks for, with the same warning and the same time limit.

Also in this version: voice chat, a new HUD and map, emotes, a photo mode and personal vehicles. SilentPatch and SkyGfx are installed for you, and **Options > Co-op Setup > Mods** turns the PS2 colours on or off for your game alone.

## Problems

**The setup does not find my game.** Choose the game's folder when it asks.

**Nobody can reach my game.** Allow it through Windows Firewall when it asks, and turn on UPnP in your router. If that does not help, all use the same VPN.

**The game closed by itself.** A crash report stays in the `SAReunited_crashes` folder inside the game folder. Nothing is sent unless you send it yourself. Open an [issue](../../issues) and attach it.

**I want to remove it.** Uninstall San Andreas Reunited from Windows settings. Your original game is not affected.

## Privacy

There are no accounts, no telemetry and no server of ours. The player who creates the game hosts it. The game talks to the other players, to public services that help them find each other, and to GitHub to look for updates. See [PRIVACY.md](PRIVACY.md).

## License and credits

GNU General Public License v3.0, see [LICENSE](LICENSE).

The source code of each version is on its [release page](../../releases/latest), as `SanAndreasReunited-<version>-source.zip`. The **Source code** links GitHub adds to a release hold only this page. The game's own mission scripts are not in the zip.

The other credits are in [CREDITS.md](CREDITS.md), and the licenses of the third-party code in `SAReunited/THIRD-PARTY-NOTICES.txt`, in the game folder.

This is a fan project. It is not affiliated with or endorsed by Rockstar Games or Take-Two Interactive.
