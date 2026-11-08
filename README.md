# antigravity-skills

Curated Antigravity skill packs for game development — **332 skills** for
Godot, Unity, and Roblox, in the standard `SKILL.md` (Agent Skills) format
used by Antigravity, Claude Code, and Codex. Each skill is one folder with a
`SKILL.md` plus its bundled files. No conversion needed.

The deliverable lives in **GitHub Releases** as a zip — the repo root stays
lean on purpose. Download the latest release, extract, restart Antigravity,
done.

## Download

- **Latest (v1.1, recommended):**
  https://github.com/aryardc868-collab/antigravity-skills/releases/tag/v1.1-gamedev
  — `antigravity-skills-gamedev-v1.1.zip` (22,693,627 bytes)
- v1.0: https://github.com/aryardc868-collab/antigravity-skills/releases/tag/v1.0-gamedev

Verify the download before extracting:

```
SHA-256 (v1.1): 6a100bdab235d6634feea0409ffde7917530dce964fd366032146cd6aee5ae09
SHA-256 (v1.0): c56cfa58f4af6cc2a374996ab1b01d6166e09029c6c6aae4f7433c1b4002b796
```

## What's inside — 332 skills

Curated from a 4,762-skill source library down to only what is actually used
for game dev. Duplicates were merged to the single most substantial variant.

| Category | Skills |
| --- | ---: |
| Godot 4 | 96 |
| Roblox | 69 |
| General game dev | 62 |
| Core agent quality | 47 |
| Unity | 35 |
| Art & assets | 23 |
| **Total** | **332** |

- **Godot:** core, GDScript, scenes/nodes, 2D/3D, physics, animation, audio,
  UI, input, multiplayer, export/build, shaders, tilemap, save/load,
  performance, mobile, testing, 12 genre kits, platform adapters,
  `scenario-godot-*`.
- **Unity:** core, C# scripting, 2D, physics, animation, UI, input, navmesh,
  ECS, ScriptableObjects, build pipeline, mobile, multiplayer/netcode,
  performance, testing, `scenario-unity-*`.
- **Roblox:** Luau, Studio, Rojo, data stores, networking, GUI, physics,
  NPC/AI, monetization, security, performance, testing, publishing,
  `scenario-roblox-*`, `rbx-*` (economy / quests / retention / trading).
- **General:** game design, prototyping, balance, economy, progression,
  dialogue, localization, audio/music/SFX, monetization, liveops,
  QA/playtesting, publishing (Steam/itch), cutscene, tutorial, save system,
  NPC AI, netcode, shader/VFX.
- **Art:** pixel art, sprite animation, Aseprite pipeline, Blender
  (modeling / animation / export to Godot & Unity), image-gen for game assets.
- **Core:** coding discipline, deep-think, systematic debugging, bug-hunter,
  verification-before-completion, project-brain, gamedesign.

Full per-skill list: [`MANIFEST-GAMEDEV.md`](MANIFEST-GAMEDEV.md).

**Excluded on purpose:** other engines (Bevy, Unreal, Defold, Ebitengine,
LÖVE, Pygame, Phaser, Three.js, PixiJS, PlayCanvas, Babylon),
security/hacking, trading/crypto/finance, marketing/SEO, and all other
non-game-dev skills. 20 VM-only skills that hard-depend on the author's
local tools were also excluded.

## Install (Windows — Antigravity desktop app)

1. Download `antigravity-skills-gamedev-v1.1.zip` from the v1.1 release.
2. Extract it to **both** folders (the app and the CLI read different
   locations — copy to both or skills will be missing in one of them):
   ```
   C:\Users\Administrator\.gemini\antigravity-cli\skills\
   C:\Users\Administrator\.gemini\config\skills\
   ```
   Overwrite existing files. Each skill must end up as its own folder with
   a `SKILL.md` inside, e.g. `...\skills\local-godot4\SKILL.md`.
3. Restart Antigravity completely, then check **Customizations → Skills** —
   it should show **332** skills with the Global badge.

## Why v1.1? (validation)

v1.0 loaded only **297 of 332** skills in the Antigravity app — 35 skills
were silently skipped because their `SKILL.md` frontmatter was missing,
duplicated, or broken YAML. v1.1 fixes exactly that; the skill content is
unchanged from v1.0:

- 37 skills without frontmatter got `name:` + `description:`
- 8 duplicate frontmatter names made unique
- 7 broken-YAML frontmatter blocks repaired
- 4 non-kebab-case names normalized

Verified 2026-11-07: 332 skill directories; every `SKILL.md` parses as
valid YAML with `name:` + `description:`; 332 unique kebab-case names,
0 duplicates; `zipfile.testzip()` clean. Details:
[`MANIFEST-GAMEDEV-v1.1.md`](MANIFEST-GAMEDEV-v1.1.md).

## Caveats

- Some skills reference Linux paths (`~/...`, `/usr/bin/...`) or shell
  commands and may need adapting on Windows.
- `local-retrodiffusion` needs a paid Retro Diffusion account + API key.
- `pixel-pipeline` uses the `pix` CLI and `aseprite-mcp-pro` (optional).
- `local-voice-over` references TTS tooling documented in another skill;
  its directing / casting / scripting guidance works standalone.

## Contributing

Issues and PRs are welcome — especially reports of skills that don't load,
are out of date for current Godot / Unity / Roblox versions, or duplicate a
better variant already in the pack. Please keep new skills in the standard
`SKILL.md` format with valid `name:` + `description:` frontmatter.

## License

MIT — see [`LICENSE`](LICENSE).
