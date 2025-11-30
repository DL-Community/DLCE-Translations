## This repo is for DLCE translation contributions. You are welcomed to contribute via Pull Request.
DLCE Discord: https://discord.gg/t2zJz68naA
# Instructions
- **Each line** is a **separate phrase**. Make sure the number of lines for each phrase matches the key in the [Keys file](/DLLocalization_Keys.txt), otherwise the game will not be able to read the correct translation.

## Reserved Lines
- The first few lines are reserved for the following purpose:

  | Line #  | Usage  |
  |--------|--------|
  | 1 | `Language Name`: The language name in your language (e.g. `English` in [English version](/DLLocalization_English.txt), `中文（简体）` (Chinese Simplified) in [Chinese version](/DLLocalization_ChineseSimplified.txt). |
  | 2 | `Fallback Language Name`: Indicates which fallback language to use. When lines are empty, the game will automatically apply the corresponding fallback language phrases. |
  | 3 | `FontName`: Game font culture, usually no need to change. |

- To reduce the game size, please leave phrases blank if you want them to match the fallback language.

## Placeholders & Escape symbols
- You need to keep them as they are, but you can adjust their positions as needed.
  Some of these will be automatically replaced with the actual content when the game runs.
  > They usually starts and ends with `#` or starts with `\` only.
  
  | Example  | Usage  |
  |--------|--------|
  | `\n` | Insert this if you want to start a new line. |
  | `\t` | Tab |
  | `<b>BOLD</b> text` | **BOLD** text |
   | `<color=#3d6ec0>COLORED</color> text` | **COLORED** text |
  | `#LEVELNAME#` | Level name |
  | `#item#` | Item name |
  | `#USERNAME#` | Username |
  | `#X%#` | Percentage
  | `{0}` `{1}`| Other |
  
# [Languages & Contributors](https://github.com/DL-Community/DLCE-Translations/graphs/contributors)
