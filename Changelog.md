### Changelog - Not fully updated, requiring previous commit notes


# 4/6 - v1.0.1
First ever use of Github. Previous updates to BD will be noted in a changelog. Currently working on porting content over and formalising their format.

# 4/6 - wizard updates 1.0.1.1

(no commit description...)

### wizard flavour text updated
All wizards share one unified type of aspects - spells. Spellcasting defines a wizard as much as their wand or pointy hat. It's the core of their class, and all of a wizard's class features come together to enhance their spellcasting. The wizard has the largest spell list - if not, largest aspect list, out of any class, offering no lack of options at all - from the whimsical and wonderous to the earth-shattering.

### the Blue Mage
The term wizard is a modern invention. In the ancient era of blue divinity, wizards were Blue Mages, capable of manipulating the blue-tinged colour of mana that seeped from ley lines. Even to this day, Wizards rely on this mysterious substance for sustained spellcasting or to brave intricate, high-tier spells; However, their own internal soul is more than enough to sustain most of their magical needs.

### schools of wizardry
Wizards often pursue specific branches of magical thought and expertise as they further their learning. the specific schools vary from different arcane academia across the world. For your PC, these are the subclass options your wizard character can choose from upon hitting milestone 1.

## 5/6 - v1.1.1

Ported over wizard details
added spell list. needs refinement.
second commit later in day.

# 6/6 - v1.1.2
1. massive class overhaul - removal of the warden archetype fully, tested with the idea of the lucent, and more.

2. expanded priest and bard into theurge and sophist, allowing for broader, more interesting class dynamics and themes.

3. Shifted oracle into a luminata pure caster, which makes sense. The theurge sits next to them.

4. The medium and artificer are made optional classes depending on the setting.

5. already begin working on balancing things like skill slots and the like, planned to be next.

6. near finalised class grid. pretty unlikely to change main power source of any class.

commit et al

# 7/6 - v1.1.3
Accidentally committed under the same version as last time. changes are made below:

Massive updates. Introduced the 11 aspects of magic in their finality, as action verbs for what magic can do.

cut out perception, metamorphosis, disortion, chaos, Miracle, as they were too overlapping with existing aspects of magic.

potential huge progress with the  sophist and the wizard. Soon to see what's going to happen when they recieve their appropraite aspects of magic.

added Information, mutation, destruction, fabrication. Adding new vectors for magic to be expressed within.

Updates coming very soon.

## 7/6 - created changelog.md and dev branch in github.

# 8/6 - 1.1.4 
Large shakeup into the aspects of magic. Removed overly niche ones (animation, destruction), and added general verbs: Fabrication, manipulation, restoration.

each covers large parts of the game that previously had no home. Fabrication finds a neat home for wall of force as it does prismatic spray.

manipulation is huge - everything from animate objects to dominate person, this is a huge gap finally plugged. mainly limited to physical matter.

Restoration is a simple, but crucial one. healing spells, full stop, rely on this cateogry.

manifestation has definitively taken over conjuration's role, and cleaned up a lot of mess with transportation and fabrication.

is all.

# 9/6 - 1.1.5
- Default format for aspects of magic created. Each magic action now has its dedicated collection to start writing aspects into.

- 11 aspect tiers finalized. A design choice that surely won't haunt us in the future.

- Unsure if there should be another Chaos action verb. to cause chaos. Distortion is also a pretty poignant one, but we'll have to see just how necessary they are.

# 23/06 - v1.1.6

#### Design philosphy: start classes on equal footing from lv1, to start in the "goldilocks zone" of play ASAP.
What this requires is shrinking the game down to streamline out any potential bloat levels. we keep our 11 tiers of aspect progression, But now classes progress through different Tiers - to different Caps. <br><br>
In this sense, a "half caster" in dnd's closest equivalent here (a T2-3 class) would still retain full, linear progression through 8 tiers of aspects. The only difference is they begin and finish at a lower tier, meaning their aspect potency is **always** lower and less versatile than a dedicated T0-1 caster. <br><br>
This is in line with the philosphy that "martials" should still get supported, Linear progression through their aspects. it's simply that their threshold for power is lower, so they rely on it less and gain more boons elsewhere.
<br><bR>
This in turn makes aspect reliant classes start at a very reasonable T3 aspects, progress up to T10-11 to 7/8 tiers of aspects, through a 15 level full progression. This streamlines the game down to its sweetest balance of mechanical power and narrative weight.

## Base mechanics
- sticking to using a baseline aspect progression through 11 tiers. Finalised decision.
- Classes progress through tiers 3-10 depending on aspect potency and reliance.**
- Tier 11 relegated to endgame play.
- Level 0 introduced. Specific rules required.


### class specific changes
- **certain classes struggle in early game levels of legacy d20 systems, such as Wizard, due to their reliance on their spells. For this reason, to make sure everyone is on "equal footing" starting from level 1, T0 casters begin at aspect T3 to balance them out against T2-3s with armor and weapon proficiency. 

### The Lore trait
- the lore trait now serves as the mental threshold needed to hold aspects in your head. it's modifier is a unanimous bonus "cost" to your prepared / known aspect list. In addition, it now also grants you the "early ascension" feature, which lets you:
- - a: Gain aspects of the next tier above your limit
- - b: gain more aspects of your current higher tier.

both rewarding and incentivising builds that go heavy into their aspects, especially the **wizard, mystic, and oracle**.

## milestone mechanic 
Each class still retains it's 6 milestones, 5 of which can be gained anytime during the bracket of a new experience value. E.g, when experience increases from 2 --> 3, anywhere in the next 3 levels a DM can choose to hand out a milestone, provided there is at least 1 level in between.
<bR><br>
1. This allows for narrative satisfaction. If the players gained a level but the DM feels like they lack the right narrative milestone to make that moment a serious increase in their adventuring experience and power, they can save that milestone for later. 
2. The DM can also choose to start at whatever Milestone they like, such as potentially delaying it from M0, or starting an experienced group from M1-2.

An important **narrative** change that's directly baked into the mechanics of the game, allowing for just enough flexibility whilst keeping progression smooth.

## The trait system
- the introduction of a sixth trait is delayed, as its utility is currently unknown and may add unecessary feature bloat.
- Currently, the spread of character skills has been refined into an early list of options through the 5 traits.
- The skill action is streamlined into a 2AP action that can continuously eat up AC or stretch multiple turns, meaning it transitions seamlessly from exploration / social into combat. *
- *this means time based social encounters are now relevant, and reliant on initiative. This is being refined into a specific **"Timed turns"** state with its own rules, and the oracle and mystic can tap into this metagame.

### skilled and experience
- **"skilled"** Simply means you can use that skill action with another appropriate trait, depending on your class, the situation, and ultimately, the DM's ruling. this simply means you're proficient enough with the skill or have a natural talent for it.
- **"experienced"** is a specific character tag dependant on your **Experience** bonus modifier. This is added onto d20 tests with said skill - check or save.
- both are not mutually independant. A character is often advised to have both for their core skills.

### the social action
- no longer a need for a "charisma stat".
- - 1: Social actions are now specific actions you can take that involve other traits. No longer an arbitrary check, the game fully supports intricate social dynamic and debate.
- - 2: Classes otherwise reliant on an arbitrary "sense of self" have either recieved proper mechanical grounding into a similar power source, or in the case of the sorcerer, currently relegated to a background lineage boon or a potential future class. (elements caster perhaps?)

## trait associated skills (important)
**tenacity**:
- Shove 
- Grapple
- leap
- Dash / Sprint - seperate AP costs and utilities.
- Climb / swim (+climbing or swimming speed, doesnt override but adds onto racial / aspect speeds)
- unarmed attack (w/finesse) - break things with brute force.
- medicine (w/lore) - can't heal others with tenacity medicine checks, but can take as a self-preventative measure.

Social: intimidate.

**Finesse**:
- stealth: requires continuous AP drain if being observed / creatures suspicious.
- sleight of hand: any nimble dexterity.
- unarmed attack (w/finesse) - attempt a precise manouvre.
- Tinker (w/ finesse) - make simple objects or solve intricate physical problems.
- dodge / disengage: Finesse makes these significantly easier.
- Hone: Aim with precision, Spend AP to raise potential critical strike chance. 

Social: performance, + sleight of hand can be taken in the same action.

**Lore**:
- logic: solve immidiate problems
- search (w/ sense): active search and query
- Knowledge: recall information
- blank: clear your mind, potentially relieving the charmed / frightened condition. potentially resist ambient psionic / mental intrusion.
- Tinker (w/ finesse) - make simple objects or solve intricate physical problems.
- medicine (w/tenacity) - attempt healing and prevent injury (to yourself and others)

Social: persuade/decieve, reason

**Sense**:
- percieve: Notive something, or focus on it.
- alert: become resistant to surprise, and force stealth checks.
- search (w/lore): use instinct to feel for clue
- Hone (w/finesse): Spend AP to raise potential critical strike chance. 
- Second sense: use a second sense (darkvision/tremorsense/truesight). may continuously expend AP.

Social: insight, +percieve can be taken in the same action

**arcana**:
- rejuvinate: if nearby magical reservoirs, refill mana / other resources.
- attune / disattune
- dispel / counter (simple magic)
- Resist: attempt resistance against ambient magical force - wild magic, planar rifts, etc. (i dont know if this will be final)
- resonate: attempt to reveal the magical signiature via resonance.

Social: Commune (w/ dead, w/ deity, w/nature)

### trait stat boons
Each trait gives a specific, generically useful stat buff equal to its modifier.

Tenacity: HP, rest HP bonus, and slower exhaustion. <br>
Finesse: movement speed. potentially intiative if higher than sense. <br>
Lore: aspect cost bonus, aspect tier ascension <br>
Sense: critical rate and reduced critical rate against, and initiative if higher than finesse. <br>
Arcana: increases the energy pool of any class, and gives a generic damage bonus to aspects. <br>

## generic class progression: Wizard alpha

| Character level | Experience | Milestone features | cantrips | T1 | T2 | T3 | T4 | T5 | T6 | T7 | T8 | T9 | T10 | T11 |
|:------------------|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0  | +1 | Spellcasting, scribe spell | 3 | 4 | 2 |  |  |  |  |  |  |  |  |
| 1  | +2  | arcane recovery, signiature spell, Simple modify spell | 4 | 4 | 3 | 2 |  |  |  |  |  |  |  |
| 2  | +2  | superior spellcasting, Subclass choice | 4 | 5 | 3 | 3 |  |  |  |  |  |  |  |
| 3  | +2  | - | 4 | 5 | 4 | 3 | 2 |  |  |  |  |  |  |
| 4  | +3  | Modify spell | 4 | 6 | 5 | 4 | 3 |  |  |  |  |  |  |
| 5  | +3  |- | 4 | 6 | 5 | 4 | 3 | 2 |  |  |  
| 6  | +3  | Contingency spell | 5 | 6 | 5 |  5| 5 | 3 |  |  |  |  |  |
| 7  | +3  |- | 5 | 6 | 6 | 5 | 5 | 3 | 2 |  |  |  |  |
| 8  | +4  | - | 5 | 6 | 6 | 6 |5 | 4 | 3 |  |  |  |  |
| 9  | +4  |- | 5 | 6 | 6 | 6 |5 | 4 | 3 | 2 |  |  |  |
| 10  | +4  | Fabricate spell |  5 | 6 | 6 | 6 | 5 |5  |4  |  3 | |
| 11  | +4  |- | 5 |  6|  6| 6 |5  |5  | 4 |  3| 1 |
| 12  | +5  |  - | 6 |  6  |6  | 6 | 5 | 5 | 4 |  4| 2 |
| 13  | +5  |  -| 6| 6 |6  | 6 | 5 |  5|  4|  4|  3| 1  | |  | 
| 14  | +5  | Glimpse into the arcanum |  6| 6 |  6|6  |5  |5  |4  |  4| 3 |  2|  |
| 15  | +5  |  -|6|  6 |6 | 6|  5 |5  | 4 |  4| 3 | 3| 1 |
| 16+  | +6  | Height of magic |6| 6|  6|  6|5  |5  |4  | 4 | 3 | 3 | 2 | 1 |

# 23/06 - v1.1.7
#### core design philosophy: optimised, balanced framework, but narrative control for the DM.

## first alpha wizard table. More class features, scaling cantrips, and increased experience thresholds.
- made significant changes to the progression of the class. instead of a level 1 "everything dump", they now stagger it throughout for a smoother, more player friendly progression. 
- Milestones are STILL DM agnostic. If the DM wants to run campaigns where milestones are detached from levelling, or tweak power dynamics to a specific subset, they can do that.
- a class should function fine withotu their abilities post levels 1-2. The DM can artifically inject "level us" where they don't gain a level but a milestone instead.
### class design: the tradeoff (v1.1.7.2)
- the core tradeoff is to optimise for modularity, balance, and a streamlined experience, it required sacrificing a degree of class variety. Now, every class gets x power increase at y level. This is **amazing** for a functional, balanced game, and of course, for the DM.
- the counterpoint is streamlining reduces character variety to a degree. it's for a crowd that values a functional, balanced game, rather than one where character flavour comes first. it intends to cater towards modern, efficient play.

## the thematic lever: milestones (v1.1.7.2)
- to still ensure that DMs who enjoy long stretching, narrative focused campaigns, they can still fully enable the milestones as "pauses" - serving as session rewards without granting a full level. These milestones are brief enough that they can be compressed into an adjacent level if needed, but impactful enough to be worth their own dedicated session.
- the milestones are placed in moments where players may need to "breathe" through progression. They offer chances for characters to get used to their Kit, and simultaneously serve as major, all-class rewards for overcoming a massive narrative moment. 
It also allows "experience points" to go towards a different goal rather than  levelling up, which a DM may feel players  are not yet ready for.

## the wizard class (v1.1.7.2)
a brief synopsis - a lot of details to come @ next update!!

### new class features
- glimpse into the arcanum
- height of magic
- minor modify spell
- arcane recovery
- scribe spell & foci merged
- Superior spellcasting

### changed class features
signiature spell compressed into one feature. Now accessed through class talents.

#### class progression
- class block cleaned up through the 15 levels. multiple adjustments from the block above.
- class features spread out through 0-2, meaning a fully playable wizard at lv1, but a rounded on at lv2.

#### new class talent options
- more options for superior spellcasting and signiature spell


## the experience mechanic
"experience" is defined through the measurement of an adventurer's well, experience. it serves as a universal modifier for d20 tests or part of pools of resources, acting as the general skill level of the character. This will see continous, further refinement for where it plays a part.

# 24/06 - v1.1.8.1 Sorcerous origins introduces
a two part update spanning today and tommorrow focusing on the sorcerer origin choice, whilst making plans for background and species features and specific feats.

#### core design philosophy: A sorcerer isn't necessarily a class.
to train one's own internal power is an admirable feat, but there's already a class for that - monk, and not all sorcerous power is magical, so it's difficult to argue for a dedicated sorcerer class, as of right now. <br><br>Something like it though is definitely planned.

## sorcerous origins
Taking a sorcererous origin is a huge investment. It sacrificies three core character pieces:
- species feat: replaces the unique feat offered through your species
- background: all sorcerers can have a narrative background, but their mechanical background is **sorcerous lineage** - which dictates terms from here on out.
- Your subclass: for most classes, their subclass is at level 2 or earlier. That doesn't matter, since all sorcerers get their first feature at level 0, and simply offers an additional boon at that level replacing the subclass features. It then entirely replaces subclass progression with a sorcerous soul progression
- Milestones. Currently unsure how to configure this - as milestones are pretty important pieces of a character's progression. Currently, the game is built around 5-6 major milestones: One at each even level 2,4,8,10,12,15. Taking a milestone away from a class is a pretty big deal, so I'm not too sure how to feel about this.

### different origins and their thematic flavours
- "soul" lineages: A direct piece of your ancestry, where your power - usually magic, comes from an internal wellspring as a gift from your ancestors or creators: **Divine soul, draconic soul, eldritch soul, primal soul**.
- "born" suggests a more esoteric, direct origin from the stars - **starborn**, or the weave itself - **weaveborn**, creating characters with thrilling, cosmic questions as part of their backstory.
- "walker" - characters that continued to live (walk) despite their circumstance - some coming back from the dead: **gravewalker**, some exploring the world as a dream / spirit: **dreamwalker**. This offers a drastically different physiology that transforms your physical presence.
- "mind" - a direct alteration to your psyche, biological or psychological. either a mind capable of posthuman perception: **psychic mind**, or one goverend by the order of technology: **mechanical mind**

### optional additional options.
These are, frankly, just stronger options and need significant testing to ensure balance and proper cohesion. These may also be turned into direct classes from now on out.

 - **moonsilver**: the material name. Moonsilver sorcerers have a rotating aspect list that allows them to manipulate gravity. 
- **rosegold**: another material. Rosegold sorcerers can use hemomancy and transmutate flesh.

## class changes
### new classes & replacements
- **rogue** finally retired. The word carried too much baggage to make it into a new system without some inevitable expectations of a martial type character.
- **warlock** allowed to fully explore the estoeric side of dark magic, leaning into necromancy and witchcraft as valid pathways.
- **mystic** and **oracle** replaced or shuffled as below:

### new classes
- **mystic**: renamed the psionic user the **psion**, to bring the elusive, obscure term "mystic" into the Noctira bracket. not final. It's the companion class to the warlock, acting as a class to host multiple unique roguish archetypes, along with a general focus on the serenity, and stillness of darkness, drawing heavily from nocturnal and lunar theming.
- **lucent** replaces **oracle** to prevent linguistic overlap between mystic and oracle. the lucent suggests something softly glowing and translucent, acting as the backline "white mage" whilst reviving themes of solar radiance, paladin auras, and etherealness into a luminata class, allowing the theurge to lean closer towards a battlemage role with divine protection and martial weapons (IF they wish).

# update 25/06 - Mystic class updates. v1.1.9.1
updated simultaneously with the sorcerer. The sorcerer update v1.1.8 will continue to recieve updates as this progresses too into v1.1.9.x

#### design philosophy: like sophist is to bard and theurge is to cleric, expand the "rogue" - a term with significant baggage, into its own soverign class.

## the mystic class
mystics have a strong theme relating to the stillness and serenity of darkness, especially with cosmic themes of night, moon, and the darkness of space that can push and pull.<br> If a warlock uses dark power - like a sophist charms with the arcane, the Mystic is to the warlock what the sophist is to the wizard. A philosopher, practioner, purveyor of dark, of any type, and what roams within that dark. 
<br><br>
1. They serve as an excellent expansion on to roguish soulknife and assassin archetypes, capable of precise, critical damage by bypassing armor or striking through shadows. They are immaculate single target DPSes.
2. They are powerful scouts, offering the ability to manipulate darkness into cover, or slip right past said cover through the shadows, or fashion deadly blades from nothingness. They offer a mix of infiltration tools that makes them uniquely valuable thieves and scouts, yet expanding their mix out into offering some defense and support.
3. they fool the senses and the soul itself. Specialising in AATK damage, Mystics are lethal against traditional defenses, capable of powerful aspects like *darkshock, negative knife,* or *Nanoblack*. This lets them cut through metal, flesh, or a magical shield alike, making them both excellent combatants but also a simple solution to an exploration puzzle.

### the resource system
The Mystic should have two resources - waxing and waning like the moon. One that increases *as* they spread darkness, or are within it, serving as a "situational boon", and a standard mana pool that regenerates a little slower than the warlock.

1. Noir. a variant on dark mana (warlock). Their noir value also is a direct boon to their general crit rate and stealthiness - meaning a mystic is most dangerous when they haven't acted. 
2. Veil. The specific type of veil - **twilight, Lunar, Phantom, Gloom**, etc, depends on your subclass. this offers you a boon depending on how generally dark it is around you, or just how generally stealthy you are, such as being hidden, being out of LOS, affected by invisiblity or cover, etc.

### Cunning action
When veiled or at a specific noir threshold, You can take cunning actions, slashing the AP cost of specific actions by 1 and reducing them to normal actions with no specific tag (e.g, take both dash and disengage). 

You gain one for free to start off with - read philosophy of dark below. you gain more options via milestones and can upgrade them as independant class talents.

### Shadow knife
You can perform one attack action this as an AATK attack - attempt to pierce defenses with a raised critical chance to deal massive damage. <br><br>
This value skyrockets as you level, offering more and more options to enable it to deal said ceiling of damage. Importantly, if you've got a magic action, you can wrap it into this if you have the AP to spare.

### hide in plain sight (part of veil)
As the name suggests. slowly manually increase your veil to blend in with the shadows, giving you the invisible condition at the cost of constantly eating your AP with the stealth skill action. 
<br><bR>
When hidden in plain sight, certain aspects no longer require somatic components.

### philosophy of dark
expertise - kind of? Their most interesting, customiseable component. These are class skills, but have a unique slot dedicated to them.

### nanoblack (M1)
Enter a temporary nanoblack state, where you automatically gain the ability to use NOTN on every turn and can disperse and reappear within darkness like an enhanced shadow step.

### motionless (M2)
All aspects of a certain tier or below now no longer require somatic components. <br><br>
in additon, If you somehow gain the same condition (invisible, hidden, silenced, etc) from multiple sources, it simply adds to your veil.

### evasion (M3)
A general slipperiness to PATK and MATK, allowing you the iconic half damage from success or no damage from save, provided your veil is strong enough to cover you from said damage.

### elusive (M4)
Instantly activate a cunning action when in a sticky situation - which are specific contingencies a bit like the wizard's ones. If you're: *prone, restrained, paralyzed, stunned*, etc...

## Philosophy of dark
The mystic can take a unique set of *expertise* class options, which are extremely powerful class aspects. They can only have 1-3 expertises active at any one time, the tier of which are determined by their *expertise slots*:

#### Move through dark (M1)
- gain the otherwise T2 Shadow step aspect, can use it a number of times equal to your finesse. an incredible bit of additional manouvreability.

#### cunning actions (M1-5)
each cunning action after your first require an expertise slot.

## WIP class block
| Character level | Experience |Milestone features | Dark shards | Aspect tier limit | Philo slot 1 | Philo slot 2 | Philo slot 3| 
|:------------------|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0  | +0 | Noir, Veil, Philosophy of dark, |- | - | 1 | 1 | - |
| 1  | +0  | Dark fragments, Shadow knife | 2  | 1 | 1 | 1 | 1 |
| 2  | +1  | Cunning action, subclass  | 3 | 1 |2  |1  |1  |  |
| 3  | +1  | -| 3 | 2 |2  |2  |1  |  |
| 4  | +2  |  nanoblack | 4 | 3 |2  |2  |2  |  |
| 5  | +2  |  -| 4 | 3 |3  |2  |2  |  |
| 6  | +2  | Eclipse mind, evasion | 4 | 4 |3  |3  |2  |  |
| 7  | +2  | - | 4 | 4 |3  |3  |3  |  |
| 8  | +3 | nanoblack (x2), motionless| 5 | 5 |4  |3  |3  |  |
| 9  | +3 | - | 5 | 5 |4  |4  |3  |  |
| 10  | +3  | Antimagic, Elusive | 5 | 6 |4  |4  |4  |  |
| 11  | +3 |- | 5 | 6 |5 |5  |4  |4  |
| 12  | +4 | nanoblack (x3), bend gravity |  6 | 7 |5 |5  |4  | 
| 13  | +4 | -| 6 | 7 |5 |5  |5  | 5 |
| 14  | +4 | Antimagic (x2)  | 6 | 8 |6 |5  |5  | 4 |
| 15  | +4| Miracle of dark |6 | 8 |6 |6  |5 |
| 16  | +5| lightless | 7 | 9 |6 |6  |6  |

philo = philosophy of dark slots
dark shards = warlock spell slots kind of

## update v1.1.9.2 
mainly focused on tidying up the Mystic and fleshing out their class features.
- shadow blade, piercing dark, pierce action. cleanly articulated.
- started work on nanoblack, still feels a little weak for such a poignant feature
- shuffled other abilities around to appropiate level breakpoints. Veil removed and integrated directly into the subclasses.
- further lore need for the mystic to move them away from purely roguish themes.
- need to write out philosophies of dark section.
- noir removed entirely - feature bloat. Piercing dark is already an interesting base mechanic.

#### nanoblack
the original "climb up walls as a shadow" effect is now a philosophy of dark. it no longer requires a dedicated milestone.

the new nanoblack functions as an enhanced veiled state, where your Noir is always maximum

### core design philosophy change
Class features small enough to not be a feature, but too big to be a talent, are now relegated to their philosophies. This includes piercing dark, shadow knife (which is free first one you get), and the pierce action effect. 

#### noir
Noir is brought back as a pseudo mana resource. Noir is dependant on your environment, which means the darker you are and the more time you spend within it, the more Noir you gain back. You expend it to enter "extended stealth" where you're guaranteed the stealth condition at the cost of continuous Noir expenditure. 

#### shadow meld
This is your first philosophy reccomended. it lets you consome Noir to travel through shadow - up walls, over water, etc.



### mystic v2
| Character level | Experience |Milestone features | Dark shards | tier limit | Philo slot 1 | Philo slot 2 | Philo slot 3| 
|:------------------|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0  | +0 | Philosophy of dark, Noir, |- | - | 1 | 1 | 1|
| 1  | +1  | monochrome, Dark fragments, invocations | 2  | 2 | 1 | 1 | 1 |
| 2  | +1  | Veil, subclass, | 3 | 2 |2  |1  |1  |  |
| 3  | +1  | -| 3 | 3 |2  |2  |1  |  |
| 4  | +2  | nanoblack | 4 | 3 |2  |2  |2  |  |
| 5  | +2  |  -| 4 | 4 |3  |2  |2  |  |
| 6  | +2  | skulker, evasion | 4 | 4 |3  |3  |2  |  |
| 7  | +2  | - | 4 | 5 |3  |3  |3  |  |
| 8  | +3 |  motionless| 5 | 5 |4  |3  |3  |  |
| 9  | +3 | - | 5 | 6 |4  |4  |3  |  |
| 10  | +3  | Elusive | 5 | 6 |4  |4  |4  |  

...only working on the early levels

# 07/07 - v1.9.9......almost there...

## mystic 
entirely reflavoured. Currently, it's unknown if we want to give the philosophies slot design to the warlock instead. we'll figure that out in due time.

the main focus is on the thematic design of the class. 

### Cultural inspirations
A strong inspiration from historic astronomers, anchorites, midnight watchmen, acolytes. it's a class for characters that are comfortable breathing in the dark. It's a class that intentionally doesn't want to be in the spotlight much.

### mechanical frameworks
- The mystic is primarily a PATK / AATK class. In addition, they are the unique class to natively reduce all DEF.
- as an anti-druid or anti-warlock of sorts, a mystic's Darkness is often chilling and bitter. they are amazing at shutting down effects or denying them in the first place.
- retains the roguish cunning action, but repurposed into a different system that's more mechanically versatile and thematically aligned.
- DoT specialists with a much friendlier action economy and less micromanaging.

### thematic frameworks
- certain celestial themes from the druid or theurge (circle of the stars, twilight domain) have been moved towards the mystic. That's not to say those two classes no longer can enjoy that theming, it's that the mystic has become a stronger host for the *cosmic dark*.
- a strong theme of resonance - tuning the space around them to a state of natural quiet or even cold. 
- a vast thematic theme, but entirely focused on being a friend of the dark, a class for those that dwell in the shadows with comfort. 
- intended to move away from traditonal "rogue" frameworks. Martial aptitude is demonstrated in their kit, but it's not their defining feature.

### a soulless class
the mystic is one of few rare classes that can be played with a soulless character - other than the psion. it makes them a profoundly detached class, with no need to store mana, circulate chi, or bind them to this plane. 
- mechanically, this makes them **blind to divination**. they cannot be detected easily with spells, or are captured in a divine augury. They seem to live as grey spots in the corner of your eye - and that also means their invisibly **cannot be seen**.
- further, that means they are extremely resilient to soul-interface AATKs. They cannot lose what they don't have.
- thematically, this can be a part of their core class as a specific subclass route.

## classs features (new)
### hide in plain sight
now reworked. other than a ribbon stealth bonus, this makes them entirely invisible to: **divination** magic, full stop.
and also, interestingly, **sight based detection**. provided they are hidden or invisible. They quite literally bend the light around them.

# 12 / 07 - update v1.2 - thematic overhaul.

#### beware! flowery prose ahead as i dump ideas. Clean changelogs will be written once this batch of mechanical changes is completed. 

as of writing, I still think a lot of the friction here is still trying to retrofit what the standard expectation for an RPG should look like, trying to turn classes that aren't really meant to be "spellcasters" into them via the aspect system. and all of this was trying to fit everything into a game that really didn't have the features meant to align well with a sharper, original design philosophy. it was like trying to use archaic mathematics to describe modern quantum physics.

let's start from the start. Throw out everything we've said about the classes so far. ignore the class features. ignore the martial vs caster duality. let's focus on building up the lore first.

with all of that as retrospect, let's introduce the lore of the game itself. The core game revolves around a set of mages, which are the core classes for the game.

### the mages

1. the blue mage. this is the wizard equivalent, blue mages are tained with the unnatural blue hue of the mana they weave into intricate formulae. there is no discrimination towards sorcerers; natural talent is a gift, and so is the capacity to learn.

2. the green mage. this is the druid equivalent. the green mage delves into all things natural and worldly, their color reflecting the lifeforce they shelter and vitalise. green mages hold an affinity for animals too (despite wildshape not being that central to them like an rpg druid), as they extend their aid to all of the natural realm.

3. the white mage. this is effectively our new class, the lucent, or a vague reflection of the "priest" archetype. The white mage is an architect of light, the most brilliant, pure, and primordial magic there is. their power sometimes drawn from, sometimes reflected, from the primordial light and its deities. their color is the purest shade of light there is, before it escapes what human eyes can see.

4. the Black mage. this is our new mystic. the black mage is a philosopher of dark, watching over the lonely expanse of where light does not fall, or find solace under the soft lunar glow or a soothing blanket of night. they are the least traditional of the scholars, seeking a connection that bleeds black into their color.

5. the violet mage. this is our warlock, a seeker of forbidden truths and deeper darks, whose color is as unnatural as their power - electrifying, crackling, and utterly aberrant. Some despise the color of their mana. others wield it as a prestigious symbol of pride of their identity. Some simply prefer the title warlock. others recieve it as a taboo.

6. the gold mage. this is our "oracle". the gold mage peers across the threads of time. their color is the richest color a mortal can imagine, reflecting the preciousness of their most limited resource. though to do so, many also develop minds bordering on the hyperreal to process this cosmic data, with far seeing eyes and farther thinking minds.

7. the red mage. this is our sophist / bard. the red mage's color often comes from their theatrical costumes, not the mana they channel. red mages adopt this color as a symbol of viceral passion, their power lies within the harmonies in every person and object their is. 

8. the silver mage. the most mysterious class, without a direct fantasy parallel. the kineticist fantasy (not pf2, in general) of wielding motion and force itself. Silver mages are not wizards, thoguh their studies often collide. They bend space, cross planes, reverse or ignore gravity, generate invisible force, fabricate invincible lattices, and can often control the flux of the weave itself. They are our theoretical physicists to our pure physicists of the wizard. 

### other classes that still exist....

1. the artificer. the artificer that of an innovater, a tinkerer, and often times, a creator. artificers work their way with what's left. what isn't magical, organic, or divine - the raw stone and metal beneath their feet, and work it into miraculous homunculi, experimental elixirs, enchanted equipment, or devastating siege machines.

2. the Monk. some wandering nomads. some attuned to the elements, some seeking inner perfection. Monks draw their power purely from lifeforce - qi - and once they master it within themselves, can influence the flow of it through the world.

3. the Mystic (as in, the original psion). the mystics are a mysterious order, some naturally gifted, others unerringly trained, bordering on what it means to be a mage, as many do not consider themselves that. Their power is often mistaken for being limited to just the mind, when in truth, it is perception itself. If they must attend as mages, mystics often are robed in silver color, a color that mana cannot take, yet it itself can meld with any. 

4. The medium. the medium delves deep into the world of the supernatural, and serve as undertakers, gravekeepers, and other roles too frightening for the average mage. mediums are, as their vocational name suggest, the mediator between the dead and the living, spirits and curses, the material and the abyssal planes. 

5. the theurge. Plenty still draw their power from the divine, and plenty more are sent down as divine emissaries, who still wield a sword and shield from a past age. Theurges are loyal to their divinity, though the exact connection - a lineage, an oath, a domain, or simply, a stolen power, depends on the specific theurge.

6. the nomads. though the green mages are our poster druid mirror, their study, even if natural and holistic, is still often organised - circles, rituals, ceremonies. The nomads are shamans, rangers, wayfarers, who live on the edge of civlisation, and if not, the material plane itself. Their work is often as invisible as they are; unglamorous, but often necessary duties like beast slaying, bounty hunting, or traveling across dangerous terrain.

#### will we add back the rogue?
the rogue is a thematically poignant class fantasy that doesn't really see good coverage in our current list. however, their mechanical chassis overlaps heavily with both the monk and the nomads, as they're all finesse based skirmishers that excel at dextrous tasks, stealth, and critical attacks.

## sorcerer class updates

#### the core design philosophy now: the sorcerer is intended to be a "wrapper" type class. you have the class "sorcerer" on your character sheet, but you progress through any other mage class of your choice. However, with two massive commitments:

### Subclass replacement
As we'll see later in "sorcerous soul", you cannot select a subclass. your subclass's free aspects, abilities, and class talents are entirely replaced by your sorcerous soul pathway.

### background replacement
as a sorcerer, you are defined by where you got your magic. A lineage, a curse, a freak accident, a pact, it doesn't matter. what matters is there's magic flowing in your system that makes your background visibly differnet to a normal character. Sorcerers replace their background features with **'Sorcerous origin'** instead. 

They are actually, quite strong, and tend to scale well as you progress sicne the features become tied into your sorcerer soul subclass.

## Sorcerer soul designs
I'm not actually sure if i want to make this list genuinely broad and flavourful or keep them tied to the fundamental power sources. regardless, the subclass itself mechanically has the following features:

#### 1. Font of magic pt 2 (pt 1 WIP concerns the power source)
As a sorcerer, your affinity for magic runs deeper than your class. you gain the ability to compliment or replace aspects of your class with that of your font of magic instead. 

you can learn a number of sorcerer aspects this way equal to your **Experience modifier.** if you already have sorcerer spells from elsewhere (background, subclass, etc), they do not count against this limit, and are considered permenantly known.

- Once per level, you can learn one aspect from your font of magic, as long as it's not exclusive to another class.
- Once you learn an aspect this way, it remains a known aspect to you. you may change your known aspects on a recovery or a level up.
- doing so means learning one less aspect you would have originally gained from levelling through your class. 
- if your chosen class *prepares* aspects, instead of learning them, your known sorcerer aspects count against the number of aspects you can prepare, but are still considered known aspects that are always prepared.
- if your class both prepares and knows aspects, they no longer count against the number of aspects you can prepare, but as known aspects, you must still take them in place of aspects gained from levelling through your class.

#### design notes...
Taking sorcerer aspects is a commitment. it's not free - just an expanded array you can pick from if you so choose. The rules neither favour known or prepared aspects.

This is intended to draw back from the idea of "less spells, more ways to cast them" from the D&D sorcerer, with a much more limited scope as it's a subclass, not a class.

# v1.2.0.2 the mystic...work in progress?
### dissolution of the silver mage
an amazing novel concept, but in the name of content bloat, it currently does not have enough to satisfy a role in the game without needing to take away from the blue, gold, white or black mages. it's amazing, it might come back, but for now it's redistributed, primiarily into the gold mage.

however, let's turn to look at the other "silver" mage on our block - the mystic. properly crowned back to their psionic identity, the modern mystic can take up a lot of what made the silver mage interesting, and seamlessly slot it in under the guise of telepathy, perception and illusion, or something else. 

#### master of the mind...
the mystic is a master of the mind. but what does that mean? psionics aren't locked to them - the monk can access psionic diciplines, they train their minds. so can the red mages - their silver tongue and charm aren't magical, but they certainly arent mundane.

as said, a mystic isn't just a master of their own mind, but they learn to masters others'. Through perception and information, they can bend the way others see the world, causing massive psychological damage without moving a single grain of dirt. they can conjure illusory dragons, maddening darkness, the projection of skybreak, or pierce someone's spell from a mile away with disrupt mind.

### The v1.2 mystic
To bolster their class fantasy, the title of a "silver mage" is a beaurocratic title for when they must attend as mages. Mystics do not learn from any one magical dicipline, but train the catalyst itself - their mind, to superhuman levels. Let's take a comprehensive, detailed look at the modern mystic design for v1.2

Firstly, they possess strong mundane utility - reflected in their immense lore and sense triaots. they are able to take both mental stats with little diminishing returns or conflict of interest - whilst martials need to look into tenacity and finesse, and other mages need arcana, they disregard all of that.

#### list of character skills avaliable:
- knowledge
- logic
- percieve 
- alert
- search

they are also considered **skilled** in any one of their choosing.

### Class features

#### prepared AND known caster
this is reflected in their class structure. their aspects are known as psionic diciplines - which follow a known-and-prepared list like a wizard's spellbook. their powerful memory allows them to memorise a vast amount of them, and prepare a few they need on the day. 

#### psionic philosophies
and they inherit a system from the retired noctira mystic - remember the philosophies of dark? we turned them into a warlock class feature, but now - that same structure can be used here as psionic philosophies - each one representing a "bucket" of abilities, not dissimilar to what the UA mystic was going for in dnd. however, unlike the warlock, who gains them by level, the mystic can swap these out - offering them a massive amount of flexibility - both their aspects and core class talents are unshackled. 

to do this of course, their class talents outside of their philosophies are quite limited, being generic stat boons or pure utility (like skill checks or surface level telepathy and mind reading). Which is a fair trade - their power budget is alreadu quite concentrated in those two main vectors.

#### class abilities (design dump)
Finally, their core class abilities revolve around enhancing their psionics in any way they can. they also gain important bonuses like innate telepathy, telekinesis, levitation, etc, and gain resistance, and later, immunity to mental conditions. 

1. at Lv0, before gaining a single philosophy, with the stillness of mind feature, which shields them from the emotional turbulence of any nonmagical charm or fear. they are trained to be precise, unerring masters of their own mind, and later, others' too.

2. This isn't just social utility - this is direct combat shutdowns. plenty of strong creature abilities rely on landing fear, charm, mad, dazed, etc, causing spellcasting disruption or misguided attacks. A dragon's frightening roar does nothing against a mystic.

3. Thirdly, it creates a sort of threat that is felt throughout the game and its table not dissimilar to dnd's stunning strike. the possibility of a potential psychic dominance is enough to sway conversation or combat, and that leads to amazing character roleplay.

## psionics
psionics are a huge part of their mechanical and thematic identity, comprising both their aspects and their importnat class feature, philosophies. Currently, the design space for psionics gives them the following boons:

#### psionics are not spellcasting. 
#### at M3, they no longer need to concentrate. at all.
1. require components, or need a magical focus. They are forever online. 
2. this also means you can't "dispel magic" them, because it's not magic. same goes for antimagic field.
3. you couldn't counterspell them anyway, they're not spells.

okay. let's start working on the mystic.

## v1.2.0.2, the mystic changelogs

### early changes - mystic boons
- there was the intend to add "psionic talents" as early game, free and useable minor effects, akin to cantrips. however, this was deemed unnecessary with the birth of Mystic boons and their evolutions.
- mystic boons recieved a lot of development, returning to a model I had in mind from a long time ago. 
- mystic boons are intended to be effects that scale with you, as fundamental psionic diciplines that don't consume psi points (at base), and continue to strengthen simply by levelling. 

### aspect progressiohn - t2 or t1?
- i'm not sure if i want to make them a t1 caster, and just bump up their philosophies a bit more. However, a lot of really flavourful psionic diciplines lie in the later levels, and cuitting them off from that supply would be more harm than benefit. In addition, i quite like the scaling of the philosophies.

- however, changing their philosophies progression to be a little faster couldn't hurt. We can give the t2 caster + 4 slot philo idea to the warlock instead?
- doing so would cause Minor telekinesis to go to lv1, and they get both psionics and philosophies at level 1? it wouldn't make much sense to give them "half"

### minor optimisations....
- using a brand new style of Class block, which explicitly lays out the milestone range. Also, for classes that scale on both class features and aspects 50/50, using a dual 

## V1.2.1 mystic class block 1 - core class

| Character level | Experience | Milestone range | Milestone features  | mystic boon| psi points | Philo slot 1 | Philo slot 2 | Philo slot 3 | 
|:------------------|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0  | +0  | M0 | psionics, telepathy  |Minor telekinesis | 2 | - | - | -
| 1  | +0  | M1 |Psionic philosophies, Cold cognition | - | 4 | 1 | 1 | 1 |
| 2  | +1  | M1 |mystic subclass, iron concentration | levitation  | 5 |2  |1  |1  |  
| 3  | +1  | M1| -| -  |  7 |2  |2  |1  |  
| 4  | +2  | M2 | Closed mind technique |Major telekinesis |  8 |2  |2  |2  | 
| 5  | +2  | M2 |  -| -  |  9 |3  |2  |2  |  
| 6  | +2  | M2 |- |  minor teleportation  | 11 |3  |3  |2  |  
| 7  | +2  | M2 | - | -  |  12 |3  |3  |3  |  
| 8  | +3 | M3  | Cyclic mind technique, Concealed concentration | Minor precognition | 15 |4  |3  |3  |  
| 9  | +3 | M3 | - | -  | 16 |4  |4  |3  |  
| 10  | +3 | M3 |-  | Major teleportation  | 17 |4  |4  |4  |
| 11  | +3 | M3|- | -| 18 |5 |5  |4  |4  |
| 12  | +4 | M4 | Redirect spell | domination | 19 |5 |5  |4  | 
| 13  | +4 | M4 | -  | -  | 20 |5 |5  |5  | 5 |
| 14  | +4| M4 | - | precognition  | 21 |6 |5  |5  | 4 |
| 15  | +4 | M5 | ascendance: avatar, ascendance: aspect | ascendance: Ascendant boons |22|11 |6  |6 |
| 16+  | +5| M5 | Lost library of Lhosung | - | 24 | 11 |11  |11  |

## WIP class block 2 - aspects

| Character level | T1 | T2 | T3 | T4 | T5 | T6 | T7 | T8 | T9 | T10 |
|:----------------|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| 0               | 3  |    |    |    |    |    |    |    |    |    |
| 1               | 3  | 2  |    |    |    |    |    |    |    |    |
| 2               | 4  | 3  |    |    |    |    |    |    |    |    |
| 3               | 4  | 3  | 2  |    |    |    |    |    |    |    |
| 4               | 4  | 4  | 3  |    |    |    |    |    |    |    |
| 5               | 4  | 4  | 3  | 2  |    |    |    |    |    |    |
| 6               | 4  | 4  | 4  | 3  |    |    |    |    |    |    |
| 7               | 4  | 4  | 4  | 3  | 1  |    |    |    |    |    |
| 8               | 4  | 4  | 4  | 3  | 2  |    |    |    |    |    |
| 9               | 4  | 4  | 4  | 3  | 2  | 1  |    |    |    |    |
| 10              | 4  | 4  | 4  | 3  | 3  | 2  |    |    |    |    |
| 11              | 4  | 4  | 4  | 3  | 3  | 2  | 1  |    |    |    |
| 12              | 4  | 4  | 4  | 3  | 3  | 3  | 2  |    |    |    |
| 13              | 4  | 4  | 4  | 3  | 3  | 3  | 2  | 1  |    |    |
| 14              | 4  | 4  | 4  | 3  | 3  | 3  | 2  | 2  |    |    |
| 15              | 4  | 4  | 4  | 3  | 3  | 3  | 2  | 2  | 1  | 1  |
| 16+             | 4  | 4  | 4  | 3  | 3  | 3  | 2  | 2  | 2  | 2  |


# v1.2.1 - mystic update
The mystic recieves plenty of direct mechanical changes, along with significnat brainstorming for how to best consolidate their identity.

The original concept was to split them 50/50 between their diciplines and philosophies, but that path is uncertain. depending on how strong their philosophies are, leaning into that element could be a very interesting class design that seperates them from the similarly planned warlock and monk.

## new class features

### detect thoughts (NOW A SUBCLASS FEATURE - but for which?)
as a fledgling mystic, you can already naturally sense the surface thoughts of nearby minds on instinct. you can deploy the aspect *detect thoughts* at will, provided you are within melee of your target creature. You may also use this aspect on objects that may contain thoughts, such as enchanted items.

it also becomes a mystic aspect for you, and does not count against the number of aspects you can prepare.

### telepathy
One of the first techiques a mystic learns is how to communicate through thought alone. provided you have line of sight with your target creature(s), you may speak with them telepathically.
- the range of your telepathy is equal to a number of metres equal to your sense score x 5.
- if the target creature is hostile or neutral, they may react with surprise or suspicion, as per a *message* aspect. 
- telepathic speech will wake a sleeping creature. 

from now on, you can prepare philosophies to enhance this feature.

### psionics
Psionics are the core of your mental training. Psionics allow you to access **psionic diciplines**, and deploy them, at the cost of **psi points**.

your psionics power is mainly comprised of the following features: **psi points, mystic recovery, psionic diciplines and silent psionics**.

### psi points
Psi points represent the total amount of mental energy you can harness to channel into your psychic power. These are consumed via psionic diciplines and psionic philosophies.

**regaining psi points**: After a respite, you regain all of your psi points. 

#### mystic recovery
When outside of initiative, you spend one minute in restorative meditation, which restores all of your psi points. when you do so, you cannot take another psychic recovery until you finish a rest. 

### psionic diciplines
A psionic dicipline is a specific methodology or technique in psionic practice you can prepare. *psychic knife*, *ward*, and *Sense lie* are reccomended.

**learning aspects**: at level 0, you select any two diciplines of your choice of Tier 1 from the mystic aspect list. As you gain levels in the mystic class, you will continue to gain more slots to prepare more aspects.

**known aspects**. Mystics memorise their diciplines through rigorous practice, and it remains in their memory until changed. 

**changing known diciplines**: You may change your known aspects on a level up or a recovery. Each time you change your known aspects, you may also change one of your **psionic talents** as detailed below.

**psionic diciplines are not spells.** They are considered magical effects, but not spells. For example, counterspell cannot be used against a dicipline, but they will be supressed under an antimagic field.

#### Silent psionics
Psionics is silent and motionless, meaning they **do not require any components to deploy**. if an aspect otherwise has a material cost, as long as it's on your character, **you are not required to hold it.**

## milestone 1

### Cold cognition
As a mystic, your first milestone is mastering your mind against emotional turmoil. You can no longer recieve the *charmed* or *frightened* condition by **nonmagical** means.

You ignore any any further effects, damage, or checks / saving throws of an effect that rely on having those conditions (e.g, the mental illusion of *phantasmal force*)

### Mystic philosophies. 
whilst your diciplines are rigorously memorised techniques, your philosophies are fluid, serving whatever role of a mystic your mind currently deems most important. These replace your *class talents*, serving as deep buckets of mental thought and theory you can invest into.

*Purity*, *Mental motion* and *Assault mind* are reccomended. 

#### Mystic philosophy slots
These act like aspect preparation slots, each one having a certain Tier Number - which represents the highest Tier psionic philosophy you can prepare with that slot. You have three **philosophy slots**, as shown on your class features block. 

**preparing philosphies**: you prepare your philosophies by consuming slots like aspects. 

**changing philosophies**: you may change one philosophy after a respite, and all of them after a rest. if you take your mystic recovery, you may also change a philosophy choice.

#### mystic focus
Your mystic focus is an extension of your baseline focus, capable of adding an additional, passive effect at the cost of action points. it can only be occupied by a specific *focus* effect at a time.

**action cost**: it takes one AP to activate and maintain your mystic focus and recieve the benefits of your chosen *focus*, and none to disable it.

**philosophical focus**: Each Mystic philosophy comes with a unique *focus* - a core representation of what that class talent is meant to achieve.  

 ## 15/7 - v1.2.1.1 update
Minor addition to the mystic class. There's a lot of content planned, so it's unsure if this is intended to be a full update or just a follow up to the last.

#### In addition, instead of dumping all of the brainstorming with the mechanical changes, i will keep github commits solely focused on the changelog, and both will be avaliable from now on in this file.

### design notes...
- I really like the introduction of mystic focus. It gives more weight to their philosophies class features without adding more bloat, ensuring they can select which one of their prepared philosophies to elevate.

- i'm not sure how much i like the mystic boon system. I might remove the major / minor system entirely, and introduce them as standalone class features, which you can take a philosophy to enhance into a "major" version - where said philosophies can be unlocked at when i had original minor / major upgrades planned.

- not only will it make gaining each one more impactful, it also makes their existance more core to the mystic class as rock solid psionic tricks you can always have.

 they should probably recieve a ribbon resistance to psychic damage somewhere...but i'm trying very hard to avoid design bloat.

## Changelog:

### mystic boons
- Updated the mystic boons system, turning them into standalone features, each one given more weight and power.
- to "upgrade" a mystic boon to its "major version", you can prepare the appropriate Philosophy for that. 
- that also allows you to access certain mystic boons typically gained at later levels, earlier, provided you can spare the experience. 
- Currently working on the first draft for each mystic boon. Will come either in this update or v1.2.1.2 as we clean up the mystic.

### Class features
- naming conventions changed. 
- purity is now added, which grants them flat immunity to all mental conditions.
- they remain a T2 aspect caster. Though their philosophies asre quite strong, their class features have slimmed down significantly to where aspects still play a major role in their kit.

## v1.2.1.1 class block 1 - core class

| Character level | Experience | Milestone range | Milestone features  | mystic boon|
|:------------------|:-----:|:-----:|:-----:|:-----:|
| 0  | +0  | M0 | psionics | telepathy  | 2 | - | - | -
| 1  | +0  | M1 |Mystic philosophies, Cold cognition | telekinesis | 4 | 1 | 1 | 1 |
| 2  | +1  | M1 |mystic subclass, iron concentration |  - | 5 |2  |1  |1  |  
| 3  | +1  | M1| -| -  |  7 |2  |2  |1  |  
| 4  | +2  | M2 | Closed mind technique | levitation |  8 |2  |2  |2  | 
| 5  | +2  | M2 |  -| -  |  9 |3  |2  |2  |  
| 6  | +2  | M2 |- |  - | 11 |3  |3  |2  |  
| 7  | +2  | M2 | - | -  |  12 |3  |3  |3  |  
| 8  | +3 | M3  | Cyclic psionics, Concealed concentration | teleportation  | 15 |4  |3  |3  |  
| 9  | +3 | M3 | - | -  | 16 |4  |4  |3  |  
| 10  | +3 | M3 |-  | -  | 17 |4  |4  |4  |
| 11  | +3 | M3|- | -| 18 |5 |5  |4  |4  |
| 12  | +4 | M4 | Purity, Redirect spell |  precognition | 19 |5 |5  |4  | 
| 13  | +4 | M4 | -  | -  | 20 |5 |5  |5  | 5 |
| 14  | +4| M4 | - | -  | 21 |6 |5  |5  | 4 |
| 15  | +4 | M5 | ascendance: avatar, ascendance: aspect | ascendance: Ascendant boons |22|11 |6  |6 |
| 16+  | +5| M5 | Lost library of Lhosung | - | 24 | 11 |11  |11  |

# 17/07 - v1.2.2 Lore update
Mainly focused around working on the lore of the world behind the game. Concete mechanical changes are coming, but currently most of the design changes are focused around exploring how classes relate to the current power structures in the Lore.

## changelog
- Silver mage indefinitely removed. Unsure if they're to be reimplimented as a unique class, since currently they share a large amount of overlap with the mystic and the wizard.
- important lore update to the worldbuilding. Important locations, deities, and the central mage's circle.
+ began work on the mystery of five. that will be reserved for the worldlore.md document.
+ changelog was previously mainly used to catalog drafts. it will no longer be used to contain literally everything in an update.

# v1.2.3 - Continuous Lore updates
- No mechanical changes at large.
- Still unknown name for the Black mage. If we make it our sole custom class, then we'll use the Nosiys placeholder, instead of making that our sorcerous origin.
- nomad removed for now. See design changelog.

As of 04/08, I've decided to no longer clog up the original changelog, meant for mechanical changes, with narrative ones. Whilst the two certainly have strong overlap, this will serve as the hosting ground for the progression of the Lore of the game as a whole. Specific design decisions tailored towards the game's design principles is left for a dedicated Design notes page.

# 10/09 v1.3 - Mystic update v2 and major class changes overral.
after a long break, returning to continue to work on the mystic, and psionics as a whole. Now, there are specific background and milestone feats avaliable specifically designed around psionics, and all classes have recieved a massive overhaul to make them more streamlined.

| Character level | Experience |Core class |  Avaliable philosophies  | philosophy slots | 
|:------------------|:-----:|:-----:|:-----:|:-----:|
| 0  | +0  |  psionics, psi points telepathy | - | - | - | - | -
| 1  | +1  | Mystic philosophies, milestone |telekinesis, Cold cognition, iron concentration, mystic recovery, Assault mind, pale purity | 2 | 1 | 1 | 1 |
| 2  | +1  | mystic subclass | subclass options | 2 |2  |1  |1  |  
| 3  | +1  |  -| - |  2 |2  |2  |1  |  
| 4  | +2  | Milestone | Closed mind technique, iron concentration,  levitation |  3 |2  |2  |2  | 
| 5  | +2  |  -| - |  3 |3  |2  |2  |  
| 6  | +2  | - | subclass options | 3 |3  |3  |2  |  
| 7  | +2  |  - | -  | 3 |3  |3  |3  |  
| 8  | +3 | Milestone | Cyclic psionics, Concealed concentration,  teleportation | 4 |4  |3  |3  |  
| 9  | +3 |  - | -  | 4 |5  |4  |3  |  
| 10  | +3 | - |  subclass options | 4 |4  |4  |4  |
| 11  | +3 | - | -| 4 |5 |5  |4  |4  |
| 12  | +4 | Milestone | Pale Purity, Redirect spell, precognition  | 5 |5 |5  |4  | 
| 13  | +4 | -  | -  | 5 |5 |5  |5  | 5 |
| 14  | +4| | - | 5 |6 |5  |5  | 4 |
| 15  | +4 |  ascendance: avatar, ascendance: aspect | -|5|11 |6  |6 |
| 16+  | +5| Lost library of Lhosung | - | 5 | 11 |11  |11  |

## philsophies and class features - Important
- a huge update to class design as a whole. Each class has a pool of different class features avaliable after each milestone they can select on even levels, whcih are seperate from core class options. 
- This means there is no need at all for class talents, as the choices between decisive, defining class features is enough to create unique characters.
- experience is now used to purchase an appropriate class feature. It is no longer just a simple marker of level strength.

- For the mystic, this is their defining identity, being able to effectively, swap in and out class features, then upgrade them by turning experience into a fluid pool.

- the three levelling slots idea is best reserved for the warlock or for medium summon slots.