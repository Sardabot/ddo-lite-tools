# DDO Character Planner lite
Originally created by EllisDee37, with input from DDOApps.
Updates by Chris Lewis (Farog on Khyber, ChicagoChris in the forums)

## Background
These tools were created by EllisDee37, but stopped being updated in 2018-05-25.  
I've taken the original VB6 code and added the Alchemist class and will be making minor updates 
as SSG releases them.

## GitHub Repo
The code and releases are available at https://github.com/ChristopherGLewis/ddo-lite-tools
Any issues and input should be filed there.

## Release Notes

### 3.5.0
Changes:
    Updated Enhancements, Feats and Races for u50
        * Added Horizon Walker
        * Updated Shadar-Kai and Radian Servant Enhancemnts
        * Added Shadar-Kai Spiked Chain Attack feat.
        * Falconry: Meticulous Weaponry now has antireq of Item Defense.
            * May need to look at other Item Defenses to add AntiReq's
    Minor updates to Enhancement tracking of Base, Racial and Universals

### 3.4.2
Changes:
    Updated how Enhancement point calcs work to allow for separate pools for RacialPL and Universal bonuses
    Recrawled Enhancement tree and fixed order of Arcanotechnician T5's 

### 3.4.1
Changes:
    Added more 48.4 enhancement changes (thanks @LrdSlvrhnd, @SardaofChaos & @Grace_ana)
    Added Destiny Tome UI element

### 3.4.0
Changes:
    Updated Builder to support Universal Tome & Destiny tome points.  
    Rev'd save version to 5
    Added 48.4 enhancement changes (thanks @LrdSlvrhnd, @SardaofChaos & @Grace_ana)
    Fixed an issue with SpellSinger T1 studies that @Grace_ana found
    Updated Compendium - easier none/6 selection on challenges
      - click on the 1st star to toggle one/none
      - click on the 5th star to toggle 5/6
      - This is in addition to clicking left/right of the stars

### 3.3.4
Changes:
    Added 4th Epic past live per circle to Compendium
    Compendium version is now 1.5.0, other versions unchanged


### 3.3.3
Changes:
    Added Alchemist, Shifter and Shifter iconic to compendium
    Updated Compendium with updates from SardaofChaos 
    Compendium version is now 1.4.0, other versions unchanged

### 3.3.2
Fixes: 
   Alchemist missing Bonus feat at 12.
   Alchemist had an extra L3 spell at L15
   Swords to Plowshares had a tab at the end of line breaking save/restore
Changes:
    The data load should now trim off tabs
Recrawled all trees.

### 3.3.1
Fix for Alchemical Studies. Alchemical Studies - X can be taken at as a Class Feat, but only 2 times per Reaction. 
Note that is required a feat rename (':' is a special character in parsing the input files) so if you reload a saved Alchemist you will have to indicate the appropriate new feat name. 
Recrawled all trees.  Updated quest info per tremlas (Thanks!)

### 3.3.0
Added Shifter race, Razorclaw Shifter iconic, and Feydark Illusionist tree.  Recrawled all trees.  Updated quest info per SardaofChaos (Thanks!)

### 3.2.4
Updated Fatesinger (U42P4).  Recrawled Destinies.

### 3.2.3
Added the new Warlock feats from U46p2.  Fix to Inquisitive "What Later?"

### 3.2.2
Updated Knight of the Chalice, Sacred Defender and Stalward Defense per U45. Pale Master and Swords to Plowshares feat per U42 patch 4. General Wiki crawl of enhancements resulting in fixes to Bladeforged and Wood Elf.

### 3.2.1
Updated Epic Destinies with changes in U42 Patch 4 

### 3.2.0
Updates for Alchemist and other Update 45 changes
