
![[fighter.PNG|center|400]]



```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Douglas Spinebeard"
level: "Fighter Lvl 1"
alignment: "NG"
size: "Medium"
trait_03: "Dwarf"
trait_04: "Dwarven"
trait_05: "Humanoid"
modifier: 6
perception:
  - name: "Perception"
    desc: "Perception +6; __darkvision__"
languages: "Common "
skills:
  - name: "Skills"
    desc: "__Arcana__: +1, __Athletics__: +7, __Diplomacy__: +1, __Medicine__: +4, __Religion__: +1, __Society__: +1, __Acrobatics__: +3, __Deception__: +1, __Intimidation__: +4, __Crafting__: +4, __Lore__: +4, __Medicine__: +4, __Nature__: +1, __Occultism__: +1, __Performance__: +1, __Religion__: +1, __Society__: +1, __Stealth__: +0, __Survival__: +1, __Thievery__: +0,"
abilityMods: [4, 1, 3, 0, 2, 3]

abilities_mid:
  - name: "Raise A Shield"
    desc: "⬻ When you’re holding a shield, you can use this action to position the shield to protect yourself. When you Raise a Shield, you gain a +2 circumstance bonus to AC. Your shield remains raised until the start of your next turn."
  - name: "Shield Block"
    desc: "⬲ __Trigger__ If you Raised a Shield on your last turn, you can spend your reaction to block a physical attack with your shield. Reduce the amount of damage by 5, but then you and your shield both take the remaining damage. This might break or destroy your shield..</li></ul>"
  - name: "Attack of Opportunity"
    desc: "⬲ If a creature you can reach with a melee attack makes a ranged attack, uses an action with the manipulate or move trait, or leaves a square on its turn, you can use your reaction to make a melee Strike against that creature. If your attack is a critical hit and the foe was using an action with the manipulate trait, their action doesn’t have any effect."
  - name: "Sudden Charge"
  - desc: ⬺ With a quick sprint, you Stride twice. After moving, if you can reach any enemies with a melee attack, you can make a melee Strike against one of those enemies.

abilities_top:
  - name: Items
    desc: "shortbow (60 arrows), half plate, steel shield (Hardness 5, 20 HP, BT 10), longsword"

speed: 20 feet

ac: 23
armorclass:
  - name: AC
    desc: "18;  (20 with shield raised); __Fort__: +7 (1d20+7), __Ref__: +5 (1d20+5), __Will__: +4 (1d20+4)"
hp: 24
health:
  - name: HP
    desc: "24"


attacks:
  - name: Longsword
    desc: "⬻ +6 ([[versatile|versatile p]]) __Damage__ 1d8+4 (1d8+4) slashing"
  - name: Dagger +6 ([[Agile]]) ([[Finesse]]) ([[Versatile]]) (Thrown 10')
  - name: Ranged
    desc: "⬻ shortbow +6 ([[range increment|range increment 120 feet]], [[reload|reload 1]]) __Damage__ 1d8+4 (1d8+3) [[Piercing]] plus [[Deadly]]"


```