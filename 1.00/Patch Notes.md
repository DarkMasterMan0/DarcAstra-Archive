All patch notes are left as they originally were at time of release (meaning they become outdated as more patches release, see the Current Changelog for all fully current changes to DarcAstra).

DarcAstra is based off DMMod 1.09b, so DarcAstra patch notes can be considered a continuation of the (discontinued) DMMod patch notes.

**1.00 Changelog (Initial Release)** (1-7-26)
  * D2RLAN Features (thanks Bonesy!)
    * Enabled multiplayer via TCP/IP
    * Increased stash tab size to 16x13 from 10x10, enabled stash "pages" system (each page has its own unique 7 shared stash tabs and 64 pages are available, giving a total of 448 shared stash tabs)
    * Increased maximum gold per stash tab to 25,000,000 from 2,500,000
    * Increased max character/carryable gold to 15,000 per level from 10,000 per level (up to 1,485,000 at level 99 instead of 990,000)
    * Increased save file size limit to 32 KB from 8 KB (now there's virtually no chance of running into the size limit which would make items disappear)
    * Increased max /players count to 16 from 8 (/players X command now goes up to 16 instead of 8)
    * Whirlwind now applies Chance to Cast on striking/attack/kill effects (but not when struck)
  * General
    * UI
      * Changed "Physical Damage Received Reduced/Increased by X%" on tooltips to "Physical Resist +/-X%"
      * NOTE: This is a purely visual change, the stat itself is unchanged.
      * Changed "Your Mana Recovery Rate" on skill tooltips to "Mana Recovery Rate"
    * Bug Fixes
      * Items
        * Halaberd's Reign Shout proc now works
      * UI
        * Changed "All Resistances +/-X" on item tooltips to "All Resistances +/-X%" (added the missing % to have visual parity with other resistances)
        * Blood Golem tooltip now properly takes the Damage synergy from Fire Golem into account
        * Defiance tooltip now properly shows the passive Defense bonus starting at 5% instead of 25%
        * Blessed Aim tooltip now properly shows the passive Attack Rating bonus starting at 5% instead of 25%
        * KNOWN ISSUE: Act 3 and Act 5 merc screens show Inner Sight skill icons instead of their actual skills, this is a hardcoded limitation and can't currently be fixed.
  * Items
    * Stats
      * Hit Blinds Target
        * Now decreases Target's Attack Rating by -30% baseline and -2% per level (this change also applies to Dim Vision)
    * Auto Mods
      * Sorceress Orbs
        * Mana
          * Lizard's (1-5 to Mana)
            * Set Max Level to 44 (no longer spawns at ilvl 45+)
          * Snake's (5-10 to Mana)
            * Set Max Level to 55
            * Decreased Required Level to 5 from 9 (Required Level on auto mods only apply to magic/rare items, not normal/"white" items)
          * Serpent's (11-20 to Mana)
            * Set Max Level to 66
            * Decreased Required Level to 11 from 16
          * Drake's (21-30 to Mana)
            * Decreased Required Level to 17 from 26
          * Dragon's (31-40 to Mana)
            * Decreased Required Level to 23 from 37
          * Wyrm's (41-60 to Mana)
            * Decreased Required Level to 28 from 48
          * Great Wyrm's (61-80 to Mana)
            * Decreased Required Level to 34 from 59
        * Life
          * of the Jackal (1-5 to Life)
            * Set Max Level to 42
          * of the Fox (6-10 to Life)
            * Set Max Level to 58
            * Decreased Required Level to 7 from 8
          * of the Wolf (11-20 to Life)
            * Set Max Level to 74
            * Decreased Required Level to 13 from 20
          * of the Tiger (21-30 to Life)
            * Decreased Required Level to 21 from 35
          * of the Mammoth (31-40 to Life)
            * Decreased Required Level to 29 from 51
          * of the Colossus (41-60 to Life)
            * Decreased Required Level to 36 from 67
      * Paladin Shields
        * All Resistances
          * Rainbow (All Resistances 11-15%)
            * Decreased All Resistances to 8-15% from 11-15%
          * Scintillating (All Resistances 16-25%)
            * Decreased All Resistances to 16-20% from 16-25%
          * Prismatic (All Resistances 25-35%)
            * This auto mod now spawns again
            * This auto mod only spawns on white and magic items (can't spawn on rare items)
            * Decreased All Resistances to 21-25% from 25-35%
        * Enhanced Damage/Attack Rating
          * Sharp (10-20% Enhanced Damage, 15-30 to Attack Rating)
            * Set Max Level to 49
            * Decreased Required Level to 3 from 5
          * Fine (21-30% Enhanced Damage, 31-60 to Attack Rating)
            * Decreased Required Level to 10 from 13
          * Warrior's (31-40% Enhanced Damage, 61-80 to Attack Rating)
            * Decreased Required Level to 19 from 23
          * Soldier's (41-50% Enhanced Damage, 81-100 to Attack Rating)
            * Decreased Required Level to 29 from 34
          * Knight's (51-65% Enhanced Damage, 101-121 to Attack Rating)
            * Decreased Required Level to 38 from 42
      * Necromancer Shrunken Heads
        * Poison Damage
          * of Blight (Adds 2-7 Poison Damage over 3 seconds)
            * Set Max Level to 47
            * Decreased Required Level to 2 from 3
            * Added Poison Length Reduced by 15%
          * of Venom (Adds 5-14 Poison Damage over 3 seconds)
            * Decreased Required Level to 7 from 11
            * Increased Poison Damage to 11-30 over 4 seconds from 5-14 over 3 seconds
            * Added Poison Length Reduced by 20%
          * of Pestilence (Adds 13-28 Poison Damage over 4 seconds)
            * Decreased Required Level to 13 from 18
            * Increased Poison Damage to 35-77 over 5 seconds from 13-28 over 4 seconds
            * Added Poison Length Reduced by 25%
          * of Anthrax (Normal) (Adds 25-50 Poison Damage over 4 seconds)
            * This auto mod now spawns on rare items
            * This auto mod only spawns on normal necromancer shrunken heads (can't spawn on exceptional/elite necro heads)
            * Decreased Required Level to 21 from 25
            * Increased Poison Damage to 52-100 over 6 seconds from 25-50 over 4 seconds
            * Added Poison Length Reduced by 30%
          * of Botulism (Normal)
            * Added new "of Botulism" auto mod for necromancer shrunken heads
            * This auto mod only spawns on white and magic items
            * This auto mod only spawns on normal necromancer shrunken heads
            * Affix Level of 48 (requires ilvl 48+ to spawn)
            * Required Level of 34
            * Frequency of 1 (has a 1/7 chance of spawning)
            * Adds 79-145 Poison Damage over 8 seconds, Poison Length Reduced by 45%
          * of Anthrax (Exceptional/Elite)
            * This auto mod now spawns on rare items
            * This auto mod only spawns on exceptional/elite necromancer shrunken heads (can't spawn on normal necro heads)
            * Decreased Required Level to 21 from 25
            * Adds 70-140 Poison Damage over 6 seconds, Poison Length Reduced by 30%
          * of Botulism (Exceptional/Elite)
            * Added new "of Botulism" auto mod for necromancer shrunken heads
            * This auto mod only spawns on white and magic items
            * This auto mod only spawns on exceptional/elite necromancer shrunken heads
            * Affix Level of 48
            * Required Level of 34
            * Frequency of 1 (has a 1/7 chance of spawning)
            * Adds 136-277 Poison Damage over 8 seconds, Poison Length Reduced by 45%
    * Crafted Items
      * Hit Power Crafts
        * Hit Power Helm
          * Increased Defense vs. Missiles to 75-150 from 25-50
          * Increased Attacker Takes Damage to 15-23 from 3-7
        * Hit Power Boots
          * Increased Defense vs. Melee to 75-180 from 25-60
          * Increased Attacker Takes Damage to 15-23 from 3-7
        * Hit Power Gloves
          * Increased Attacker Takes Damage to 15-23 from 3-7
        * Hit Power Belt
          * Increased Damage Taken Goes To Mana to 10-15% from 5-10%
          * Increased Attacker Takes Damage to 15-23 from 3-7
        * Hit Power Shield
          * Changed 5-10% Increased Chance of Blocking to Socketed (1)
          * Increased Attacker Takes Damage to 18-27 from 3-10
          * Added Requirements -7-11%
        * Hit Power Body
          * Changed 10-20% Faster Hit Recovery to Slows Target by 4-8%
          * Increased Attacker Takes Damage to 18-27 from 3-10
        * Hit Power Amulet
          * Increased Hit Causes Monster to Flee to 8-14% from 3-11%
          * Increased Attacker Takes Damage to 18-27 from 3-10
        * Hit Power Ring
          * Increased Attacker Takes Damage to 15-20 from 3-6
        * Hit Power Weapon
          * Increased Enhanced Damage to 60-85% from 35-60%
          * Increased Attacker Takes Damage to 15-23 from 3-7
        * Greater Hit Power Helm
          * Added new Cube recipe for Greater Hit Power Helm
          * Magic Helm (any helm) + Dol Rune + Perfect Sapphire + Rare Jewel
          * 175-350 Defense vs. Missiles
          * 7% Chance to Cast Level 12 Frost Nova when Struck
          * Attacker Takes Damage of 34-49
        * Greater Hit Power Boots
          * Added new Cube recipe for Greater Hit Power Boots
          * Magic Boots (any boots) + Hel Rune + Perfect Sapphire + Rare Jewel
          * 200-400 Defense vs. Melee
          * 7% Chance to Cast Level 12 Frost Nova when Struck
          * Attacker Takes Damage of 34-49
        * Greater Hit Power Gloves
          * Added new Cube recipe for Greater Hit Power Gloves
          * Magic Gloves (any gloves) + Ko Rune + Perfect Sapphire + Rare Jewel
          * 10-20% Piercing Attack
          * Knockback
          * 7% Chance to Cast Level 12 Frost Nova when Struck
          * Attacker Takes Damage of 34-49
        * Greater Hit Power Belt
          * Added new Cube recipe for Greater Hit Power Belt
          * Magic Belt (any belt) + Shael Rune + Perfect Sapphire + Rare Jewel
          * 20-30% Damage Taken Goes To Mana
          * 7% Chance to Cast Level 12 Frost Nova when Struck
          * Attacker Takes Damage of 34-49
        * Greater Hit Power Shield
          * Added new Cube recipe for Greater Hit Power Shield
          * Magic Shield (any shield) + Lum Rune + Perfect Sapphire + Rare Jewel
          * Socketed (1-2)
          * Requirements -14-19%
          * 9% Chance to Cast Level 12 Frost Nova when Struck
          * Attacker Takes Damage of 39-56
        * Greater Hit Power Body
          * Added new Cube recipe for Greater Hit Power Body
          * Magic Body Armor (any body armor) + Io Rune + Perfect Sapphire + Rare Jewel
          * Slows Target by 7-15%
          * 9% Chance to Cast Level 12 Frost Nova when Struck
          * Attacker Takes Damage of 39-56
        * Greater Hit Power Amulet
          * Added new Cube recipe for Greater Hit Power Amulet
          * Magic Amulet + Dol Rune + Perfect Sapphire + Rare Jewel
          * Hit Causes Monster to Flee 17-30%
          * 7% Chance to Cast Level 12 Frost Nova when Struck
          * Attacker Takes Damage of 34-49
        * Greater Hit Power Ring
          * Added new Cube recipe for Greater Hit Power Ring
          * Magic Ring + Ko Rune + Perfect Sapphire + Rare Jewel
          * 6-10 to Dexterity
          * 7% Chance to Cast Level 12 Frost Nova when Struck
          * Attacker Takes Damage of 34-41
        * Greater Hit Power Weapon
          * Added new Cube recipe for Greater Hit Power Weapon
          * Magic Weapon (any weapon) + Fal Rune + Perfect Sapphire + Rare Jewel
          * 80-135% Enhanced Damage
          * 7% Chance to Cast Level 12 Frost Nova when Struck
          * Attacker Takes Damage of 34-49
      * Blood Crafts
        * Blood Shield
          * Changed Attacker Takes Damage of 4-7 to Increase Maximum Life 3-6%
        * Blood Body
          * Increased Life after each Demon Kill to 4-6 from 1-3
        * Greater Blood Helm
          * Added new Cube recipe for Greater Blood Helm
          * Magic Helm (any helm) + Lum Rune + Perfect Ruby + Rare Jewel
          * 9-15% Deadly Strike
          * 2-5% Life stolen per hit
          * 18-25 to Life
        * Greater Blood Boots
          * Added new Cube recipe for Greater Blood Boots
          * Magic Boots (any boots) + Io Rune + Perfect Ruby + Rare Jewel
          * Replenish Life 8-15
          * 2-5% Life stolen per hit
          * 18-25 to Life
        * Greater Blood Gloves
          * Added new Cube recipe for Greater Blood Gloves
          * Magic Gloves (any gloves) + Ko Rune + Perfect Ruby + Rare Jewel
          * 9-15% Chance of Crushing Blow
          * 2-5% Life stolen per hit
          * 18-25 to Life
        * Greater Blood Belt
          * Added new Cube recipe for Greater Blood Belt
          * Magic Belt (any belt) + Ko Rune + Perfect Ruby + Rare Jewel
          * 9-15% Chance of Open Wounds
          * 2-5% Life stolen per hit
          * 18-25 to Life
        * Greater Blood Shield
          * Added new Cube recipe for Greater Blood Shield
          * Magic Shield (any shield) + Hel Rune + Perfect Ruby + Rare Jewel
          * Increase Maximum Life 5-10%
          * 2-5% Life stolen per hit
          * 18-25 to Life
        * Greater Blood Body
          * Added new Cube recipe for Greater Blood Body
          * Magic Body Armor (any body armor) + Io Rune + Perfect Ruby + Rare Jewel
          * 7-12 Life after each Demon Kill
          * 2-5% Life stolen per hit
          * 18-25 to Life
        * Greater Blood Amulet
          * Added new Cube recipe for Greater Blood Amulet
          * Magic Amulet + Lum Rune + Perfect Ruby + Rare Jewel
          * 9-15% Faster Run/Walk
          * 2-7% Life stolen per hit
          * 18-25 to Life
        * Greater Blood Ring
          * Added new Cube recipe for Greater Blood Ring
          * Magic Ring + Fal Rune + Perfect Ruby + Rare Jewel
          * 6-10 to Strength
          * 2-5% Life stolen per hit
          * 18-25 to Life
        * Greater Blood Weapon
          * Added new Cube recipe for Greater Blood Weapon
          * Magic Weapon (any weapon) + Fal Rune + Perfect Ruby + Rare Jewel
          * 55-100% Enhanced Damage
          * 2-7% Life stolen per hit
          * 18-25 to Life
      * Caster Crafts
        * Caster Helm
          * Increased Regenerate Mana to 9-15% from 4-10%
        * Caster Boots
          * Increased Regenerate Mana to 9-15% from 4-10%
        * Caster Gloves
          * Increased Regenerate Mana to 9-15% from 4-10%
        * Caster Belt
          * Increased Regenerate Mana to 9-15% from 4-10%
        * Caster Shield
          * Changed 5-10% Increased Chance of Blocking to 8-16% Damage Taken Goes To Mana
          * Increased Regenerate Mana to 9-15% from 4-10%
          * Added 2-8% Faster Cast Rate
        * Caster Body
          * Increased Mana after each Kill to 2-4 from 1-3
          * Increased Regenerate Mana to 9-15% from 4-10%
        * Caster Amulet
          * Increased Regenerate Mana to 9-15% from 4-10%
        * Caster Ring
          * Increased Regenerate Mana to 9-15% from 4-10%
        * Caster Weapon
          * Changed Increase Maximum Mana 3-7% to 1-5% Faster Cast Rate
          * Increased Regenerate Mana to 9-15% from 4-10%
        * Greater Caster Helm
          * Added new Cube recipe for Greater Caster Helm
          * Magic Helm (any helm) + Hel Rune + Perfect Amethyst + Rare Jewel
          * 2-7% Mana stolen per hit
          * Regenerate Mana 12-25%
          * 17-25 to Mana
        * Greater Caster Boots
          * Added new Cube recipe for Greater Caster Boots
          * Magic Boots (any boots) + Lum Rune + Perfect Amethyst + Rare Jewel
          * Increase Maximum Mana 3-9%
          * Regenerate Mana 12-25%
          * 17-25 to Mana
        * Greater Caster Gloves
          * Added new Cube recipe for Greater Caster Gloves
          * Magic Gloves (any gloves) + Io Rune + Perfect Amethyst + Rare Jewel
          * 2-5 Mana after each Kill
          * Regenerate Mana 12-25%
          * 17-25 to Mana
        * Greater Caster Belt
          * Added new Cube recipe for Greater Caster Belt
          * Magic Belt (any belt) + Lum Rune + Perfect Amethyst + Rare Jewel
          * 8-20% Faster Cast Rate
          * Regenerate Mana 12-25%
          * 17-25 to Mana
        * Greater Caster Shield
          * Added new Cube recipe for Greater Caster Shield
          * Magic Shield (any shield) + Hel Rune + Perfect Amethyst + Rare Jewel
          * 6-15% Faster Cast Rate
          * 18-34% Damage Taken Goes To Mana
          * Regenerate Mana 12-25%
          * 17-25 to Mana
        * Greater Caster Body
          * Added new Cube recipe for Greater Caster Body
          * Magic Body Armor (any body armor) + Shael Rune + Perfect Amethyst + Rare Jewel
          * 3-7 Mana after each Kill
          * Regenerate Mana 12-25%
          * 17-25 to Mana
        * Greater Caster Amulet
          * Added new Cube recipe for Greater Caster Amulet
          * Magic Amulet + Ko Rune + Perfect Amethyst + Rare Jewel
          * 7-15% Faster Cast Rate
          * Regenerate Mana 12-25%
          * 17-25 to Mana
        * Greater Caster Ring
          * Added new Cube recipe for Greater Caster Ring
          * Magic Ring + Lum Rune + Perfect Amethyst + Rare Jewel
          * 6-10 to Energy
          * Regenerate Mana 12-25%
          * 17-25 to Mana
        * Greater Caster Weapon
          * Added new Cube recipe for Greater Caster Weapon
          * Magic Weapon (any weapon) + Fal Rune + Perfect Amethyst + Rare Jewel
          * 5-10% Faster Cast Rate
          * Regenerate Mana 12-25%
          * 17-25 to Mana
      * Safety Crafts
        * Safety Helm
          * Increased Enhanced Defense to 25-40% from 10-30%
          * Increased Magic Damage Reduced to 1-3 from 1-2
          * Increased Damage Reduced to 2-5 from 1-4
        * Safety Boots
          * Increased Enhanced Defense to 25-40% from 10-30%
          * Increased Magic Damage Reduced to 1-3 from 1-2
          * Increased Damage Reduced to 2-5 from 1-4
        * Safety Gloves
          * Increased Enhanced Defense to 25-40% from 10-30%
          * Increased Magic Damage Reduced to 1-3 from 1-2
          * Increased Damage Reduced to 2-5 from 1-4
        * Safety Belt
          * Increased Enhanced Defense to 25-40% from 10-30%
          * Increased Magic Damage Reduced to 1-3 from 1-2
          * Increased Damage Reduced to 2-5 from 1-4
        * Safety Shield
          * Increased Enhanced Defense to 25-40% from 10-30%
          * Increased Magic Damage Reduced to 2-4 from 1-2
          * Increased Damage Reduced to 3-6 from 1-4
          * Added 5-10% Increased Chance of Blocking
        * Safety Body
          * Increased Enhanced Defense to 25-40% from 10-30%
          * Increased Magic Damage Reduced to 2-4 from 1-2
          * Increased Damage Reduced to 3-6 from 1-4
        * Safety Amulet
          * Increased Magic Damage Reduced to 1-3 from 1-2
          * Increased Damage Reduced to 2-5 from 1-4
          * Added Poison Length Reduced by 11-25%
        * Safety Ring
          * Increased Magic Damage Reduced to 1-3 from 1-2
          * Increased Damage Reduced to 2-5 from 1-4
          * Added Physical Resist 1-2%
        * Safety Weapon
          * Increased Enhanced Defense to 20-40% from 5-10%
          * Increased Magic Damage Reduced to 1-3 from 1-2
          * Increased Damage Reduced to 2-5 from 1-4
          * Added 10-25% Enhanced Damage
        * Greater Safety Helm
          * Added new Cube recipe for Greater Safety Helm
          * Magic Helm (any helm) + Io Rune + Perfect Emerald + Rare Jewel
          * 45-100% Enhanced Defense
          * Lightning Resist 8-15%
          * Magic Damage Reduced by 3-6
          * Damage Reduced by 4-9
        * Greater Safety Boots
          * Added new Cube recipe for Greater Safety Boots
          * Magic Boots (any boots) + Lum Rune + Perfect Emerald + Rare Jewel
          * 45-100% Enhanced Defense
          * Fire Resist 8-15%
          * Magic Damage Reduced by 3-6
          * Damage Reduced by 4-9
        * Greater Safety Gloves
          * Added new Cube recipe for Greater Safety Gloves
          * Magic Gloves (any gloves) + Hel Rune + Perfect Emerald + Rare Jewel
          * 45-100% Enhanced Defense
          * Cold Resist 8-15%
          * Magic Damage Reduced by 3-6
          * Damage Reduced by 4-9
        * Greater Safety Belt
          * Added new Cube recipe for Greater Safety Belt
          * Magic Belt (any belt) + Dol Rune + Perfect Emerald + Rare Jewel
          * 45-100% Enhanced Defense
          * Poison Resist 8-15%
          * Magic Damage Reduced by 3-6
          * Damage Reduced by 4-9
        * Greater Safety Shield
          * Added new Cube recipe for Greater Safety Shield
          * Magic Shield (any shield) + Ko Rune + Perfect Emerald + Rare Jewel
          * 45-100% Enhanced Defense
          * 8-15% Increased Chance of Blocking
          * Magic Resist 8-15%
          * Magic Damage Reduced by 4-9
          * Damage Reduced by 5-11
        * Greater Safety Body
          * Added new Cube recipe for Greater Safety Body
          * Magic Body Armor (any body armor) + Fal Rune + Perfect Emerald + Rare Jewel
          * 45-100% Enhanced Defense
          * Cannot Be Frozen
          * Magic Damage Reduced by 4-9
          * Damage Reduced by 5-11
        * Greater Safety Amulet
          * Added new Cube recipe for Greater Safety Amulet
          * Magic Amulet + Lum Rune + Perfect Emerald + Rare Jewel
          * 5-15% Increased Chance of Blocking
          * Poison Length Reduced by 20-40%
          * Magic Damage Reduced by 3-6
          * Damage Reduced by 4-9
        * Greater Safety Ring
          * Added new Cube recipe for Greater Safety Ring
          * Magic Ring + Io Rune + Perfect Emerald + Rare Jewel
          * 2-4% Physical Resist
          * 6-10 to Vitality
          * Magic Damage Reduced by 3-6
          * Damage Reduced by 4-9
        * Greater Safety Weapon
          * Added new Cube recipe for Greater Safety Weapon
          * Magic Weapon (any weapon) + Fal Rune + Perfect Emerald + Rare Jewel
          * 20-40% Enhanced Damage
          * 45-70% Enhanced Defense
          * Magic Damage Reduced by 3-6
          * Damage Reduced by 4-9
    * Unique Items
      * Stormspire
        * Removed Indestructible (had to replace it to facilitate a change/buff to the behavior of the Chance to Cast Blizzard)
      * Eaglehorn
        * Increased Target Defense to -100% from -80%
  * Mercenaries
    * Act 5 Frenzy
      * Decreased Iron Skin level scaling to 1/3 (to account for changes to Iron Skin hard point scaling)
  * Monsters
    * The Summoner
      * Increased his cold damage by 33% in Nightmare and 100% in Hell
      * Now reduces your (and mercenary/pet) cold resistance by 25% in Nightmare and 50% in Hell
      * Increased his fire damage by 75% in Nightmare and 250% in Hell
    * Ubers/Diablo Clone
      * Decreased curse resistance to 75% from 80% (decreases curse duration by 75%)
  * Skills
    * General
      * Added a "Soft Point/Hard Point Skill Scaling" section to skill tooltips that have differing soft point/hard point scaling.
      * KNOWN ISSUE: Skill tooltips with hard point scaling won't calculate the next level stats properly. This is only a display bug, the stats increase as expected.
      * Pseudo Synergies (PSyn)
        * Added a new system that under specific circumstances will simulate skill synergies when using a skill via charges, oskills, Aura When Equipped, or Chance to Cast procs. See the Pseudo Synergies section at the bottom of the 1.00 changelog for more info.
    * Amazon
      * Valkyrie
        * Fixed a bug where Valkyries summoned from Chance to Cast items would disappear nearly instantly (this was already fixed by Blizzard in later versions of D2R, I just refixed it for this version of D2R)
        * NOTE: Unlike later versions you need to keep the CtC item equipped to keep the Valkyrie, if you proc it then switch the item out the Valkyrie will disappear.
    * Sorceress
      * Chilling Armor (CA)
        * Increased CA Ice Bolt missile duration to 34 frames from 25 frames (CA Ice Bolts travel 36% farther)
    * Necromancer
      * Amplify Damage
        * Decreased (nerfed) Physical Resist baseline to -60% from -100%, now decreases Physical Resist by -2% per soft point and -4% per hard point
        * NOTE: This change also applies to Cursed affix unique monsters (their Amp level is equal to [mlvl/5]+1 and is considered soft points, for example a unique Fallen in Hell Blood Moor will have [70/5]+1=level 15 Amplify Damage, which will have -60% + (-2% * 14) = -88% Physical Resist.
        * NOTE 2: This change also applies to Succubi that cast Amplify Damage in Act 5 and is considered hard points, for example a Vile Witch in Hell Worldstone Keep Level 1 will have level 10 Amplify Damage, -60% + (-4% * 9) = -96% Physical Resist.
        * NOTE 3: This change does not apply to Oblivion Knights, they are hardcoded to use a monster version of Amplify Damage and will always apply -100% Physical Resist.
      * Dim Vision
        * Now decreases Target's Attack Rating by -30% baseline and -2% per level (this change also applies to Hit Blinds Target)
      * Weaken
        * Now decreases Enemy Damage by -2% per hard point (hard points 2-19 decrease Enemy Damage by -2% each, hard point 20 decreases it by -4% for a final Enemy Damage of -73% at level 20)
      * Poison Dagger
        * Renamed to Poison Fang
        * Now works with javelins and spears in addition to daggers
      * Iron Maiden
        * Decreased (nerfed) Physical Resist baseline to -30% from -33%
      * Life Tap
        * Decreased Life returned baseline to 15% from 20%, per level scaling remains the same at 1% per soft point, now increases by 3% per hard point (hard points 2-19 increase Life returned by 3% each, hard point 20 increases it by 6% for a final Life returned of 75% at level 20)
      * Blood Golem
        * Now regenerates life twice as fast as other golems (~3.66% max life regenerated per second instead of ~1.83%)
        * Decreased Life stolen per hit baseline to 35% from 86%, changed per level scaling to 2% per soft point and 6% per hard point (hard points 2-19 increase Life stolen by 6% each, hard point 20 increases it by 12% for a final Life stolen of 155% at level 20)
      * Decrepify
        * Decreased (nerfed) Enemy Damage, Physical Resist, Attack Speed, and Run/Walk Speed baseline to -30% from -50%, now decreases each by -1% per level
        * NOTE: This change also applies to Oblivion Knights, they cast level 3 Decrepify in Normal, level 6 in Nightmare, and level 10 in Hell.
      * Fire Golem
        * Now has 95% baseline fire resistance (Summon Resist no longer increases FG fire resist), 10,000 integer Fire Absorb, and fire resist decreases by 1% per soft point and 2% per hard point (hard points 2-19 decrease fire resist by 2% each, hard point 20 decreases it by 4% for a final fire resist of 55% at level 20)
        * DEV COMMENT: This change has the effect of making the Fire Golem heal from fire damage instead of merely being immune to it as in vanilla D2R. The decreasing fire resistance per level means the integer Fire Absorb becomes more effective and the golem heals more (because it takes more fire damage which the absorb then applies to). For example level 1 FG has 95% fire resistance, an attack doing 1000 fire damage would be reduced to 50, integer FA would decrease 50 to 0, then the golem would be healed by 50 life. With 20 hard points the golem has 55% fire resist, 1000 fire damage would be reduced to 450, integer FA would decrease 450 to 0, then it would be healed by 450 life.
        * Death explosion fire and physical damage now scales with level, dealing double the golem's minimum fire damage (excludes added Holy Fire attack damage) each for fire and physical damage. For example level 1 FG has 10 minimum fire damage, so the death explosion would deal (10 * 2) fire + (10 * 2) physical = 40 total damage. Level 2 FG has 21 min fire damage so would deal (21 * 2) fire + (21 * 2) phys = 84 total damage, etc. Corpse Explosion synergy also applies to the death explosion, for example 10 hard points in CE would increase both the fire and phys damage by 50%, level 2 FG would deal (21 * 2 * 1.5) fire + (21 * 2 * 1.5) phys = 126 total damage.
      * Revive
        * Increased Duration per hard point to 15 seconds from 12 seconds
        * 20th/final hard point Duration increase is now twice as effective (hard points 2-19 increase Duration by 15 seconds each, hard point 20 increases it by 30 seconds for a final Duration of 480 seconds at level 20)
    * Paladin
      * Might
        * Now supplies 1% Crushing Blow to wielder and allies per level past 20 when aura is active (level 21 gives 1% CB, level 22 gives 2%, level 23 gives 3%, etc.)
      * Prayer
        * Increased Healing per level to 2 from 1 at level 9-16, 3 from 2 at level 17-22, 4 from 2 at level 23-28, and 5 from 3 at level 29+
        * Decreased Healing synergy provided to Cleansing and Meditation to 1/2 effectiveness (rounding down)
      * Holy Bolt
        * Increased Healing per level to 4-8 from 2-4 at level 17-28 and 6-12 from 2-4 at level 29+
        * Added 25% Blessed Hammer damage synergy
        * DEV COMMENT: Blizzard removed the 50% Blessed Hammer damage synergy in patch 2.4 and their patch notes said they increased Holy Bolt's base damage by 50% to compensate, in reality they didn't increase it so their patch notes are incorrect.
      * Defiance
        * Fixed a bug where Defiance Defense bonus would overwrite Iron Skin, they now stack as expected
        * Now supplies 1% Physical Resist per 2 hard points when aura is active and 1% Physical Resist per 4 hard points passively
      * Blessed Aim
        * Fixed a bug where Blessed Aim Attack Rating bonus would overwrite Penetrate, they now stack as expected (this was already fixed by Blizzard in later versions of D2R, just had to refix it for this version of D2R)
      * Concentration
        * Decreased Chance uninterruptable baseline to 20% from 24%, now increases by 2% per soft point and 4% per hard point (hard points 2-19 increase Chance uninterruptable by 4% each, hard point 20 increases it by 8% for a final Chance uninterruptable of 100% at level 20)
      * Conversion
        * 20th/final hard point Duration increase is now twice as effective (hard points 2-19 increase Duration by 0.8 seconds each, hard point 20 increases it by 1.6 seconds for a final Duration of 32 seconds at level 20)
      * Holy Shield
        * 20th/final hard point Faster Block Rate increase is now twice as effective (hard points 2-19 increase FBR by 2% each, hard point 20 increases it by 4% for a final FBR of 58% at level 20)
      * Sanctuary
        * Increased Magic Damage per level to 5 min/6 max from 4/5 at level 9-16, 6/7 from 5/6 at level 17-22, 8/9 from 5/6 at level 23-28, and 11/12 from 6/7 at level 29+
        * Increased Cleansing damage synergy to 9% from 7%
        * Added 12% Blessed Hammer damage synergy
      * Meditation
        * Now fully effective for allies when supplied by a player, 1/2 effectiveness only applies when supplied by a mercenary or Iron Golem
      * Fist of the Heavens
        * Increased Lightning Damage per level to 70 min/70 max from 55/55 at level 23-28 and 100/100 from 65/65 at level 29+
    * Barbarian
      * Bash
        * Increased Enhanced Damage per level to 15% from 10%
        * Removed +Damage
        * DEV COMMENT: Bash's +Damage is a bugged stat that doesn't actually increase your damage, so I removed it and increased the Enhanced Damage instead.
      * Double Swing
        * Added 50% Attack Speed to the tooltip (this is only a tooltip change, it always had 50% IAS)
      * Iron Skin
        * Now increases Defense by 30% per hard point (hard points 2-19 increase Defense by 30% each, hard point 20 increases it by 60% for a final Defense of 630% at level 20)
      * Frenzy
        * Increased Duration to 0.12 per hard point from 0.08, 20th/final hard point Duration increase is now twice as effective (hard points 2-19 increase Duration by 0.12 seconds each, hard point 20 increases it by 0.24 seconds for a final Duration of 8.4 seconds at level 20)
        * Increased Damage per level to 7% from 5%, decreased Double Swing Damage synergy per hard point to 12% from 16%
    * Druid
      * Twister
        * 20th/final hard point Stun Length increase is now twice as effective (hard points 2-19 increase Stun Length by 0.04 seconds each, hard point 20 increases it by 0.08 seconds for a final Stun Length of 1.2 seconds at level 20)
      * Hunger
        * 20th/final hard point Damage increase is now twice as effective (hard points 2-19 increase Damage by 2.5% (rounding down) each, hard point 20 increases it by 5% for a final Damage of -25% at level 20)

**Pseudo Synergies (PSyn)**
In vanilla D2R any class that uses skills that aren't native to themselves (whether it be from charges, oskills, Aura When Equipped, or Chance to Cast procs) are unable to benefit from that skills synergies. For example a barbarian using level 5 Meteor charges from a staff will only deal the Meteor's base fire damage of 172-200, he can't benefit from the 16% fire damage per skill point in Fire Bolt or Fire Ball.

This renders non-utility/one point wonder skills almost completely unusable outside of the very early levels of Normal difficulty since they won't deal any meaningful damage without synergies. This is where PSyns come into play, allowing these skills to scale as the game progresses while not being too powerful, there are specific conditions that must be met for PSyns to take effect.

PSyns will not take effect if any hard points are invested in a skill or its synergies, instead the regular synergies will take effect so a class can't benefit from both regular synergies and PSyns at the same time, i.e. they are mutually exclusive. Certain skills also have further conditions that restrict PSyns from applying and will be noted in the list below.

PSyns scale at a similar pace to the native class "reasonably" placing skill points into a skills synergies. For example, Fire Bolt has Fire Ball and Meteor as synergies. A sorceress can't place points into Fire Ball until character level 12, so PSyns for Fire Bolt also won't start applying until clvl 12. She would "reasonably" alternate placing points between Fire Bolt and Fire Ball, at level 12 putting a point in FBall, level 13 a point in FBolt, 14 FBall, 15 FBolt, etc. The PSyn would apply at the same rate, simulating 1 point in a synergy every other level (12, 14, 16, etc.).

PSyns have a maximum cap that's roughly 2/3 (being slightly higher than 2/3 if exactly 2/3 isn't possible) of the damage/bonuses that the native class can reach with fully maxing their synergies. For example a necromancer with a level 20 Bone Spear (192-204 base magic damage) and 20 points in all of its synergies (8% per point, with 4 synergy skills it's 80 points total for 8% * 80 = +640% magic damage) deals 1420-1509 magic damage, Bone Spear's PSyn is capped to 50 "points" (8% * 50 = +400% magic damage) and deals 960-1020 magic damage.

If a skill has damage synergies with differing bonuses (e.g. Strafe getting 5% Damage per level from Multiple Shot and 10% Damage per level from Guided Arrow) then PSyns will simulate points in the lower synergy until the level that the higher synergy becomes available, then it switches to that synergy.

PSyns will also apply to the native class as long as the conditions for that skill are met, this is intentional to incentivize using charges on that class (like Concentrate/Grim Ward charges on barb helms).

PSyns will also benefit mercs or Iron Golems that use Auras When Equipped and Chance to Cast procs (they can't use charges or active oskills), however they will not benefit the mercs actual skills. They also do not benefit monsters that use player skills (Travincal council members using Hydras for example).

Here is a list of all skills with PSyns, their conditions required, their scaling, their max cap, and any other relevant info.

NOTE: Summoning skills and Druid skills have been postponed to a later patch due to time restraints.

* Amazon
  * Bow and Crossbow Skills
    * Fire Arrow
      * Conditions
        * No hard points in Fire Arrow (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise no synergy will apply)
      * Scaling
        * Starts with 1 "point" (12% Fire Damage per point) at character level (clvl) 12 and +1 "point" every 2 levels after (clvl 14, 16, 18, etc.)
        * Max cap is 11 "points" at clvl 22 (12% * 11 = +132% Fire Damage)
    * Cold Arrow
      * Conditions
        * No hard points in Cold Arrow (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (12% Cold Damage per point) at clvl 18 and +1 "point" every 2 levels after (20, 22, 24, etc.)
        * Max cap is 11 "points" at clvl 38 (12% * 11 = +132% Cold Damage)
    * Multiple Shot
      * Conditions
        * No hard points in Multiple Shot (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (12% Damage per point) at clvl 18 and +1 "point" every 2 levels after (20, 22, 24, etc.)
        * Max cap is 11 "points" at clvl 38 (12% * 11 = +132% Damage)
    * Exploding Arrow
      * Conditions
        * No hard points in Fire Arrow (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise no synergy will apply)
      * Scaling
        * Starts with 6 "points" (14% Fire Damage per point) at clvl 12, +1 "point" at clvl 13, and +1 "point" every 2 levels after (15, 17, 19, etc.)
        * Max cap is 11 "points" at clvl 21 (14% * 11 = +154% Fire Damage)
    * Ice Arrow
      * Conditions
        * No hard points in Cold Arrow (otherwise normal synergies will apply)
      * Scaling (Cold Damage synergy)
        * Starts with 6 "points" (10% Cold Damage per point) at clvl 18, +1 "point" at clvl 19, and +1 "point" every 2 levels after (21, 23, 25, etc.)
        * Max cap is 10 "points" at clvl 25 (10% * 10 = +100% Cold Damage)
      * Scaling (Freeze Length synergy)
        * Starts with 1 "point" (10% Freeze Length per point) at clvl 30 and +1 "point" every 2 levels after (32, 34, 36, etc.)
        * Max cap is 10 "points" at clvl 48 (10% * 10 = +100% Freeze Length)
    * Guided Arrow
      * Conditions
        * No hard points in Multiple Shot (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (12% Damage per point) at clvl 18, +1 "point" at clvl 19, and +1 "point" every 2 levels after (21, 23, 25, etc.)
        * Max cap is 11 "points" at clvl 27 (12% * 11 = +132% Damage)
    * Strafe
      * Conditions
        * No hard points in Multiple Shot (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (10% Damage per point) at clvl 24, +1 "point" at clvl 25, and +1 "point" every 2 levels after (27, 29, 31, etc.)
        * Max cap is 17 "points" at clvl 45 (10% * 17 = +170% Damage)
    * Immolation Arrow
      * Conditions
        * No hard points in Fire Arrow (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise no synergy will apply)
      * Scaling (Fire Damage synergy)
        * Starts with 6 "points" (10% Fire Damage per point) at clvl 24, +1 "point" at clvl 25, and +1 "point" every 2 levels after (27, 29, 31, etc.)
        * Max cap is 10 "points" at clvl 31 (10% * 10 = +100% Fire Damage)
      * Scaling (Average Fire Damage per Second synergy)
        * Starts with 7 "points" (5% Average Fire Damage per point) at clvl 24
        * Max cap is 7 "points" at clvl 24 (5% * 7 = +35% Average Fire Damage)
    * Freezing Arrow
      * Conditions
        * No hard points in Cold Arrow (otherwise normal synergies will apply)
      * Scaling (Cold Damage synergy)
        * Starts with 11 "points" (12% Cold Damage per point) at clvl 30
        * Max cap is 11 "points" at clvl 30 (12% * 11 = +132% Cold Damage)
      * Scaling (Freeze Length synergy)
        * Starts with 6 "points" (5% Freeze Length per point) at clvl 30 and +1 "point" at clvl 31
        * Max cap is 7 "points" at clvl 31 (5% * 7 = +35% Freeze Length)
  * Javelin and Spear Skills
    * Power Strike
      * Conditions
        * No hard points in Power Strike (otherwise normal synergies will apply)
        * No soft or hard points in Lightning Mastery (otherwise no synergy will apply)
      * Scaling
        * Starts with 1 "point" (14% Lightning Damage per point) at clvl 12 and +1 "point" every 2 levels after up to level 40, then +1 "point" every level after 40 (14, 16, 18, etc. then 41, 42, 43, etc.)
        * Max cap is 38 "points" at clvl 63 (14% * 38 = +532% Lightning Damage)
    * Charged Strike
      * Conditions
        * No hard points in Power Strike (otherwise normal synergies will apply)
        * No soft or hard points in Lightning Mastery (otherwise no synergy will apply)
      * Scaling
        * Starts with 6 "points" (14% Lightning Damage per point) at clvl 18, +1 "point" at clvl 19, and +1 "point" every 2 levels after up to level 39, then +1 "point" every level after 39 (21, 23, 25, etc. then 40, 41, 42, etc.)
        * Max cap is 38 "points" at clvl 60 (14% * 38 = +532% Lightning Damage)
    * Plague Javelin
      * Conditions
        * No hard points in Poison Javelin (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (14% Poison Damage per point) at clvl 18, +1 "point" at clvl 19, and +1 "point" every 2 levels after (21, 23, 25, etc.)
        * Max cap is 11 "points" at clvl 27 (14% * 11 = +154% Poison Damage)
    * Lightning Strike
      * Conditions
        * No hard points in Power Strike (otherwise normal synergies will apply)
        * No soft or hard points in Lightning Mastery (otherwise no synergy will apply)
      * Scaling
        * Starts with 12 "points" (11% Lightning Damage per point) at clvl 30, +1 "point" at clvl 31, and +1 "point" every 2 levels after up to level 39, then +1 "point" every level after 39 (33, 35, 37, etc. then 40, 41, 42, etc.)
        * Max cap is 37 "points" at clvl 59 (11% * 37 = +407% Lightning Damage)
* Sorceress
  * Fire Spells
    * Pseudo Fire Mastery
      * Conditions
        * Applies to all sorceress Fire Spells as long as that skills conditions are met
      * Scaling
        * Starts with 1 "point" (30% Fire Damage for first point and 7% per point after) at clvl 30 and +1 "point" every 3 levels after (33, 36, 39, etc.)
        * Max cap is 20 "points" at clvl 87 (30% + 7% * 19 = +163% Fire Damage)
        * Multiplicative with PSyns (just like how regular sorceress Masteries are multiplicative with normal synergies)
    * Fire Bolt
      * Conditions
        * No hard points in Fire Bolt (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (16% Fire Damage per point) at clvl 12 and +1 "point" every 2 levels after up to clvl 28, then +1 "point" at clvl 31 and +1 "point" every 2 levels after (14, 16, 18, etc. then 33, 35, 37, etc.)
        * Max cap is 25 "points" at clvl 61 (16% * 25 = +400% Fire Damage, then multiplied by Pseudo Fire Mastery)
    * Inferno
      * Conditions
        * No hard points in Inferno or Warmth (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 3 "points" (16% Fire Damage per point) at clvl 6, +1 "point" at clvl 7, and +1 "point" every 2 levels after (9, 11, 13, etc.)
        * Max cap is 12 "points" at clvl 23 (16% * 12 = +192% Fire Damage, then multiplied by Pseudo Fire Mastery)
    * Blaze
      * Conditions
        * No hard points in Blaze or Warmth (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (6% Fire Damage per point) at clvl 12, +1 "point" at clvl 13, and +1 "point" every 2 levels after (15, 17, 19, etc.)
        * Max cap is 8 "points" at clvl 15 (6% * 8 = +48% Fire Damage, then multiplied by Pseudo Fire Mastery)
    * Fire Ball
      * Conditions
        * No hard points in Fire Bolt (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (14% Fire Damage per point) at clvl 12, +1 "point" at clvl 13, and +1 "point" every 2 levels after (15, 17, 19, etc.)
        * Max cap is 25 "points" at clvl 49 (14% * 25 = +350% Fire Damage, then multiplied by Pseudo Fire Mastery)
    * Fire Wall
      * Conditions
        * No hard points in Inferno or Warmth (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 9 "points" (4% Fire Damage per point) at clvl 18
        * Max cap is 9 "points" at clvl 18 (4% * 9 = +36% Fire Damage, then multiplied by Pseudo Fire Mastery)
    * Enchant
      * Conditions
        * No hard points in Warmth (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 9 "points" (9% Fire Damage per point) at clvl 18, +1 "point" at clvl 19
        * Max cap is 10 "points" at clvl 19 (9% * 10 = +90% Fire Damage, then multiplied by Pseudo Fire Mastery)
    * Meteor
      * Conditions
        * No hard points in Fire Bolt or Inferno (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise normal synergies will apply)
      * Scaling (Fire Damage synergy)
        * Starts with 12 "points" (5% Fire Damage per point) at clvl 24, +1 "point" at clvl 25, and +1 "point" every 2 levels after (27, 29, 31, etc.)
        * Max cap is 20 "points" at clvl 39 (5% * 20 = +100% Fire Damage, then multiplied by Pseudo Fire Mastery)
      * Scaling (Average Fire Damage per Second synergy)
        * Starts with 3 "points" (3% Average Fire Damage per point) at clvl 24
        * Max cap is 3 "points" at clvl 24 (3% * 3 = +9% Average Fire Damage)
        * NOTE: Meteor Average Fire Damage isn't increased by Pseudo Fire Mastery due to calc limits
    * Hydra
      * Conditions
        * No hard points in Fire Bolt (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 15 "points" (3% Fire Damage per point) at clvl 18, +1 "point" at clvl 31
        * Max cap is 16 "points" at clvl 31 (3% * 16 = +48% Fire Damage, then multiplied by Pseudo Fire Mastery)
  * Lightning Spells
    * Pseudo Lightning Mastery
      * Conditions
        * Applies to all sorceress Lightning Spells as long as that skills conditions are met
      * Scaling
        * Starts with 1 "point" (50% Lightning Damage for first point and 12% per point after) at clvl 30 and +1 "point" every 3 levels after (33, 36, 39, etc.)
        * Max cap is 20 "points" at clvl 87 (50% + 12% * 19 = +278% Lightning Damage)
        * Multiplicative with PSyns (just like how regular sorceress Masteries are multiplicative with normal synergies)
    * Charged Bolt
      * Conditions
        * No hard points in Charged Bolt (otherwise normal synergies will apply)
        * No soft or hard points in Lightning Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (6% Lightning Damage per point) at clvl 12 and +1 "point" every 2 levels after (14, 16, 18, etc.)
        * Max cap is 8 "points" at clvl 26 (6% * 8 = +48% Lightning Damage, then multiplied by Pseudo Lightning Mastery)
    * Nova
      * Conditions
        * No hard points in Static Field (otherwise normal synergies will apply)
        * No soft or hard points in Lightning Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 3 "points" (5% Lightning Damage per point) at clvl 12, +1 "point" at clvl 13, and +1 "point" every 2 levels after (15, 17, 19, etc.)
        * Max cap is 7 "points" at clvl 19 (5% * 7 = +35% Lightning Damage, then multiplied by Pseudo Lightning Mastery)
    * Lightning
      * Conditions
        * No hard points in Charged Bolt (otherwise normal synergies will apply)
        * No soft or hard points in Lightning Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (8% Lightning Damage per point) at clvl 12, +1 "point" at clvl 13, and +1 "point" every 2 levels after (15, 17, 19, etc.)
        * Max cap is 36 "points" at clvl 71 (8% * 36 = +288% Lightning Damage, then multiplied by Pseudo Lightning Mastery)
    * Chain Lightning
      * Conditions
        * No hard points in Charged Bolt (otherwise normal synergies will apply)
        * No soft or hard points in Lightning Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 9 "points" (4% Lightning Damage per point) at clvl 18, +1 "point" at clvl 19, and +1 "point" every 2 levels after (21, 23, 25, etc.)
        * Max cap is 32 "points" at clvl 63 (4% * 32 = +128% Lightning Damage, then multiplied by Pseudo Lightning Mastery)
  * Cold Spells
    * Pseudo Cold Mastery
      * Conditions
        * Applies to all sorceress Cold Spells as long as that skills conditions are met
      * Scaling
        * Starts with 1 "point" (-20% Enemy Cold Resistance for first point and -5% per point after) at clvl 30 and +1 "point" every 4 levels after (34, 38, 42, etc.)
        * Max cap is 13 "points" at clvl 78 (-20% + -5% * 12 = -80% Enemy Cold Resistance)
    * Ice Bolt
      * Conditions
        * No hard points in Ice Bolt or Frost Nova (otherwise normal synergies will apply)
        * No soft or hard points in Cold Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (15% Cold Damage per point) at clvl 6 and +1 "point" every 2 levels after up to clvl 38, then +1 "point" every level after 39 (8, 10, 12, etc. then 40, 41, 42, etc.)
        * Max cap is 52 "points" at clvl 74 (15% * 52 = +780% Cold Damage)
    * Frost Nova
      * Conditions
        * No hard points in Frost Nova (otherwise normal synergies will apply)
        * No soft or hard points in Cold Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (10% Cold Damage per point) at clvl 24 and +1 "point" every 2 levels after up to clvl 38, then +1 "point" every level after 39 (26, 28, 30, etc. then 40, 41, 42, etc.)
        * Max cap is 24 "points" at clvl 55 (10% * 24 = +240% Cold Damage)
    * Ice Blast
      * Conditions
        * No hard points in Ice Bolt (otherwise normal synergies will apply)
        * No soft or hard points in Cold Mastery (otherwise normal synergies will apply)
      * Scaling (Cold Damage Synergy)
        * Starts with 3 "points" (8% Cold Damage per point) at clvl 6, +1 "point" at clvl 7, and +1 "point" every 2 levels after up to clvl 39, then +1 "point" every level after 39 (9, 11, 13, etc. then 40, 41, 42, etc.)
        * Max cap is 36 "points" at clvl 55 (8% * 36 = +288% Cold Damage)
      * Scaling (Freeze Length Synergy)
        * Starts with 1 "point" (10% Freeze Length per point) at clvl 18 and +1 "point" every 3 levels after (21, 24, 27, etc.)
        * Max cap is 10 "points" at clvl 45 (10% * 10 = +100% Freeze Length)
    * Glacial Spike
      * Conditions
        * No hard points in Ice Bolt (otherwise normal synergies will apply)
        * No soft or hard points in Cold Mastery (otherwise normal synergies will apply)
      * Scaling (Cold Damage Synergy)
        * Starts with 9 "points" (5% Cold Damage per point) at clvl 18, +1 "point" at clvl 19, and +1 "point" every 2 levels after up to clvl 39, then +1 "point" every level after 39 (21, 23, 25, etc. then 40, 41, 42, etc.)
        * Max cap is 34 "points" at clvl 53 (5% * 34 = +170% Cold Damage)
      * Scaling (Freeze Length Synergy)
        * Starts with 1 "point" (3% Freeze Length per point) at clvl 24 and +1 "point" every 3 levels after (27, 30, 33, etc.)
        * Max cap is 10 "points" at clvl 51 (3% * 10 = +30% Freeze Length)
    * Blizzard
      * Conditions
        * No hard points in Ice Bolt (otherwise normal synergies will apply)
        * No soft or hard points in Cold Mastery (otherwise normal synergies will apply)
      * Scaling
        * Starts with 12 "points" (5% Cold Damage per point) at clvl 24, +1 "point" at clvl 25, +1 "point" every 2 levels after up to clvl 39, then +1 "point" every level after 39 (27, 29, 31, etc. then 40, 41, 42, etc.)
        * Max cap is 34 "points" at clvl 53 (5% * 34 = +170% Cold Damage)
    * Chilling Armor
      * Conditions
        * No hard points in Ice Bolt or Frozen Armor (otherwise normal synergies will apply)
        * No soft or hard points in Cold Mastery (otherwise normal synergies will apply)
      * Scaling (Cold Damage synergy)
        * Starts with 12 "points" (16% Cold Damage per point) at clvl 24
        * Max cap is 12 "points" at clvl 24 (16% * 12 = +192% Cold Damage)
        * NOTE: Chilling Armor doesn't benefit from Pseudo Cold Mastery due to limits with the implementation
      * Scaling (Duration synergy)
        * Starts with 12 "points" (10 Seconds per point) at clvl 24 and +1 "point" every 2 levels after (26, 28, 30, etc.)
        * Max cap is 27 "points" at clvl 53 (10 * 27 = +270 Seconds)
* Necromancer
  * Poison and Bone
    * Teeth
      * Conditions
        * No hard points in Teeth or Bone Wall (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (15% Magic Damage per point) at clvl 12, +1 "point" every 2 levels after up to clvl 38, then +1 "point" every level after 39 (14, 16, 18, etc. then 40, 41, 42, etc.)
        * Max cap is 52 "points" at clvl 77 (15% * 52 = +780% Magic Damage)
    * Bone Armor
      * Conditions
        * No hard points in Bone Armor (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (15 Damage Absorbed per point) at clvl 12 and +1 "point" every 2 levels after (14, 16, 18, etc.)
        * Max cap is 27 "points" at clvl 64 (15 * 27 = +405 Damage Absorbed)
    * Poison Fang
      * Conditions
        * No hard points in Poison Fang (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (20% Poison Damage per point) at clvl 18, +1 "point" every 2 levels after up to clvl 38, then +1 "point" every level after 39 (20, 22, 24, etc. then 40, 41, 42, etc.)
        * Max cap is 25 "points" at clvl 53 (20% * 25 = +500% Poison Damage)
    * Poison Explosion
      * Conditions
        * No hard points in Poison Fang (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (15% Poison Damage per point) at clvl 18, +1 "point" at clvl 19, +1 "point" every 2 levels after up to clvl 39, then +1 "point" every level after 39 (19, 21, 23, etc. then 40, 41, 42, etc.)
        * Max cap is 25 "points" at clvl 47 (15% * 25 = +375% Poison Damage)
    * Bone Spear
      * Conditions
        * No hard points in Teeth or Bone Wall (otherwise normal synergies will apply)
      * Scaling
        * Starts with 9 "points" (8% Magic Damage per point) at clvl 18, +1 "point" at clvl 19, +1 "point" every 2 levels after up to clvl 39, then +1 "point" every level after 39 (21, 23, 25, etc. then 40, 41, 42, etc.)
        * Max cap is 50 "points" at clvl 69 (8% * 50 = +400% Magic Damage)
    * Poison Nova
      * Conditions
        * No hard points in Poison Fang (otherwise normal synergies will apply)
      * Scaling
        * Starts with 12 "points" (10% Poison Damage per point) at clvl 30, +1 "point" at clvl 31, +1 "point" every 2 levels after up to clvl 39, then +1 "point" every level after 39 (33, 35, 37, etc. then 40, 41, 42, etc.)
        * Max cap is 24 "points" at clvl 46 (10% * 24 = +240% Poison Damage)
    * Bone Spirit
      * Conditions
        * No hard points in Teeth or Bone Wall (otherwise normal synergies will apply)
      * Scaling
        * Starts with 15 "points" (8% Magic Damage per point) at clvl 30, +1 "point" at clvl 31, +1 "point" every 2 levels after up to clvl 39, then +1 "point" every level after 39 (33, 35, 37, etc. then 40, 41, 42, etc.)
        * Max cap is 50 "points" at clvl 69 (8% * 50 = +400% Magic Damage)
  * Curses
    * Iron Maiden
      * Conditions
        * No hard points in Amplify Damage (otherwise normal synergies will apply)
      * Scaling
        * Starts with 2 "points" (-2% Physical Resist per point) at clvl 12, +1 "point" at clvl 13, and +1 "point" every 6 levels after (19, 25, 31, etc.)
        * Max cap is 9 "points" at clvl 49 (-2% * 9 = -18% Physical Resist)
* Paladin
  * Combat Skills (Paladin)
    * Sacrifice
      * Conditions
        * No hard points in Sacrifice, Redemption, or Fanaticism (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (15% Damage per point) at clvl 30 and +1 "point" every 2 levels after (32, 34, 36, etc.)
        * Max cap is 18 "points" at clvl 64 (15% * 18 = +270% Damage)
    * Holy Bolt
      * Conditions
        * No hard points in Holy Bolt or Prayer (otherwise normal synergies will apply)
      * Scaling (Magic Damage synergy)
        * Starts with 1 "point A" (25% Magic Damage per point) at clvl 18 and +1 "point A" every 2 levels after up to clvl 28, then +1 "point B" (50% Magic Damage per point) every 2 levels after 28 ("point A" for 20, 22, 24, etc. then "point B" for 30, 32, 34, etc.)
        * Max cap is 6 "points A" and 17 "points B" at clvl 64 (25% * 6 + 50% * 17 = +1000% Magic Damage)
      * Scaling (Healing synergy)
        * Starts with 3 "points" (20% Healing per point) at clvl 6 and +1 "point" every 2 levels after (8, 10, 12, etc.)
        * Max cap is 12 "points" at clvl 24 (20% * 12 = +240% Healing)
    * Zeal
      * Conditions
        * No hard points in Sacrifice (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (12% Damage per point) at clvl 12, +1 "point" at clvl 13, and +1 "point" every 2 levels after (15, 17, 19, etc.)
        * Max cap is 14 "points" at clvl 27 (18% * 19 + 13% * 3 = +168% Damage)
    * Vengeance
      * Conditions
        * No hard points in Vengeance, Resist Fire, Resist Cold, Resist Lightning, or Salvation (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery or Lightning Mastery (otherwise no synergy will apply)
      * Scaling
        * Starts with 6 "points A" (8% Fire Damage per point) at clvl 18, +1 "point" at clvl 19, and +1 "point" every 3 levels after (22, 25, 28, etc.)
        * Starts with 4 "points B" (8% Cold Damage per point) at clvl 18, +1 "point" at clvl 20, and +1 "point" every 3 levels after (23, 26, 29, etc.)
        * Starts with 2 "points C" (8% Lightning Damage per point) at clvl 18, +1 "point" at clvl 21, and +1 "point" every 3 levels after (24, 27, 30, etc.)
        * Starts with 1 "point D" (3% Fire/Cold/Lightning Damage per point) at clvl 69
        * Max cap is 18 "points A", 18 "points B", 18 "points C", and 1 "point D" at clvl 69 (8% * 18 + 3% * 1 = 147% Fire/Cold/Lightning Damage)
    * Blessed Hammer
      * Conditions
        * No hard points in Blessed Hammer, Vigor, or Blessed Aim (otherwise normal synergies will apply)
      * Scaling
        * Starts with 3 "points" (19% Magic Damage per point) at clvl 18, +1 "point" at clvl 19, and +1 "point" every 2 levels after (21, 23, 25, etc.)
        * Max cap is 25 "points" at clvl 61 (19% * 25 = +475% Magic Damage)
    * Fist of the Heavens
      * Conditions
        * No hard points in Fist of the Heavens, Holy Bolt, or Holy Shock (otherwise normal synergies will apply)
        * No soft or hard points in Lightning Mastery (otherwise no Lightning Damage synergy will apply)
      * Scaling (Lightning Damage synergy)
        * Starts with 3 "points" (7% Lightning Damage per point) at clvl 30, +1 "point" at clvl 31, and +1 "point" every 2 levels after (33, 35, 37, etc.)
        * Max cap is 9 "points" at clvl 41 (7% * 9 = +63% Lightning Damage)
      * Scaling (Holy Bolt Damage synergy)
        * Starts with 13 "points" (15% Holy Bolt Damage per point) at clvl 30
        * Max cap is 13 "points" at clvl 30 (15% * 13 = +180% Holy Bolt Damage)
  * Offensive Auras
    * Holy Fire
      * Conditions
        * No hard points in Holy Fire, Resist Fire, or Salvation (otherwise normal synergies will apply)
        * No soft or hard points in Fire Mastery (otherwise no synergy will apply)
      * Scaling
        * Starts with 3 "points A" (18% Fire Damage per point) at clvl 6, +1 "point A" at clvl 7, and +1 "point A" every 2 levels after up to clvl 37, then +1 "point B" (13% Fire Damage per point) every 2 levels after 37 ("point A" for 9, 11, 13, etc. then "point B" for 39, 41, 43)
        * Max cap is 19 "points A" and 3 "points B" at clvl 43 (18% * 19 + 13% * 3 = +381% Fire Damage)
    * Holy Freeze
      * Conditions
        * No hard points in Holy Freeze, Resist Cold, or Salvation (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points A" (15% Cold Damage per point) at clvl 18, +1 "point A" at clvl 19, and +1 "point A" every 2 levels after up to clvl 37, then +1 "point B" (7% Cold Damage per point) every 2 levels after 37 ("point A" for 21, 23, 25, etc. then "point B" for 39, 41, 43)
        * Max cap is 16 "points A" and 3 "points B" at clvl 43 (15% * 16 + 7% * 3 = +261% Cold Damage)
    * Holy Shock
      * Conditions
        * No hard points in Holy Shock, Resist Lightning, or Salvation (otherwise normal synergies will apply)
        * No soft or hard points in Lightning Mastery (otherwise no synergy will apply)
      * Scaling
        * Starts with 6 "points A" (12% Lightning Damage per point) at clvl 24, +1 "point A" at clvl 25, and +1 "point A" every 2 levels after up to clvl 41, then +1 "point B" (4% Lightning Damage per point) every 2 levels after 41 ("point A" for 27, 29, 31, etc. then "point B" for 43)
        * Max cap is 15 "points A" and 1 "point B" at clvl 43 (12% * 15 + 4% * 1 = +184% Lightning Damage)
    * Sanctuary
      * Conditions
        * No hard points in Sanctuary, Cleansing, or Blessed Hammer (otherwise normal synergies will apply)
      * Scaling
        * Starts with 5 "points A" (9% Magic Damage per point) and 1 "point B" (12% Magic Damage per point) at clvl 24, +1 "point B" at clvl 25, and +1 "point B" every 2 levels after ("point B" for 27, 29, 31, etc.)
        * Max cap is 5 "points A" and 17 "point B" at clvl 43 (9% * 5 + 12% * 17 = +249% Magic Damage)
* Barbarian
  * Combat Skills (Barbarian)
    * Bash
      * Conditions
        * No hard points in Bash (otherwise normal synergies will apply)
      * Scaling (Damage synergy)
        * Starts with 1 "point" (5% Damage per point) at clvl 12 and gains +1 "point" every 2 levels after (14, 16, 18, etc.)
        * Max cap is 14 "points" at clvl 38 (5% * 14 = +70% Damage)
      * Scaling (Attack Rating synergy)
        * Starts with 1 "point" (5% Attack Rating per point) at clvl 18, +1 "point" at clvl 19, and +1 "point" every 2 levels after (21, 23, 25, etc.)
        * Max cap is 14 "points" at clvl 43 (5% * 14 = +70% Attack Rating)
    * Stun
      * Conditions
        * No hard points in Bash (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (8% Damage per point) at clvl 12, +1 "point" at clvl 13, and +1 "point" every 2 levels after (15, 17, 19, etc.)
        * Max cap is 14 "points" at clvl 27 (8% * 14 = +112% Damage)
    * Concentrate
      * Conditions
        * No hard points in Bash or Battle Orders (otherwise normal synergies will apply)
      * Scaling (Damage synergy)
        * Starts with 9 "points A" (5% Damage per point) at clvl 18, +1 "point A" at clvl 19, and +1 "point A" every 2 levels after up to 23, then +1 "point B" (10% Damage per point) at clvl 24, +1 "point B" at clvl 25, and +1 "point B" every 2 levels after 25 ("point A" for 21, 23 then "point B" for 27, 29, 31, etc.)
        * Max cap is 12 "points A" and 14 "points B" at clvl 49 (5% * 12 + 10% * 14 = +200% Damage)
      * Scaling (Magic Damage synergy)
        * Starts with 1 "point" (1% Magic Damage per point) at clvl 30 and +1 "point" every 3 levels after (33, 36, 39, etc.)
        * Max cap is 14 "points" at clvl 69 (1% * 14 = 14% Magic Damage)
    * Berserk
      * Conditions
        * No hard points in Bash or Battle Orders (otherwise normal synergies will apply)
      * Scaling
        * Starts with 15 "points" (10% Magic Damage per point) at clvl 30, +1 "point" at clvl 31, and +1 "point" every 2 levels after (33, 35, 37, etc.)
        * Max cap is 27 "points A" at clvl 53 (10% * 27 = +270% Magic Damage)
  * Warcries
    * Shout
      * Conditions
        * No hard points in Shout (otherwise normal synergies will apply)
      * Scaling
        * Starts with 1 "point" (10 Seconds per point) at clvl 24 and +1 "point" every 2 levels after (26, 28, 30, etc.)
        * Max cap is 27 "points" at clvl 76 (10 * 27 = +270 Seconds)
    * Battle Orders
      * Conditions
        * No hard points in Shout (otherwise normal synergies will apply)
      * Scaling
        * Starts with 9 "points" (10 Seconds per point) at clvl 24, +1 "point" at clvl 25, and +1 "point" every 2 levels after (27, 29, 31, etc.)
        * Max cap is 27 "points" at clvl 59 (10 * 27 = +270 Seconds)
    * Grim Ward
      * Conditions
        * No hard points in Find Potion (otherwise normal synergies will apply)
        * No soft or hard points in Grim Ward (otherwise normal synergies will apply)
      * Scaling
        * Starts with 6 "points" (-5% Physical Resist per point) at clvl 24, +1 "point" at clvl 25, and +1 "point" every 4 levels after (29, 33, 37, etc.)
        * Max cap is 12 "points" at clvl 45 (-5% * 12 = -60% Physical Resist)
    * Battle Command
      * Conditions
        * No hard points in Shout (otherwise normal synergies will apply)
      * Scaling
        * Starts with 12 "points" (10 Seconds per point) at clvl 30, +1 "point" at clvl 31, and +1 "point" every 2 levels after (33, 35, 37, etc.)
        * Max cap is 27 "points" at clvl 59 (10 * 27 = +270 Seconds)