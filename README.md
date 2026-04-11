# D&D DM Inspiration Toolkit

A self-contained, single-file companion app for D&D 5e Dungeon Masters. No installation, no account, no server just open the file and play.

Features:

Party Tab — PC cards with class, subclass, species, level, HP, AC, spell slots, class resources, death saves, conditions, exhaustion, and inspiration. Color-coded cards, campaign-aware data.

Session Tab — Live session notes, weather, calendar, tension tracker, session timer, combat tracker with initiative order, spotlight tracker, and countdown timer.

Generator Tab — One-click generators for names, NPCs, dungeon rooms, random encounters, shops, loot, story hooks, and more. All filterable and re-rollable.

Saved Tab — Session history with notes and recap, party snapshots, and a persistent notes pad.

Tools Tab — Quick reference tables for conditions, spells, actions, and rules. Rumour board and event log.

Campaign Manager — Switch between multiple campaigns. Each campaign maintains its own party, session history, and tracker data independently.


## Technical

Pure HTML + CSS + JavaScript — zero dependencies, zero build step
All data stored locally via localStorage — nothing leaves your device
Works offline once loaded
Also available as a desktop app via Tauri for Mac and Windows

Usage
Open index.html in any modern browser, or visit the hosted version.


## Live App
👉 **[Open the Toolkit](https://schneepers.github.io/dndit)**

## Deploy Your Own

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: **main**, folder: **/ (root)**
5. Click Save — live in ~1 minute

## Data & Privacy
All data is stored locally in your browser via `localStorage`. Nothing is sent to any server.
