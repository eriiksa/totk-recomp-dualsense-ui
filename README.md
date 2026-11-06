# Simple PS5 UI — DualSense prompts for TotK Recomp

DualSense (PS5) button prompts for **The Legend of Zelda: Tears of the Kingdom** running on **TotK Recomp**. It swaps the Switch glyphs for PlayStation ones everywhere they show up:

- on-screen action prompts (A / B / X / Y → ✕ / ○ / △ / □)
- pause menu
- the controller illustration in *Controles básicos* / *Basic Controls*

Drop-in mod: no dependencies, no patches, no rebuild.

## Download

Grab the zip from the [latest release](../../releases/latest).

## Requirements

- TotK Recomp **0.3.1** or newer (built on `0.3.10+101132a`)
- Game update **1.4.3**
- Your own legitimate copy of the game

## Install (3 steps)

1. Extract the zip into the `mods` folder next to `totk.exe`
   (in game: **F1 → Mods → Open mods folder**).
2. Start the game, press **F1 → Mods** and switch **Simple PS5 UI - DualSense Prompts** ON.
3. Restart the game. Done.

After extracting you should have:

```text
mods/
└── Simple PS5 UI - DualSense Prompts/
    ├── README.md
    └── romfs/UI/LayoutArchive/Common.Product.140.Nin_NX_NVN.blarc.zs
```

## Conflict

Only if another UI mod replaces the same file (e.g. *Dualshock 4 Controller UI*): keep this one **above** it in the Mods list — the top entry wins — or turn the other one off.

## Info

| | |
|---|---|
| File | `UI/LayoutArchive/Common.Product.140.Nin_NX_NVN.blarc.zs` |
| sha1 | `1a4567cec72bfa5ad98eccc54665139e216c333f` |
| size | 6,286,991 bytes |
| version | 1.0.0 |

## Legal

Contains modified UI assets extracted from the game, redistributed for personal use — you still need your own legitimate copy of *The Legend of Zelda: Tears of the Kingdom*. Not affiliated with or endorsed by Nintendo.
