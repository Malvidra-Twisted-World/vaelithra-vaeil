# Appendix B: Creatures

This appendix contains the homebrewed creatures that appear in *Vaelithra VI: Vaeil*. Each entry reflavors a standard *Monster Manual* stat block (Veteran, Guard, Scout, or Knight); the full stat block below already includes those changes.

These creatures appear in two encounters: "Caught Between Two Fires" (*Part II: Hollow Battlefield*) pits the Radiant Inquisition against the Ashen Covenant, with the party caught between them; "Hold the Bridge" (*Part III: The Sun's Passage*) pits the party against Sōyō Gumi, the Sun's Host.

## The Radiant Inquisition

### Ser Kaelion Veyr

Commander of the Silverbinders. A reflavored Veteran, tougher than most and equipped with a radiant Sun Spear in place of a crossbow.

```statblock
layout: Basic 5e Layout
source: Vaelithra VI - Vaeil
name: Ser Kaelion Veyr
size: Medium
type: Humanoid
alignment: Lawful Neutral
cr: 3
ac: 17
hp: 72
hit_dice: 11d8+22
speed: 30ft
stats: [16,13,14,10,11,10]
skillsaves:
  - Athletics: 5
  - Perception: 2
senses: Passive Perception 12
languages: Common
traits:
  - name: Divine Formation
    desc: While within 10 feet of another Silverbinder, Kaelion has +2 to his Armor Class.
  - name: Take Her Alive
    desc: Kaelion's weapon attacks can deal nonlethal damage with no penalty. As a bonus action, he can direct up to two Silverbinders within 30 feet to do the same until the start of his next turn.
actions:
  - name: Multiattack
    desc: Kaelion makes two melee attacks.
  - name: Longsword
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft. Hit: 7 (1d8 + 3) Slashing damage, or 10 (2d8 + 3) Slashing damage if used with two hands."
  - name: Sun Spear
    desc: "Ranged Weapon Attack: +5 to hit, range 30/120 ft. Hit: 10 (2d6 + 3) Radiant damage."
creature: Ser Kaelion Veyr
```

### Silverbinders (4)

Rank-and-file soldiers of the Radiant Inquisition. Reflavored Guards, each carrying a Sun Pike and a set of binding chains meant to capture, not kill.

```statblock
layout: Basic 5e Layout
source: Vaelithra VI - Vaeil
name: Silverbinder
size: Medium
type: Humanoid
alignment: Lawful Neutral
cr: 1/8
ac: 16
hp: 22
hit_dice: 4d8+4
speed: 30ft
stats: [13,12,12,10,11,10]
skillsaves:
  - Perception: 2
senses: Passive Perception 12
languages: Common
traits:
  - name: Silver Binding Chains
    desc: As an action, a Silverbinder can attempt to bind one creature within 10 feet of it. The target must succeed on a DC 13 Strength saving throw or become Restrained until the end of the Silverbinder's next turn. While restrained this way, the target cannot teleport or use any form of planar travel.
actions:
  - name: Sun Pike
    desc: "Melee Weapon Attack: +4 to hit, reach 10 ft. (5 ft. when not wielded with two hands). Hit: 8 (1d10 + 2) Radiant damage."
creature: Silverbinder
```

## The Ashen Covenant

### Mordren Ashveil

Warlock leader of the Ashen Covenant. A reflavored Scout, hardier and stronger than his warband, wielding an Infernal Brand and a pact-granted spell.

```statblock
layout: Basic 5e Layout
source: Vaelithra VI - Vaeil
name: Mordren Ashveil
size: Medium
type: Humanoid
alignment: Chaotic Evil
cr: 2
ac: 13
hp: 48
hit_dice: 9d8+9
speed: 30ft
stats: [11,14,12,11,13,11]
skillsaves:
  - Nature: 4
  - Perception: 5
  - Stealth: 6
senses: Passive Perception 15
languages: Common, Infernal
traits:
  - name: Keen Hearing and Sight
    desc: Mordren has advantage on Wisdom (Perception) checks that rely on hearing or sight.
  - name: Burning Blood
    desc: When Mordren is reduced to 0 hit points, each creature within 5 feet of him must succeed on a DC 13 Dexterity saving throw or take 7 (2d6) Fire damage.
  - name: Warlock's Pact
    desc: Once per short rest, Mordren can cast hex (as a 2nd-level spell, no material components required) as a bonus action.
actions:
  - name: Multiattack
    desc: Mordren makes two Infernal Brand attacks.
  - name: Infernal Brand
    desc: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120 ft. Hit: 5 (1d8 + 1) Piercing damage plus 3 (1d6) Fire damage."
creature: Mordren Ashveil
```

### Covenant Warband (5)

Rank-and-file members of the Ashen Covenant. Reflavored Scouts, each carrying an Infernal Brand identical to Mordren's.

```statblock
layout: Basic 5e Layout
source: Vaelithra VI - Vaeil
name: Covenant Warband
size: Medium
type: Humanoid
alignment: Chaotic Evil
cr: 1/2
ac: 13
hp: 24
hit_dice: 4d8+4
speed: 30ft
stats: [11,14,12,11,13,11]
skillsaves:
  - Nature: 4
  - Perception: 5
  - Stealth: 6
senses: Passive Perception 15
languages: Common, Infernal
traits:
  - name: Keen Hearing and Sight
    desc: The warband member has advantage on Wisdom (Perception) checks that rely on hearing or sight.
actions:
  - name: Multiattack
    desc: The warband member makes two Infernal Brand attacks.
  - name: Infernal Brand
    desc: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120 ft. Hit: 5 (1d8 + 1) Piercing damage plus 3 (1d6) Fire damage."
creature: Covenant Warband
```

## Sōyō Gumi, the Sun's Host

### Grand Captain Kiyomasa

Commander of the Sun's Host. A reflavored Knight, wielding a radiant Longsword and rallying his Dawn Knights with a shout of Leadership.

```statblock
layout: Basic 5e Layout
source: Vaelithra VI - Vaeil
name: Grand Captain Kiyomasa
size: Medium
type: Humanoid
alignment: Lawful Neutral
cr: 5
ac: 18
hp: 80
hit_dice: 12d8+24
speed: 30ft
stats: [16,11,14,11,11,15]
saves:
  - CON: 4
  - WIS: 2
skillsaves:
  - Persuasion: 4
senses: Passive Perception 10
languages: Common
traits:
  - name: Brave
    desc: Kiyomasa has advantage on saving throws against being Frightened.
  - name: Solar Bulwark
    desc: While an allied Dawn Knight is within 10 feet of him, Kiyomasa has advantage on saving throws against being Frightened or Charmed.
  - name: Leadership (Recharges after a Short or Long Rest)
    desc: For 1 minute, Kiyomasa can utter a special command or warning whenever a nonhostile creature that he can see within 30 feet of him makes an attack roll or a saving throw. The creature can add a d4 to its roll, provided it can hear and understand Kiyomasa. A creature can benefit from only one Leadership die at a time. This effect ends if Kiyomasa is incapacitated.
actions:
  - name: Multiattack
    desc: Kiyomasa makes two Longsword attacks.
  - name: Longsword
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft. Hit: 8 (1d8 + 3) Slashing damage, or 10 (1d10 + 3) Slashing damage if used with two hands, plus 3 (1d6) Radiant damage."
  - name: Heavy Crossbow
    desc: "Ranged Weapon Attack: +2 to hit, range 100/400 ft. Hit: 5 (1d10) Piercing damage."
reactions:
  - name: Parry
    desc: Kiyomasa adds 2 to his AC against one melee attack that would hit him. To do so, he must see the attacker and be wielding a melee weapon.
creature: Grand Captain Kiyomasa
```

### Dawn Knights (4)

Rank-and-file soldiers of the Sun's Host. Reflavored Guards, each carrying a radiant Sunblade.

```statblock
layout: Basic 5e Layout
source: Vaelithra VI - Vaeil
name: Dawn Knight
size: Medium
type: Humanoid
alignment: Lawful Neutral
cr: 1/2
ac: 17
hp: 24
hit_dice: 4d8+4
speed: 30ft
stats: [13,12,12,10,11,10]
skillsaves:
  - Perception: 2
senses: Passive Perception 12
languages: Common
actions:
  - name: Sunblade
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft. Hit: 6 (1d8 + 2) Slashing damage plus 2 (1d4) Radiant damage."
creature: Dawn Knight
```

![](https://i.imgur.com/0e4MgaL.jpeg)
