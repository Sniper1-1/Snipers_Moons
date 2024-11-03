
---

**<details><summary>Version 0.3.1</summary>**

 - After some consideration, all moons now have a standalone version available for download and are now depencencies of this pack. Their files are no longer directly included. If you use a mod manager (which you should), the dependencies will automatically download with this pack. This should have 2 main benefits. You can pick only the ones you want and drop the bloat, and second if there is a big game update that breaks things I can push an update to each moon as I fix them instead of needing to wait to get them all fixed. 
 
 </details>
 
---

**<details><summary>Version 0.3.0</summary>**

 - Added Timbrance and Tundaria as moons.
 - Added hidden moons as a category (hidden moons will have some way of discovering their name in-game, like new story logs. Currently one new moon and SS-13 are in this category).
 - Reduced probability of large rocks spawning on Valiance to reduce chance of path being cut off (might still technically be able to happen, but it's even more unlikely now).
 - Falling in Natit's canal should trigger a "drowned" cause of death instead of "gravity".
 - Fixed AI navigation issues with SS-13.
 - SS-13 ceiling has collision.
 - Tweaked Natit audio.
 - Fixed a null reference error on landing/takeoff on Phuket.
 - Readme updated.
 
 </details>

---

**<details><summary>Version 0.2.3</summary>**

 - Fixed softlock when soccer balls spawned as scrap (turns out they're called "SoccerBall" not "SockerBall").
 - Fixed Torus fog not covering whole map.
 - Dropship music now waits until landed (I know some may have liked the early music to know where the ship is landing but since I'm trying to match vanilla this was a bug).
 - Uses ExtendedMod (behind the scenes stuff).
 
 </details>
 
---

**<details><summary>Version 0.2.2</summary>**

 - Fixed a visually broken ladder on Valiance.
 - Set dependencies to modern versions.
 
 </details>

---

**<details><summary>Version 0.2.1</summary>**

 - Updated to V60.
 - Sky now better reflects weather and nightime.
 - Tweaked the outside of SS-13 (planets moved some and stars now present, but they need more work).
 - README tweaks.
 - Added a license file.
 
 </details>

---

**<details><summary>Version 0.2.0</summary>**

 - Added 360 Torus as a new moon.
 - SS-13 now displays weather on terminal confirmation screen and whatever price you've configured it to be instead of a hardcoded price. Additionally, your new balance after purchase is announced.
 - SS-13 has audio from hangar shield generators.
 - Turned off lights on fake ships in SS-13.
 - A pumpkin is now in shiping on SS-13.
 - Tweaked rocks on Valiance.
 - Moons now have SnipersMoons tag for filtering in terminal.
 - Shrunk file sizes (When referencing things like vanilla items, enemies, etc in levels the lethalbundle file would include all those meshes, textures, audio, scripts, etc but LethalLevelLoader is smart enough to allow you to substitute those objects for empty ones and as long as they're named the same (minus an _0 in some cases) it'll dynamically replace the empty ones with the vanilla at runtime).
 - Updated manifest to prefer a more modern version of LethalLevelLoader.
 
 </details>

---

**<details><summary>Version 0.1.3</summary>**

 - Updated to V56.
 - Fixed sun clipping.
 - More decor Phuket & SS-13.
 - Loot table tweaks.
 - Natit fog tweaks.
 - Tweaked Natit's middle bridge path (should not be able to cross from ship side to main entrance side without ladder/jetpack/etc which is what I intended originally).
 - Renumbered 44 Valiance to 45 Valiance (44 belongs to an unreleased vanilla moon. This may require redoing your config).
 - Widened Valiance bridge some (I think it might be possible to thread the needle with the cruiser to cross the bridge but not sure I'd recommend it on this moon).
 - Fixed a hole in the hull of SS-13.
 - New landing pad texture for SS-13 (old one had a weird 3D look to it that I somehow never caught).
 - Attempted to address weird lighting on SS-13 by increasing the distance shadows are simulated.
 - Changed SS-13 terminal selection text.
 - Attempted to boost SS-13 performance by combining groups of boxes into one larger collider instead of each box having its own (not sure if this actually helps much).
 - README now includes risk level.
 
 </details>

---

**<details><summary>Version 0.1.2</summary>**

 - Valiance terrain adjustments for some issues.
 - Reduced max outside map objects on Valiance to attempt to address a crash (we'll see).
 - Fixed invisible quicksand on Valiance.
 - Loot table tweaks (minor SS-13 and major Valiance. Valiance's is my first attempt at a mostly custom one and likely still needs work).
 - Increased interior weights for SS-13 (Each vanilla interior weight was 1, giving a 50-50 chance, but this could easily be overpowered by modded interiors. 50-50 remains with just vanilla interiors, and vanilla interiors have a better chance when combined with modded ones now).
 
 </details>
 
---

**<details><summary>Version 0.1.1</summary>**

 - Grass/sand terrain no longer glows.
 - Valiance interior size and loot tweaks.
 
 </details>
 
---

**<details><summary>Version 0.1.0</summary>**

 - Added Valiance as a new moon.
 - Renamed internal file for consistency.
 - Added tags to moons.
 - Natit snow fire exit no longer floats.
 - Natit has propper footstep sounds on railing.
 - Added bushes to Phuket and Natit.
 - Terrain tweaks near Phuket river to address sun clipping (still present but less noticeable from ship).
 - Grass/sand terrain texture made more 3D (odd glow still present, but this might break it up some).
 - SS-13 loot tweaks.
 
 </details>
 

---

**<details><summary>Version 0.0.5</summary>**

 - Item dropship no longer floats in the air when landed.
 - Fixed a floating rock on Phuket.
 - Terrain tweaks around Phuket water fire exit.
 - Phuket quicksand fire exit collision/position fix.
 - Fixed water clipping through terrain in one pit on Phuket.
 - Natit/Phuket flood tweaks.
 - Natit/Phuket visual tweaks.
 - Accidentally broke but (hopefully) fixed the sky.
 
 </details>
 

---

**<details><summary>Version 0.0.4</summary>**

 - Added moon pics (pls work now).
 
 </details>
 

---

**<details><summary>Version 0.0.3</summary>**

 - Added moon pics (I think).
 
 </details>
 

---

**<details><summary>Version 0.0.2</summary>**

 - Added Discord link to and updated credits in README.
 
 </details>
 

---

**<details><summary>Version 0.0.1</summary>**

 - Initial test upload to figure this out.
 
 </details>
 
---
