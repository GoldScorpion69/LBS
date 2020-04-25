## Introduction

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

Hello, my callsign is Cacophony and I got into modding as a teenager purely for the purposes of applying nudity. For a long time that was my only goal... until the modding communities surrounding Skyrim evolved. From there I branched out, building the TUCOGUIDE, Lexy, morphing Lexy into LOTD Plus, and finally discovering Wabbajack and spending almost all of my time either starting a new list or changing one I or someone else had made. With the discovery of Lover's Lab, I found out through much pain and torture that usually porn doesn't work well with playing Skyrim and playing Skyrim doesn't mesh well with playing porn and I lacked the skill to change that. So I solved it by simply paring back my ambitions.

If you want the gist of what this horribly cribbed modlist is, it grew out of the two most common questions I heard in the Lexy Discord's NSFW channel: how do I add SexLab to this? And: how do I switch the body to CBBE? I quickly came to realize that you don't do either of these things... unless you want a broken list that would have been more easily built from the ground up. So I did just that, keeping the parts of Lexy that I liked (which was the vast majority of it), throwing in a few other things to the mix, and adding some options to sex things up for both male and female characters. Hopefully this will take the heat off other modlist authors Discord channels and maybe even tide us over until erri120 gets around to finishing Lotus and we can descend into the pure depravity we all crave. Without further ado I present to you the Light Sexy Modlist: Please Stop Bothering Other Modlist Authors Edition.

## Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)

You can also install any Wabbajack Modlist without a Nexus Premium account but you will have to download each file manually. 

### System Specs

A note here. I use a 1080p monitor and I suspect the vast majority looking to play Skyrim in this day and age do too. So this modlist is geared toward two things: low VRAM usage and quick load times. You shouldn't need more than a decent CPU and GPU from the last 5 years along with 8 GB VRAM and maybe 16 GB RAM (might could get away with 8). Strongly recommended is a solid state drive with at least 100 GB for the game itself and 50GB for the downloads (unless you never plan to update).

## Installation

This section was stolen from Lotus. Sorry, erri.

### Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Steam Config

##### Disable the Steam Overlay

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox.

##### Change Steams Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

##### Set the Game language to English

Wabbajack will check your game files and make sure that we have the same version. This also means that any other language than English will fail the installation.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/`. You can also use [Skyrim Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133) br trawz that will clean your installation.

#### Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1) Click on _Ultra_
2) Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3) Set _Antialiasing_ to _Off_
4) Uncheck _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

### Using Wabbajack

#### Preparations

Let's get to the actual installation. Grab the latest release from [GitHub](https://github.com/erri120/lotus/releases).

Download the release to a _working folder_. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [GitHub](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1) Open Wabbajack
2) Load the Modlist from Disk
3) Adjust the download and installation paths
4) Click the Go/Begin button
5) Wait for Wabbajack to finish

#### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you loose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

#### Copy Game Folder Files

Download the latest ENB Series from [here](http://enbdev.com/download_mod_tesskyrimse.htm) and copy `d3d11.dll` and `d3dcompiler_46e.dll` to your game folder.

Copy the following files from the `MO2/Game Folder Files` directory to your game folder:

- `enbseries/*`
- `binkw64.dll`
- `d3dx9_42.dll`
- `enblocal.ini`
- `enbseries.ini`
- `skse64_*`
- `tbb.dll`
- `tbbmalloc.dll`

#### A note on BodySlide

My taste in BodySlides is as fickle as the wind... not only do I alternate between the naturalistic "Dream Girl" and something on the far end of - t h i c c - I also constantly change body types between UNP and CBBE depending on my mood or what armor mod I'd like to look at. For now everything is built with a custom "3BBB Cacophony thicc" body but it is entirely customizable. If you want to change this, pop into the NSFW channel and ask me.

## Updating

If this Modlist receives an update, check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## A Few More Specific Notes

I'm not going to get deep into the weeds on all the mods included because quite frankly there's not anywhere near the amount of detail in this list as a lot of them and I don't think most of the people seeking to try this have a desire to read much about it. But here I will note a few things. My primary goal in creating this list was to play a super expanded LOTD with almost all of the huge worldspace mods like Falskaar, Wyrmstooth, Vigilant, etc included. I also wanted plenty of weapons and items to find organically without adding a bunch of collectibles that don't appeal to me. Does anybody ever find every collectible without looking them up? Doesn't that kinda defeat the purpose? Anyway, I speculate here. Most of the visuals, character development and gameplay mechanics are either cribbed from Lexy or strongly resemble Lexy with the exception of TUDM The Ultimate Dodge Mod. I guess that's all I have to say about that.

I did NOT include creature support not only because it's not my thing but because I wanted to use the Nemesis Behavior Engine without having to shoehorn FNIS in there too. I also did not include Devious Devices or any of its soft dependencies like Cursed Loot because only someone with more modding experinece than me would know how to get those to stay stable in the long term. Hell I've run a list with nothing but ZaZ, DD, and Cursed Loot on Oldrim (their native soil) and have my save crap itself with guards attacking me in an infinite bondage prison loop within 12 hours of starting a new game so ¯\_(ツ)_/¯

### Be A Casanova, Not A Maquis De Sade

The primary and most visible SexLab mods you'll be able to see are Amorous Adventures and Amorous Adventures Extended. These add hilarious meme-worthy sexy quests to a lot of the biggest female NPCs in Skyrim (including poor Elisif) and not only that, original voice assets are mixed and matched to give complete voiceover support to the custom dialogs. The next biggest one is SLEN - SexLab Eager NPCs which allows for a customizable seduction system. To round out the mix is SexLab Solutions which adds a bunch of ways to complete quests by either sexing them up yourself or offering one of your followers in case you're not into the target in question.

## Defeat

Yes, Defeat is in here. Yes, I have a setup for it ready to go. No, you won't see it a lot unless you change it yourself. The long and short of it is, if you want to see yourself getting taken advantage of every time you lose, under "Player as Victim" set yourself to "Essential." If you don't want to be taken advantage of at all and prefer a quick, merciful death, disable the victim section completely. This will still allow you to sublimate your fantasies harmlessly into Skyrim by tying people up and putting them in bags for later (ab)use.

### Camera

I included the vastly inferior IFPV because I've got it defaulting to off so it doesn't muck with gameplay. You have to hit Numpad 0, then F a couple times to switch it on. It doesn't work at all when the partners are really close together (too much clipping) but it at least gives you a quick default to setting up your own POV view with Numpad 3. Relax and enjoy on it. Honestly I use this more to take a quick look down at my own huge bouncy boobs. :3

#### General Skyrim Gameplay

Most of the actual Gameplay of this modlist is cribbed, again, from Lexy so if you're at all familiar with that setup you'll be right at home here. One thing I did add was the Ultimate Dodge Mod for a script-free instantaneous dodge roll (or step, or both) so you can still get away quickly after you install all 7 of those Lover's Lab NPC scanning nightmarish cloak script frameworks you're just dying to add. Just kidding, I love you. One thing I left out was the tedium and yes, cloak scripting of Needs mods so if you want to freeze, starve, and dehydrate you'll have to do it on your own list. I did add CACO and CCOR for the fun of building lotsa stuff that's overpowered. I'm helping!

#### Bodies and NPCs

For the bodies I used CBBE 3BBB with the custom 3BBB Cacophony preset. This can be rebuilt to your liking using BodySlide if you want to drop by the NSFW channel. Note that leaving SMP on is NOT recommended because that physics mod was never completed and has a memory leak, to the best of my knowledge. The longer you leave it on the more likely it will crash, especially in combat, and then you have to restart Skyrim unless you like looking at non-Euclidean objects. Anyway you can switch between 3BBB and the friendlier but less flashy CBPC by pressing Numpad +. For the NPCs just trust that they're pretty, I'm lazy, and I haven't seen any BFBs (brown face bugs) yet. Everyone wearing vanilla clothes or armor has been outfitted with "super sloot" courtesy of Bad Dog so that makes this list decidedly unwelcome among mixed company. Play it alone! If you want to hide your shame, or simply muh immersion at the idea of Mjoll walking around with all four cheeks on display, stop by NSFW and I'll tell you how to get everyone to cover up their meat. The armor from the worldspace mods like Falskaar has been left unchanged.

#### Final Notes

LODs HAVE NOT BEEN RUN. I don't want to do it until a little testing is done. I had 17 hours on this modlists previous version before a bunch of stuff updated and that had LODs, but c'est la vie. I'll get to it eventually.

This modlist is ugly. I used The Method on the whole thing for maximum compatibility but didnt merge anything to ensure easy expandability. So there are like 100 ESLs and far more modgroups. Don't open xEdit (SSEEdit in MO2) unless you know what you're doing. If you want to add something either have me write a patch for it or ask me how because my mind is not as other minds.

## In-Game MCM Options

None of this is written in stone, these are just the settings I use. Play freely with great abandon on all the sexy stuff. Consider carefully any gameplay changes because with just a couple of them you can make things either really hard or really easy. I myself don't have the balance perfect, bandits and dragons crush me but I generally walk through everything else.

**Wait until no new messages appear in the top left corner!**

If you get no more messages, save the game and open the MCM.

### 3PCO - 3rd Person Camera Overhaul

**Melee**:

(Personal preference, I like to keep the camera somewhat close to the character. Try different values adn find what feels best to you!)

*Positive X Offset* - `60`

*Negative X Offset* - `60`

### AGO

**Settings**:

Enable/Disable

*Persistent Arrows* - `Disabled`

### Bestial Essence

**Settings**:

*Controller Vibration During Sex* - `Disabled`

(If you don't want Creature animations use the `Fade to Black During Sex` options or don't play this quest)

### Blush When Aroused

**General**:

Compatibility

*SexLab Aroused Redux* - `Enabled`

**Cause and Effect**:

Player

*Nakedness* - `Enabled`

NPCs

*Nakedness* - `Enabled`

**Exceptions**:

Player types

*Victims blush* - `Enable`

NPC types

*Victims blush* - `Enable`

### CBBE 3BBB Addon

Player Use Set

*Player Use Slot*: `60 - Devious Devices Compatible`

You can either use a hotkey (`Numpad -` by default) or a spell to toggle the Physics for the player.

*Add Player 3BBB Physics Toggle Spell*: `Enable`

Exit the MCM, go to your Spells Menu and use `3BBB Physics Toggle - Player`

### Dogma - Thief

**System**:

*Schlongs animation* - `Enable`

*Schlong size* - `Enable`

*SFX* - `Disable`

*Blush* - `Disable`

*Squirting* - `Disable`

*Fade* - `Enable`

*Unequip shoes* - `Disable`

*Notes by the author* - `Enable`

*Sound Effects* - `New`

**Thief**:

Settings

*Tips* - `Enable`

*Achievement notifications* - `Enable`

*Checkpoint Autosave* - `Disable`

*Overlays* - `Disable`

### FNIS PCEA2

**Available Animation Collections**:

*Female* - `Enable` if player character is female

*Male* - `Enable` if player character is male

Click `Refresh PCEA2 animations NOW`, exit and reopen the MCM.

### Follower Framework

**Activity**:

Sandboxing

*Ignore Special Furniture* - `Enabled`

*Stop During Player Dialogue* - `Enabled`

*Only Sandbox in Town* - `Enabled`

*Only Sandbox in Non-Dungeon* - `Enabled`

**System**:

Hotkeyed Abilities

(You don't have to assign any hotkeys if you want. As a [Republic Commando](https://store.steampowered.com/app/6000/STAR_WARS_Republic_Commando/) lover, I like to assign the F1-F4 hotkeys)

*Command Followers* - `F4`

*Calm Followers* - `F1`

*Followers Retreat* - `F3`

*Followers Attack* - `F2`

### Forgotten Wenches

**Forgotten Configuration**:

Ondeath Summon Chance

*Forgotten Wench Spawn* - `25% Chance`

### Growl Werebeasts

**Features**:

*Invulnerable During Transformation* - `Enabled`

### Hateful Wenches

**Hateful Configuration**:

Summon Undead Wench Spell

*Draugrs* - `20%`

### Judgment Wenches

**Judgment Configuration**:

Judgment Wenches spawn chance.

*Judgment Wench* - `20%`

### Poser Hotkeys

**Hotkeys**:

Make sure to use the *Enable/Disable All Hotkeys* button when you're not using this pose mod! It is important that *Hotkey Status* says `Hotkeys are Disabled`. If you see `Hotkeys are Enabled` exit the MCM and press the hotkey for *Enable/Disable All Hotkeys*.

### Quick Light

(Brightness can be adjusted to whatever you like)

*Brightness* - `Wide`

(Personal preference, I like to disable the light key and just use `E`.)

*Set light key* - `ESC`

*Long press time for activate key* - `1.5s`

### Sacrosanct Vampires

**Vampire Spells, Powers and Abilities**:

*Fortitude*: `Disable`

### Schlongs of Skyrim

**General Settings**:

Global Settings

*SOS Potions* - `Disabled`

### Sky UI

(Sky UI keeps bitching about the map sfw being outdated. This can be ignored and disabled.)

**Advanced**:

SWF Version Checking

*Map Menu*: `Disable`

### SSSO

*Rotating Automatic Save* - `Enabled`

*Auto Save Count* - `5 Slots`

*Delay Before Exit Game* - `7 Seconds` (might be set higher if you have a slow drive)

### Storm Lightning

**Presets**:

Click `Realistic`

**Advanced**:

*Compatibility Mode* - `Enabled`

### TK Dodge

Control Settings

*Dodge Key* - `V` (set this to whatever you like)

*Double Tap input* - `Disable` (personal preference)

Other Settings

*Stamina Cost* - `7.0` (choose something between `5.0` and `10.0`)

### Ultimate Combat

**General**:

Stagger

*Enemy Poise* - `Disabled`

*Player Stagger* - `Disabled`

Locational Damage

*Locational Damage Sound* - `Disabled`

*Locational Damage Effect* - `Disabled`

### WetFunction Redux

**Visuals**:

Texture effects

Disable everything except `Body - Sweat`

Texture swapping - female

Disable everything except `Body (specular)`

### Wildcat Combat

**Dynamic Combat**:

*Disable Slow at 0 Stamina* - `Enabled`

*Disable Swimming Stamina Cost* - `Enabled`

*Disable Bow Interrupts* - `Enabled`

**Stamina Costs**:

*Bow Attacks Cost* - `0 Stamina`

*Disable Pulled / Held Bow Stamina Cost* - `Enabled`

**Timed Block**:

*Disable Timed Block* - `Enabled`

### XPMSE

**Styles**:

Quiver Style

*Player* - `Frostfall Quiver (XP32)`

*Non-Player* - `Frostfall Quiver (XP32)`

### SexLab

**Install**:

SexLab v.163 SE dev Beta 8 by Ashal@LoversLab.com

Click `INSTALL/UPDATE SEXLAB 1.63 SE DEV BETA 8`

Close the MCM and wait until you receive the message:

`SexLab - SexLab v1.63 SE dev beta 8 - Ready!`

Save your game, reopen the MCM and continue configuration of SexLab

**Animation Settings**:

(If you don't want Creature animations, skip this step)

*Allow Creature Animations* (Top Right, Under Animation Profile) - `Enabled`

Close the MCM and wait until you receive the message:

`SexLab Creature Animations Installed`

Save your game, reopen the MCM and continue configuration of SexLab

**Rebuild & Clean**:

Click `Import Settings`, click `Accept`.

### SexLab Aroused

**SETTINGS**:

General

*Purge Dead Actors Every 10 Game Days* - `Enabled`

*Enable SOS* - `Enabled`

Arousal

*Default Exposure Rate* - `1.7` (personal preference)

*Decay Rate* - `1.5` (personal preference)

### Radiant Prostitution

**PC Settings**:

Stripping

*Use Beds* - `Enable`

Reward Settings

*Female PC Gold Bonus* - `10`

*Male PC Gold Bonus* - `40`

### SL Anim Loader

**General Options**:

Click `Enable All`

Click `Register Animations`

Wait in the MCM until you receive the Completed message

### Defeat

**General Settings**:

Click `Mod Status - Disabled`

Close the MCM and wait for the message `Defeat: Installed` and reopen the MCM.

Click `Import settings`.

### Spell Research

**Options**:

Click `Import Spells`, close the MCM and click `YES` to every prompt.

## Adding more Mods

### Using LOOT

I like LOOT. It can be great if you are willing to invest some time in setting up some groups and custom rules. I still can't understand why most modlist authors and "pro modder" refuse to use LOOT, guess they never tried. Anyway: this modlist comes with a ton of custom rules, groups and whatnot to make it even easier adding mods.

You can access the Groups Editor by using the three dots in the top right corner and selecting "Open Groups Editor". The graph will most likely make no sense to you but this is what I use. Some groups are auto-assigned using Regex. If you have no idea what Regex than don't even bother trying to understand it.

- "Enemy Variations": `^(Enemy\sVariations)\s(V3|V4)\s-\s(?!NPCs)(?!Weapons)(?!Armor)[^\.]+\.(esp|esl)$`
- "Enemy Variations - Armor": `^(Enemy\sVariations)\s(V3|V4)\s-\s(Armor)[^\.]+\.(esp|esl)$`
- "Enemy Variations - NPCs": `^(Enemy\sVariations)\s(V3|V4)\s-\s(NPCs)(?!\s-\sResourcesSSE)(?!\s-\sTextures)[^\.]*\.(esp|esl)$`
- "Enemy Variations - Weapons": `^(Enemy\sVariations)\s(V3|V4)\s-\s(Weapons)[^\.]+\.(esp|esl)$`
- "kryptopyr's Patches": `^(CACO|TCIY|CCOR|WACCF|SPO)[\s_][^P]?(Patch)?[^\.]*\.(esp|esl)$` [Example](https://regex101.com/r/9VXgiY/1)
- "LotD Patches": `^(DBM|BCS)_(?!RelicHunter)[^\.]+\.(esp|esl)$` [Example](https://regex101.com/r/o7VOiZ/1)
- "OCW": `^(OCW_)(?!Obscure''s_CollegeofWinterhold)(?!CellSettings)[^\.]+\.(esp|esl)$` [Example](https://regex101.com/r/T5qHVh/1)
- "QUASIPC": `^(Qw_)[^\.]+\.(esp|esl)$` [Example](https://regex101.com/r/sITg6c/1)
- "erri120 Patches": `^(erri120_)[^-]*(-Patch)[^!](esp|esl)$` [Example](https://regex101.com/r/OP6Acn/1)
- "Merges": `^[^-]+(\s-\sMerged).(esp|esl)$` [Example](https://regex101.com/r/hilhlv/1)

Some notes about using Regex in LOOT: there are still some problems, see [this](https://github.com/loot/loot/issues/1193) and [this](https://github.com/loot/libloot/issues/64), and you can't override a regex group assignment.

When adding a new mod with an esp, go into LOOT, use the three dots next to the plugin, click "Edit Metadata", go to the "Main" tab and assign it a group. The group names make somewhat sense like "Outfits", "Followers", "Accessories" or "Weapons". If you're in doubt ask on the discord or use the "default" group.

After assigning a plugin to a group sort the load oder.

### Textures

Textures are by far the easiest mods to install. Simply install the mod and check what other mod also changes the same textures in MO2. The only textures that could be problematic are landscape/environment textures like new mountain textures.

#### Skin Textures

You might not like the default skins (see [Character Mods](#character-mods)) but there is one thing you need to be careful about: seams.

If you change the default female texture, take a look at [this](https://www.loverslab.com/topic/137830-easy-way-to-make-seamless-sos-textures/) post on how to make seamless SOS textures.

### Meshes

Similar to [Textures](#textures) just slap them into MO2. Just be careful that those new meshes are for outfits as those should be compatible with the character body of this setup (see [Character Mods](#character-mods)).

### Animations

New animations can be easily added depending on the category. You have to differentiate between [SLAL Animations](#slal-animations) and [Normal Animations](#normal-animations). The former being animations for Sexlab and the later being animations like [Pretty Sit Idles](https://www.nexusmods.com/skyrimspecialedition/mods/10399).

#### SLAL Animations

[SLAL](https://www.loverslab.com/files/file/5328-sexlab-animation-loader-sse/) or _Sexlab Animation Loader_ requires special animations. You should only install additional Sexlab animations if those are made for SLAL.

Simply install them and re-run FNIS. If the animations come with an ESP, than you will have to jump into xEdit or zEdit and find out what the ESP adds/changes. Most ESPs of animations simply add animations objects and do not change any vanilla records. These ESPs can be loaded anywhere in the loadorder.

#### Normal Animations

Simply install the new animations and re-run FNIS. You might want to take a look at [FNIS PCEA2](https://www.nexusmods.com/skyrimspecialedition/mods/13281) if you want those new animations to be player exclusive.

### Pose Mods

(check the [Poses](#poses) section first)

Aside from simply running Nemesis, there are some actions you might want to execute:

You need to do a little work if you want to fully integrate additional pose mods into this setup. The first thing you should do is check compatibility with [Poser Hotkeys SE](https://www.loverslab.com/files/file/5132-poser-hotkeys-se/). Poser Hotkeys requires `PoserData` (see `SKSE/plugins/PoserHotKeys/PoserData/*.json`) which can be generated with the `PoserDataGen` tool (see the executable list).

Pose mods are often standalone and might give you spells and/or rings to use certain poses. You won't need those since we use Poser Hotkeys. I recommend you clean the plugin from the pose mod to remove all those spells, rings, object effects, quests, form id lists and so on. The only records you need are of type `Idle Animation` and `Animated Object`.

Another thing you might want to consider is merging the plugin into the `Poses - Merged.esp` merge. Simply use the `Merge Plugins Hide` MO2 plugin to enable all plugins from that merge, go into zMerge, add that plugin to the merge, re-generate the merge and disable all plugins again with `Merge Plugins Hide`.

### Outfits

Another category of mods you can easily add to this setup. You only have to make sure that the outfits fit the character body (see [Character Mods](#character-mods)). It's also a good idea to find BodySlide files for that outfit so you can customize it.

Install the outfit and, optionally but highly recommended, merge the outfit in the `Outfits - Merged` merge. Use the `Merge Plugins Hide` to activate all plugins from that merge, assing the new plugin to the Outfits LOOT group (see [Using LOOT](#using-loot)), sort with LOOT, open zMerge, add the esp to the merge and rebuild it. Make sure you disable all plugins with `Merge Plugin Hide` when you're finished.

If the outfit contains high heels, check out [Heels Sound](https://www.loverslab.com/files/file/1795-heels-sound/) and change the Footstep Set of the Armor Addon to `AngelFSTHeelsFootstepSet`.

### ENB

The weather mod used in this Modlist is [Cathedral Weathers and Seasons](https://www.nexusmods.com/skyrimspecialedition/mods/24791) and the lighting mods are [Relighting Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/8586) and [Enhanced Lighting for ENB (ELE)](https://www.nexusmods.com/skyrimspecialedition/mods/1377). If you want to swap out the ENB, make sure that it is compatible with Cathedral Weathers and looks somewhat decent with RS and ELE. You could try and swap the those two mods with any other weather + lighting mod but this may disrupt the visual consistency that the entire Cathedral lineup has.

Other ENBs you can use (not tested, experience may vary):

ENBs that work with Cathedral Weathers:

- [Silent Horizon](https://www.nexusmods.com/skyrimspecialedition/mods/21543)
- [Ljoss - Semi-realistic performance preset with Nighteye and ENB Light support](https://www.nexusmods.com/skyrimspecialedition/mods/30971)

ENBs that maybe work with Cathedral Weathers:

- [Rudy ENB](https://www.nexusmods.com/skyrimspecialedition/mods/4796)
- [NVT](https://www.nexusmods.com/skyrimspecialedition/mods/11203)
- [PRT](https://www.nexusmods.com/skyrimspecialedition/mods/4743)
- [Apex](https://www.nexusmods.com/skyrimspecialedition/mods/18042)

## Tweaking Performance

My Setup:

- i7-7700k running at ~4.6 GHz
- 1060 6GB overclocked to ~1800MHz (got +160 Core Clock and +400 on Memory Clock)
- 16GB DDR4-3200 RAM (CL 14 iirc)
- Game and MO2 running on an m.2

### Tweaking the ENB

This should always be the first thing you tweak. Disabling the ENB entirely can give you anything from 20 to >70 FPS. The ENB this Modlist comes with (see [ENB: Silent Horizon](#enb-silent-horizon)) is rather performance friendly. Open the ENB GUI using `Right Shift + Enter` (`Right Shift` is under the `Enter` key). This will open up the ENB GUI where you can enable and disable certain effects in the left panel.

- `Bloom`: Can give you up to 3 FPS, will make light sources less bright
- `DepthOfField`: Can give you up to 10 FPS, disabled by default and not really suited for gameplay
- `Ambient Occlusion`: This one is a big hitter. You can get up to 20 FPS by disabling this but the effect is very noticeable
- `Distant/DetailedShadow`: Those two can really give you a lot of FPS back depending on your shader settings (game settings). They are very noticeable.
- `ComplexFire/ParticleLights`: You won't see a lot of difference at first when disabling those two, but when particles are on screen (eg using magic or near light sources such as fires), they can _burn_ through your FPS

### Tweaking the Game Settings

I highly recommend using [BethINI](https://www.nexusmods.com/skyrimspecialedition/mods/4875) which is included in this Modlist (can be found in `MO2/tools/BethINI`). I recommend tweaking the `Detail` section for more FPS:

- `Shadow Resolution`: Very big one. A good balance is `2048` which is the borderline between high FPS drainage and garbage looking shadows.
- `Ambient Occlusion`: Highly recommended to leave this at `None`. The ENB this Modlist comes with, uses the ENB SAO which is 10x better and performance friendly than base game SAO.
- `Detailed Draw Distance`: Maybe try `2000` instead of `2800` but you won't notice a lot of FPS gain (maybe 1-3)
- `Remove Shadows`: If you really struggle, use this. This will disable all Shadows (not recommended)

### Using dxvk

**THIS IS EXPERIMENTAL AND I WON'T PROVIDE SUPPORT IF YOU USE IT**!

[DXVK](https://github.com/doitsujin/dxvk) is a Vulkan-based implementation of various DirectX versions. Did that sentence made no sense to you? Vulkan and DirectX are APIs that can be used in game engines to tell your graphics card how to render stuff. LE uses DirectX 9 (D3D9) while SSE uses DirectX 11 (D3D11).

You can _try_ using DXVK. Vulkan runs better on AMD cards and better for D3D9 games. SSE is D3D11 so it may not even work for you. I recommend not using DXVK if you don't want to tinker with it but you are welcome to try it out.

To use it, grab the latest [release](https://github.com/doitsujin/dxvk/releases), extract the archive and grab `x64/d3d11.dll` and `x64/dxgi.dll`. ENB might not be compatible with DXVK so I recommend trying it without one first. Copy those files into the main Skyrim folder and download this [dxvk.conf](https://pastebin.com/KAgwsbBf) file. This is the config file that works on my system so you might wanna tweak it for yours.

If you do wanna use an ENB and you made DXVK work without an ENB, rename `d3d11.dll` to `d3d11_dxvk.dll`, install an ENB, open `enblocal.ini` and add `d3d11_dxvk.dll` as a proxy libaray:

```ini
[PROXY]
EnableProxyLibrary=true
InitProxyFunctions=true
ProxyLibrary=d3d11_dxvk.dll
```

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Afterword

I must applaud you if you have read the entire README. I started with this modlist in December 2019 and thought about it as early as November I think. When creating this modlist my main goal was to have a NSFW poster boy for Wabbajack and introduce + convince people from other communities to try out Wabbajack. There are still a ton of people who have no idea what Wabbajack does and still accosiate the word "modpack" with it. I also wanted to show users and modlist authors some good practices when creating a modlist and actually publishing it, this is not about the actual modlist itself but everything around it such as a README, Changelog, how to contribute, releases and so on.

The READMEs of other modlists are mostly written on GDocs and only contain information on how to install the thing and how to setup the MCM. This is fine if you have something like [SME(FT)](https://github.com/EzioTheDeadPoet/SME-FT-) which is a small little starting point but not if you have a massive modlist with 800+ mods, 100+GB downloads and 90% of your README is MCM. My vision for a good modlist README is reflected here and you already read it. It should contain information on the general idea, why you would wanna install it, what you need but most importantly: what you actually get and what are the most important mods you should know about.

I hope we will get more READMEs like this in the future so that the user has a better experience and asks less questions. Other modlists authors often complain about "stupid users" with "stupid questions" even tho their own README has like 20 lines on how to install it. I might also be that NSFW users are simply superior to plebs but I rarely get stupid questions since you can just pop up this README and likely find the information you need.

Another reason I wanted to create an maintain a modlist is because I am also developing Wabbajack. Since starting this modlist I have added a lot of additional features and fixed equaly as much bugs because I actually used the program I develop. I have previously only compiled test modlists and installed some major public ones but never compiled a huge modlist like this myself.

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I would advise checking the [Issues](https://github.com/erri120/lotus/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
