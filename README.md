A project dedicated to restoration of various elements cut during the development of S.T.A.L.K.E.R.: Clear Sky.

CHANGES
=======
Note: Changes with asterisk next to them are pure cut content restoration. Changes in square brackets are the ones I had to make myself, with either plus, minus or tilde describing whether a certain feature is added, removed or changed.

**Gameplay:**
* Restored an ability to heal injured teammates using bandages instead of medkits.
* Restored a requirement to capture the other Cordon level changer and Agroprom level changer in the last phase of Clear Sky Faction War.
* Restored random emissions on Great Swamps by uncommenting a line in a script. They start happening if you return to the location after visiting Cordon at least once.
* Brought back artifact-dropping boxes and cases. These were a concept in SoC which clearly made it to CS (devs hid the boxes all around the maps) but since no maps have artifacts in drop lists, the containers are essentially empty in vanilla.
[~] Since the artifact drop was removed early on, way before artifact overhaul, SoC artifacts have been replaced with CS artifacts, with drop chance depending on rarity and price. Rarest artifacts (namely Firefly, Fire, Goldfish and Snowflake) never drop from containers, just the way most rare SoC artifacts don't.
[+] Made own progression with rarer artifacts dropping on norther locations, similar to the way artifact progression is implemented in SoC and the way ammo progression is implemented in CS.

**Quests:**
* Find the migration map — descend into the Agroprom Undeground to find the lost migration map. The quest is given by Inquisitor on Duty base.
[+] Added a previously missing reward - a pack of AP 5,45 ammo and 1500 RU. It was originally a flash drive with data on modifying the gas exhaust of a machine gun as well as GP-25 Koster, but that was later transferred to Hermit's quest and this one was left rewardless.

**Characters:**
* Made Professor Beanpolev move between unused points in his shack instead of staying in the same place.

**Sounds:**
* Restored Father Valerian's greeting and farewell phrases. Besides, since one of the latter was a copy of another, an original file has been ported from Build 3436.

**Dialogues:**
* Restored a set of unique Scar answers to Suslov and Cold phrases.
* Restored a unique Scar answer to the long starting dialogue with Suslov after returning to CS base after second emission happens.
* Restored a dialogue with Flea Market night trader where you got to convince him you're trustworthy before trading.
* Made Duty Scar neutral towards bandits and Bandit Scar neutral towards Duty in order to restore two dialogues about switching factions. Duty — Bandit relationship has been left unchanged.

**Graphics and visuals:**
* Restored Clear Sky stalker models from Build 3120.
[+] Made own icons to fix incosistency between NPC visuals and icons due to the lack of those in Build 3120 and lack of any further builds where these icons might be present.

OPTIONAL ADDONS
=======
**Alternative Text:**
Changes raw development text written by programmers for the cut quests to the one that is way richer in details. This is the way the text would have been if game designers were ever rewriting it for final game.
It changes the dialogue of getting the quest on retrieving the migration map and the dialogue of giving the map to Inquisitor.

INSTALLATION
=======
1. Ensure there is no 'gamedata' folder in your game directory - Clear Sky Uncut is incompatible with other mods unless you know how to merge them manually.
2. Put 'gamedata' folder from the archive in your game directory.
3. Navigate to the folder with sounds of your language and transfer the 'gamedata' folder from there to your root directory as well.
4. Navigate to optional addons folder, pick the ones you'd like to have and, again, copy the 'gamedata' folder from there to where your game lies.

SPECIAL THANKS
=======
**Decane** — huge help with getting xr_smartcover scheme to support def_state_moving parameter.
**JoeJack** — huge help with writing for alternative text optional addon.
**Nemrtvi** — a lot of work done going through the text files finding unused strings.
**OGSM Team** — for porting B3120 models into the final game format.