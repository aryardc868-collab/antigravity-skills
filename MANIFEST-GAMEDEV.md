# Antigravity Skills Pack — GAME DEV (Godot / Unity / Roblox) — MANIFEST

Dibangun: 2026-11-07 (dari `~/workspace/custom-skills/` di VM asisten).
Kurasi atas perintah user: HANYA skill yang bener-bener kepake untuk game dev
(Godot / Unity / Roblox) — BUKAN seluruh 4.762 skill.
Format: satu folder per skill, masing-masing berisi `SKILL.md` + file bundelannya.

## Angka

| | |
|---|---|
| Total folder di sumber | 4.783 |
| Skill yang disertakan | **332** |
| File di dalam zip | 4.462 |
| Ukuran zip | **22.296.353 byte (~21,3 MB)** |
| SHA-256 zip | `c56cfa58f4af6cc2a374996ab1b01d6166e09029c6c6aae4f7433c1b4002b796` |

## Kategori yang disertakan

- **Godot 4** — 96 skill
- **Unity** — 35 skill
- **Roblox** — 69 skill
- **General game dev** — 62 skill
- **Art & assets** — 23 skill
- **Core agent quality** — 47 skill

Godot: core, GDScript, scenes/nodes, 2D/3D, physics, animation, audio, UI,
input, multiplayer, export/build, shaders, tilemap, save/load, performance,
mobile, testing, 12 genre kit, platform adapter, scenario-godot-*.
Unity: core, C# scripting, 2D, physics, animation, UI, input, navmesh, ECS,
ScriptableObjects, build pipeline, mobile, multiplayer/netcode, performance,
testing, scenario-unity-*. Roblox: Luau, Studio, Rojo, data stores, networking,
GUI, physics, NPC/AI, monetization, security, performance, testing, publishing,
scenario-roblox-*, rbx-* (economy/quests/retention/trading).
General: game design, prototyping, balance, economy, progression, dialogue,
localization, audio/music/SFX, monetization, liveops, QA/playtesting, publishing
(Steam/itch), cutscene, tutorial, save system, NPC AI, netcode, shader/VFX.
Art: pixel art, sprite animation, Aseprite pipeline, Blender (modeling/animation/
export ke Godot/Unity), image-gen untuk aset game (pilih 1-2 terbaik, bukan 30 varian).
Core: coding-expert, codex-grade-coding, coder-pro/apex, deep-think,
claude/chatgpt-thinking, opus-astra-doctrine, verification-before-completion,
systematic-debugging, bug-hunter, project-brain, gamedesign.

## Yang DIKELUARKAN (dan kenapa)

- **Engine lain**: Bevy, Unreal, Defold, Ebitengine, LÖVE, Pygame, Phaser,
  Three.js, PixiJS, PlayCanvas, Babylon — web game di luar scope pilihan user.
  (Pack web/Phaser/Three.js bisa dibuatkan terpisah kalau diminta.)
- **Security/hacking, trading/crypto/finance, marketing/SEO**, dan semua skill
  non-game-dev lainnya.
- **Duplikat**: kalau 2+ skill bahas topik yang sama (mis. tiga varian
  `local-godot-gdscript-patterns`, tiga varian `local-roblox-datastores`),
  yang disimpan SATU — yang SKILL.md-nya paling substansial/lengkap.
- **Skill meta Muse** (cara mengoperasikan Muse, skill-authoring, harness
  superpowers) — kecuali skill thinking/doctrine yang tercantum di atas.
- **Stub**: SKILL.md di bawah ~20 baris atau hanya pointer ke tool yang tidak
  ada — kecuali router tipis asli yang menunjuk ke skill yang disertakan
  (mis. `local-godot-master`).
- **20 skill dari MANIFEST pack full** yang hard-depend ke tool/layanan khusus
  VM asisten (`~/workspace/tools/`, `127.0.0.1:8765`) — tetap dikecualikan.
- 31 file di dalam skill yang disertakan ikut di-skip karena namanya cocok
  filter secret (secret/credential/token/.pem/.key/.env) — mayoritas hanya
  dokumen tentang token/secret, bukan secret asli. Folder `.git`,
  `node_modules`, `__pycache__` tidak disertakan.
- Skill dari `/opt/muse/skills/` (skill produk Muse) TIDAK disertakan — skill
  itu merujuk ke tool/connector khusus Muse.

## Cara install di Windows (Antigravity app desktop)

1. Download `antigravity-skills-gamedev.zip` dari halaman release GitHub.
2. Verifikasi SHA-256 file hasil download sama dengan yang di atas.
3. Extract isi zip ke:
   ```
   C:\Users\Administrator\.gemini\antigravity-cli\skills\
   ```
   Hasil akhirnya harus seperti ini — tiap skill jadi folder sendiri dengan
   `SKILL.md` di dalamnya:
   ```
   C:\Users\Administrator\.gemini\antigravity-cli\skills\local-godot4\SKILL.md
   C:\Users\Administrator\.gemini\antigravity-cli\skills\local-roblox\SKILL.md
   ...
   ```
4. Restart aplikasi Antigravity (tutup total lalu buka lagi).
5. Cek di panel **Customizations → Skills** — skill yang ter-load akan muncul di sana.

## Catatan penting / caveat

- **Sebagian skill merujuk path/script Linux** (misal `~/...`, `/usr/bin/...`,
  atau perintah shell Linux) dan mungkin perlu penyesuaian di Windows.
- `local-retrodiffusion` butuh akun + API key berbayar Retro Diffusion.
- `pixel-pipeline` memakai CLI `pix` dan MCP `aseprite-mcp-pro` (opsional).
- `local-voice-over` merujuk tool TTS di dokumen skill lain; panduan
  directing/casting/script-nya tetap bisa dipakai tanpa tool itu.
- Skill-skill ini berformat `SKILL.md` standar (Agent Skills) — format yang
  sama dipakai Claude Code, Codex, dan Antigravity — jadi tidak perlu konversi.

## Daftar skill yang disertakan (332)

### Godot 4 (96)

- `godot-optimization`
- `local-godot--bfollington`
- `local-godot-2d-animation`
- `local-godot-2d-movement`
- `local-godot-2d-physics`
- `local-godot-3d-essentials`
- `local-godot-3d-lighting`
- `local-godot-3d-materials`
- `local-godot-3d-world-building`
- `local-godot-4-migration`
- `local-godot-ability-system`
- `local-godot-ai-navigation`
- `local-godot-analyst`
- `local-godot-animation`
- `local-godot-animation-player`
- `local-godot-animation-tree-mastery`
- `local-godot-asset-generator`
- `local-godot-audio`
- `local-godot-auditor`
- `local-godot-autoload-architecture`
- `local-godot-best-practices`
- `local-godot-camera-systems`
- `local-godot-characterbody-2d`
- `local-godot-combat-system`
- `local-godot-composition`
- `local-godot-csharp`
- `local-godot-debugging`
- `local-godot-dev`
- `local-godot-development`
- `local-godot-dialogue-system`
- `local-godot-economy-system`
- `local-godot-export-builds`
- `local-godot-game-loop-collection`
- `local-godot-game-loop-waves`
- `local-godot-gdscript`
- `local-godot-gdscript-headless-testing`
- `local-godot-gdscript-mastery`
- `local-godot-gdscript-patterns--sickn33`
- `local-godot-genre-action-rpg`
- `local-godot-genre-card-game`
- `local-godot-genre-horror`
- `local-godot-genre-idle-clicker`
- `local-godot-genre-metroidvania`
- `local-godot-genre-platformer`
- `local-godot-genre-puzzle`
- `local-godot-genre-roguelike`
- `local-godot-genre-shooter-fps`
- `local-godot-genre-simulation`
- `local-godot-genre-survival`
- `local-godot-genre-tower-defense`
- `local-godot-input-handling`
- `local-godot-inventory-system`
- `local-godot-master`
- `local-godot-mechanic-secrets`
- `local-godot-multiplayer`
- `local-godot-multiplayer-networking`
- `local-godot-navigation-pathfinding`
- `local-godot-nodes-scenes`
- `local-godot-optimization`
- `local-godot-particles`
- `local-godot-physics`
- `local-godot-physics-3d`
- `local-godot-platform-desktop`
- `local-godot-platform-mobile`
- `local-godot-procedural-generation`
- `local-godot-project-foundations`
- `local-godot-quest-system`
- `local-godot-raycasting-queries`
- `local-godot-resources`
- `local-godot-rpg-stats`
- `local-godot-save-load-systems`
- `local-godot-scene-management`
- `local-godot-server-architecture`
- `local-godot-shaders`
- `local-godot-signals-groups`
- `local-godot-state-machine-advanced`
- `local-godot-testing-patterns`
- `local-godot-tilemap`
- `local-godot-turn-system`
- `local-godot-tweening`
- `local-godot-ui`
- `local-godot-ui-containers`
- `local-godot-ui-control`
- `local-godot-ui-theming`
- `scenario-godot-2d`
- `scenario-godot-3d-world`
- `scenario-godot-animation`
- `scenario-godot-architecture`
- `scenario-godot-audio`
- `scenario-godot-gameplay`
- `scenario-godot-multiplayer`
- `scenario-godot-performance-export`
- `scenario-godot-rendering-lighting`
- `scenario-godot-shaders`
- `scenario-godot-ui`
- `scenario-godot-vfx`

### Unity (35)

- `local-unity`
- `local-unity-animation`
- `local-unity-build-pipeline`
- `local-unity-csharp-scripting`
- `local-unity-developer--sickn33`
- `local-unity-development`
- `local-unity-ecs-patterns`
- `local-unity-export`
- `local-unity-input-system`
- `local-unity-navmesh`
- `local-unity-package-management`
- `local-unity-physics`
- `local-unity-pipeline`
- `local-unity-scriptableobjects`
- `local-unity-tilemap-2d`
- `scenario-unity-animation`
- `scenario-unity-architecture`
- `scenario-unity-gameplay`
- `scenario-unity-mobile`
- `scenario-unity-performance`
- `scenario-unity-pipeline-automation`
- `scenario-unity-rendering-lighting`
- `scenario-unity-shaders`
- `scenario-unity-ui`
- `scenario-unity-vfx`
- `scenario-unity-world-building`
- `unity-2d-core`
- `unity-2d-tilemap`
- `unity-build-platforms`
- `unity-mobile-game-development`
- `unity-multiplayer`
- `unity-netcode`
- `unity-performance`
- `unity-testing`
- `unity-tooling`

### Roblox (69)

- `local-roblox`
- `local-roblox-analytics`
- `local-roblox-animation-vfx`
- `local-roblox-animations`
- `local-roblox-architecture--el4cteo`
- `local-roblox-audio--nonlooped`
- `local-roblox-building`
- `local-roblox-camera`
- `local-roblox-characters`
- `local-roblox-code-review`
- `local-roblox-core`
- `local-roblox-datastores--nonlooped`
- `local-roblox-development`
- `local-roblox-game-design`
- `local-roblox-game-developer`
- `local-roblox-game-systems`
- `local-roblox-gui--sentinelcore`
- `local-roblox-input--el4cteo`
- `local-roblox-lighting`
- `local-roblox-luau--el4cteo`
- `local-roblox-luau-core`
- `local-roblox-luau-patterns`
- `local-roblox-luau-types`
- `local-roblox-monetization--el4cteo`
- `local-roblox-networking`
- `local-roblox-npc-ai--el4cteo`
- `local-roblox-performance--el4cteo`
- `local-roblox-physics--el4cteo`
- `local-roblox-publish-checklist`
- `local-roblox-remote-events`
- `local-roblox-rojo`
- `local-roblox-security--el4cteo`
- `local-roblox-server-data`
- `local-roblox-studio-workflow`
- `local-roblox-teleport`
- `local-roblox-testing`
- `local-roblox-tooling--el4cteo`
- `local-roblox-ui`
- `local-roblox-ui-mastery`
- `local-roblox-vfx`
- `local-roblox-world-building`
- `rbx-analytics-events`
- `rbx-economy-currencies`
- `rbx-economy-progression`
- `rbx-liveops-events`
- `rbx-mtx-devproducts`
- `rbx-quests-dailies`
- `rbx-quests-dialogue`
- `rbx-quests-engine`
- `rbx-retention-daily`
- `rbx-trading-antiscam`
- `rbx-trading-economy`
- `rbx-trading-flow`
- `roblox-game-builder`
- `roblox-game-ux`
- `roblox-monetization`
- `scenario-roblox-animation`
- `scenario-roblox-architecture`
- `scenario-roblox-assets`
- `scenario-roblox-data`
- `scenario-roblox-environment`
- `scenario-roblox-gameplay`
- `scenario-roblox-luau`
- `scenario-roblox-monetization`
- `scenario-roblox-networking`
- `scenario-roblox-performance`
- `scenario-roblox-tooling`
- `scenario-roblox-ui`
- `scenario-roblox-vfx-audio`

### General game dev (62)

- `game-2d-art-animation-and-vfx-pipeline`
- `game-audio-implementation`
- `game-balance`
- `game-cg-director`
- `game-data-analytics-and-live-economy`
- `game-design--opendcai`
- `game-designer-forgewright`
- `game-developer`
- `game-ideation`
- `game-monetization`
- `game-narrative-and-interactive-story-design`
- `game-production-planning`
- `game-store-page`
- `game-testing-polish`
- `game-ui-ux`
- `game-version-control`
- `local-3d-games`
- `local-game-accessibility`
- `local-game-ai`
- `local-game-ai-behavior-trees`
- `local-game-anti-cheat`
- `local-game-architecture`
- `local-game-art`
- `local-game-asset-generation`
- `local-game-assets--playableintelligence`
- `local-game-audio`
- `local-game-balance-lab`
- `local-game-build`
- `local-game-concept`
- `local-game-design`
- `local-game-design-core`
- `local-game-designer--playableintelligence`
- `local-game-dev-combat-animation`
- `local-game-dev-combat-skill-polish`
- `local-game-developer`
- `local-game-development--hkuds`
- `local-game-dialogue`
- `local-game-economy`
- `local-game-engines`
- `local-game-feel`
- `local-game-feel-advanced`
- `local-game-jam`
- `local-game-liveops`
- `local-game-localization`
- `local-game-monetization`
- `local-game-netcode`
- `local-game-networking`
- `local-game-patterns`
- `local-game-playtesting`
- `local-game-production`
- `local-game-prototyping`
- `local-game-qa--playableintelligence`
- `local-game-save-system`
- `local-game-servers`
- `local-game-shader-vfx`
- `local-game-trailer-store`
- `local-game-tutorial`
- `local-game-ui-design`
- `local-game-ui-ux`
- `local-game-world-design`
- `local-mobile-game-dev`
- `local-pc-games`

### Art & assets (23)

- `aseprite-godot-pipeline`
- `blender-animation`
- `blender-export`
- `blender-materials`
- `blender-modeling`
- `blender-uv-texturing`
- `local-blender`
- `local-blender-to-unity`
- `local-pixel-art-animator`
- `local-pixel-art-creator`
- `local-pixel-art-exporter`
- `local-pixel-art-professional`
- `local-pixel-art-scaler`
- `local-pixel-art-sprites`
- `local-pixel-art-style`
- `local-sprite-editor`
- `local-spritecook-generate-sprites`
- `local-spritecook-use-assets-in-godot`
- `local-spritecook-use-presets`
- `local-spritecook-workflow-essentials`
- `local-voxel-art`
- `pixel-art`
- `pixel-pipeline`

### Core agent quality (47)

- `ai-game-spritesheets`
- `local-2d-pixel-perfect`
- `local-ai-game-art-generation`
- `local-bug-hunter`
- `local-character-design`
- `local-chatgpt-thinking`
- `local-claude-thinking`
- `local-coder-apex`
- `local-coder-pro`
- `local-codex-grade-coding`
- `local-coding-expert`
- `local-combat-design`
- `local-cutscene-direction`
- `local-deep-think`
- `local-design-reference`
- `local-fal-assets`
- `local-gacha-economy-math`
- `local-game-automation`
- `local-game-autotest`
- `local-gamedesign`
- `local-gameplay-mechanics`
- `local-godot-monte-carlo-balancer`
- `local-godot4`
- `local-itch-publish`
- `local-launch-checklist`
- `local-level-design`
- `local-narrative-design`
- `local-opus-astra-doctrine`
- `local-opus-visual-audit`
- `local-playtest-report`
- `local-procedural-generation`
- `local-project-brain`
- `local-qa-plan`
- `local-qa-review`
- `local-quest-design`
- `local-release-checklist`
- `local-retrodiffusion`
- `local-roblox-design-consultant`
- `local-roblox-growth-design`
- `local-roblox-player-psychology`
- `local-roblox-simulator-economy`
- `local-sfxmint`
- `local-steam-publish`
- `local-systematic-debugging`
- `local-verification-before-completion`
- `local-voice-over`
- `local-worldbuilding`
