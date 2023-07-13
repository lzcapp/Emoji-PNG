# Emoji-PNG

Extracted PNG images from Emoji font files.

## Emojis

1. **Apple Emoji** from [Keinta15/Magisk-iOS-Emoji](https://github.com/Keinta15/Magisk-iOS-Emoji).
2. **Blobmoji** from [C1710/blobmoji](https://github.com/C1710/blobmoji).
3. **JoyPixels** from [JoyPixels® Official Site](https://www.joypixels.com/download). (JoyPixels 7.0 is temporarily hosted at [cdn.joypixels.com](https://cdn.joypixels.com/distributions/generic/font/7.0/joypixels-android.ttf).)
4. **Noto Emoji** from [googlefonts/noto-emoji](https://github.com/googlefonts/noto-emoji).
5. **Samsung One UI Emoji** from [Emoji magisk modules by RKBDI](https://forum.xda-developers.com/t/magisk-module-emoji-sets-by-rkbdi.4120991/).
6. **Twemoji** from [Gontier-Julien/Twemoji-Remastered](https://github.com/Gontier-Julien/Twemoji-Remastered).

  | Apple Emoji                       | Blobmoji                        | JoyPixels                     | Noto Emoji                       | Samsung One UI Emoji          | Twemoji                        |
  | --------------------------------- | ------------------------------- | ----------------------------- | -------------------------------- | ----------------------------- | ----------------------------- |
  | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Apple%20Emoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Blobmoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Noto%20Emoji/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/JoyPixels/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Samsung%20One%20UI/PNG/u1F60A.png" width="128" /> | <img src="https://github.com/lzcapp/Emoji-PNG/raw/main/Twemoji/PNG/u1F60A.png" width="128" /> |

## Extraction Method

- `pip install fonttools`, fontTools from [fonttools/fonttools](https://github.com/fonttools/fonttools).

  ```
  fontTools requires Python 3.7 or later.
  ```

- `ttx -z extfile [emojifontfile.ttf]`.

  Then you can get:

  - A `.ttx` file.
  - PNG files under `bitmaps\trike0`.
