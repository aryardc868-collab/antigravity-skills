# antigravity-skills-gamedev v1.1

Perbaikan atas v1.0-gamedev (release 2026-11-07). Isi pack SAMA — 332 skill yang sama —
hanya frontmatter SKILL.md yang diperbaiki supaya Antigravity bisa mendaftarkan
semuanya sebagai slash command. v1.0 cuma ke-load 297 dari 332 di app.

## Yang berubah dari v1.0

1. **37 skill tanpa frontmatter → ditambah `name:` + `description:`**
   (deskripsi diambil dari judul + kalimat pertama tiap SKILL.md):
   local-blender, local-bug-hunter, local-chatgpt-thinking, local-claude-thinking,
   local-coder-apex, local-coder-pro, local-codex-grade-coding, local-coding-expert,
   local-cutscene-direction, local-deep-think, local-design-reference,
   local-gacha-economy-math, local-game-anti-cheat, local-game-audio,
   local-game-autotest, local-game-balance-lab, local-game-dialogue,
   local-game-economy, local-game-feel-advanced, local-game-liveops,
   local-game-localization, local-game-netcode, local-game-playtesting,
   local-game-production, local-game-prototyping, local-game-save-system,
   local-game-shader-vfx, local-game-trailer-store, local-game-tutorial,
   local-gamedesign, local-godot4, local-opus-astra-doctrine,
   local-opus-visual-audit, local-project-brain, local-systematic-debugging,
   local-verification-before-completion, local-voice-over.

2. **8 nama frontmatter yang dobel → yang satu dipertahankan, yang lain diunikkan**
   (isi skill tidak berubah, hanya `name:`):
   - game-design: local-game-design → `local-game-design`
     (game-design tetap `game-design`)
   - game-designer: local-game-designer--playableintelligence →
     `local-game-designer-playableintelligence`
     (game-designer-forgewright tetap `game-designer`)
   - game-developer: local-game-developer → `local-game-developer`
     (game-developer tetap `game-developer`)
   - game-monetization: local-game-monetization → `local-game-monetization`
     (game-monetization tetap `game-monetization`)
   - game-ui-ux: local-game-ui-ux → `local-game-ui-ux`
     (game-ui-ux tetap `game-ui-ux`)
   - godot-optimization: local-godot-optimization → `local-godot-optimization`
     (godot-optimization tetap `godot-optimization`)
   - godot-development: local-godot-development → `local-godot-development`
     (local-godot-dev tetap `godot-development`)
   - roblox-monetization: local-roblox-monetization--el4cteo →
     `local-roblox-monetization-el4cteo`
     (roblox-monetization tetap `roblox-monetization`)

3. **7 frontmatter lama yang YAML-nya rusak → diperbaiki** (deskripsi tanpa
   kutip yang mengandung `": "`, mis. local-combat-design,
   local-game-accessibility, local-game-patterns, local-narrative-design,
   local-pixel-art-creator, local-procedural-generation, local-quest-design).
   Deskripsi di-quote ulang supaya bisa di-parse.

4. **4 nama bukan kebab-case → dinormalisasi** (`Pixel Art Animator` /
   `Creator` / `Exporter` / `Professional` → nama foldernya, karena spasi
   merusak slash command).

## Verifikasi (2026-11-07, di VM asisten)

- 332 direktori skill; SEMUA SKILL.md ter-parse sebagai YAML valid, punya
  `name:` + `description:`; 332 nama frontmatter UNIK, 0 dobel, semua
  kebab-case.
- Zip `antigravity-skills-gamedev-v1.1.zip`: 22.693.627 byte, 5.366 entri,
  332 SKILL.md, `zipfile.testzip()` bersih.
- SHA-256: 6a100bdab235d6634feea0409ffde7917530dce964fd366032146cd6aee5ae09

## Install (Windows VPS) — sama seperti v1.0

1. Download antigravity-skills-gamedev-v1.1.zip dari release v1.1-gamedev
2. Extract ke C:\Users\Administrator\.gemini\antigravity-cli\skills\
   DAN ke C:\Users\Administrator\.gemini\config\skills\ (tiban file lama)
3. Restart Antigravity, cek Customizations -> Skills — harus 332, badge Global
