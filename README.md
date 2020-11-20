OutFox-Translations

Where translations that are in Project OutFox are stored. Please tick the box of your language when done for the requested version.

English is not included here because they're updated internally and are not hosted in Tiny-Foxes.
## Language Status

Language | 4.8.3 | 4.8.5 | 4.8.9 | 4.9 | 4.9.1 | 4.9.2 
:------------ | :------------- | :------------- | :------------- | :------------- | :------------- | :-------------
pt-BR | ✅ | ✅ | ✅ | ✅| ✅| ✅
Español | ✅ | ✅ | ✅ | ✅| ⬜️| ⬜️
Japanese | ✅ | ✅ | ✅ | ✅| ✅| ✅
German | ✅ | ⬜️ | ✅ | ⬜️| ✅| ✅
Polish | ✅ | ✅ | ✅ | ✅| ✅| ⬜️
French | ✅ | ⬜️ | ✅ | ⬜️| ⬜️| ⬜️
Italian | N/A | N/A | N/A | N/A | N/A | ⬜️
Hebrew | N/A | N/A | N/A | N/A | ✅ | ✅


<!--- This is a comment that won't appear in the read me, here are the emojis that you can add to tell if your language is done or not. Done: ✅Not Done: ⬜️Non applicable: N/A--->

### Fallback

```Ini
[ScreenDebugOverlay]
Both at Once=Both at Once # New
Monkey Input=Monkey Input # This feature is no longe usable in 5.3 alpha 4.9.2 (?) but we should not remove for compatibility in case anything tries to get that key

[OptionExplanations]
Test Analog Lua Input=Test the responsiveness of analog inputs (such as analog sticks, triggers, and MIDI inputs). # New

[OptionTitles]
Test Analog Lua Input=Test Analog Input # New

[ScreenTestInput]
HeaderText=Test Button Input # Changed

[ScreenTestLuaAnalog] # New, recommended to put bellow "[ScreenTestInput]"
HeaderText=Test Analog Input # New
```

### Default

```Ini
[OptionExplanations]
ShowMascotCharacter=Display Narumi, the OutFox mascot, on the title screen. # Changed

[ScreenTestLuaAnalog]
HelpText=Hold &BACK; or &START; to exit. # New

[ScreenEvaluation]
# Judgment histogram page
HistogramCol=Judgment Histogram # New
Mean=Mean # New
Median=Median # New
Mode=Mode # New
Late=Late # New
Early=Early # New

[OptionExplanations]
SoundwavesMenuBG=Choose a menu background style for the Soundwaves theme. # New
VideoRenderer=Choose between modern (GLAD) or legacy OpenGL graphics rendering engines.\nRequires a restart in order to take effect. # Changed
UseOldJoystickMapping=If enabled, a HIDAPI-based ("legacy") input system modeled upon SM 5.0.x is used instead of XInput.\nRequires a restart in order to take effect. # Changed

[OptionTitles]
UseOldJoystickMapping=Use Legacy input system # Changed
SoundwavesMenuBG=Menu background # New

[OptionNames]
swBGSolid=Solid # New
swBGBlack=Black # new
```
