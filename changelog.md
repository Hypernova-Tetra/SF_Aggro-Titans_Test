## Aggro-Titans Starfall

* Some time before August 15.



##### Aggro-Titans (Test) 1.25

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



##### Aggro-Titans (Test) 1.24

* Slight tweaks to Rifle01 attack patterns
* Tweaked "BossRifle01.hmm" to reflect the changed attack patterns across Phase 1's immediate Actions for Final Horizon.
* Tweaked "BossEvent.hmm" so it uses less code for Supreme's Dynamic Events. No longer separated between versions of Ouranos Island.
* Removed a Lua.Call for "PlayingDiEvent" across multiple sections of code in favor of new code that achieves the same function.
* Added "Sound Overhaul" as a 3rd option to the Titan Audio settings.
* Updated code that removes Riflebeast's Tackle Attack courtesy of thej01.
* Updated Unused Grand Slam Cinematic code. (Still need to investigate an issue involving this code.)
* Reworked "Bitlaser01" and "Bitlaser02" for the "Retooled" QTE option, didn't like the old one too much.
* Very small tweaks to Wyvern, Knight, and Supreme's QTE files.

##### Aggro-Titans (Test) 1.23

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

##### Aggro-Titans (Test) 1.22

* Attempting to adjust and fix random crash issues with Riflebeast (turns out it's a memory leak problem.)
* New Sword RNG attacks for Knight in Phase 1.
* New Sword Counter Attack for Knight in Phase 2
* Adjusted scene: "zev\_parrymiss\_riflebs03"

##### Aggro-Titans (Test) 1.21

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

##### Aggro-Titans (Test) 1.20

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

##### Aggro-Titans Version 1.12

* Improved a method in which to support the mod for version 1.41.
* Fixed animation for bo6190.
* An oopsie fixed with SS2's Grand Slam animation when a certain setting was set to "Vanilla (Blue Aura)"
* Moved ev1770.usm from "Parrymiss" directories to the "RifleEnd" directories.

##### Aggro-Titans Version 1.11

* Monologue files adjustments.
* Fixing an audio problem in which the Italian voice line plays a line twice.
* Removed a code in Rifle01.hmm that overrides text in "sy4500\_026" in other languages.
* Fixed a problem with certain voice audio of Sage, Amy, Knux, and Tails playing on the left ear in bo6140's monologue "on" setting.
* Fixed a small issue with Supreme's pillars on a QTE not glowing red energy.

##### Aggro-Titans Version 1.1 (Release Feb. 01)

* Public Update Release after game update 1.42

##### Aggro-Titans (Update Beta)

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

# Aggro-Titans (Release Version Jan. 16)

* Public Mod Release

##### Aggro Titans Pre-release Patches

Things that were done right when I thought I was done with the mod as a whole, but almost ended up missing a few things that I forgot to do, extending the original planned release date.

* R1: Further fixing QTE files so QTE inputs register properly.
* R2: Last minute tweaks to gun QTEs.
* R3: Changed cutscene bo4160.
* R4: Tweaked a certain shot for cutscene bo4110
* R5: Fixed Shoot01 in "Restored": Sonic was clipping through the first "Red Circle" QTE graphic.
* R6: Adjusted Supreme's Drone Homing Missile to avoid a bug where the homing missiles and Supreme's counter swipe attack making Sonic unable to parry. Slight update to Supreme's idle animation.
* R7: Updated "Combat Mods" Hmm code option: Added "BossBitConfig.hmm"
* R8: Tweaked a few parameters across several scenes. Reset Supreme's idle pose back to default for the time being.
* R9: Last minute fix to Shoot01 again in "Restored" option where Sonic was clipping through another "Red Circle" QTE Graphic on the 3rd shot during the slow-motion button prompt. Fixed a scene in "Retooled" option where one of the QTE prompt types didn't match. Tweaked an animation for Supreme when parrying his counter spin attack.
* R10: Adjusted "Winglaser\_v1" QTE. Added effects to a Mash QTE that was missing effects in a certain area when Supreme tried to crush Sonic with his hands. Added 4k.usm files for 4k Resolution Support for Cutscenes.
* R11: Adjusted "bo6xxx.pac". I hope it reduces lag during the SS2 transformation cutscenes.

##### Aggro-Titans V0.2.2

* Adjustments to Supreme's QTE files for better pacing and to cut down on length for some.

##### Aggro-Titans V0.2.1

* New Grand Slam animation for Hyper Sonic skin option when selecting "ParryMiss QTE option".
* "Zev\_Parrymiss\_Riflebeast.pac" adjusted to remove a detail that didn't quite make sense.

##### Aggro-Titans V0.2.0

* Files reuploaded to the GitHub Repo
* Tweaks and adjustments made to Boss Health and Attack Patterns to both Rifle01 and Riflebeast
* Added Holoska's code for "AT\_SHOT2" to play "Zev\_Rfl\_Sp02"
* Updated "Event/Scene/bo4xxx.pac" (For bo4110)

##### Aggro-Titans V0.1.9

* Some adjustments to Supreme's attack speed and attack patterns.
* Adjusted Supreme's "attackHomingLaser" and "attackHandLaser" parameters.
* Adjusted "immediateActions" parameters

##### Aggro-Titans V0.1.8

* Riflebeast "attackPattern" and "attackPatternAfter" slightly changed.
* Riflebeast "attackHominglaserPattern" slightly changed.
* Adjusted Winglaser\_2 slightly. Fixed a problem where the QTE didn't fail immediately on the wrong button press. Second QTE prompt changed: "TheEndVariant" -> "PressPrompt".
* Other slight changes.

##### Aggro-Titans V0.1.7

* A fix for SSCyber and SSDamage model and assets not loading in the cutscene.
* Event/Scene bo6140 (Phase2) updated. Overlapping voices of Sage, Amy, Knux, and Tails are fixed.
* Adjustment to Event/Scene bo6190 (The Finale) for Hyper Sonic skins that may include slightly altered camera angle shots and added effects when Sonic going full Cyber attacks Supreme and The End.
* Reduced file size for "bo6190.usm". Eggman's scope HUD shows up in Realtime now, but only during Eggman's glasses. The scope P.O.V. still remains pre-rendered for now. I doubt I can get the POV working for Realtime.
* Event/Scene "bo4110" is slightly updated.
* Event/Scene "bo4160" is slightly updated more changes coming soon.
* Barrier HP in Extreme Mode changed: 67 -> 50

##### Aggro-Titans V0.1.6

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

##### Aggro-Titans V0.1.5

* Optimized certain QTEs related to Shoot02 and its variants across the mod to load quicker in the fight.
* Fixed Winglaser\_2 QTE's second input auto failing due to incorrect timescale parameter.
* Changed Supreme's "immediateActions" or rather what the asm file calls "counterPose" animation.
* New short QTE animation for the "Restored" option during Phase 1.
* Supreme's @attack\_counter01 animation file swapped with @attack\_counter04.

##### Aggro-Titans V0.1.4

* Rearranged files
* Adjusted Red Circle QTE on "Zev\_Blow" for Fixed Vanilla option
* Small Adjustment to the "Winglaser\_2" QTE (This is still being worked on)
* Added some effects to the QTE scene from file "test\_qte\_sample"
* Fixed incorrect Resource Pointer from "Zev\_rfl\_Sp02"
* Adjusted "bo6xxx.pac" for the Hyper Sonic skin option as it was an outdated version of what I used for the Monologue mod.
* "Zev\_rfl\_Shoot01" had an issue with Sonic being in the wrong spot when failing parts of the QTE. So this scene was updated with new fail scenes.

##### Aggro-Titans V0.1.3

* Patched Rifle01.pac
* Added and revised certain Final Horizons QTEs to support Hyper Sonic's blue outline
* Final Horizons Monologue Mod update coming soon.
* Fixed Mod.ini

##### Aggro-Titans V0.1.2

* Tweaked some things.
* Fixed a soft lock from incorrect Resource Pointer parameters related to Shoot02
* Fixed a soft lock from "immediateActions" triggering "AT\_Bit\_Wave" in which Supreme will lock himself after spawning his drones.

##### Aggro-Titans V0.1.1

* Updated Combat Mod Option. Now converted to HMM code for reduced file size.

## Aggro-Titans V0.0

Work In Progress

