# Changelog

## 1.1 (2026-11-22)

Fixes the gender of some NPCs.

- Fixed: Andover Potbello was taken for a woman and heard the female voice. The portrait list (`pics.tsv`)
  relied, for ten portraits, on names that stand in both the men's and the women's street-NPC lists (Pat, Robin,
  Heather, ...). Those names no longer vote. `names.tsv` now lists Andover Potbello as male.
- No new recordings; the package is the same size as 1.0.

## 1.0 (2026-11-19)

First release as a separate add-on.

- 8,502 recordings for 3,803 of the 3,881 dialog texts of MM6, MM7, MM8 and MAW, male and female voices,
  made with Kokoro-82M.
- Voice by the NPC's gender (name list, portrait), texts with placeholders (hire pitches, greetings with a name).
- F9 repeats the last line (press again within 2 seconds for the line before it, and once more for the one before
  that), F10 stops it.
- Settings in `MAWSettings.lua`: `npcVoices`, `npcVoiceVolume`, `repeatVoiceKey`, `stopVoiceKey`.
- Only adds files: no file of the game, MMMerge or MAW is changed, saved games are not touched.
- Works together with MAW NPC Voices DE.
