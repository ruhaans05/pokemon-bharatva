# Pokémon Bharatva

A fan-made, GBA-style (Emerald/FireRed era) Pokémon game set in **Bharatva**, a region based on India — built as a single self-contained HTML file. No dependencies, no build step: open `index.html` in any browser.

## The region

Journey south to north, following India's geography: from the coconut backwaters of **Nariyalpur** (Kerala), through the Western Ghats, the tech hub of **Yantra City**, the beaches of **Sona Beach** (Goa), the megacity of **Mahanagar** (Mumbai), across the **Thar Desert** to the golden fort of **Marudhara**, along the Gangetic plain to the ghats of **Ganga City** (Varanasi), up into the tea gardens of **Chai Hills** (Darjeeling), and finally to Himalayan **Himadri City**, Victory Road and the **Indraprastha League**.

## Features

- **71 brand-new Pokémon** inspired by Indian wildlife and culture — peacocks, Bengal tigers, gharials, langurs, king cobras, snow leopards, a possessed auto-rickshaw, and more
- **8 gyms** (Grass, Electric, Water, Fighting, Ground, Ghost, Flying, Ice), **Elite Four + Champion**
- **Team Dhuan** — an evil team built around a real modern Indian problem: air pollution and waste dumping. They erase emission data, choke beaches with plastic, dump sludge in the Ganga, and finally try to weaponize the smog itself
- **Legendaries**: Garjaraj (the monsoon storm bird), Dhuasur (the smog titan), and postgame mythic Shwetavya (the white tiger)
- Full battle system: 18 types, physical/special split by move, stat stages, statuses, catching, evolution, move learning
- 10+ routes, forest/desert/cave dungeons, wild encounters, trainer line-of-sight battles
- Procedurally drawn sprites, WebAudio soundtrack built on Hindustani ragas (Bhairav, Kafi, Malkauns…) with tanpura drone and tabla
- Save/load via localStorage, PC box, Pokédex, badges

## Saving & Explorer Mode

- **Autosave**: your adventure saves itself automatically (on map changes, after battles, and every few steps). Close the tab any time — reopen and hit **CONTINUE** to resume exactly where you stood. Saves live in your browser's localStorage, so use the same browser/origin.
- **Explorer Mode** (title screen or in-game menu): a separate free-roam save that opens the entire region — every gate, pass and guard stands aside, no battles, no wild encounters. Pure sightseeing, and it never touches your real adventure. Your explorer position is remembered separately.
- Tip: for a stable localhost origin, run `python3 -m http.server` in this folder and open `http://localhost:8000`.

## Controls

| Key | Action |
|-----|--------|
| Arrows / WASD | Move / navigate |
| Z or Space | A — talk, confirm |
| X | B — cancel, back |
| Enter | Menu (party, bag, dex, badges, save) |
| M | Toggle music |

## Also in this repo

`mario-backup.html` — a NSMBU-style 2D platformer (6 worlds, powerups, boss fight) from an earlier iteration of this project.

---

*Fan project for fun/education. Pokémon is a trademark of Nintendo/Creatures/Game Freak; this project is unaffiliated.*
