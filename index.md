# DiesIraeNXEN

This project ports English translation from PC to Switch with some changes to match some differences in Switch release.

Main differences:
- PC release is using `UTF-16`, while Switch `Shift-JIS` which limits in what I can do with characters
- Switch release has additional story which is a prologue to unreleased (yet) `Dies Irae Pantheon`. Because of that text blocks count is different than on Steam PC and this story is not translated (if someone with experience wants to translate it, contact me)
- Playing voices is attached to pause count in each text block, so because pauses must match to play voices correctly and Steam PC pause count was sometimes different, I have changed break lines and didn't delete few japanese lines in blocks playing voices if they didn't exist in Steam PC
- Switch version doesn't support italic binary tags from Steam PC, so I have changed them with `《` and `》`
- Switch version is breaking text by last character, not by last space, so lines are breaked differently than on Steam PC
- For Configuration menu + Extra Switch version is using different assets, so I have translated them and swapped original assets. Help menu is not translated (if someone with experience wants to translate it, contact me) + popups
- Character names offset cannot be changed without decompiling bytecode. So if English name is bigger than Japanese, I'm changing sound file name that is always after to shorter name, fix offset for audio file and pack audio file with new name.
- Some dialogues have joined or splitted audio files in comparison to steam pc release, so texts were appropriately redacted

Mod is in `alpha` phase. There is no ETA of beta and full release.

Expected issues:
- Text going out of boundaries
- Some character names may remain untranslated
- Some audio files may not play
- Some text blocks may have additional text that in Switch release doesn't exist

How to install it:
- Just copy `0100BB900B5B4000` folder to `atmosphere/contents`
- Run game

Credits for translation goes to staff from `Dies irae World Emanation Project`.
All things related to porting and translating new assets were done by `MasaGratoR`

All files in package are only related to port. They don't have any untouched original files from Switch version. They have been packed to data5.dat that doesn't exist in Switch version, but it's overriding any files that have the same pathname as in other data*.dat files

---

# Screenshots:

![Config](https://github.com/masagrator/DiesIraeNXEN/raw/main/Images/2020122717575200-88DABD6BF029E4019C69DC28281AC19B.jpg)
![SCR1](https://github.com/masagrator/DiesIraeNXEN/raw/main/Images/2020122717585500-88DABD6BF029E4019C69DC28281AC19B.jpg)
![SCR2](https://github.com/masagrator/DiesIraeNXEN/raw/main/Images/2020122717590700-88DABD6BF029E4019C69DC28281AC19B.jpg)
![SCR3](https://github.com/masagrator/DiesIraeNXEN/raw/main/Images/2020122717591900-88DABD6BF029E4019C69DC28281AC19B.jpg)
![SCR4](https://github.com/masagrator/DiesIraeNXEN/raw/main/Images/2020122718005000-88DABD6BF029E4019C69DC28281AC19B.jpg)

---

# [Download](https://drive.google.com/file/d/1X2ayeIGz9NOLdtGg23SQuMnaUdbZ3SHk/view?usp=sharing)

---

# Troubleshooting

Any issues that glitch game please write here:
[https://github.com/masagrator/DiesIraeNXEN/discussions](https://github.com/masagrator/DiesIraeNXEN/discussions)
