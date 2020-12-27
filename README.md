# DiesIraeNXEN

This project ports English translation from PC to Switch with some changes to adjust to some differences between Switch release and Steam PC.
Main differences:
- PC release is using `UTF-16`, while Switch `Shift-JIS` which limits in what I can do with characters
- Switch release has additional story which is a prologue to unreleased (yet) Dies Irae Pantheon. Because of that text blocks count is different than on Steam PC and this story is not translated (if someone with experience wants to translate it, contact me)
- Playing voices is attached to pause count in each text block, so because pauses must match to play voices correctly and Steam PC pause count was sometimes different, I have changed break lines and didn't delete few japanese lines in blocks playing voices if they didn't exist in Steam PC
- Switch version doesn't support italic binary tags from Steam PC, so I have changed them with 《》
- Switch version is breaking text by last character, not by last space, so lines are breaked differently than on Steam PC
- For Configuration menu + Extra Switch version is using different assets, so I have translated them and swapped original assets. Help menu is not translated (if someone with experience wants to translate it, contact me)
- Character names offset cannot be changed without decompiling bytecode. So if English name is bigger than Japanese, I'm changing sound file name that is always after to shorter name, fix offset for audio file and pack audio file with new name.
- Some dialogues have joined or splitted audio files in comparison to steam pc release, so texts was appropriately redacted

Mod is in alpha fase.

Expected issues:
- Text going out of boundaries
- Some character names may remain untranslated
- Some audio files may not play

How to install it:
- Just copy `0100BB900B5B4000` folder to `atmosphere/contents`
- Run game

---

Screenshots:
