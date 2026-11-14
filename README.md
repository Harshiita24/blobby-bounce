# Blobby — Bounce Back

**[Play Blobby in your browser](https://harshiita24.github.io/blobby-bounce/)**

Blobby is an endless pixel-art platformer built in Godot for Hack Club’s **Bounce Back** theme. Steer a bouncing slime through a haunted shaft, land on floating junk, and climb as high as you can before the lava catches up.

## How to play

Blobby bounces automatically when he lands. Steer around solid objects and land on top of them. Hitting an underside knocks him downward. The layout changes each run, and the lava speeds up as you climb faster. Your best height is saved in your browser.

| Key | Action |
| --- | --- |
| **A / D** or **← / →** | Steer left or right |
| **P** or **Esc** | Pause or resume |
| **R** | Retry |
| **F** | Toggle fullscreen |
| **M** | Mute or unmute |

The game is designed for a keyboard. Select **Play** from the main menu to start a run. The **Manual** shows each special object, and **Settings** lets you adjust music and sound effects separately or replace the heart’s red pulse with a steady tint.

## Special objects

| Object | What happens when you land on it |
| --- | --- |
| **Chaos Skull** | Launches Blobby roughly twice as high and reverses left and right for **2 seconds**. |
| **Grasping Hand** | Holds Blobby for **0.65 seconds**, then slows his steering for **1.2 seconds**. The lava keeps rising. |
| **Surge Heart** | Speeds up the lava for **2.8 seconds** and shows a red effect and countdown. |

A regular chest beside each hand or heart gives you a way around it. The opening can contain any of the three special objects or only regular junk.

## Web build

This repository contains the exported Godot browser build. GitHub Pages serves `index.html` from the root of `main`.

To play a local copy, run the following from the repository root, then open [localhost:8000](http://localhost:8000/).

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

## Credits

- Pixel art from **0x72’s DungeonTileset II**, with the hand adapted from **Dungeon Crawl Stone Soup** tiles.
- **Orbital Colossus** by Matthew Pablo (CC BY 3.0).
- Retro sound effects by **Juhani Junkala** (CC0).
- **Pixelify Sans** under the SIL Open Font License.

See [CREDITS.md](CREDITS.md) for sources and license details.
