# Sound Voltex Custom Practice Charts

## History
As a level 15 player (as of writing, 25th Apr 2025) after on-off play on weekends over the past four months, I’ve been continually frustrated with needing to skill up on specific chart patterns the game asks you to do, such as:

- one-handing,
- laser+both FX buttons,
- double-note chord patterns etc, 

and have been looking for ways to practice the patterns I’ve identified as needing to be practiced in order to start improving and working my way up the difficulties.

However, playing the game normally doesn’t give me the opportunity to practice these patterns that often, as songs only ever have specific patterns as part of their charts for maybe 4-5 measures in the song, and you often have to play through the rest of the song in its entirety to be able to practice those patterns. That, and you need to find songs that even have those chart patterns to begin with.

So I decided to make my own practice charts to focus on these patterns.

## Information
These charts are created using **kshootmania 1.75’s Song Editor**, with the April Fools tutorial parody song 「エクシード仮面ちゃんのちょっと一線をえくしーどしたEXCEED講座」(*Exceed kamen-chan no chotto issen wo exceed shita EXCEED kouza*) as a base, so it includes some effects baked in. The practice chart uses the song’s correct BPM of 130 and a song duration of 130,000ms.

The charts have been tested to work on:
- kshootmania 1.75
- Unnamed Sound Voltex Clone 1.60

The idea behind these charts is that each one focuses on a particular type of pattern or skill for the duration of the song, and each chart and pattern starts off slowly to give you time to get used to the hand positioning and rhythm, before speeding up on subsequent measures to test your execution and timing.

Some of these are designed to be quite difficult, but through repetition they should help you improve your pattern recognition and execution.

For experts (*level 19+ players of around VOLFORCE 19 or higher*), try setting Random on for an additional challenge. ^_-

I’ve also recently found a utility called [VoxCharger](https://github.com/SirusDoma/VoxCharger) that can manage files for your arcade data installation, including importing KSM-made charts, so I’ve also converted these practice charts for use with Exceed Gear data. You’ll need [IFS_LayeredFS](https://github.com/mon/ifs_layeredfs) installed in order to inject custom charts into the arcade data, but I’ve tested these out in the game and they work fine.

They’ve been purposely changed to Level 1 with radar charts zeroed out, so they won’t affect your Volforce rating.

## Pattern Charts
There are a number of pattern charts created so far, including:

- BT and FX chord combinations
- long BT hold patterns
- double-BT note chord patterns
- a chart with more complex chords
- a very long double FX hold chart with additional BT patterns
- a very long BT staircase sequence
- combination FX hold and BT staircases
- hand-trip practice charts focusing on each hand
- quick laser-switching and laser-cutback patterns
- one-handing practice

More charts may be added as time goes on with new patterns to focus on.

## Usage

### KSM Songs
- Download the songs in the repo, and add them to your copy of KSM/USDVXC under their *songs* folder - you can add them to a subfolder such as “Custom” or similar for organisation.
- Open KSM/USDVXC with these songs added, then navigate to the folder in-game and find the song you want to practice.
- Practice!

Also, in USDVXC, you can further focus your practice by using Practice Mode - accessed either through the FX-L+FX-R menu, or by pressing the grave key (`) - and setting what measures you want to loop through in practice.

### Arcade Omnimix Songs
- You’ll need to install [IFS_LayeredFS](https://github.com/mon/ifs_layeredfs) into your AC data folder using the usual instructions.
- Create a `data_mods` folder in the root of your data installation.
- Download the repo, and copy the entirety of the `omnimix_practice` folder (including the folder itself) into `data_mods`, so your folder structure looks like `data_mods\omnimix_practice\(the three folders inside)`.
- Run the game - it should boot up as normal if it’s working fine. If it crashes after the initial boot check, something has gone wrong.
- If it’s working, you should find the practice songs in the Level 1 folder.
- Practice!