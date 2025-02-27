```
################################################################################
#   _____                                                                      #
#  /  ___|                                                                     #
#  \ `--.  ___  _ __ ___ ___ _ __ ___ _ __                                     #
#   `--. \/ _ \| '__/ __/ _ \ '__/ _ \ '__|                                    #
#  /\__/ / (_) | | | (_|  __/ | |  __/ |                                       #
#  \____/ \___/|_|  \___\___|_|  \___|_|                                       #
################################################################################
```
Rather than making a pact, learning a mystic art, or begging a god for magical abilities, Sorcerer's have magic come to them naturally. Either by birthright or by happenstance, Sorcerers are the generators and conduits of their own magical energy.

## Hit Die
Your hit die is a d4

## Starting Hitpoints
Your starting hitpoints are 4 + your constitution modifier

## Skills
You gain proficiency in 2 skills of your choice. You also gain proficiency in will and Mana.

```
| --------------- | -------------------------------------------------- |
|  Proficiency    |  Applicable Items                                  |
| --------------- | -------------------------------------------------- |
|  Armor          |  None.                                             |
| --------------- | -------------------------------------------------- |
|  Weapons        |  Daggers, Clubs                                    |
| --------------- | -------------------------------------------------- |
|  Tools          |  None.                                             |
| --------------- | -------------------------------------------------- |
|  Saving Throws  |  Dexterity or Intelligence, Constitution           |
| --------------- | -------------------------------------------------- |

```

```

LVL = Level
XP = Total Experience For Level              
HD = Hit Dice
Prof = Proficiency Bonus
DML = Dark Magic Limit
ST = Amount of Sorcerer Techniques
+-----+-------+----+-----+-----+-----+------------------------------------------------------+
| LVL | XP    | HD |Prof | DML |  ST | Features                                             |
+-----+-------+----+-----+-----+-----+------------------------------------------------------+
|   1 |     0 | 2  | +1  |  1  |  0  | Supernatural Origin, Mana Casting                    |
|   2 |   300 | 4  | +1  |  3  |  0  | Hitpoint Increase, Dark Magic Release                |
|   3 |   900 | 6  | +2  |  5  |  2  | Sorcery Techniques, Hitpoint Increase                |
|   4 |  1800 | 8  | +2  |  7  |  3  | Supernatural Origin Feature, Minor Hitpoint Increase |
|   5 |  3600 |10  | +2  |  8  |  3  | Ability Score Increase                               |
|   6 |  6100 |12  | +2  | 10  |  3  | Supernatural Origin Feature                          |
|   7 |  9100 |14  | +3  | 14  |  4  | Dark Magic Techniques                                |
|   8 | 13100 |16  | +3  | 18  |  4  | Ability Score Increase                               |
|   9 | 22600 |18  | +4  | 24  |  4  |                                                      |
|  10 | 44600 |20  | +4  | 32  |  5  | Epic Spells                                          |
+-----+-------+----+-----+-----+-----+------------------------------------------------------+

```

### Supernatural Origin
Your sorcerous powers originate from somewhere, be it through being touched by a god or through a connection to another realm, pick one sorcerous origin from the following:

- Corrupt Soul
- Eldritch Heart
- Fireblood
- Rotmind 

the specific features of each supernatural origin may be found at the end of this document.

### Mana Casting
You have the ability to alter reality at its most basic level, energy that flows through all of creation, the essence of all magic: Mana. You may move mana around you to shape magic into being, but doing so builds up dark magic capable of consuming you entirely. Your casting modifier for these spells is constitution. when a spell refers to a saving throw the DC is 8 + Your Proficiency Bonus + Your Constitution Modifier. Refer to the dark magic limit column of the sorcerer level chart to determine how much dark magic you can withstand before facing consequences. 

You may cast a spell while your magic buildup is full, but you will become corrupted. If you cast a spell that puts your dark magic accumulated over your limit then you will take necrotic damage equal to the amount of points you are placed over your limit and roll a mana check against 12 + the limit overage or else gain a corruption according to the rules of the [Accursed Journal](https://github.com/ErinaTheDummy/SwordToShield/blob/main/Gamemaster_Resources/AccursedJournal.md). The specific table you will roll on is dependent on the level of the last spell you cast, meaning that casting lesser spells will cause less detriment. Refer to the following chart:

```
| Spell level | Dark Magic Buildup |    Roll Table     |
|-------------|--------------------|-------------------|
| cantrip     |                  0 | N/A               |
| 1st         |                  1 | Neutral           |
| 2nd         |                  3 | Minor Detrimental |
| 3rd         |                  4 | Minor Detrimental |
| 4th         |                  8 | Bad               |
| 5th         |                 16 | VERY BAD          |
| 6th         |                999 | VERY BAD          |
``` 

At level 1 You learn 2 cantrips and 3 first level spells from the sorcerer spell list. Each time you level up you learn a spell of a level you are capable of casting without surpassing your dark magic limit, no more than 5th level, from the sorcerer spell list. A sorcerer who knows a spell that you do not may teach you that spell over the course of one week. You lose all dark magic buildup after a rest.

### Hitpoint Increase
Your hitpoints increase by 1d4 + your constitution modifier. If your constitution modifier increases by any means, reflect that change retroactively in your maximum hp.

### Dark Magic Release
As a bonus action you may release your build up dark magic. All creatures within 10 feet of you must make a dexterity save against your dark magic accumulated or take necrotic damage equal to five times your proficiency modifier. After performing this release your dark magic resets to 0 and you lose the ability to cast your maximum spell level available, which is the highest level of spell you can cast without going over your dark magic limit. This effect compounds until you are left only with cantrips and is removed when you rest.

### Sorcery Techniques
You have gained an intermediate level of skill with spellcasting, and begin to find ways to mix up your spells or cast them differently. You learn two sorcery techniques. Refer to the sorcery techniques column of the sorcerer level chart
to determine how many sorcery techniques you know at a given level. You may learn one additional sorcery technique from a sorcerer who spends 14 days training you on how to do it.

### Minor Hitpoint Increase
At 4th level, and every level after, add your constitution modifier to your maximum hitpoints. If your constitution modifier increases by any means, reflect that change retroactively in your maximum hp.

### Ability Score Increase
You may increase one of your ability scores by 2 or two of them by 1. You may forgo your ability score increase and take a feat instead.

### Dark Magic Techniques
At 7th level you may either succumb to the temptations of dark magic and gain power or resist its whispers and gain a greater amount of control over it. Choose one option from the following:

- **Darkness Consume Me:** Your Darkness limit doubles, and you become immune to bad corruptions (but not VERY BAD ones), but each time you cast a spell you gain a neutral corruption, and you lose the Dark Magic Release feature. If your dark magic accumulated reaches 500 or greater you explode into a massive ball of necrotic energy, dealing 12d6 necrotic damage to all creatures within 360 feet.
- **Leave Me Darkness:** Your Dark Magic Release feature may be activated as a free action and its radius and damage is doubled. 
- **Darkness Needs Light:** Your Dark Magic Release feature changes to require your entire turn (action, bonus action, and movement), but does not reduce your maximum spell level at all.

Alternatively you may reject dabbling in the dark arts entirely and learn 7 spells.

### Epic Spells
You are capable of casting 6th level spells, Spells which are so strong that they incur great physical toll. When you cast a 6th level spell, you lose the ability to cast spells for 1d4 * 7 days (unless you have the **Darkness Consume Me** technique). You may not cast a 6th level spell more than once in a year.

---

# Supernatural Origin

## Corrupt Soul
You gained your magical abilities through your soul being exposed to the perfect amount of corrupted mana at some point throughout its existence. Your magic is unreliable at best, and massively powerful at worst. Roll or choose any amount of quirks you'd like from the following chart.

```

| Roll (1d8)   |                        Quirk                        |
|--------------|-----------------------------------------------------|
| 1            | When a creature stands near you they taste a        |
|              | metallic flavor on their tongue                     |
|--------------|-----------------------------------------------------|
| 2            | You have an additional appendage or sensory organ   |
|--------------|-----------------------------------------------------|
| 3            | a faint clicking emanates from you at all times     |
|--------------|-----------------------------------------------------|
| 4            | Your eyes blink sideways                            |
|--------------|-----------------------------------------------------|
| 5            | You have one neutral corruption                     |
|--------------|-----------------------------------------------------|
| 6            | Corrupted mana feels good on your skin              |
|--------------|-----------------------------------------------------|
| 7            | You crave to eat strange substances such as uranium |
|--------------|-----------------------------------------------------|
| 8            | You feel hot at all times                           |
|--------------|-----------------------------------------------------|

```

### Origin Spells
You gain the following spells thanks to your supernatural origin. These spells do not count against your spells known.

```

|  Spell level   |  Spell                              |
| -------------- | ----------------------------------- |
|  1st           |  Bane, Divine Favor                 |
|  2nd           |  Enhance Ability, Enlarge or Shrink |
|  3rd           |  Corrupt, Gills                     |
|  4th           |  Confusion, Giant Bug               |
| -------------- | ----------------------------------- |

```

### Arcane Adaptation (level 1)
You have an innate ability to control the corruption your magic has upon your body. When you wake up after a rest you may grant yourself two beneficial corruptions of your choice which are dispelled next time you rest.

### Battle Corruption (level 4)
Whenever you target a creature with a spell, you may gain 1 dark magic and expend 2 hit dice to force them to make a constitution saving throw against your spellcasting DC. on a failure they are inflicted with one of the following corruptions of your choice for the next minute, after which time their body returns to normal.

- Eye Flaps
Flaps of skin grow over the targets eyes, blinding them for the duration
- Twisted Limbs
The targets legs and arms grow gnarled and twisted, spiraling outwards from their torso. The target has disadvantage on weapon attacks and their movement speed is halved for the duration.
- Redundant head
An extra head grows on the target and begins fighting for control of their body. For the duration, if the target makes an attack or casts a spell they must make a wisdom saving throw against your save DC or target themself.     

### Corruptive Correction (level 6)
The mana you manipulate is corrupted by your very touching it. Each time you cast a spell roll a d20. On a 19 or 20 the damage of the damage or duration of the spell is doubled, depending on if it deals damage or not. You gain immunity
to the effects of contact and radiative corruption, but consumable corruptants still have an effect on you.

---

## Eldritch Heart
You gained your powers through a brush with an ancient and esoteric being from the depths of reality. Your heart has grown black and hard, gnarled by the magic of some ancient evil. Roll or choose any amount of quirks you'd like from the following chart.

```

| Roll (1d8)   |                        Quirk                        |
|--------------|-----------------------------------------------------|
| 1            | Each beat of your heart is slightly painful         |
|--------------|-----------------------------------------------------|
| 2            | Your blood is black and thick like ink              |
|--------------|-----------------------------------------------------|
| 3            | Shards of black and green crystals and metals grow  |
|              | from your back                                      |
|--------------|-----------------------------------------------------|
| 4            | Your nightmares are haunted by an unimaginable      |
|              | creature beyond your understanding or recall        |
|--------------|-----------------------------------------------------|
| 5            | You obsess over letters and number in random,       |
|              | nonsensical patterns                                |
|--------------|-----------------------------------------------------|
| 6            | Your eyes resemble those of an octopus              |
|--------------|-----------------------------------------------------|
| 7            | Your hair turns black and produces an ink-like goo  |
|--------------|-----------------------------------------------------|
| 8            | You feel uncomfortable sleeping unless you're       |
|              | suspended in air or water                           |
|--------------|-----------------------------------------------------|

```

### Origin Spells
You gain the following spells thanks to your supernatural origin. These spells do not count against your spells known.

```

|  Spell level   |  Spell                                             |
| -------------- | -------------------------------------------------- |
|  1st           |  Chilling Tendrils, Entangle (looks like tentacles)|
|  2nd           |  Read Mind, Crown of Madness (looks like worms)    |
|  3rd           |  Hunger of Horrors, Vass' Psychic Blast            |
|  4th           |  Nightmare, Blight (looks like tentacles)          |
| -------------- | -------------------------------------------------- |

```
### Mindlink (level 1)
As an action you may choose to create a psychic link between you and up to 3 creatures, this mindlink lasts for 1 hour. For the duration you and the other mind linked creatures may communicate psychically with each other over any distance as long as you are on the same plane.

### Esoteric Static (level 4)
As a reaction to being targeted by an attack you may gain 1 dark magic and expend 2 hit dice to create a field of esoteric energy to fog the minds of those around you. All hostile creatures within 30 feet of you and the creature that targeted you must make a charisma saving throw against your spell save DC or be paralyzed until your next turn.  

### Eldritch Form (6th Level)
You power grows and festers beneath the surface, allowing you to unleash it fully in short bursts through massive energy expenditure. You may expend a bonus action and 5 hit dice on your turn to gain the following benefits for 10 minutes:

- You gain a hovering flying speed of 60 feet
- You gain a swimming speed equal to twice your walking speed.
- You gain truesight
- You become slimy and squishy, being able to fit through a hole as small as 1
square inch.
- You gain 5d8 temporary hitpoints
- Your appearance may alter drastically or stay exactly the same

---

## Fireblood
Either through draconic or hellish lineage, your magic tends towards fire and flame. Boiling, burning blood runs through your body and all that it touches is empowered with mana.

```

| Roll (1d8)   |                        Quirk                        |
|--------------|-----------------------------------------------------|
| 1            | You are constantly hot to the touch                 |
|--------------|-----------------------------------------------------|
| 2            | Your blood resembles lava and turns to rock when it | 
|              | dries                                               |
|--------------|-----------------------------------------------------|
| 3            | Scales of hardened rock grow on the surface of your |
|              | skin                                                |
|--------------|-----------------------------------------------------|
| 4            | Your eyes resemble those of a goat or a lizard      |
|--------------|-----------------------------------------------------|
| 5            | You become engulfed in flames whenever you are      |
|              | enraged, these flames are harmless                  |
|--------------|-----------------------------------------------------|
| 6            | Light emanates from your mouth when you open it     |
|--------------|-----------------------------------------------------|
| 7            | Your hair is replaced by flowing fire               |
|--------------|-----------------------------------------------------|
| 8            | Water you stand in bubbles as if boiling in a 2 inch| 
|              | radius around you                                   |
|--------------|-----------------------------------------------------|

```

### Origin Spells
You gain the following spells thanks to your supernatural origin. These spells do not count against your spells known.

```

|  Spell level   |  Spell                                             |
| -------------- | -------------------------------------------------- |
|  1st           |  Burning Hands, Hellish Rebuke                     |
|  2nd           |  Scorching Ray, Flame Blade                        |
|  3rd           |  Fireball, Elemental Weapon                        |
|  4th           |  Wall of fire, Shield of Flame                     |
| -------------- | -------------------------------------------------- |

```

### Burning hot (1st Level)
Whenever you cast a spell that deals fire damage, roll an addition damage die and substitute the lowest roll with the result. Whenever you take fire damage from an enemy, regain 3 hitpoints. 

### Wings of Flame (4th Level)
As a bonus action you may expend 2 hit dice and gain 1 dark magic to envelope yourself in roaring flames. You gain 4d6 temporary hitpoints and for the duration any melee attacks against you take fire damage equal to the damage dealt. You also gain 60 feet of flying speed. This envelop of flames dissipates when you have no remaining temporary hitpoints. 

### Supernova Accustomed (6th Level)
Due to the boiling blood pumping through your veins, you have become accustomed to the heat. You become immune to fire damage and excessively hot weather has no effect on you. Additionally, When you cast a spell that deals fire damage it burns exceptionally hot, making it ignore fire resistance and treating immunity as resistance.

---

# Sorcerer Techniques

### Quickened Casting
You expend a hit die and change the casting time of a spell that takes 1 action to cast to 1 bonus action

### Dual Spell
You attempt to double the casting of a spell that targets a single creature. Expend a hit die and a number of mana points equal to the level of the spell cast  (1 for cantrips). You cast the spell twice instead of once. You may only use Dual spell once in a turn.

### Subtle Casting
You expend a hit die and cast a spell without any vocal or somatic components. 

### Curved Spell
You expend a hit die and make a spell that targets one creature appear as if it is going to miss and then curve it back at them during the last moment. The spell gains a +2 to its attack roll.

### Heightened Casting
When you cast a spell you may expend a hit die as you attempt to heighten the damage of a spell. You may reroll one die of your choice for the damage of the spell.

### Defensive Spell
When you cast a spell with a target of self you may expend a hit die to grant yourself temporary hitpoints equal to your casting modifier.

### Distant Casting
When you cast a ranged spell you may expend a hit die to double the range of the spell. If you use this technique on a touch spell the range becomes 30 feet.

### Difficult Spell
You cause the save for a spell to become extremely difficult. You may expend a hit die, giving the target disadvantage on the saving throw of the spell. 

### Safe Spell
You protect your allies by bending a spell that affects an area around them. Expend 2 hit dice and 4 creatures of your choice within the area of the spell are unaffected until the start of your next turn.

### Raw Spell
You cast a damaging spell without changing the form of the mana used in it. when you cast a spell that deals damage you may expend 1 hit die to change the damage type to force. 

### Mana Boost
You are capable of using latent magic to guide your ability checks. When you fail an ability or skill check you may expend 1 hit die and reroll it.

---

# Sorcerer Spell List

## Cantrips
- Acid Splash
- Necrotic Grasp
- Control Fire
- Create Fire
- Lights
- Flame Bolt
- Friends
- Frostbite
- Control Air
- Swarm
- Lightning Whip
- Mage Hand
- Mending
- Message
- Cut Thoughts
- Minor Illusion
- Shape Earth
- Poison Spray 
- Prestidigitation
- Bestial Visage
- Produce Flame
- Ray of Frost
- Shape Water
- Shocking Grasp
- Thorn Whip
- Thunderclasp
- True Strike

## 1st Level Spells
- Frost Armor
- Shield
- Magic Missile
- Mage Armor
- Entangle
- Create Familiar
- Befriend Animals
- Burning Hands
- Charm Person
- Chromatic Orb
- Comprehend Languages
- Create or Destroy Water
- Detect Magic
- Disguise Self
- Discordant Voice
- Retreat
- Glowing Lights
- False Life
- Feather Fall
- Fog
- Fast Feast
- Grease
- Jump
- Longstrider
- Sickening Ray
- Sleep
- Beast Tongue
- Thunderwave
- Witch Bolt
- Summon Green Slime

## 2nd Level Spells
- Alter Self
- Morph Shell
- Obscure
- Calm
- Cloud of Daggers
- Crown of Madness
- Darkness
- Darkvision
- Read Mind
- Enthrall
- Flame Blade
- Wind
- Heat Metal
- Hold Person
- Lesser Invisibility
- Knock
- Float
- Misty Step
- Ray of Enfeeblement
- Scorching Ray
- Lesser Truesight
- Shatter
- Silence
- Spider Climb
- Suggestion
- Rewind


## 3rd Level Spells
- Blink
- Clairvoyance
- Create Food and Water
- Dispel Magic
- Fear
- Fireball
- Flight
- Haste
- Hypnotic Spiral
- Lightning Bolt
- Major Image
- Nondetection
- Summon Mount
- Plant Growth
- Proof From Energy
- Sending
- Slow
- Plant Tongue
- Stinking Cloud
- Tongues
- Draining Touch
- Gills
- Water Walk
- Vass' Psychic Blast
- Stoneskin
- Snowball

## 4th Level Spells
- Banish
- Blight
- Confusion
- Control Water
- Dimension Door
- Beguile Creature
- Shield of Flame
- Freedom of Movement
- Greater Invisibility 
- Ice Storm
- Phantom Hound
- Bubble
- Polymorph
- Wall of Fire
- Cloudkill
- Antimagic Field
- Cardiac Arrest
- Conjure Devil
- Scrying

## 5th Level Spells
- Summon Undead Horde
- Conjure Demon
- Disintegrate
- Time Stop
- Gateway
- Perish
- Invincibility
- Shapeshift
- Raise Dead
- Mindwash

## 6th Level Spells
- Black Hole
- Time Jump
- Grand Resurrection