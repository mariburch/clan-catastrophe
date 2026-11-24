# Clan Catastrophe

A web page that strikes a [ClanGen](https://github.com/ClanGenOfficial/clangen) Clan with a mass-death disaster. Shield the cats you love, roll as many times as you like, and only save the result you want to keep.

This is an unofficial fan tool. It is not made by or connected to the ClanGen team.

## What it does

- **Loads your save** from a zipped `saves` folder or the folder itself. Everything happens in your browser; nothing is uploaded.
- **Lets you pick the Clan** to strike.
- **Shields cats** so they can never be picked. Shields are remembered per Clan in your browser.
- **Disasters:** flood, wildfire, sickness, famine, storm, blizzard, rockslide, Twolegs, badgers and rogue invasion, plus your own. Each disaster has several death lines, and every struck cat gets one at random. Add your own disasters with one death line per line of text (use `{name}` where the cat's name goes).
- **Individual deaths:** after a roll, press **Edit** on any struck cat to write exactly how they died, or **Another line** to pick a different one.
- **How many:** an exact number, a percent of the Clan, or a random range.
- **Leader lives:** a random number, one, all, or a number you choose. A leader with lives left survives.
- **Survivors:** some cats can live through the disaster with injuries, illnesses or permanent conditions. Each disaster suggests fitting ones (a flood brings water in their lungs, greencough and raspy lungs; a rockslide brings broken bones and lost legs), and you can add or remove any of ClanGen's own conditions. After a roll you can add, remove or reroll any cat's conditions, or hurt a cat by hand.
- **Reroll** freely, reroll only the survivors, or **Spare** single cats from a roll. Nothing is saved until you download.
- **Downloads** a new copy of that Clan's folder to swap into your saves.

## How deaths are written

The page follows ClanGen's own rules for a death:

- The cat moves to the afterlife of the Clan's guide (StarClan or the Dark Forest). A cat with a negative affinity for that afterlife may be turned away and sent to the other one. Kits are always accepted.
- The disaster is added to the cat's history and to that moon's events.
- Mentors and apprentices are unlinked, injuries and illnesses are cleared, and a pregnancy is removed if the mother dies.
- A dead leader or deputy is replaced by the game at the next moon, as after any death.

Built for saves from builds that store each Clan in its own folder with a `clan.json` inside.

## Use it

Open `index.html` in a browser, or turn on GitHub Pages for this repo (Settings → Pages → Deploy from a branch → `main`).

1. Close ClanGen and **back up your whole `saves` folder**.
2. On a Mac the saves live in `~/Library/Application Support/ClanGen/saves`. In the file picker, press Cmd + Shift + G and paste that path.
3. Roll until you like the result, then download.
4. Move the Clan's old folder out of `saves`, unzip the download and drag the new folder in.
