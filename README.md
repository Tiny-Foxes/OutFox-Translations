OutFox-Translations

Where translations that are in Project OutFox are stored. English is not included here because they're updated internally and are not hosted in Tiny-Foxes.

Learn how to translate in [OutFox wiki](https://outfox.wiki/dev/translation/).
## Language Status

Please tick the box of your language when done for the requested version.

Version | pt-BR | Español | Japanese | German | Polish | French | Italian | Hebrew | Slovak | Czech | Simplified Chinese
:------------ | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :-------------
4.10.0 | ✅ | ⬜️ | ✅ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️
4.9.10 | ✅ | ⬜️ | ✅ | ⬜️ | ⬜️ | ✅ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️
4.9.9 | ✅ | ✅ | ✅ | ⬜️ | ✅ | ✅ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ✅
4.9.7.1 - 4.9.8 | ✅ | ✅ | ✅ | N/A | ✅ | ✅ | N/A | ✅ | N/A  | N/A | ✅
4.9.7 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | WIP | ✅ | WIP  | WIP | N/A
4.9.6 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | N/A
4.9.2 - 4.9.5 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | N/A | ✅ | N/A | N/A | N/A
4.9.1 | ✅ | ✅ | ✅ | ✅| ✅| ✅| N/A | ✅ | N/A | N/A | N/A
4.9.0 | ✅ | ✅ | ✅ | N/A| ✅| ✅| N/A | N/A | N/A | N/A | N/A
4.8.9 | ✅ | ✅ | ✅ | ✅| ✅| ✅| N/A | N/A | N/A | N/A | N/A
4.8.5 | ✅ | ✅ | ✅ | N/A| ✅| ✅| N/A | N/A | N/A | N/A | N/A
4.8.3 | ✅ | ✅ | ✅ | ✅| ✅| ✅| N/A | N/A | N/A | N/A | N/A

Trivia: 

✅ - Fully implemented

⬜️ - Not implemented

N/A - Non existant at its time

WIP - Work in Progress
<!--- This is a comment that won't appear in the readme.

1. Here are the emojis that you can add to tell if your language is done or not. 
    Done: ✅ 
    Not Done: ⬜️ 
    Non applicable: N/A 
    Work in Progress: WIP

2. If you aren't part of OutFox Team, DO NOT change table formatting without asking for confirmation.
--->

### Keep your files clean/synchronized 

To keep your files clean and synchronized with the EN files, you can use the Translation-Toolkit: https://github.com/Tiny-Foxes/Translation-Toolkit/releases/latest, find more tools at [OutFox wiki tools page](https://outfox.wiki/dev/translation/#tools-and-practices)

## 4.10.0

### Fallback
```ini
[OptionExplanations]
BackPlates=Select a BackPlate to display behind the Notefield. # Added
GDDMRealToNew=Change GDDM Real charts to New. # Added

[OptionTitles]
BackPlates=BackPlates # Added
GDDMRealToNew=Real To New # Added
```

### Replacements (Fallback)
```diff
[StepsType]
-Guitar_Five=5 Frets
-Guitar_Six=6 Frets
-Bass_Six=5 Frets Bass
-Guitar_Three=3 Frets
-Bass_Four=3 Frets Bass
+Gdgf_Five=5 Frets
+Gdgf_Six=6 Frets
+Gdgf_Three=3 Frets
+Gdgf_Bass_Five=5 Bass
+Gdgf_Bass_Six=6 Bass
+Gdgf_Bass_Three=3 Bass
```