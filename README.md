<div align="center">

# 📮 PMD Rescue Team Wonder Mail & SOS Mail Generator (`v1.0`)

**The Ultimate All-in-One Offline Password Suite & Interactive Pixel-Art Diorama for _Pokémon Mystery Dungeon: Red Rescue Team_ (GBA) & _Blue Rescue Team_ (NDS)**

[![Version v1.0](https://img.shields.io/badge/Version-v1.0-f59e0b?style=for-the-badge&logo=pokemon&logoColor=white)](https://github.com/helloyellow-hub/PMD-Rescue-Team-Wondermail-Generator)
[![100% Offline Standalone HTML](https://img.shields.io/badge/100%25_Offline-Standalone_HTML-10b981?style=for-the-badge&logo=html5&logoColor=white)](PMD-Rescue-Team-Mail-Generator-v1.0.html)
[![386 Gen I–III Pokémon](https://img.shields.io/badge/Pokémon-386_Gen_I–III-ef4444?style=for-the-badge)](https://github.com/helloyellow-hub/PMD-Rescue-Team-Wondermail-Generator)
[![19 Dynamic Themes](https://img.shields.io/badge/Themes-19_Starters_%26_Legendaries-8b5cf6?style=for-the-badge)](https://github.com/helloyellow-hub/PMD-Rescue-Team-Wondermail-Generator)
[![MIT License](https://img.shields.io/badge/License-MIT-3b82f6?style=for-the-badge)](LICENSE)

<br />

![Interactive Rescue Team Base Diorama — Outdoor & Indoor Modes](readme-assets/hero-banner.gif)

*Above: The **Interactive Rescue Team Base Diorama** in **Outdoor Mode** (6-frame waving team flag, 10 animated fire braziers, Pelipper sky mail drop, and clickable Wonder Mail letter with a 7-frame purple smoke poof) and **Indoor Mode** (talking to your Partner with PMD1 emotes, sleeping on the cushion bed with rising `Zzz`s, and standing on the center emblem).*

<br />

[🌐 **Launch Live Web App**](https://helloyellow-hub.github.io/PMD-Rescue-Team-Wondermail-Generator/) · [📥 **Download Offline Standalone HTML (`PMD-Rescue-Team-Mail-Generator-v1.0.html`)**](PMD-Rescue-Team-Mail-Generator-v1.0.html) · [📖 **How to Use**](#-how-to-use-all-4-tabs) · [🏆 **Credits**](#-credits--acknowledgments)

</div>

---

## ✨ Overview

**PMD Rescue Team Wonder Mail Generator (`v1.0`)** is a faithful, feature-packed modernization of the classic UPokeCenter *Pokémon Mystery Dungeon: Red & Blue Rescue Team* password tools — packaged into a **single, 100% self-contained offline `.html` file** with zero external dependencies.

Every bit-packing encryption table, checksum validator, dungeon floor rule, CHUNSOFT character portrait, GBA/DS overworld sprite, Rescue Team Base hut, Legendary Friend Area lair, and dungeon background is embedded directly inside **`PMD-Rescue-Team-Mail-Generator-v1.0.html`**. Whether you want to generate a specific **Friend Bow** or **Golden Seed** mission, unlock Wonder Mail-exclusive **Friend Areas**, decode an old password, or rescue yourself from a fainted floor in *Purity Forest* or *Wish Cave* by converting an **SOS Mail ➔ A-OK Mail**, everything works instantaneously in any browser — online or completely offline.

---

## 🚀 Live Demo & Quick Start

### 1. Play Instantly in Your Browser (GitHub Pages)
👉 **[https://helloyellow-hub.github.io/PMD-Rescue-Team-Wondermail-Generator/](https://helloyellow-hub.github.io/PMD-Rescue-Team-Wondermail-Generator/)**

### 2. Run 100% Offline (Single-File Standalone HTML)
1. Download **[`PMD-Rescue-Team-Mail-Generator-v1.0.html`](PMD-Rescue-Team-Mail-Generator-v1.0.html)** from this repository (or clone the repo via `git clone https://github.com/helloyellow-hub/PMD-Rescue-Team-Wondermail-Generator.git`).
2. Double-click **`PMD-Rescue-Team-Mail-Generator-v1.0.html`** to open it in any desktop or mobile browser (`Chrome`, `Firefox`, `Safari`, `Edge`).
3. **No internet connection, no local server, and no `npm install` required.** All 386 Pokémon sprites, portraits, maps, and generators run locally in your browser.

---

## 🌟 Features & Functions

### 1. 📜 Wonder Mail Generator & Decoder (24-Character Passwords)
Generate and inspect authentic **24-character Pelipper Post Office Wonder Mail passwords** (`XXXX XXXX XXXX` / `XXXX XXXX XXXX`) compatible with both *Red Rescue Team* (GBA) and *Blue Rescue Team* (NDS):
- **All 5 Official Mission Types**:
  - `Help me.` — Rescue the client Pokémon on the target floor.
  - `Find someone.` — Locate and rescue the target Pokémon for the client.
  - `Escort.` — Escort the client Pokémon through the dungeon to the target Pokémon.
  - `Find item.` — Obtain a specific item inside the selected dungeon and hand it to the client.
  - `Deliver item.` — Bring an item into the dungeon and deliver it to the client on the target floor.
- **Full PMD1 Dungeon & Floor Validation**: Automatically populates the exact floor count and `B1F` / `1F` direction for every dungeon in the game.
- **Smart Item Spawn Verification (`ItemInDungeon`)**: When creating a *Find item* mission, the generator checks the internal PMD1 dungeon spawn tables in real time and warns you if the chosen item does not naturally spawn in that dungeon (so your mission is guaranteed to work in-game).
- **Instant Search Across All 386 Gen I–III Species**: Filter Clients, Targets, Dungeons, and Rewards instantly with live search boxes and animated sprite previews (automatically excluding legendaries/bosses that cannot legally appear as regular Wonder Mail clients).
- **Friend Area Unlock Validation**: Supports all 4 Wonder Mail-exclusive Friend Areas (**Sky Blue Plains**, **Mt. Moonview**, **Bountiful Sea**, **Treasure Sea**) and automatically enforces the in-game requirement that Friend Area rewards require at least **D-Rank** mission difficulty (or **Pelipper Isle**).
- **Authentic Parchment Mission Letter**: Renders an in-game Pelipper Post Office job letter complete with dynamic flavor headlines and body text, a left-facing **CHUNSOFT client portrait**, reward item sprite, **GBA Rescue Team Rank badge** (`E` through `★`), and copyable **Unicode `♂` / `♀` / `…` passwords**.
- **24-Character Wonder Mail Decoder**: Paste any existing 24-character password to verify its checksum, inspect every bit-packed parameter, and preview the decoded mission live on the World Map and 3-Lane Dungeon Walker. Includes one-click `♂`, `♀`, and `…` symbol buttons plus automatic `M` / `F` / `.` shorthand conversion.

---

### 2. 🆘 SOS Mail, A-OK Mail & Thank-You Mail Suite (54-Character Passwords)
Never stay stranded in a 99-floor dungeon again! Full support for **54-character Rescue Passwords** (`XXXXX XXXXXXXX XXXXX` across 3 rows):
- **Bi-Directional SOS ➔ A-OK Mail Converter**:
  - Fainted in *Silver Trench*, *Buried Relic*, *Wish Cave*, or *Purity Forest*? Enter your 54-character **SOS Mail** password from your game screen and convert it directly into a valid **54-character A-OK Mail** password in one click.
  - Rescue yourself or friends across GBA, Nintendo DS, Virtual Console, and emulators **without needing a GBA Link Cable or DS Wireless connection**.
- **Custom SOS / A-OK / Thank-You Mail Generator**:
  - Generate custom 54-character **SOS Mail**, **A-OK Mail**, or **Thank-You Mail** codes from scratch.
  - Customize the **Dungeon & Floor**, **Fainted Client Pokémon**, **4-Digit Mail ID** (`0000`–`9999`), **Remaining Rescue Chances** (`1`–`10`), and **Bonus Reward Item** (for *Thank-You Mail*).

---

### 3. 🎨 19 Starter, Partner & Legendary Themes

<div align="center">

![19 Starter, Partner & Legendary Themes Showcase](readme-assets/themes-showcase.gif)

*Above: Cycling through the **19 dynamic themes** — transforming the UI color palette, CHUNSOFT starter portrait, Rescue Team Base hut or Legendary Friend Area lair, and Floating Partner Companion.*

</div>

Choose from **19 handcrafted themes** via the **Lead Pokémon** selector. Switching your Lead Pokémon dynamically recolors the entire interface, swaps your Rescue Team Base architecture, updates the Lead walker in the dungeon scene, and updates your Floating Partner Companion:

| Category | Themes Included | Special Visual Details |
| :--- | :--- | :--- |
| **Gen I–III Fire Starters (3)** | **Torchic** (`#255`), **Charmander** (`#004`), **Cyndaquil** (`#155`) | Species-specific Fire Hut + **10 outdoor & 5 indoor animated flaming stone braziers** |
| **Gen I–III Water Starters (3)** | **Squirtle** (`#007`), **Totodile** (`#158`), **Mudkip** (`#258`) | Species-specific Water Base Hut + ocean/aqua UI palette & matching team flag |
| **Gen I–III Grass Starters (3)** | **Bulbasaur** (`#001`), **Chikorita** (`#152`), **Treecko** (`#252`) | Species-specific Forest Leaf Base Hut + botanical emerald/sage UI palette |
| **PMD1 Personality Test Partners (6)** | **Pikachu** (`#025`), **Meowth** (`#052`), **Psyduck** (`#054`), **Machop** (`#066`), **Cubone** (`#104`), **Eevee** (`#133`), **Skitty** (`#300`) | Authentic species-shaped Rescue Team Bases + custom team flags & partner palettes |
| **Classic Theme (1)** | **Classic / Riolu** (`#447`) | Clean dark-slate aesthetic featuring the **initial unupgraded rock Rescue Team Base** |
| **Weather Trio Legendaries (3)** | **Rayquaza** (`#384`), **Groudon** (`#383`), **Kyogre** (`#382`) | Replaces the Rescue Team Base with each Legendary's animated **Friend Area Lair** |

---

### 4. 🏠 Interactive Rescue Team Base Diorama (Outdoor & Indoor Modes)
At the top of the app sits a living **`240×180` native GBA/DS pixel-art diorama** of your Rescue Team Base:
- **6-Frame Waving Team Flags**: Your starter's custom emblem flag waves smoothly in the breeze beside the base.
- **Outdoor & Indoor Flaming Braziers**: Selecting **Torchic**, **Charmander**, or **Cyndaquil** lights up 10 stone fire braziers around the outdoor courtyard and 5 indoor wall braziers with multi-frame flickering flames.
- **Occasional Bird-Only Sky Flybys**: Watch **Pelipper**, **Pidgeot**, **Articuno**, **Zapdos**, **Moltres**, **Latias**, **Latios**, **Mew**, **Celebi**, and **Jirachi** soar across the sky with ground shadows.
- **Interactive Pelipper Sky Mail Drop**:
  - Periodically, **Pelipper** swoops down over your Rescue Team Base and drops a bouncing **Wonder Mail Letter** onto the path at `(120, 142)`.
  - Your Lead Pokémon reacts with an authentic PMD1 **`!`** exclamation icon above its head.
  - **Click the dropped letter** to trigger a **7-frame purple smoke poof** and immediately roll & generate a complete, ready-to-play Wonder Mail mission!
- **Indoor Base Mode (`🏠` / `🌲` Toggle)**:
  - Click the **`🏠`** button in the bottom-left corner of the diorama to step inside your Rescue Team Base interior with both your **Lead Pokémon** and **Following Partner**.
  - Use the **3 Interactive Indoor Action Buttons** in the bottom-right corner:
    - **`💤` Sleep on the Bed**: Your Lead Pokémon teleports onto the cushion bed in a purple smoke poof, curls up in its authentic sleeping sprite, and floats rising **`Zzz`** icons while your Partner watches.
    - **`💬` Talk to Partner**: Lead and Partner move to the center floor star emblem, face each other with authentic PMD1 emotion icons (`!`, `?`, `♪`, sparkles, heart, sweat drop), and trigger a personality-matched dialogue bubble.
    - **`👣` Stand in the Room**: Wakes your Lead Pokémon from the cushion bed with a 7-frame purple smoke poof and `?` emote, returning them to the center floor circle `(120, 118)`.

---

### 5. 🌋 Animated Legendary Friend Areas (Weather Trio Showcase)

<div align="center">

![Weather Trio Legendary Friend Areas — Rayquaza, Groudon & Kyogre](readme-assets/legendary-friend-areas.gif)

*Above: The three **Weather Trio Legendary Themes** — **Rayquaza** at *Stratos Lookout*, **Groudon** at *Volcanic Pit* (pulsing magma runes, dual lava waterfalls & popping lava bubbles), and **Kyogre** at *Seafloor Cave* (pulsing abyssal floor sigil & rising deep-sea bubbles).*

</div>

Selecting one of the **Weather Trio Legendaries** transforms the top diorama into their iconic *Red/Blue Rescue Team* **Friend Area**:
- **Rayquaza (`#384`) — *Stratos Lookout***: Rayquaza rests atop the ancient Sky Shrine altar high above the clouds with an emerald-and-gold sky aura theme.
- **Groudon (`#383`) — *Volcanic Pit***: Features an **8-frame pulsing magma altar glow** around Groudon, **dual cascading lava waterfalls** pouring down the upper cliffs, and **bubbling lava pools** that rise and pop across the chamber.
- **Kyogre (`#382`) — *Seafloor Cave***: Features a **pulsing crimson-gold ancient floor sigil** beneath Kyogre and continuous **rising underwater bubble streams** drifting up through the deep-sea cavern.

---

### 6. 🗺️ Interactive PMD1 World Map & 3-Lane Animated Dungeon Walker

<div align="center">

![3-Lane Animated Dungeon Walker, Interactive PMD1 World Map & Parchment Mission Letter](readme-assets/dungeon-walker-and-map.gif)

*Above: Live **Interactive PMD1 World Map** camera pan & pulsing target pin paired with the **3-Lane Animated Dungeon Walker (`336×144`)**, **Unicode `♂`/`♀`/`…` Password Box**, **GBA Rank Bar**, and **Authentic Parchment Mission Letter**.*

</div>

Every generated or decoded Wonder Mail mission comes alive through two synchronized canvas engines:
- **Interactive PMD1 World Map (`240×180`)**:
  - Smoothly pans the camera across the authentic *Red/Blue Rescue Team* overworld map to the selected dungeon's exact coordinates.
  - Highlights the active dungeon with a **pulsing red-and-gold target pin** and your Lead Pokémon's badge.
- **3-Lane Animated Dungeon Walker (`336×144`)**:
  - Renders the authentic **dungeon floor & wall tileset** matching the selected dungeon (volcanic rock in *Mt. Blaze*, crystal crater tiles in *Meteor Cave*, forest paths in *Tiny Woods*, etc.), complete with dungeon stairs and scattered floor items.
  - **Center Lane (Rescue Team Party)**: Your **Lead Pokémon**, **Following Partner**, and (on *Escort* missions) the **Client Pokémon** march East together through the dungeon.
  - **Top & Bottom Depth Lanes (Wild Spawns, Bosses & Kecleon)**:
    - Spawns authentic **wild Pokémon** native to that specific dungeon walking West across the upper and lower depth lanes.
    - **All 25 PMD1 Dungeon Bosses**: Selecting a Boss Dungeon spawns its iconic boss patrolling the outer lanes — including **Moltres**, **Zapdos**, **Articuno**, **Groudon**, **Rayquaza**, **Kyogre**, **Mewtwo**, **Lugia**, **Ho-Oh**, **Celebi**, **Jirachi**, **Regirock**, **Regice**, **Registeel**, **Entei**, **Raikou**, **Suicune**, **Latios**, and all **4 Deoxys Formes** (*Normal*, *Attack*, *Defense*, and *Speed*) in **Meteor Cave**.
    - **Rare Green & Purple Kecleon Walk-Bys**: In dungeons that feature Kecleon Shops, **Green Kecleon** and **Purple Kecleon** occasionally stroll across the outer lanes.

---

### 7. 💬 Floating Partner Companion
In the bottom-right corner of the screen sits your interactive **Rescue Team Partner Companion**:
- **Dynamic Personality Dialogues**: Speaks in character based on your selected Lead/Partner Pokémon whenever you switch themes, roll a mission, or click the portrait.
- **6 Official CHUNSOFT Expressions**: Switch between *Neutral*, *Happy*, *Determined*, *Joyous*, *Surprised*, and *Sad* portraits via the `⚙️` **Settings** panel, with configurable **Auto-Close (`6s`)** and **Auto-Neutral (`4.5s`)** timers.
- **One-Click `🎲` Quest Randomizer**: Click the floating **`🎲`** dice button (or the **`🎲`** button next to *Generate Wonder Mail*) to roll a 100% valid random mission across all 386 Pokémon, dungeons, floors, and rewards.

---

## 📖 How to Use (All 4 Tabs)

### Tab 1: `Wonder Mail` (24-Character Generator)
1. **Pick a Mission Type** (`Help me`, `Find someone`, `Escort`, `Find item`, or `Deliver item`) — or click **`🎲`** to roll a complete valid mission automatically.
2. **Choose Your Reward & Friend Area**:
   - Select any item in the game (such as `Friend Bow`, `Golden Seed`, `Tight Belt`, `Gold Ribbon`, or `TM`s) or a **Wonder Mail-Exclusive Friend Area** (*Sky Blue Plains*, *Mt. Moonview*, *Bountiful Sea*, *Treasure Sea*).
   - Use the live search box above the dropdown to filter items by name or category.
3. **Select Client & Target Pokémon**:
   - Search and pick from all **386 Gen I–III Pokémon**.
4. **Select Dungeon, Floor & Flavor Text**:
   - Choose the **Dungeon** and **Floor** (remember: unlocking a *Friend Area* reward requires at least **Rank D** difficulty or *Pelipper Isle*).
   - Customize the **Headline** and **Letter Body** text or leave the authentic defaults.
5. **Click `Generate Wonder Mail`**:
   - Copy the **2-line 24-character password** (`XXXX XXXX XXXX` / `XXXX XXXX XXXX`) and enter it at the **Main Menu ➔ Wonder Mail** screen in *Red Rescue Team* or *Blue Rescue Team*.

### Tab 2: `Generate SOS` (54-Character Custom SOS / A-OK / Thank-You Generator)
1. Choose the **Mail Mode**: `SOS Mail (Need Rescue)`, `A-OK Mail (Rescue Completed)`, or `Thank-You Mail (Send Reward)`.
2. Select the **Dungeon**, **Floor**, and **Fainted Client Pokémon**.
3. Set a **Mail ID** (`0000`–`9999`), **Remaining Rescue Chances** (`1`–`10`), and (if generating a *Thank-You Mail*) a **Bonus Reward Item**.
4. Click **`Generate 54-Char Mail`** to get the 3-line 54-character password formatted exactly as the game expects (`XXXXX XXXXXXXX XXXXX`).

### Tab 3: `SOS ➔ A-OK` (54-Character Self-Rescue Converter)
1. When you faint in a dungeon and request a rescue, copy the **54-character SOS Mail password** displayed by Pelipper Post Office.
2. Paste the 3-line password into the **SOS ➔ A-OK Converter** tab (use the **`Insert ♂`**, **`Insert ♀`**, and **`Insert …`** buttons for special symbols, or type `M`, `F`, `.`).
3. Optionally select a **Reward Item** if you also want a **Thank-You Mail** code.
4. Click **`Convert to A-OK Mail`** to immediately receive the matching **54-character A-OK Mail password** — enter it in your game under **Receive A-OK Mail** to revive your team right on the floor where you fainted!

### Tab 4: `Decode Mail` (24-Character Wonder Mail Inspector)
1. Paste any **24-character Wonder Mail password** into the decoder box.
2. Click **`Decode Wonder Mail`** to validate its bit-packed checksum and inspect the exact **Mission Type**, **Client**, **Target**, **Dungeon & Floor**, **Difficulty Rank**, **Money/Item/Friend Area Reward**, and **Flavor Text** on the live World Map, 3-Lane Dungeon Walker, and Parchment Letter.

---

## ⚠️ Important In-Game Requirements (*Red & Blue Rescue Team*)

To ensure the game accepts your generated passwords without errors, keep these built-in *Pokémon Mystery Dungeon* rules in mind:
1. **Friend Area Requirement for Recruits & Clients**: You must already own the **Friend Area** of the Client/Target Pokémon for certain missions, and you must unlock a dungeon in your story progression before taking missions there.
2. **Unlocking the 4 Wonder Mail-Exclusive Friend Areas**:
   - **Sky Blue Plains**, **Mt. Moonview**, **Bountiful Sea**, and **Treasure Sea** can *only* be unlocked via Wonder Mail rewards.
   - The game requires the mission difficulty to be **at least Rank D** (or located at **Pelipper Isle**) for a Friend Area reward to be valid. *(The generator enforces this rule automatically!)*
3. **Identical Client & Target**: A Pokémon cannot rescue or escort itself — always pick a different species for Client and Target.
4. **Deliver / Find Item Missions**:
   - For **Find item** missions, the item must naturally spawn in the chosen dungeon *(verified automatically by the built-in `ItemInDungeon` checker)*.
   - For **Deliver item** missions, you bring the item from your own Toolbox/Kangaskhan Storage into the dungeon.

---

## 🏆 Credits & Acknowledgments

### Project Team
- **Put Together by:** [Dave Alfred](https://github.com/helloyellow-hub)

### Core Algorithm & Game Data Research
- **Original Wonder Mail & SOS/A-OK Bit-Packing Research:** [UPokeCenter / Peter O.](https://www.upokecenter.com/) — For pioneering the reverse-engineering and documentation of the *Pokémon Mystery Dungeon: Red & Blue Rescue Team* bit-packing, checksum, encryption table, and dungeon/item ID specifications.

### Sprites, Portraits, Maps & Visual Assets
- **Rescue Team Base Huts, Friend Area Backgrounds, Dungeon Tilesets & Overworld Maps:** Rippers and contributors at [The Spriters Resource — Pokémon Mystery Dungeon: Red / Blue Rescue Team](https://www.spriters-resource.com/game_boy_advance/pokemonmysterydungeonredrescueteam/) and [Blue Rescue Team (NDS)](https://www.spriters-resource.com/ds_dsi/pokemonmysterydungeonbluerescueteam/).
- **CHUNSOFT Character Portraits & Animated Dungeon Sprites:** **Chunsoft** original game assets & the [PMD Collab / SpriteCollab Project](https://sprites.pmdcollab.org/).
- **Game Mechanics, Dungeon Spawn Tables & Friend Area Documentation:** [Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Pok%C3%A9mon_Mystery_Dungeon:_Red_Rescue_Team_and_Blue_Rescue_Team).

### Legal Disclaimer
*Pokémon*, *Pokémon Mystery Dungeon*, *Red Rescue Team*, *Blue Rescue Team*, and all associated character names, sprites, portraits, and imagery are trademarks and © of **Nintendo**, **Creatures Inc.**, **GAME FREAK inc.**, and **Spike Chunsoft Co., Ltd.** This project is a free, non-commercial, open-source fan tool created for educational and preservation purposes.

---

<div align="center">

Made with ❤️ for the *Pokémon Mystery Dungeon* community by **[Dave Alfred](https://github.com/helloyellow-hub)**

</div>
