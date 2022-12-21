# OutFox-Translations

Where translations that are in Project OutFox are stored. English is not included here because they're updated internally and are not hosted in Tiny-Foxes.

Learn how to translate with [OutFox wiki](https://outfox.wiki/dev/translation/).

### Alpha V Branch

This is meant for Alpha V and future translation, if you want to translate Alpha 4 LTS, go to the master branch instead.

Q: _"How do I get Alpha V?"_

1. [Join our Discord Server](https://discord.gg/cN4TjgQdcA) (https://discord.gg/cN4TjgQdcA) to participate in our testing program.
    - Select the `#pick-a-role` channel.
    - Scroll the channel all the way down and click the "Test Alpha V" button which should be with the last message sent in that channel.
    - You should now be able to see a channels that start with "alpha5" inside the `OutFox-Development Category`, select the `alpha5-test-builds` channel.
    - Grab the latest build for your platform.
2. [Join our Discord Server](https://discord.gg/cN4TjgQdcA) (https://discord.gg/cN4TjgQdcA) to ask For a Steam key
    - Select the `#steam-general` channel inside the "OutFox on Steam" Category
    - Send a message requesting a key. (Depending on when you do this there might not have keys left)
## Language Status

## Installer

Version | pt-BR | Español | Japanese | German | Polish | French | Italian | Hebrew | Slovak | Czech | Simplified Chinese | Dutch
:------------ | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :-------------
0.5.0.0 RC30 | ✅| N/A | ✅ | ✅ | ✅ | N/A | N/A | N/A | N/A | N/A | ✅ | N/A
0.5.0.0 RC28 | ✅| N/A | ✅ | ✅ | ✅ | N/A | N/A | N/A | N/A | N/A | N/A | N/A
0.5.0.0 RC26 | ✅ | N/A | ✅ | ✅ | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A

## Fallback

Version | pt-BR | Español | Japanese | German | Polish | French | Italian | Hebrew | Slovak | Czech | Simplified Chinese | Dutch
:------------ | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :-------------
0.5.0.0 RC30 | ✅ | ⬜️ | ✅| ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️
0.5.0.0 RC28 | ✅ | ⬜️ | ⬜️| ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️
0.5.0.0 RC26 | ✅ | ✅ | LGC | LGC | LGC | LGC | LGC | LGC | LGC | LGC | LGC | LGC

## alphav-dance

Version | pt-BR | Español | Japanese | German | Polish | French | Italian | Hebrew | Slovak | Czech | Simplified Chinese | Dutch
:------------ | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :-------------
0.5.0.0 RC30 | ✅ | ⬜️ | ✅ | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A
0.5.0.0 RC28 | WIP | ✅ | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A
0.5.0.0 RC26 | WIP | ✅ | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A

Trivia: 

✅ - Fully implemented

⬜️ - Not implemented

N/A - Non existent at its time

WIP - Work in Progress

LGC - Legacy Translation (From Alpha 4)

---

<!--- This is a comment that won't appear in the readme.

1. Here are the emojis that you can add to tell if your language is done or not. 
    Done: ✅ 
    Not Done: ⬜️ 
    Non applicable: N/A 
    Work in Progress: WIP
    Legacy Translation: LGC

2. If you aren't part of OutFox Team, DO NOT change table formatting without asking for confirmation.
--->

### Keep your files clean/synchronized 

To keep your files clean and synchronized with the EN files, you can use the Translation-Toolkit: https://github.com/Tiny-Foxes/Translation-Toolkit/releases/latest, find more tools at [OutFox wiki tools page](https://outfox.wiki/dev/translation/#tools-and-practices)

## 0.5.0.0 RC30

### alphav-dance

```diff
[LuaSelectMusic]
- HelpText=&MENULEFT;&MENURIGHT; Scroll songs &SELECT; + &START; Sort &SELECT; Open Menu &SELECT; + &MENULEFT; OR &MENURIGHT; Change Style &START; Confirm
+ HelpText=&MENULEFT;&MENURIGHT; Scroll songs &SELECT; Open Menu &START; Confirm::&SELECT; + &START; Sort - &SELECT; + &MENULEFT; OR &MENURIGHT; Change Play Style
+ NPSDataNotLoaded=Not rendered for performance reasons.

[OptionTitles]
+ UseTouchControls=Enable mouse/touch controls
```

### Fallback

```ini
[OptionNames]
80Percent=80Percent
```

## 0.5.0.0 RC28

### Fallback

```ini
[GameButton]
Bongo Left=Bongo Left
Bongo Right=Bongo Right
Bongo Clap=Bongo Clap

[OptionExplanations]
AutoKeySoundBMS=Enable or disable autokeysounds so you dont have to hit them to play.
BMSHeaderLoad=Enable or disable loading header files on BMS - Disable for Old HDD's.

# This comment is here only to fix the colors'

[OptionNames]
Enable=Enable
Disable=Disable
BMS=BMS
Full=Full
OutFox=OutFox

[OptionTitles]
AutoKeySoundBMS=AutoKeysounds for BMS
BMSHeaderLoad=Load BMS Header

[NativeLanguageNames]
PortugueseBR=Português brasileiro
```

## 0.5.0.0 RC26

### Fallback
```ini
[ProfileAction]
AssignToOnlineAccount=Assign to OutFox Online Account

[ScreenOptionsManageProfiles]
Enter a username.=Enter a username to assign this profile.
Enter an email address.=Enter an email address.
Check User Inbox=Check your inbox for the registration email.
Email Duplicate=The email provided already has an account assigned to it.
Timed Out=Operation timed out.

[ScreenSelectMusic]
PermanentlyDeleteChart=Permanently delete chart '%s' ( From song %s ) from disk?

[StepsType]
Boxing_Freestyle=Freestyle
```

### alphav-dance
```ini
[ScreenWithMenuElements]
Continue=Continue

# These are made for the Lua wheel.
[SortingModes]
group=Group
title=Title
artist=Artist
genre=Genre
bpm=BPM
length=Length
search=Search
# The following modes are exclusive to the search feature.
subtitle=Subtitle
pack=Pack
meter=Meter

[ScreenEvaluation]
ScoreSubmitExisting=Score already submitted.

[LuaSelectMusic]
SearchButton=SEARCH
PersonalBest=Personal Best

[SearchSongWide]
FlagSuggestion=Use these flags to find specific songs!

[OptionsMenu]
# Left-side option titles
Game=Game
Controls=Controls
Sound=Sound
Calibration=Calibration
Graphics=Graphics
Theme=Theme
Help=Help

[OptionTitles]
# Lua wheel options
Search for Song=Search for Song
ShowLeaderboard=Show leaderboard
Change Profile=Change Profile
Exit Menu=Exit Options Menu
UseTouchControls=Enable mouse/touch controls

# Options Menu items
Go to legacy options=Go to legacy options

[KnownBugs]
Continue=Continue
HelpText=&START; Continue
```
