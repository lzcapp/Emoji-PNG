# Emoji-PNG

![GitHub repo size](https://img.shields.io/github/repo-size/lzcapp/Emoji-PNG?style=for-the-badge) &ensp; ![GitHub Release](https://img.shields.io/github/v/release/lzcapp/Emoji-PNG?style=for-the-badge)

Extracted PNG images from Emoji font files.

## Emojis

1. **Apple Emoji** from [Keinta15/Magisk-iOS-Emoji](https://github.com/Keinta15/Magisk-iOS-Emoji).
2. **Blobmoji** from [C1710/blobmoji](https://github.com/C1710/blobmoji).
3. **Fluent Emoji** from [Magisk-Modules-Alt-Repo/FluentEmojiMagisk](https://github.com/Magisk-Modules-Alt-Repo/FluentEmojiMagisk).
4. **JoyPixels** from [EmojiReplacer/Emoji-Replacer](https://github.com/EmojiReplacer/Emoji-Replacer) ~~[JoyPixels® Official Site](https://www.joypixels.com/download) and [Arch Linux - ttf-joypixels](https://archlinux.org/packages/extra/any/ttf-joypixels/)~~.
5. **Noto Emoji** from [googlefonts/noto-emoji](https://github.com/googlefonts/noto-emoji).
6. **Segoe UI Emoji** from latest Windows 11, extrated with [Character Map UWP](https://apps.microsoft.com/store/detail/character-map-uwp/9WZDNCRDXF41).
7. **Samsung One UI Emoji** from [Android Dumps](https://dumps.tadiphone.dev/dumps/samsung).
8. **Twemoji** from [Gontier-Julien/Twemoji-Remastered](https://github.com/Gontier-Julien/Twemoji-Remastered).
9. **WhatsApp Emoji** from [anfeichtinger/Magisk-WhatsApp-Emoji](https://github.com/anfeichtinger/Magisk-WhatsApp-Emoji).
10. **HarmonyOS Emoji** extracted from latest HarmonyOS.
11. **OpenMoji** from [hfg-gmuend/openmoji](https://github.com/hfg-gmuend/openmoji).

  | Apple Emoji | Blobmoji | Fluent Emoji | JoyPixels | Noto Emoji | Segoe UI Emoji | Samsung One UI Emoji | Twemoji | WhatsApp Emoji | HarmonyOS | OpenMoji |
  | ----------- | -------- | ------------ | --------- | ---------- | -------------- | -------------------- | ------- | -------------- | --------- | -------- |
  | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Apple%20Emoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Blobmoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Fluent%20Emoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Noto%20Emoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/JoyPixels/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Segoe%20UI%20Emoji/PNG/Smiling%20Face%20With%20Smiling%20Eyes.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Samsung%20One%20UI/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Twemoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/WhatsApp%20Emoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/HarmonyOS/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/OpenMoji/PNG/u1F60A.png" width="128" /> |
  | 136 × 128 | 136 × 128 | 136 × 128 | 136 × 128 | 136 × 128 | 2048 × 2048 | 108 × 108 | 76 × 72 | 160 × 160 | 136 × 128 | 128 × 128 |

## Extraction Method

Prerequisite: `fontTools` from [fonttools/fonttools](https://github.com/fonttools/fonttools): `pip install fonttools`.

> fontTools requires Python 3.7 or later.

```
ttx -z extfile [emojifontfile.ttf]
```

  Then you can get:

  - A `.ttx` file.
  - PNG files under `bitmaps\trike0`.
