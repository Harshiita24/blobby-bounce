# Art and font credits

## 16x16 DungeonTileset II v1.7 — Robert / 0x72

- Creator and license: https://0x72.itch.io/dungeontileset-ii
- License: Creative Commons Zero v1.0 Universal (CC0).
- Creator's listing explicitly declares that no generative AI was used.
- Download mirror: https://github.com/marceloferreira357/bun-crawler-client/tree/main/public/sprites/0x72_DungeonTilesetII_v1.7
- CC0 legal text: https://creativecommons.org/publicdomain/zero/1.0/legalcode
- Included original README: `assets/pixel/0x72-README.txt`.

Blobby uses the four tiny_slug animation frames. The floating objects use chest, mimic chest, crate, skull, potion flask, hammer, rusty sword, and ui_heart_full sprites. Dungeon walls use wall_mid, wall_hole_1, wall_goo, and wall_banner_red.

Modifications: transparent borders trimmed from object sprites; weapons rotated 90 degrees; three original skull sprites arranged into a bone pile. The chaos skull reuses the original skull at 6x scale with a runtime purple pulse. Other source colors and shapes are retained. Ordinary sprites render at integer 3x size with nearest-neighbor filtering. Collision rectangles follow their opaque pixels. No artwork was generated with AI.

## Pixelify Sans

- Source: https://github.com/google/fonts/tree/main/ofl/pixelifysans
- Copyright: The Pixelify Sans Project Authors.
- License: SIL Open Font License 1.1, included in `assets/pixel/PixelifySans-OFL.txt`.
- Font file is unmodified.

## Godot

Web runtime templates: official Godot 4.7.2 release, https://github.com/godotengine/godot-builds/releases/tag/4.7.2-stable . Engine licensing: https://godotengine.org/license/ .

UI panels, layout, lava strips, and embers are basic Godot drawing code. No AI-generated image, sound, or model assets are included. Kenney prototype assets have been removed from the active project.

## Grasping hand — Dungeon Crawl Stone Soup CC0 tile release

- Source: https://github.com/crawl/tiles/blob/master/releases/Nov-2015/gui/invocations/ru_sacrifice_hand.png
- License provenance: https://github.com/crawl/tiles (curated CC0 releases).
- Original project README and artist acknowledgments are included as `assets/pixel/Crawl-README.md` and `Crawl-ARTISTS.md`.
- Modification: extracted the original red hand silhouette from the invocation icon, removed the UI border/background, and recolored it moss green. This is a crop and palette change of existing artist-made pixels, not AI-generated artwork.

Slime droplets are small rectangles drawn by Godot; squash/stretch and status pulses are runtime animation effects.

## Music — Orbital Colossus by Matthew Pablo

- Supplied file: `Orbital Colossus.mp3`; embedded artist/title metadata identifies Matthew Pablo (2013).
- Original source: https://opengameart.org/content/space-boss-battle-theme
- Artist: https://www.matthewpablo.com/
- License: Creative Commons Attribution 3.0 Unported (CC BY 3.0).
- License link: https://creativecommons.org/licenses/by/3.0/
- Legal text: https://creativecommons.org/licenses/by/3.0/legalcode
- The original MP3 is included unmodified. In-game playback uses volume mixing and a 1.4-second end-to-start crossfade. No endorsement by the artist is implied.
- Attribution is also displayed on the in-game Credits page.

## Sound effects — Juhani Junkala

- The Essential Retro Video Game Sound Effects Collection [512 sounds], supplied by the user.
- Source: https://opengameart.org/content/512-sound-effects-8-bit-style
- License: CC0, as stated in the included original `assets/audio/Juhani-Junkala-INFO.txt`.
- Nine unmodified WAVs were selected and renamed for game events; the exact mapping is in `assets/audio/SFX-MAPPING.txt`.
- Runtime changes: volume mixing, slight pitch variation for ordinary bounces, looping the supplied alarm during a surge.
