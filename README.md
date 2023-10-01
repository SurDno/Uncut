A project dedicated to restoration of various elements cut during the development of S.T.A.L.K.E.R.: Clear Sky, incorporating unused content in release files, early prototypes, design documents and concept arts.

# OVERVIEW
* Restores over 5 cut and early elements of release locations.
* Restores 45 previously unused voice lines.
* Restores 38 lines of dialogue with 6 unique characters and 22 lines of dialogue with generic NPCs.
* Restores 1 unique cut quest and 2 generic faction Faction War quests.

# CHANGES
Note: Changes with asterisk next to them are pure cut content restoration. Changes in square brackets are the ones that are made in order to make the cut content more coherent with the game, with either plus, minus or tilde describing whether a certain feature is added, removed or changed.

## Gameplay Changes
* Restored an ability to heal injured teammates using bandages instead of medkits. - SurDno
* Restored cut behaviour with camp inhabitants losing disposition towards player upon stealing loot from their camp box. - SurDno
* Restored random emissions on Great Swamps happening after completion of storyline there. - SurDno
* Restored pre-1.5.03 bandit blockpost behaviour with them taking not just the money but also all the items with the exception of Scar's most expensive pistol and ammo for it. The things are now again stored in a box behind the closed gate at bandit base and can be taken back after clearing Depot or joining bandits.
  
## Quest Changes
* NEW - Find the migration map — descend into the Agroprom Undeground to find the lost migration map. The quest is given by Inquisitor on Duty base. - SurDno
  - [+] Added a previously missing reward - a pack of AP 5,45 ammo and 1500 RU. It was originally a flash drive with data on modifying the gas exhaust of a machine gun as well as GP-25 Koster, but that was later transferred to Hermit's quest and this one was left rewardless. - SurDno
  - [~] Changed dialogue from early draft written by programmers to the one that is way richer in details. This is a recreation of the way the text would have been if game designers were ever rewriting it for final game. - SurDno
* Restored a requirement to capture the other Cordon level changer and Agroprom level changer in the last phase of Clear Sky Faction War. - SurDno

## Character Behaviour Changes
* Made Professor Beanpolev move between unused points in his shack instead of staying in the same place. - SurDno
  - [+] Added logic to move once a minute if the player is not currently talking to the character. - SurDno

## Sound Changes
* Restored 6 Father Valerian's greeting and farewell phrases. Besides, since one of the latter lienes was a duplicate in release files, an original file has been ported from Build 3436. - SurDno
* Restored 2 unused Sidorovich farewell phrases. - SurDno
* Restored 36 unused background phrases for Clear Sky soldiers at CNPP. - SurDno
  - [~] Added logic to play once every 4-7 seconds between the starting and ending cutscenes.
* Restored unused Forester voiceline meant for initial greeting. It is now used prior to the first dialog. - SurDno

## Location Changes
* Great Swamps:
  - Ported an early version of Clear Sky base from the model source leak. Most notable changes include Gray's shack having holes in the floor, making AKM-74/2 possible to take without bug abuse, and the fireplace in Lebedev's building being two-sided. - Pirat
  - Ported fishing hamlet texturing from Build 3120. - Pirat
  - Ported pump station from Build 3120. Most notable changes include the pipes at the roof having smoke coming out of them and the building looking less run-down. - Pirat
  - Restored slimey water around pump station, which can be seen on prerelease screenshots and concept arts. - Pirat
    - [+] Made the texture semi-transparent to preserve soft water effect. - Pirat
  - Opened the gate at Clear Sky base to match the layout of early screenshots. - Pirat

## Dialogue Changes
* Restored a set of unique Scar answers to Suslov and Cold phrases.
* Restored a unique Scar answer to the long starting dialogue with Suslov after returning to CS base after second emission happens. - SurDno
* Restored a dialogue with Flea Market night trader where you got to convince him you're trustworthy before trading. - SurDno
  - [+] Added custom script conditions to ensure that the NPC does not act as a trader before the dialogue is finished. - SurDno
* Made Duty Scar neutral towards bandits and Bandit Scar neutral towards Duty in order to restore two dialogues about switching factions. Duty — Bandit relationship has been left unchanged. - SurDno
* Spawned two loner squads at otherwise unused smart terrains - Shore barricades and Bonfire on shore - in order to restore unique loner Great Swamps dialogues and populate otherwise empty camps. Since these smart terrains do not have links to any others, this does not affect faction war in any way. - SurDno

## Graphics & Visuals Changes
* Restored Clear Sky stalker models from Build 3120. - SurDno, OGSM Team
  - [+] Made own icons to fix incosistency between NPC visuals and icons were created only after the model change. - SurDno
* Added two elements present on Forester's texture that were missing from the model's UV - a radio and a pistol. - Pirat

# BUGFIXES
* Fixed the game crashing when a squad occupies shore barricades smart terrain due to animation name typo. - Decane
* Fixed Professor Beanpolev not using the script-specified animation when moving between points. - Decane
* Fixed bandit robberies not taking SIP-t 200M and any modified pistols into consideration during the search for most expensive pistol. - SurDno
* Fixed bandit robberies leaving 9 x 18 ammo instead of 9 x 19 if player's most expensive pistol is the upgraded PMm they took from renegades at Swamps. - SurDno

# FAQ
* Q: Is that like a prerelease build?
  - A: No. This is more of a mash up of content cut during very different points of development.
* Q: Is it a definite version of the game?
  - A: No. Most things cut were cut for a reason, with time constraints being a very rare scenario. Release game is the definite experience.
* Q: Is it faithful to developers' intentions? 
  - A: No. GSC deemed most content removed from the game as unsuitable. Besides, some things cannot be restored properly because they had not been fully done by the point when they got removed.
* Q: Is that suitable for a first playthrough?
  - A: God no. Just play vanilla.
* Q: So what's the point of the mod?
  - A: Providing an interactive tour into the world of Clear Sky cut and unused content. 

# INSTALLATION
1. Ensure there is no 'gamedata' folder in your game directory - Clear Sky Uncut is incompatible with other mods unless you know how to merge them manually.
2. Put 'gamedata' folder from the archive in your game directory.
3. Navigate to the folder with sounds of your language and transfer the 'gamedata' folder from there to your root directory as well.

# KNOWN ISSUES
* While you are able to give a bandage to an injured NPC, this does not actually heal them and they still need to be given a medkit.
* There is a hole in geometry at Clear Sky base that you can fall through.
* It is possible to get your weapon out if you go through the open gate.

# CREDITS
## Developer Team
* **SurDno** - configs & text cut content restoration.
* **Pirat** - models & location cut content restoration.

## Special Thanks
* **Decane** — huge help with getting xr_smartcover scheme to support def_state_moving parameter.
* **Nemrtvi** — a lot of work done going through the text files finding unused strings.
* **OGSM Team** — porting B3120 models into the final game format.