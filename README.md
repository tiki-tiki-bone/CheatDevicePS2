Cheat Device for PS2 (Custom 640-Codes Build)
==============================================

This package is an unofficial custom build based on:
https://github.com/root670/CheatDevicePS2

## What is changed
- Cheat code line limit per game: `250 -> 640`
- "Too many codes enabled" threshold: `250 -> 640`
- Core loading/hook behavior remains the original mechanism.

Code changes were limited to:
- `engine/Makefile`
- `src/cheats.c`

## Package contents
- `cheatdevice.elf`
- `CheatDevicePS2.ini`
- `CheatDatabase.zip` (contains `CheatDatabase.txt`)
- `LICENSE`
- `README.md` (this file)

## Quick install
1. Copy `cheatdevice.elf` to your PS2 launcher location.
2. Keep `CheatDevicePS2.ini` next to the ELF (or in your expected config path).
3. Extract `CheatDatabase.zip` if your setup expects plain `CheatDatabase.txt`.
4. Launch and verify your boot path settings in `CheatDevicePS2.ini`.

## 日本語説明
- これは `CheatDevicePS2` の非公式カスタム版（640行対応）です。
- 既存の `CheatDevicePS2` をすでに使っている場合は、基本的に `cheatdevice.elf` の上書きだけで利用できます。
- 初回導入や構成を作り直す場合は、`CheatDevicePS2.ini` と `CheatDatabase.zip` もあわせて確認してください。
- 本パッケージの利用は自己責任です。環境によっては正常に動作しない可能性があります。

## Notes
- This is provided as-is, with no warranty.
- If you still see "Too many codes enabled", the enabled line count has exceeded 640.

## License
Cheat Device is licensed under GNU GPL-3.0. See `LICENSE`.
The cheat engine is from ps2rd by Mathias Lafedlt.
The bootstrap is based on EE_CORE from OpenPS2Loader.
