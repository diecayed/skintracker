# Privacy

Skin Tracker runs entirely on your computer. There is no account, no analytics and no telemetry.

## What it reads
From **your own League client**, on your machine, with read-only requests: your Riot ID (shown in Settings), your
skin/chroma/emote/icon/ward inventory with purchase dates, your RP / Blue Essence / Mythic Essence balance, and the
store and Mythic Shop listings the client already shows you. To talk to the client it uses the local connection details
the client itself publishes (its lockfile or process arguments). These are used only on your machine and are never
stored or sent anywhere.

## What it stores (on your computer only)
In `%APPDATA%\SkinTracker`: a cache of game data, a snapshot of your last inventory (so the app still opens when the
client is closed), your wishlist, your notifications, and a small log. Delete the folder to remove all of it.

## What it connects to
| Where | Why | What is sent |
|---|---|---|
| `raw.communitydragon.org` | public game data and images (skin names, art, PBE data) | an ordinary web request (your IP address, program name/version); nothing about your account |
| `api.github.com`, `github.com` | check for and download updates | an ordinary web request (your IP address, program name/version) |

Your Riot ID, inventory, balances and wishlist never leave your computer.

## Changes
If this ever changes, it will be written here and in the release notes.
