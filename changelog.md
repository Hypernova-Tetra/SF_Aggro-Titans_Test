# **Aggro-Titans Blackscreen Removal** - 2026.03.03



#### ***Aggro-Titans***

* Going for a March 2026 release I suppose... Didn't think it'd take this long.



###### ***Aggro-Titans*** *(Test) **1.4***

* ***(R-18 Changes)***
* Added Sonic Power Boost scene that now starts and ends more quickly.
* Small animation tweaks in bo1xxx.pac
* Fixed Sonic's position after Giganto's Phase 2 event(s) end to patch a bug that occurred after implementing the Skip Cutscene feature.
* Wyvern's Missile, Psycho, and Finish QTEs now start and end more quickly.
* Custom Wyvern events in Battle Rush and Boss Rush also start and end more quickly.
* Knight's Phase 2 event now starts more quickly.
* Knight's Shieldride event now ends more quickly when succeeding the QTE prompt.
* Knight's Shieldride02 event has been tweaked slightly.
* Supreme's intro cutscene and extended intro now start and end more quickly.
* Some HMM files have been tweaked.
* **R-17 Changes**
* Any time an event name is added or changed, "Bosscommon.pac" is updated to accommodate its updated "mlevel" file for said changes.
* "Giant01.hmm" script updated to include RNG for Giganto's knockback counter swipe attack for Boss Rush only.
* Giganto Howl attack updated. Now will play a different animation in Phase 2.
* Event files for "knight01" received an update.
* Fixed an error with an attack animation in where Knight stops moving permanently.
* Fixed an error in transformation cutscene where certain particles still persisted when the extended animation played.
* The original Final Sword QTE for Knight (zev\_knight\_atk\_sp01) has been readded for base Story "Chaos Island"
* The new Final Sword QTE that restores an unused camera pan has been moved to Boss Rush Chaos Island.
* The new Final Sword QTE's first prompt type updated from "PressPrompt" to "Red Circle".
* The new Final Sword QTE event file has been renamed (to zev\_knight\_atk\_sp03) and updated camera shot of Sonic kicking the sword.
* Certain other QTE prompts may have had their button prompts changed.
* Renamed internal files for unused Supreme Grand Slam cutscene name.
* "Rifle01.hmm" script file updated to fix up some Dynamic event cycles when performing certain actions.
* Fixed position offset errors causing the first "Winglaser" cutscene to take a while to transition back to gameplay.
* **R-16 Changes**
* Further adjustments to some event and boss pac files.
* "Giant01.hmm" script updated to where a scene file may play a different version based on whether or not "Boss Select" mod is active and added RNG to
* "Dragon01.hmm" script updated to add a script that resets certain memory values related to Wyvern back to their default if Wyvern's object isn't loaded.
* "zev\_dragon\_sp\_missile" file updated to remove certain Near-Far settings to fix issues with Cyberspace Skybox mod rendering improperly.
* "bo3xxx.pac" file updated for scene "bo3160" to fix the same issue above.
* "BossRush.hmm" script updated to add in "Time of Day" parameters differences based on whether or not "Boss Rush Cyberspace" mod is active.
* Updated Unused Cinematic Grand Slam script to fix an error in which the scene does not trigger properly and having this option selected crashes the game when attempting to parry Riflebeast's shield tackle attack.
* **R-15 Changes**
* Updated "bossconfig" to remove the option for Giganto's "Blue Rings", now they only show in base and Battle Rush Kronos Island while disappearing in Boss Rush (Master King Trials) Kronos.
* Further animation adjustments to the "Oops All Bitlaser" QTE preset, new animations added to certain files.
* **R-14 Changes**
* Updated several QTE files across all 3 Presets for Supreme. Animation changes, polish, etc.
* Updated "bosscommon.pac" for updated mlevel entries.
* Fixed an issue where Wyvern's custom Phase 2 Grand Slam would crash the game.
* Updated initial "Winglaser" QTE animation.
* **R-13 Changes**
* Fixed an issue with Giganto's Phase 2 scene not being able to be skipped in base story Kronos Island.
* Updated "bo2xxx.pac" in where the cutscene of Sonic latching on to Wyvern and being flung off before the road segment starts and ends more quickly.
* Updated Wyvern and Knight's pac files for animation tweaks.
* Resolving RNG script for Wyvern's scratch and counter attack issues.
* Resolved certain issues involving incorrect dvscene parameter values, causing sounds not to play, or the game crashes when loading the scene.
* Custom Event: "Winglaser v2" file updated with new animation.
* Updated "bo6xxx.pac"
* **R-12 Changes**
* Giant01 HP updated: 250k -> 300k
* Dragon01 HP updated: 275k -> 325k
* Knight01 HP updated: 300k -> 350k
* Updated bo3xxx.pac to resolve transition issues.
* Updated "shieldride02\_aerial" event file.
* Rifle01 HP updated: 333k -> 385k (Base Story) / 350k -> 400k (Another Story)
* Updated Bitlaser01 and laser01 event files.
* RifleBeast HP updated: 367k -> 420k
* **R-11 Changes**
* Fixed an error in Wyvern's Grand Slam that caused the game to crash.
* Updated "bo4xxx" and "bo6xxx"
* Updated Giganto's dynamic script files to change the defeat scene based on stage ID.
* Updated Rifle01.pac to update asm file to include new state names.
* Updated Supreme's dynamic script files to bugcheck and add RNG to Supreme's Sp02 animation.
* **R-10 Changes**
* Updated Sound Effects for Riflebeast in "Sound Edit" to add extra Sonic grunts. (And only Sonic, no Eggman grunts.)
* **R-09 Changes**
* Update to Riflebeast's "Final Blow" QTE files to fix an error with transitioning to either the next scene or back to gameplay when failing.
* Readded "Bossbit.hmm" for Supreme after it went missing previously.
* **R-08 Changes**
* Adjustments to Knight's "sonic\_damage01" and custom "sonic\_damage02" event files.
* Fixed an error with one of Supreme's attack move set scripts.
* **R-07 Changes**
* Adjustments to Script files again, merged Dynamic files with Boss hmm files.
* Adjustment to a QTE in "Vanilla Restored" preset to fix an error.
* **R-06 Changes**
* Adjustments to bo6xxx.pac's animation files.
* Further adjustments to Supreme's QTE Preset 1 (Vanilla Restored) files.
* **R-05 Changes**
* Several animation adjustments made to Supreme's QTE Preset files.
* Updated "bosscommon.pac" for new scene entries.
* Updated Giganto and Supreme's Dynamic script files.
* Updated Supreme's Attack Moveset scripts.
* **R-04 Changes**
* Updated Supreme for moveset adjustments.
* **R-03 Changes**
* Update to Riflebeast's custom Grand Slam files.
* Updated Riflebeast's pac file.
* **R-02 Changes**
* Readded several mod files to fix issues.
* Clean-up for file size optimization.
* **R-01 Changes**
* Several small tweaks.
* Added missing .usm files.
* **R-00 Changes**
* Revamped Monologue option, now runs on HMM code with new scene files based on selected option combinations.
* Overhauled HMM scripts
* Updated Riflebeast QTE files for "Final Blow" and "Parry Miss"
* Updated Riflebeast Grand Slam Files.
* Updated "bo6xxx" file.
* Additional changes to Giganto and Supreme.
* "Bosscommon.pac" updated to include new scene entries for Monologue option.



###### ***Aggro-Titans*** *(Test) **1.39***

* **R-02 Changes**
* Another round of changes
* Readded "zev\_sp\_riflebeast" for skin mods using "SuperSonicDamage" and "SuperSonicCyber" assets.
* **R-01 Changes**
* Updated Version String
* Updated "mod\_files.txt"
* **R-00 Changes**
* HMM Script changes to Dynamic Event files for the Titans.
* Removed unneeded usm files.
* Changes to Giganto, Supreme, bo6xxx, Bitlaser01, and other files.
* Changes to Knight's formerly unused "ShieldRide02\_aerial"
* Changes to Knight's bo3xxx file.
* Changes to Supreme's "zev\_rfl\_sp02" file.
* Changes to audio files for Knight and Supreme.



###### ***Aggro-Titans*** *(Test) **1.38***

* Supreme's QTE dynamic script rewritten by GordonRamsy (Huge Thanks)
* Some adjustments to "Dynamic" files for the other Titans.



###### ***Aggro-Titans*** *(Test) **1.37***

* **Giant01 Changes**
* Updated Giganto's ImmediateActions between base game and Master King Trials
* Changes to "AT\_HOWL" in where the attack itself will now play sound effects.
* Changes to "AT\_COUNTER\_SP\_01" in where '@attack\_counter\_bite\_end.cam-anim' is now more accurate to the Frontiers 2021 Beta leak footage.
* Implemented a leftover action for "AT\_COUNTER\_SP\_03" in Master King's Trial for Giganto to play a previously unused laser attack animation.
* Giganto Finale option adjusted.
* "Tru-Blu Giganto Finale" moved to Master King's Trial.
* "Tru-Blu Giganto Super Sonic Transformation" added for Master King's Trial.
* "BOI's animation" for Super Sonic added and will play in Main story Kronos.
* "Vanilla" Super Sonic scene will play in Battle Rush only.
* Adjustments made to GiantDynamics.hmm
* **Dragon01 Changes**
* "BOI's animation" for Super Sonic added and will play Master King's Trial.
* "Vanilla" Super Sonic scene will play in Battle Rush and Main Story.
* "Dragon\_Finish\_00" moved to Master King's Trial.
* **Knight01 Changes**
* "BOI's animation" for Super Sonic added and will play Master King's Trial.
* "Vanilla" Super Sonic scene will play in Battle Rush and Main Story.
* **Rifle01 Changes**
* Changes to "AT\_SP02" in where the starting Mega Laser attack animation has been updated to keep its uniqueness.
* Small changes to some of Supreme's "giantPhase" actions.
* Updated "WingLaser" QTE files. They should hopefully take less time for the event to start.
* Winglaser's config option is now in code form rather than folders.
* Winglaser's config now has an "Off" option to play a different event instead, but will only occur when Supreme reaches low health.
* New "Bitlaser03" scene implemented for first encounter.
* **RifleBeast Changes**
* In bo6xxx.pac: Reduced loading time for Riflebeast Cutscenes bo6110, bo6125, bo6130, bo6140, bo6150, bo6160, bo6190 and its variants for the FH Monologue option.



###### ***Aggro-Titans version Big3 (Separate download)***

* Giganto, Wyvern, and Knight are a mod built from version 1.37.
* Includes Kronos Reimagined support for Giganto.
* Ares Reimagined works as is without any additional changes.
* Certain Adjustments were made for Giganto, see patch notes 1.37.



###### ***Aggro-Titans version Rifle (Separate download)***

* Standalone build for Supreme with support for "Kronos Reimagined" and "Kronos with Ares Island Reimagined" mods.
* Removed "QTE" presets in this build in place of a folder config for "Default" and "Reimagined" Ouranos Island option.
* Reimagined option will show relocated "ev5020", "ev5030", "ev1770", "bo4xxx", and "bo6xxx" events to reflect Supreme's battle being in the crater.
* Reduced loading times for certain cutscenes, see patch notes 1.37.



###### ***Aggro-Titans*** *(Test) **1.36***

* Further tweaks to Super Sonic 2's transformation for the "Edited" Animation type: Now references the Final Horizons Trailer camera panning when first transforming.



###### ***Aggro-Titans*** *(Test) **1.35***

* Overhauled Monologue entries, less folders, more streamlined.
* Some tweaks in bo6120, bo6165, and bo6190.
* Tweaked a combo-move for Sonic only when Supreme's "Unuse Cinematic Event" is active during Supreme's fight.



###### ***Aggro-Titans*** *(Test) **1.34***

* Fixed a typo in one of the config values
* Update Sonic 0 Ring Cutscene for Phase 2 in Supreme's fight.
* Updated bo1xxx.pac to fix some errors



###### ***Aggro-Titans*** *(Test) **1.33***

* Updated code to have "AT\_Tackle" be automatically disabled when "Unused Grand Slam Event" option is selected for Supreme.
* Added Tru-Blu animation for Super Sonic Transformation for Master King's Trial only.
* Added Tru-Blu Giganto Defeat as a 4th Option in Giganto Finale section.
* Updated scene file: "zev\_rfl\_wing.pac"



###### ***Aggro-Titans*** *(Test) **1.32***

* BossEvent.hmm and BossTitanFinish.hmm files removed.
* Added "Boss(Name)Dynamics" hmm files for their respective Titan bosses and the code for "TitanFinish" is moved to the Dynamics hmm files based on the respective Titan.



###### ***Aggro-Titans*** *(Test) **1.31***

* Updated "bo3xxx.pac" Super Sonic now shows up when the Super Sonic transformation scene transitions to the fight.
* Updated Grand Slam scene file for Riflebeast in name only for Phase 1 to avoid conflicts with Sonic skin mods.



###### Aggro-Titans version 1.3

* Bumped to version 1.3 for release.



###### Aggro-Titans (Test) 1.26

* Updated "bo1xxx.pac" includes a new Phase 2 scene exclusive to Master King's Trial courtesy of Tru-blu.
* Added a toggle option for Sonic's Animation Speed Changes
* Very small update to Supreme's subphases in Phase 1.
* Tweaked .hmm code files to iron out potential issues with performance problems.
* Tweaked BossEvent.hmm, BossRifle01.hmm, and BossRiflebeast.hmm by reimplementing certain changes based off version 1.25b and improved them with the newer changes.
* Improved Unused Grand Slam Event animation for Supreme.
* Changed Memory Address of Giganto's Beta Defeat cutscene in the mod's coding to not inflict with an unused memory address with the game.
* Lowered the HP of the Titans when using non-modded Max Stat Sonic.
* Added a toggle option to choose between Default Texture and MatiosDX's Fitting Textures mod.
* A variant of Wyvern's Psycho QTE was added that restores an unused shot. Some tweaks to Wyvern were made.
* Fixed a sound sync error in a scene.
* A slight tweak to the custom scene of Supreme's defeat.
* Supreme's Intro Cutscene config option has under-the-hood tweaks done.
* Giganto's blue rings have a toggle option.
* Wyvern Counter Laser animation tweaked. The unused version now plays at Phase 2 on either side of Wyvern



###### Aggro-Titans (Test) 1.25

* Final touches in certain areas.
* Updated Supreme's attacks.
* Phase 1 QTEs are more dynamic.
* Fixed a softlock issue.
* Fixed a crash issue with Riflebeast Tackle Attack somehow caused by activating the unused Grand Slam event for regular Supreme.
* The Ouranos Pyramid's Chaos Emerald pillar effect now disappears when in base game's Supreme fight and will respawn when reloading the save file. (Why does a mod need to address this problem)
* Sonic's 0 Ring Cutscenes (bo1180, bo2180, bo3180, and bo4180) have a Phase 2 version added.
* Fixed an issue with Riflebeast's cable asset not using the correct animation during the Darkball QTE.
* Fixed the issue in where Riflebeast's Material and UV animations didn't play properly in certain cutscenes.
* Config tweaks.
* No more confliction with other mods using "master.levels" file.
* Restored unused Cyloop Counter animation for Giganto.
* Code Tweak for Wyvern's Phase 2 cutscene when the "Skip" option is active. Reverted to Lua.Call functions to fix a lingering issue with Sonic being respawned in the wrong spot after the cutscene ends.
* Textures for Wyvern and Knight have been changed, using the "Fitting Titan Re-textures Mod" by MatiosDX. Wyvern reflects the purple-tier enemies while Knight now reflects the red-tier enemies.
* Fixed a cutscene error and did some other tweaks across different parts of the mod.
* Supreme QTE adjustments. Both Winglasers now show up in the same battle.



###### Aggro-Titans (Test) 1.24

* Slight tweaks to Rifle01 attack patterns
* Tweaked "BossRifle01.hmm" to reflect the changed attack patterns across Phase 1's immediate Actions for Final Horizon.
* Tweaked "BossEvent.hmm" so it uses less code for Supreme's Dynamic Events. No longer separated between versions of Ouranos Island.
* Removed a Lua.Call for "PlayingDiEvent" across multiple sections of code in favor of new code that achieves the same function.
* Added "Sound Overhaul" as a 3rd option to the Titan Audio settings.
* Updated code that removes Riflebeast's Tackle Attack courtesy of thej01.
* Updated Unused Grand Slam Cinematic code. (Still need to investigate an issue involving this code.)
* Reworked "Bitlaser01" and "Bitlaser02" for the "Retooled" QTE option, didn't like the old one too much.
* Very small tweaks to Wyvern, Knight, and Supreme's QTE files.



###### Aggro-Titans (Test) 1.23

* New option added in Riflebeast's config setting. (Darkball QTE) (Currently Experimental)
* Adjusted Cutscene bo6190 to fix an error.
* Fixed an oversight with code "Dynamic\_Sp02" in BossRifle01.hmm
* Fixed a 1 frame camera error in Cutscene bo4140.
* Adjusted "Counter\_Attack" RNG code for Giganto and Supreme
* Optimized .hmm code files for "Rifle01.hmm" and "BossRifleBeast.hmm" to fix instability problems in Final Horizons Ouranos Island.
  (Did I finally fix the Crash Problem on Final Horizons Ouranos Island?)
* Very small barely noticeable tweaks made to 3 animation files for Supreme.
* Fixed a Battle Rush QTE error in which a Phase 1 QTE appeared in Phase 2.
* Adjustments to Knight.
* Alternate Sword QTE added for Battle Rush.



###### Aggro-Titans (Test) 1.22

* Attempting to adjust and fix random crash issues with Riflebeast (turns out it's a memory leak problem.)
* New Sword RNG attacks for Knight in Phase 1.
* New Sword Counter Attack for Knight in Phase 2
* Adjusted scene: "zev\_parrymiss\_riflebs03"



###### Aggro-Titans (Test) 1.21

* Fixed the Edited "parrymiss" QTE having missing sounds when Riflebeast strikes Sonic to start the QTE.
* Fixed the Edited "Final Blow" Riflebeast QTE having the wrong sound effects that used different names.
* Updated "master.levels" in the Hedgehog folder.
* Small update to bo6125 and bo6190.
* Updated bo6190.usms.
* Another adjustment Supreme's Event files to implement gradual changes to the Bitlaser Event Slot for Phase 1 and 2. BIG shoutout to Holoska for this implementation.
* Adjusted Address Memory code scripts for Unused Supreme Grand Slam Event.
* Adjusted audio for Knight's Grand Slam Event Scene.
* Parrymiss QTE options updated, the "Edited" version is now a Phase 2 QTE during the fight.
* New QTE added, reuses "bo6160" for a new QTE in-place of Parrymiss for Phase 2 of The End's fight only after the player gets hit with the homing laser attack to start the cutscene of Sonic surviving The End's Dark Ball.
* Adjustments made to Wyvern's boss file and hmm code file.
* Several adjustments have been made across other hmm code files.
* Fixed Supreme from disappearing in Phase 2.
* "extra\_sound" directory added.
* Wyvern Phase 2 Grand Slam added.
* File and Code Adjustments made.



###### Aggro-Titans (Test) 1.20

* Supreme's scratch attacks are slightly faster.
* Supreme's Bit Drone projectiles have been retextured.
* Supreme's Bit Drone attacks are slightly more aggressive.
* Rearranged Supreme's QTE files.
* Updated animations to Supreme's QTEs and defeat cutscene.
* Changes to Supreme's Wing Laser QTE were made and is exclusive to Final Horizons Supreme fight.
* Converted Supreme's Grand Slam into the unused cutscene. (Doesn't do damage, but will give rings while "Combat Mods" is active.
* Final Horizons Cutscenes updated.
* bo6120: Added new effects from Sonic's stat boost cutscenes. Will be red when using the "Edited" option. Will be Red/Blue for the "Hyper\_Blue Aura" options. The Power Boost eye effect has been repositioned properly so that it better overlaps the eyes better. (Can't change their color for now though.)
* bo6165: The "blue-eye" effect for SS2 has been properly positioned to overlap the eyes.
* Giganto, Wyvern, and Knight added to the mod.
* Giganto received adjustments to restore unused attacks and have his attacks more aggressive.
* New animation for Giganto's defeat using leftover files possibly from the beta have been added.
* Giganto's "bo1xxx.pac" updated to have additional content. (Making this mod have higher priority over other mods using this file.)
* Adjusted Giganto's Sp01 attack. Giganto's "Counter\_Bite\_Start" pose was updated to utilize an unused animation file. "Counter\_Bite\_Loop" camera animation from the beta has been implemented.
* Added a small extra animation for the start of Giganto's Sp02 attack that originally wasn't there before.
* bo1120: Super Sonic's transformation cutscene is updated to include an unused animation for Super Sonic and a almost seamless transition to the fight.
* bo1150: Added as a variant for Giganto's defeat. This is primarily based off of leftover beta files left in the game.
* bo1170: Added as another variant for Giganto's defeat. This is a mixed version of the Beta and the Final's animations.
* bo1180: Added the unused "Zero Ring Warning" sound effect. Other than that, mostly remains unchanged.
* Wyvern's attack patterns are slightly adjusted.
* Wyvern's scratch attack animation and animation speed are slightly adjusted.
* Added more chances to attack Wyvern after failing to parry his attacks.
* Wyvern's "bo2xxx.pac" updated to have additional content.
* bo2120: Updated Super Sonic's transformation cutscene.
* bo2180: New animation was added when Sonic loses his rings.
* Phase 2 "Chase" after the transition cutscene has been moved.
* Parry slow effect adjusted.
* Wyvern will counter attack more times before the laser.
* New animation added in Wyvern's Missile QTE when failing.
* Wyvern's Events may change briefly after Phase 2 in the Master King's trials.
* Restored Unused "Counter\_Laser" animation if you're on Wyvern's LEFT side.
* Unused Beta-inspired Finale implemented and configurable.
* Knight's climb phase updated to have the hand slam go by a bit faster
* Knight's sword slash animations are adjusted a little. (Still in a WIP. I'll adjust them based on feedback.)
* Knight's Battle Start animation was moved in to cutscene bo3120, making the fight start sooner instead of waiting for Knight to pull his sword out.
* Knight's QTEs adjusted:
* "shieldride01": Remains unchanged for the most part in terms of its animation, but the QTE prompt is a bit faster now.
* "shieldride01\_short": Slight animation change in how Knight tosses the shield, QTE button changed, and ends early when winning the QTE.
* "shieldride02": New segment added so it's not a complete copy of "shieldride01\_short" using a new file.
* Knight's "bo3xxx.pac" updated to have additional content.
* bo3120: Updated to include Knight's Battle Start animation where he pulls the sword out.
* bo3180: New animation was added when Sonic loses his rings.
* Knight's "Grand Slam" for Phase 2 may instead play a QTE at a random chance.
* Cutscene: "zev\_knight\_sonic\_sp01\_phase2" is updated. Cylinders weren't protruding as they should be, and Sonic will punch the Titan as the final attack instead of kicking him down.
* Knight's "Sword QTE" was updated to reflect his Phase 2 appearance and adds a cut segment where the camera will pan to Sonic preparing to catch the sword.
* Master King Trials have been adjusted to reflect the new changes.
* All the above changes to Giganto, Wyvern, and Knight are automatically reflected in the MK trials since they use the same pac files.
* Rings will be granted between fights in Master King Trials.
* Added a condition to earn rings from parrying while ring count is low during the Wyvern fight.
* Giganto and Knight can also grant rings via cylooping them and Grand Slam.
* Time of Day is adjusted.
* Experimental changes to Phase 2 cutscene for Giganto, Wyvern, Knight, and base Supreme to be skippable. (Sonic's position might be affected)



###### Aggro-Titans Version 1.12

* Improved a method in which to support the mod for version 1.41.
* Fixed animation for bo6190.
* An oopsie fixed with SS2's Grand Slam animation when a certain setting was set to "Vanilla (Blue Aura)"
* Moved ev1770.usm from "Parrymiss" directories to the "RifleEnd" directories.



###### Aggro-Titans Version 1.11

* Monologue files adjustments.
* Fixing an audio problem in which the Italian voice line plays a line twice.
* Removed a code in Rifle01.hmm that overrides text in "sy4500\_026" in other languages.
* Fixed a problem with certain voice audio of Sage, Amy, Knux, and Tails playing on the left ear in bo6140's monologue "on" setting.
* Fixed a small issue with Supreme's pillars on a QTE not glowing red energy.



###### Aggro-Titans Version 1.1 (Release Feb. 01)

* Public Update Release after game update 1.42



###### Aggro-Titans (Update Beta)

* Merged Monologue Add-on with Main Mod with additional options.
* Realtime Cutscene for ev5030
* Updated Final Horizons Cutscenes
* bo6110: Adjusted opening scene where The End takes over Supreme.
* bo6120 and bo6165 (SS2): Super Sonic's eyes turn blue using a certain effect before model swapping to SS2.
* bo6120 and bo6165 (Hyper): Same as the SS2 note, with the addition of adjusted effects using Cyber Sonic's particles before he turns Hyper.
* Tweaked base Supreme's cyloop animations
* Updated Winglaser v1 and v2.
* Tweaks to Supreme's Shot projectiles after destroying drones.
* Overhauled QTE files. The RNG code will choose 1 from 2 possible events instead of 3. A 3rd QTE Preset is implemented to compensate for the rearranging of files.
* Added the original "Parrymiss QTE" animation for Hyper Sonic skin mods.
* Added code file for version 1.41: To apply just modify the "mod.ini" file to match the code file for the previous game version.
* A couple of adjustments to bo4160 - I promise this is the last time.
* Added "bo6190\_4k" to the GitHub Repo (in 30FPS, the 60 was too big for GitHub)
* Updated Rifle01.hmm to isolate affected lines of code after the 1.42 Update.
* Added "BossRifle\_SHOT2-4\_v1.42.hmm" To support the new game version.
* Added "BossRifle\_SHOT2-4\_v1.41.hmm" For those still on version 1.41. To apply this, open "mod.ini" and change the code file name to this file.
* Adjusted Monologue Descriptions.



##### **Aggro-Titans (Release Version Jan. 16)**

* Public Mod Release



###### Aggro Titans Pre-release Patches

Things that were done right when I thought I was done with the mod as a whole, but almost ended up missing a few things that I forgot to do, extending the original planned release date.

* R11: Adjusted "bo6xxx.pac". I hope it reduces lag during the SS2 transformation cutscenes.
* R10: Adjusted "Winglaser\_v1" QTE. Added effects to a Mash QTE that was missing effects in a certain area when Supreme tried to crush Sonic with his hands. Added 4k.usm files for 4k Resolution Support for Cutscenes.
* R9: Last minute fix to Shoot01 again in "Restored" option where Sonic was clipping through another "Red Circle" QTE Graphic on the 3rd shot during the slow-motion button prompt. Fixed a scene in "Retooled" option where one of the QTE prompt types didn't match. Tweaked an animation for Supreme when parrying his counter spin attack.
* R8: Tweaked a few parameters across several scenes. Reset Supreme's idle pose back to default for the time being.
* R7: Updated "Combat Mods" Hmm code option: Added "BossBitConfig.hmm"
* R6: Adjusted Supreme's Drone Homing Missile to avoid a bug where the homing missiles and Supreme's counter swipe attack making Sonic unable to parry. Slight update to Supreme's idle animation.
* R5: Fixed Shoot01 in "Restored": Sonic was clipping through the first "Red Circle" QTE graphic.
* R4: Tweaked a certain shot for cutscene bo4110
* R3: Changed cutscene bo4160.
* R2: Last minute tweaks to gun QTEs.
* R1: Further fixing QTE files so QTE inputs register properly.



###### V0.2.2

* Adjustments to Supreme's QTE files for better pacing and to cut down on length for some.



###### V0.2.1

* New Grand Slam animation for Hyper Sonic skin option when selecting "ParryMiss QTE option".
* "Zev\_Parrymiss\_Riflebeast.pac" adjusted to remove a detail that didn't quite make sense.



###### V0.2.0

* Files reuploaded to the GitHub Repo
* Tweaks and adjustments made to Boss Health and Attack Patterns to both Rifle01 and Riflebeast
* Added Holoska's code for "AT\_SHOT2" to play "Zev\_Rfl\_Sp02"
* Updated "Event/Scene/bo4xxx.pac" (For bo4110)



###### V0.1.9

* Some adjustments to Supreme's attack speed and attack patterns.
* Adjusted Supreme's "attackHomingLaser" and "attackHandLaser" parameters.
* Adjusted "immediateActions" parameters



###### V0.1.8

* Riflebeast "attackPattern" and "attackPatternAfter" slightly changed.
* Riflebeast "attackHominglaserPattern" slightly changed.
* Adjusted Winglaser\_2 slightly. Fixed a problem where the QTE didn't fail immediately on the wrong button press. Second QTE prompt changed: "TheEndVariant" -> "PressPrompt".
* Other slight changes.



###### V0.1.7

* A fix for SSCyber and SSDamage model and assets not loading in the cutscene.
* Event/Scene bo6140 (Phase2) updated. Overlapping voices of Sage, Amy, Knux, and Tails are fixed.
* Adjustment to Event/Scene bo6190 (The Finale) for Hyper Sonic skins that may include slightly altered camera angle shots and added effects when Sonic going full Cyber attacks Supreme and The End.
* Reduced file size for "bo6190.usm". Eggman's scope HUD shows up in Realtime now, but only during Eggman's glasses. The scope P.O.V. still remains pre-rendered for now. I doubt I can get the POV working for Realtime.
* Event/Scene "bo4110" is slightly updated.
* Event/Scene "bo4160" is slightly updated more changes coming soon.
* Barrier HP in Extreme Mode changed: 67 -> 50



###### V0.1.6

* Changed animation for Riflebeast's recoil animation when parrying Claw attacks.
* Changed "slowSetting" parameters for "cyloopState" when SS2 crushes Riflebeast are adjusted.
* se\_rangers\_giant04.acb file was adjusted: Sounds with the label "riflecrush" were modified to reflect changes in cyloopState listed above.
* Riflebeast's Hominglaser\_Orb base speed was adjusted. 155 -> 135
* The unused "AttackHomingLaserPatterns" (Also known as "AT\_HIMING") for "06, 07, 08, and 09" are implemented, though they're in a WIP state.
* Fixed cutscene "ev5040" where it loaded as a black screen.
* Fixed cutscene "ev6030" where it loaded as a black screen. Another adjustment was made to the location of Eggman and his computer console. The scene is located at the start of Ouranos Island as a temporary workaround until I figure out a way to load Chaos Island's assets to get him in his proper spot.
* ev1770 and ev5020 use the Beta Super Sonic transformation effects.
* "Boss\_Bit\_Param" was adjusted. 2 attacks from the drone's attack patterns have their order swapped.
* "smallbit\_Laser" rotation speed adjusted. Is now the 1st drone attack that occurs when the fight starts. Before it was the 3rd attack.
* "smallbit\_Homing" homingDelay and homingAccuracy slightly adjusted. Is now the 3rd attack that the drones do in order. Before it was the 1st attack.
* Event/Scene "Zev\_rfl\_Sp02" in Retooled option received animation updates during the fail scene.
* Event/Scene "Zev\_rfl\_Shoot01" and "02 in "Retooled" Option (The extended Bitlaser01 and 02 animations) received an animation update: Extended frames during the QTE button mash phase. Different fail animation implemented depending on if the wrong button was pressed or no button was pressed, timing out the chance to win the QTE.
* Updated "Winglaser\_2" animation
* Changed the "flyMoveCircleRadius" parameter so that he doesn't fly too far away and end up stuck against the Ouranos pyramid temple with no way to reach him, soft-locking he fight.
* "@attack\_counter\_bite\_start" and "bite\_dead" cam-anim files (for Supreme) are properly working now.
* Low HP phase for og Supreme's attack pattern slightly adjusted.



###### V0.1.5

* Optimized certain QTEs related to Shoot02 and its variants across the mod to load quicker in the fight.
* Fixed Winglaser\_2 QTE's second input auto failing due to incorrect timescale parameter.
* Changed Supreme's "immediateActions" or rather what the asm file calls "counterPose" animation.
* New short QTE animation for the "Restored" option during Phase 1.
* Supreme's @attack\_counter01 animation file swapped with @attack\_counter04.



###### V0.1.4

* Rearranged files
* Adjusted Red Circle QTE on "Zev\_Blow" for Fixed Vanilla option
* Small Adjustment to the "Winglaser\_2" QTE (This is still being worked on)
* Added some effects to the QTE scene from file "test\_qte\_sample"
* Fixed incorrect Resource Pointer from "Zev\_rfl\_Sp02"
* Adjusted "bo6xxx.pac" for the Hyper Sonic skin option as it was an outdated version of what I used for the Monologue mod.
* "Zev\_rfl\_Shoot01" had an issue with Sonic being in the wrong spot when failing parts of the QTE. So this scene was updated with new fail scenes.



###### V0.1.3

* Patched Rifle01.pac
* Added and revised certain Final Horizons QTEs to support Hyper Sonic's blue outline
* Final Horizons Monologue Mod update coming soon.
* Fixed Mod.ini



###### V0.1.2

* Tweaked some things.
* Fixed a soft lock from incorrect Resource Pointer parameters related to Shoot02
* Fixed a soft lock from "immediateActions" triggering "AT\_Bit\_Wave" in which Supreme will lock himself after spawning his drones.



###### V0.1.1

* Updated Combat Mod Option. Now converted to HMM code for reduced file size.



###### V0.0.0

Work In Progress

