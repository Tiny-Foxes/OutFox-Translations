OutFox-Translations

Where translations that are in Project OutFox are stored. English is not included here because they're updated internally and are not hosted in Tiny-Foxes.

Learn how to translate in [OutFox wiki](https://outfox.wiki/dev/translation/).
## Language Status

Please tick the box of your language when done for the requested version.

Version | pt-BR | Español | Japanese | German | Polish | French | Italian | Hebrew | Slovak | Czech | Simplified Chinese
:------------ | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :------------- | :-------------
0.5.0-pre043-a6 | WIP | WIP | WIP | ⬜️ | WIP | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️
0.5.0-pre042-a34 | ✅ | WIP | WIP | ⬜️ | WIP | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️
0.5.0-pre042-a26 | ✅ | WIP | WIP | ⬜️ | WIP | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️
0.4.19.0 | ✅ | ✅ | ✅ | ⬜️ | ✅ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ✅
0.4.15.0 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
0.4.14.0 | ✅ | ✅ | ✅ | ✅ | ✅ | ⬜️ | ⬜️ | ⬜ | ✅ | ⬜️ | ✅
4.13.0 | ✅ | ✅ | ✅ | ✅ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | WIP | ⬜️ | ✅
4.11.1 | ✅ | ✅ | ✅ | ✅ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ⬜️
4.10.0 | ✅ | ⬜️ | ✅ | ⬜ | ⬜️ | ✅ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ✅
4.9.10 | ✅ | ⬜️ | ✅ | ⬜️ | ⬜️ | ✅ | ⬜️ | ⬜️ | ⬜️ | ⬜️ | ✅
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

## 0.5.0-pre043-a6
### alphav-theme
```diff
+ [ScreenSelectPlayMode]
+ EasyExplanation=For those just starting out.
+ NormalExplanation=The standard game.
+ # RecentExplanation=List of recently played songs.
+ RaveExplanation=Charge attacks to distract your opponent!
+ NonstopExplanation=Play through sets of songs consecutively.
+ OniExplanation=Play through sets of songs with limited life.
+ EndlessExplanation=How long can you last?

+ EasyTitle=Easy
+ NormalTitle=Normal
+ # RecentTitle=Recent
+ ExtendedTitle=Extended
+ OniTitle=Oni
+ EndlessTitle=Endless
+ RaveTitle=Rave

+ ConfirmText=Confirm?

[OptionsMenu]
+ Experimental=Experimental

[ScreenSelectProfile]
+ MemDescText=Use your Memory Card for this session.
+ GuestDescText=Skip using a profile and just play songs!
+ 
+ LastPlayedHeader=LAST PLAYED
+ TotalPlayTimeHeader=TOTAL PLAY TIME
+ SongsPlayedHeader=SONGS PLAYED
+ LastSessionString=LAST SESSION: %s
+ 
+ LocalProfile=LOCAL PROFILE
+ MemoryCardProfile=MEMORY CARD
+ GuestProfile=GUEST
+ 
+ PlayerNumberText=PLAYER %d
+ JoinText=JOIN
+ JoinHelpText=Touch, Press &START; or [Enter]!

[ScreenEvaluation]
+ ButtonFinishSession=End Session

[OptionTitles]
+ SkipHomeEvaluationChoices=Skip evaluation two-step options
+ HereBeDragons=Here be dragons! These are experimental features, so expect them to break.

[OptionExplanations]
+ SkipHomeEvaluationChoices=Tells the game to skip the theme's two-step choices present in Evaluation, mimicking the original behavior of pressing start to move on. This is forced on when in non-Event Mode.
```

## 0.5.0-pre042-a26
### alphav-theme
[File is available here](./alphav-dance/en.ini).

## 0.4.19.0
### Fallback
```ini
[GameButton]
Bongo Left=Bongo Left # New
Bongo Right=Bongo Right # New
Bongo Clap=Bongo Clap # New

[OptionExplanations]
InputDebounceTime=Time that a panel takes to depress. Use this to deal with ghost steps that occur a few milliseconds after a real step. # Changed
DebounceCoinInputTime=Time that the coin mechanism takes to depress. Use this to deal with double credits that occur when only one coin is inserted. # New

[OptionTitles]
DebounceCoinInputTime=Coin Mechanism Debounce Time # New

[StepsType]
Bm_Single6=5+P Keys # New
Bm_Double6=10+P Keys # New
Bongo=Bongo # New

[NativeLanguageNames]
PortugueseBR=Português brasileiro # New

[StepsDisplay StepsType]
Bm_Single6=5+P Keys # New
Bm_Double6=10+P Keys # New

[StepsListDisplayRow StepsType]
Bm_Single6=5+P Keys # New
Bm_Double6=10+P Keys # New
```
### Default

```ini
[ScreenSelectMusic]
AddFavorites=&MENUUP; Add/remove song from favorites # New
```
