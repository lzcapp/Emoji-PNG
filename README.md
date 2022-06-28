# Emoji-PNG

## Emojis

Extracted PNG images from Emoji TTF files

1. **Apple Emoji** from [Keinta15/Magisk-iOS-Emoji](https://github.com/Keinta15/Magisk-iOS-Emoji).
2. **JoyPixels** from [JoyPixels® Official Site](https://www.joypixels.com/download).
3. **Noto Emoji** from [googlefonts/noto-emoji](https://github.com/googlefonts/noto-emoji).
4. **Twemoji** from [Gontier-Julien/Twemoji-Remastered](https://github.com/Gontier-Julien/Twemoji-Remastered).

## Extraction Methods

- `pip install fonttools`, fontTools from [fonttools/fonttools](https://github.com/fonttools/fonttools).

  ```
  fontTools requires Python 3.7 or later.
  ```

- `ttx -z extfile [emojifontfile.ttf]`.

  Then you can get:

  - A `.ttx` file.
  - PNG files under `bitmaps\trike0`.
