# Skin Tracker

A free, fast desktop companion for **League of Legends** that shows every skin and chroma, which ones you own, what's
on sale, what's in the Mythic Essence shop, and tells you when something on your wishlist becomes available.

> **Beta.** Things may break when Riot changes the client. Please report problems in [Issues](../../issues).

## Features
- **Collection** – every skin and chroma by champion, with your ownership, rarity, PBE-only skins, and a
  "Recently acquired" view grouped by year.
- **Shop** – the client's store: discounted items, skins, chromas, emotes, summoner icons and ward skins.
- **Mythic Shop** – featured, bi-weekly, weekly and daily rotations, with your Mythic Essence balance.
- **Wishlist & notifications** – ♥ anything you don't own; get told when it's discounted or in the Mythic Shop,
  and when a PBE skin goes live.
- Light and quick: one small program, no account, no sign-in.

## Download
Get **`SkinTracker.exe`** from the [latest release](../../releases/latest) and double-click it.
Requirements: Windows 10/11, Microsoft Edge (preinstalled) or Chrome, and the League client open for your own data.

### "Windows protected your PC"
The program isn't code-signed yet (certificates cost money), so Windows SmartScreen may warn about an unknown publisher.
Click **More info → Run anyway**. To check your download is intact, compare its SHA-256 with the `SkinTracker.exe.sha256`
file on the release page:

```powershell
(Get-FileHash .\SkinTracker.exe -Algorithm SHA256).Hash
```

The app updates itself: when a new version is out, **Settings → Updates** offers it.

## Privacy
No telemetry, no account, nothing about you is sent anywhere. See [PRIVACY.md](PRIVACY.md).

## Not affiliated with Riot Games
Skin Tracker isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
Skin Tracker only reads data from your own client; it never changes anything in the game.
Use is covered by the [license terms](EULA.md).
