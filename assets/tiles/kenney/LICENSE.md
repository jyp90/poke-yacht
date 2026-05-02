# Kenney Dungeon Tileset License

This directory contains assets from the **Kenney Dungeon Tileset** package.

## Assets

### Active (in use by code)
- `dungeon_tileset.png` — 256×256 spritesheet (8×8 grid of 32×32 tiles)
  - Self-generated fallback PNG (Kenney-style colors)
  - Loaded by `LoadingScene.js:58` as `kenney_dungeon` spritesheet
  - File Size: ~1.7 KB

### Real Kenney assets (downloaded 2026-05-02, not yet wired into code)
- `tiny-dungeon/tilemap_packed.png` — 192×176 spritesheet (12×11 grid of 16×16 tiles, 132 frames)
- `tiny-dungeon/tilemap.png` — 203×186 (1px gap padded, 132 frames)
- `tiny-dungeon/Preview.png` — 미리보기
- `tiny-dungeon/LICENSE.txt` — Kenney 원본 라이선스 (CC0)
- Source: https://kenney.nl/media/pages/assets/tiny-dungeon/b56d7a13e3-1674742415/kenney_tiny-dungeon.zip
- 통합 작업: LoadingScene + DungeonScene frame 인덱스 매핑 변경 필요 (별도 sprint)

## License Information

- **Source**: https://kenney.nl/assets/dungeon-tileset
- **License**: CC0 1.0 Universal (Public Domain)
- **Attribution**: Not required but appreciated

## CC0 Terms

These assets are released into the public domain with no copyright restrictions.
You are free to use, modify, and distribute these assets for any purpose, 
including commercial projects, without any attribution requirement.

## Integration Status

- ✅ Self-generated fallback PNG (`dungeon_tileset.png`) — 활성 사용 중
- ✅ Spritesheet loader registered in LoadingScene.js:58 (32×32, 8×8 grid)
- ✅ Real Kenney Tiny Dungeon ZIP downloaded → `tiny-dungeon/` (2026-05-02)
- 🔄 Real Kenney 통합 보류 — 16×16 grid 매핑 변경 + DungeonScene 9개 sprite frame 인덱스 재매핑 필요
