# Even-Simpler
The Dead Simple Sprite Mod - downported to Vanilla.  The goal of this project is to provide a more **_visually appealing_** (notice: not necessarily "smoother") experience while playing Doom, Doom II, and its plethora of mods.  Additionally this mod is designed to fulfill the goal I'd originally set out to meet when creating The Dead Simple Sprite Mod (since I kinda lost the plot with that one) by maximizing compatibility for both source ports and map wads.  This is accomplished by manipulating states at an individual level and using as little DeHackEd as possible.

# Features:
NEW ENEMY CHANGES:  
- The Zombieman has been given fullbright on his firing frame, a Spawn animation unique from his See sprites, and has a new death animation.  
- Lost Souls do not bleed.
- ShotgunGuy has been given a new death animation and a Spawn animation unique from the See sprites.
- Since the chaingun is now an SMG, the Chaingunner has been replaced by a Machinegunner I made, who will drop the SMG on death. His rate of fire remains unchanged from the original, but the frame duration has been halved to make the animation match the rate of fire.
- Imp pre-firing frames got a little hotter...
- Barons now have black legs to make them a little easier to differentiate at a distance from Hell Knights.
- Cacodemons, Hell Knights, Barons, and Pain Elementals also have blue, green, and orange blood, respectively, in supported ports.
- Revenants now wear black armor. This has no in-game purpose, I just think it looks sick af.
- New sprites for the Calamity Blade, the Shocktrooper, and their forcefully-separated head in Legacy of Rust
- New gorier death animation for the Archvile (deserved).  

BRIGHTMAPS:  
WE GOT EM (in supported ports). Enemies now have glowing eyes and cybernetic enemies also have glowing machine bits, in addition to flats for nukage and lava and most pickup sprites having something on them that glows, if appropriate. Imps and bruisers also have glowing hands as they prepare to fire.

NUGHUD: Included a minimalist NUGHUD file for Nugget Doom users.

DEHEXTRA ADD-ON:  
Hey man, y'all like smooth decorations and powerups? Dead Simple now comes with a small DEHEXTRA-compatible add-on that can be loaded alongside the other included add-ons to get:  
- Animated Medikits
- Smooth health potions
- Smooth torches and barrels
- Spinny keys and skulls
- A super cool trail effect for plasma balls
- Compatibility built-in with the brightmaps lump  
Add it in your load order after the gameplay mod of your choosing today!! Or don't, I'm not your boss!

THIS MOD HAS BEEN TESTED AND IS FULLY* COMPATIBLE WITH:
    The Woof! family of ports (incuding Nugget and Cherry)
    Doom Retro
    DSDA-Doom
    Crispy Doom
    GZDoom
    The Eternity Engine
    Helion

*KNOWN ISSUES:  
Currently, of the ports I've tested here, only Woof!-family ports and Helion are able to accept the BRGHTMPS lump, though Doom Retro should be fixing this feature in a future update

HOW TO USE:  
If your source port has an autoload folder and you want to use them, you can go ahead and add the NUGHUD into the "all" section and just skip anything related to it in the instructions below.  
Load order matters here, though in most instances it's no different than you're used to. If you're NOT playing Legacy of Rust, load the IWAD, then map PWAD, then the weapons mod of your choosing, then the NUGHUD if you so-desire. If you ARE playing Legacy of Rust, the weapons mod must be loaded BEFORE Legacy of Rust to allow overwriting the Plasma Rifle and BFG. The Rust Patch must be loaded afterwards to put the new shocktrooper sprites and strings consistent with the LoR content in the game. Regardless the gameplay mod you're using, load DeadSimpleExtra.wad afterwards. NUGHUD goes at the end as per usual.

CREDITS:  
- Sonik.o.Fan aka Tesefy - Fists, Pistol, Shotgun, Rocket Launcher  
- 6BD - Super Shotgun, taken from c0mbolynch's Supercharge weapons addon  
- OSJC Latchford - Major Crisis (SMG, Plasma Rifle)  
- Lobo - Doom Forever (Imp Sprites, some effects)

Please enjoy my mods and don't hesitate to reach out for any reason.  As always: Comments, feedback, and constructive criticism are all welcome. All other complaints can be emailed to rpitchford@gearbox.com.

**VERSION 2.0 IS NOW RELEASED!**

A lot has changed under the hood from the previous releases, though you may not notice immediately when playing.  Two big changes to address first and foremost:
1. A new file, EvenSimplerGloves.wad, is now included.  This version of the mod has been resprited to use Tesefy's box art gloves on the weapons.  More importantly though:
2. **EVEN SIMPLER HAS BEEN DOWNPORTED FROM BOOM/COMPLVL 9 TO VANILLA/COMPLVL 2.** This should mean more compatibility with more things and, theoretically, compatibility with Chocolate Doom.  I have no idea how to get Chocolate working though, so that part is left as an exercise for the reader.  Make sure you let me know how you did it though, if you do.  See the changelog in the release for full details.
