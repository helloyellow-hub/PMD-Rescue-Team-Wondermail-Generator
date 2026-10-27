# PMD-WM v1.0 — Pokémon Mystery Dungeon: Red & Blue Rescue Team Wonder Mail & SOS Mail Generator

[![Play Live in Browser (GitHub Pages)](https://img.shields.io/badge/%F0%9F%8E%AE_Play_Live_in_Browser-GitHub_Pages-f59e0b?style=for-the-badge)](https://helloyellow-hub.github.io/PMD-Rescue-Team-Wondermail-Generator/)
[![Download Standalone Offline HTML (v1.0.0 Release)](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F_Download_Standalone_Offline_HTML-v1.0.0_Release-10b981?style=for-the-badge)](https://github.com/helloyellow-hub/PMD-Rescue-Team-Wondermail-Generator/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-3b82f6?style=for-the-badge)](LICENSE)

> **🌐 Live Web App (GitHub Pages):** **[https://helloyellow-hub.github.io/PMD-Rescue-Team-Wondermail-Generator/](https://helloyellow-hub.github.io/PMD-Rescue-Team-Wondermail-Generator/)**  
> **📦 Standalone Offline Release (`v1.0.0`):** **[Download from GitHub Releases](https://github.com/helloyellow-hub/PMD-Rescue-Team-Wondermail-Generator/releases/latest)**

A standalone, zero-dependency, offline-capable single-file HTML application (`PMD-Rescue-Team-Mail-Generator-v1.0.html`) for generating, decoding, and converting **Wonder Mail**, **SOS Mail**, **A-OK Mail**, and **Thank-You Mail** passwords for ***Pokémon Mystery Dungeon: Red Rescue Team* (GBA)** and ***Blue Rescue Team* (Nintendo DS)**—complete with an interactive Rescue Team Base diorama (Outdoor & Indoor modes), animated Legendary Friend Areas, a live World Map dungeon tracker, a 3-lane animated dungeon walker, and a customizable Rescue Team Partner companion.

---

## 📸 Preview Screenshots

| 🏕️ Outdoor Rescue Team Base & Wonder Mail Generator | 🏠 Indoor Rescue Team Base Diorama & Partner Talk (`💬`) |
| :---: | :---: |
| ![Outdoor Rescue Team Base & Wonder Mail Generator](screenshots/01-outdoor-base-and-generator.png) | ![Indoor Rescue Team Base Diorama](screenshots/02-indoor-base-diorama.png) |
| *Starter-specific Outdoor Rescue Team Base hut, waving team flag, fire braziers, clickable Pelipper mail delivery, and 24-character Wonder Mail Generator controls.* | *Interactive Indoor Rescue Team Base (`🏠`) featuring Sleep (`💤`), Talk to Partner (`💬`) with authentic PMD1 emotion icons & dialogue bubbles, and Stand (`👣`).* |
| **🗺️ Live World Map, 3-Lane Dungeon Walker & Client Letter** | **🌋 Legendary Friend Area Theme & SOS ➔ A-OK Converter** |
| ![World Map, 3-Lane Dungeon Walker & Parchment Client Letter](screenshots/03-world-map-and-dungeon-walker.png) | ![Legendary Theme & SOS to A-OK Mail Converter](screenshots/04-legendary-theme-and-sos-converter.png) |
| *Generated Wonder Mail password with Rank badge, animated World Map dungeon flight tracker, 3-lane dungeon walker, and authentic parchment client letter.* | *Weather Trio Legendary Friend Area diorama (*Volcanic Pit* with Groudon, *Stratos Lookout*, *Seafloor Cave*) alongside the 54-character SOS ➔ A-OK & Thank-You Mail Converter.* |

---

## ✨ Complete Feature List

### 1. ✉️ 24-Character Wonder Mail Generator & Decoder
- **All 5 Official Mission Types**:
  - `Help me` — Rescue the client Pokémon on the target floor.
  - `Find someone` — Locate and rescue a target Pokémon for the client.
  - `Escort to X` — Escort the client Pokémon through the dungeon to the target Pokémon.
  - `Find item` — Find a specific requested item in the dungeon (or bring one from your Toolbox).
  - `Deliver item` — Deliver a specific item to the client on the target floor.
- **Complete Gen I–III Pokédex (#001 Bulbasaur – #386 Deoxys)**:
  - All 386 species selectable as Client or Target Pokémon with authentic CHUNSOFT portraits and animated sprites, plus automatic validation against game-locked pairs (e.g., Client and Target cannot be identical on rescue/escort jobs).
- **Accurate Dungeons, Floors & Items**:
  - Every *Red/Blue Rescue Team* dungeon with accurate `B#F` / `#F` floor ranges, dungeon difficulty validation, and authentic item icons across all obtainable items.
- **All Reward Types & Friend Area Rewards**:
  - Supports `Money`, `Money + ? (Item)`, `Item`, `Item + ?`, and `Friend Area` rewards (automatically filtered to the 4 eligible Wonder Mail reward Friend Areas: *Mt. Moonview*, *Sky Blue Plains*, *Dragon Cave*, and *Bountiful Sea*, which automatically set the mission difficulty to `D` or higher as required by the game).
- **Authentic Parchment Client Letter Preview**:
  - Live-rendered PMD1 client letter displaying the client's left-facing portrait, authentic PMD1 headline & flavor dialogue, place/floor, Rescue Team Rank badge (*Normal*, *Bronze*, *Silver*, *Gold*, *Diamond*, *Super*, *Ultra*, *Hyper*, *Master*, *Lucario Rank*), difficulty points, and formatted 2-line 24-character Wonder Mail password using authentic Unicode symbols (`♂`, `♀`, `…`).
- **24-Character Wonder Mail Decoder**:
  - Paste any 24-character Wonder Mail code (accepts both Unicode `♂` / `♀` / `…` and ASCII shorthand `(m)` / `(f)` / `...`) to verify its checksum, inspect its full mission breakdown, and preview its World Map location, 3-lane dungeon scene, and parchment client letter.

### 2. 🆘 54-Character SOS Mail / A-OK Mail / Thank-You Mail Suite
- **SOS → A-OK Mail Converter**:
  - Paste a 3-line (54-character) **SOS Mail** password from a fainted player to immediately generate a matching **A-OK Mail** rescue password—and optionally generate a **Thank-You Mail** password with a chosen reward item.
- **SOS / A-OK / Thank-You Mail Decoder**:
  - Inspect any 54-character password to view its Mail Type, Faint Dungeon & Floor, Fainted Pokémon species & nickname, Mail ID, Rescue Chances remaining, and Rescuer name.
- **Custom SOS Mail Generator**:
  - Generate valid 54-character SOS Mail passwords for any Pokémon, dungeon, floor, nickname, Rescue Chances (`1–99`), and Mail ID (`0000–9999`), with one-click transfer into the SOS → A-OK Converter.

### 3. 🎨 19 Interactive Lead Pokémon & Legendary Themes
- **16 PMD1 Starters**: *Bulbasaur, Charmander, Squirtle, Chikorita, Cyndaquil, Totodile, Treecko, Torchic, Mudkip, Pikachu, Eevee, Meowth, Skitty, Psyduck, Machop,* and *Cubone*.
- **Classic Theme (*Riolu*)**: Custom dark-slate Rescue Team theme paired with the classic Rock Hut base.
- **Weather Trio Legendaries**: *Rayquaza*, *Groudon*, and *Kyogre*, each with custom color palettes and animated signature Friend Area dioramas.
- **Following Partner Selector**: Pair your Lead Pokémon with any of the 17 starter/classic partners (or `None` for solo runs) across the header diorama, indoor room, and dungeon walker.

### 4. 🏠 Interactive Rescue Team Base Diorama (Outdoor & Indoor Modes)
- **Outdoor Mode**:
  - Authentic starter-specific **Rescue Team Base huts** with a 6-frame waving team flag, animated exterior fire braziers (for Fire starters *Charmander, Cyndaquil,* and *Torchic*), and your Lead & Following Partner idling outside.
  - **Ambient Sky Flyers & Legendary Easter Eggs**: Periodic solo flying Pokémon (*Pelipper, Wingull, Murkrow, Swablu, Altaria, Fearow*) plus rare 1% Easter egg flybys (*Latias, Latios, Articuno, Zapdos, Moltres, Lugia, Ho-Oh, Mew, Celebi,* and *Jirachi*, plus ultra-rare *Shiny Celebi*).
  - **Clickable Pelipper Mail Delivery**: Pelipper flies across the sky above the hut entrance and drops a Wonder Mail letter right in front of your Lead Pokémon (triggering an authentic PMD1 `!` exclamation reaction). Click or tap the dropped letter on the ground to trigger a smoke poof, randomize a brand-new Wonder Mail mission, and smoothly scroll down to the generated client letter!
- **Indoor Mode (`🏠` / `🌲`)**:
  - Click the `🏠` button in the bottom-left corner of the diorama to step inside your starter's authentic Rescue Team Base interior room alongside your Following Partner:
    - **`💤` (Sleep)**: Your Lead Pokémon teleports to the room's bed with a 7-frame purple smoke poof and curls up to sleep with rising `Zzz`s. Clicking `💤` or `🌲` while sleeping wakes your Pokémon back to the center floor first with a confused `?` reaction.
    - **`💬` (Talk to Partner)**: Your Lead Pokémon steps beside your Following Partner (`(146, 110)` next to `(174, 110)`), both turn to face each other (East/West directional sprites), display an authentic PMD1 emotion icon (`!`, `?`, sweat drop, shock spikes, or happy sparkles), and trigger a personality-matched Partner dialogue bubble before turning back toward the front.
    - **`👣` (Stand)**: Returns your Lead Pokémon to the center floor emblem (`(120, 118)`) with a purple smoke poof.
- **Animated Legendary Friend Areas**:
  - **Rayquaza (*Stratos Lookout*)**: Sky-high cloud shrine with drifting cloud layers.
  - **Groudon (*Volcanic Pit*)**: Pulsing 8-frame crimson/magenta altar runes, dual cascading lava waterfalls with splash pools, and 3-frame popping magma bubbles.
  - **Kyogre (*Seafloor Cave*)**: Pulsing crimson floor sigil and rising deep-sea water bubbles.

### 5. 🗺️ Interactive World Map & 3-Lane Dungeon Walker
- **Live PMD1 World Map Tracker**:
  - Displays the authentic *Red/Blue Rescue Team* overworld map and smoothly flies a animated marker + glowing target reticle to the selected dungeon whenever you change dungeons or decode a password.
- **3-Lane Animated Dungeon Scene**:
  - Renders an authentic dungeon tileset matching the selected dungeon's biome, featuring:
    - **Top & Bottom Lanes**: Wild Pokémon native to the dungeon walking across the floor, plus periodic **Dungeon Boss walk-bys** (all 25 PMD1 bosses mapped to their exact boss dungeons, including all 4 *Deoxys* Formes—*Normal, Attack, Defense, Speed*—cycling in *Meteor Cave*) and rare **Green & Purple Kecleon** walk-bys in dungeons that spawn Kecleon Shops.
    - **Middle Lane**: Your Lead Pokémon, Following Partner, and (on Escort missions) the Escort Client materializing via a purple smoke poof and marching together in formation.
    - **Mission Summary Footer**: Animated client & target sprites alongside a live objective readout (`Place`, `Objective`, `Client`, `Reward`, and `Difficulty`).

### 6. 💬 Floating Partner Companion & Quick Randomizer (`🎲`)
- **Interactive Partner Bubble**: Tap your Partner's portrait (or the `💬 Talk` pill) for reactive commentary when generating codes, decoding passwords, changing dungeons/items, or idling.
- **Expression & Dialogue Settings (`⚙️`)**: Switch between *Neutral, Happy, Inspired, Determined,* and *Worried* CHUNSOFT portraits, and toggle `⏱ Auto-Close (6s)` or `🔄 Auto-Neutral (4.5s)`.
- **One-Tap Mission Randomizer (`🎲`)**: Instantly generates a 100% valid, conflict-free Wonder Mail mission and updates the World Map, 3-lane dungeon scene, and parchment client letter.

---

## 📖 How to Use the Tool Properly

### 1. Running the App (Offline or Online)
- **Zero Installation Required**: Simply open `PMD-Rescue-Team-Mail-Generator-v1.0.html` (or `index.html` if hosted on GitHub Pages) in any modern desktop or mobile browser (Chrome, Firefox, Edge, Safari).
- All sprites, portraits, maps, fonts, and generator logic are self-contained inside the single HTML file—no internet connection, external server, or build step is needed to use the app.

### 2. Generating a 24-Character Wonder Mail Code
1. Open the **Wonder Mail Generator** tab (selected by default).
2. Choose your **Mission Type** (*Help me*, *Find someone*, *Escort to X*, *Find item*, or *Deliver item*).
3. Select the **Client Pokémon** and (for rescue/escort jobs) the **Target Pokémon**.
   - *Tip*: Use the search filter boxes above the dropdowns to quickly jump to any of the 386 Pokémon or items by name.
4. Select the **Dungeon** and **Floor**.
5. Choose a **Reward Type** and (if applicable) a **Reward Item** or **Friend Area**.
6. Click **Generate Wonder Mail** (or click **`🎲` Randomize** in the bottom-right corner / click the dropped **Pelipper letter** in the top diorama).
7. Enter the 2-line **24-character password** in *Pokémon Mystery Dungeon: Red/Blue Rescue Team* via **Main Menu → Wonder Mail → Receive Wonder Mail → Password**.

> **⚠️ Important In-Game Requirements for Wonder Mail**:
> - **Dungeon Unlock**: You must have unlocked the mission's dungeon in your save file before the game will let you accept the job.
> - **Friend Area Requirement**: For **Escort** missions or missions that reward a **Friend Area** / recruitable client, you must already own the corresponding Friend Area in-game (or for a Friend Area reward, you must *not* already own that Friend Area).
> - **Special Symbols (`♂`, `♀`, `…`)**: In the password display, `♂` = Male symbol, `♀` = Female symbol, and `…` = horizontal ellipsis (a single character on the in-game password entry screen, not three separate periods).

### 3. Decoding an Existing Wonder Mail Password
1. Switch to the **Wonder Mail Decoder** tab.
2. Paste any 24-character password (spaces and line breaks are ignored; you may use `♂`, `♀`, `…` or type `(m)`, `(f)`, `...`).
3. Click **Decode Wonder Mail** to verify the password and view its full mission details, World Map pin, 3-lane dungeon preview, and parchment letter.

### 4. Rescuing a Friend (SOS Mail → A-OK Mail Converter)
1. Switch to the **SOS → A-OK Converter** tab.
2. Paste your friend's 54-character (3-line) **SOS Mail** password into the input box.
3. Optionally enter your **Rescuer / Team Name** and pick a **Reward Item** if you also want to generate a **Thank-You Mail**.
4. Click **Convert to A-OK Mail** and send the resulting 54-character **A-OK Mail** password back to your friend so they can revive on the exact dungeon floor where they fainted!

### 5. Customizing Your Theme, Partner & Rescue Team Base
- Use the **Lead Pokémon** and **Following Partner** dropdowns in the top header to switch themes and sprites at any time.
- Click **`🏠`** on the top diorama to enter your **Rescue Team Base** indoor room, where you can click **`💤`** (Sleep on bed), **`💬`** (Talk to Partner), or **`👣`** (Stand on the center emblem), or click **`🌲`** to head back outdoors.

---

## 🏆 Credits & Acknowledgments

### 🛠️ Development, Design & Interactive Engineering
- **Put Together by:** [Dave Alfred (`@helloyellow-hub`)](https://github.com/helloyellow-hub)

### 🔐 Core Password Generation & Decoding Algorithms
- **[UPokeCenter (Peter O. / The Ultimate Pokémon Center)](https://www.upokecenter.com/games/dungeon/guides/wondermail.php)** — Most importantly, special thanks to **UPokeCenter** (`wondermail.php` & `sosgen.php`) for reverse-engineering and documenting the original *Pokémon Mystery Dungeon: Red & Blue Rescue Team* 24-character Wonder Mail and 54-character SOS / A-OK / Thank-You Mail bit-packing tables, checksums, encryption tables, mission validation rules, and flavor-text generation logic.

### 🎨 Sprites, Portraits, Maps & Visual Assets
- **[The Spriters Resource](https://www.spriters-resource.com/game_boy_advance/pokemonmysterydungeonredrescueteam/)** — Authentic *Red/Blue Rescue Team* (GBA/NDS) and *Explorers of Time/Darkness/Sky* Rescue Team Base huts (outdoor & indoor), waving flags, fire braziers, Friend Area maps (*Volcanic Pit*, *Seafloor Cave*), Pelipper mail-carrier sprites, and PMD1 emotion icons (`19786_Effects.png` ripped by KillerAslox).
- **[PMD Collab / SpriteCollab](https://sprites.pmdcollab.org/)** — Authentic CHUNSOFT Nintendo DS / GBA Pokémon character portraits and directional idle, walking, and sleeping sprite sheets across all 386 Gen I–III Pokémon.
- **[Bulbapedia & Bulbagarden Archives](https://bulbapedia.bulbagarden.net/wiki/Pok%C3%A9mon_Mystery_Dungeon:_Red_Rescue_Team_and_Blue_Rescue_Team)** — *Red/Blue Rescue Team* dungeon floor tables, item sprites, Rescue Team rank badges, boss listings, and overworld map references.

### 🎮 Original Game & Intellectual Property
- ***Pokémon Mystery Dungeon: Red Rescue Team* & *Blue Rescue Team*** — Developed by **Chunsoft (Spike Chunsoft)** and published by **Nintendo** & **The Pokémon Company** (© 2005–2006 Nintendo / Creatures Inc. / GAME FREAK inc. / Chunsoft).
- *Disclaimer*: This project is an unofficial, non-commercial fan-made utility built for game preservation and community use. All Pokémon names, characters, sprites, and trademarks are the property of Nintendo, Creatures Inc., GAME FREAK inc., The Pokémon Company, and Spike Chunsoft.
