# Enhanced AI

Ashen Legacy has reworked mob behavior across nearly every category. It adds smarter movement, new combat responses, better targeting, and special behaviors for specific mob types.
## Global Categories Enabled
These mob groups are all **enhanced**:
Animals, Blazes, Creepers, Endermen, Illagers, Shulkers, Bugs, Skeletons, Slimes, Spiders, Villagers, Witches, Warden, Drowned, Ghast, Snow Golems.



## Core Mob Behaviors (All Mobs)

### Movement & Pathing
- **Riding**: Mobs can mount other mobs (10% chance across difficulties). They dismount if suffocating.
- **Climbing**: Ladder climb chance is **100%** for eligible mobs.
- **Jumping**: Mobs can jump in place if targets are above them.
- **Sprint**: 25% chance for sprint‑capable mobs.
- **Pathfinding**: Mobs path to your **standing position** (fixes edge cheese), and can walk over open trapdoors.
- **Random Stroll**: Higher wander frequency; they can wander away from players.

### Targeting & Aggro
- **Alert Range**: Mobs can alert others within **32 blocks**.
- **Follow Range Override**: Eligible mobs see **24–48 blocks**.
- **X‑ray Targeting**: 50% chance for special “see through walls” range (**12–24 blocks**), and they can see glowing entities.
- **Target Switching**: Enabled with strong player preference; **90% infighting prevention**.
- **Neutral Chances** (Better Nearby Targeting):
  - Easy: **25%**
  - Normal: **10%**
  - Hard: **4%**

### Combat & Survival
- **Melee Range Update**: Uses 1.20.2 reach mechanics (attribute‑based).
- **Attack Speed**: Attribute‑based, max **2 attacks/sec**, scaled to **0.5x** by difficulty.
- **Biting**: Mobs can bite unarmed attackers (3 damage, 20–30% chance).
- **Leaders & Reinforcements**:
  - 5% chance to be a **leader**
  - Leaders get **4x health** and **+15 armor**
  - Reinforcement chance scales to full at **6 damage**
- **Panic When Burning**: 80% chance to panic on fire.
- **Fire Immunity Ticks**: 20 ticks before being set on fire.
- **Avoid Explosions**: 80% chance to flee (1.25x speed near, 1.1x far).
- **Pick Up & Throw**: Mobs can throw other mobs (5–24 block range, 10 min cooldown).

### Anti‑Cheese Systems
- **Vehicle Break**: Mobs can destroy vehicles to escape.
- **Teleport Anti‑Cheese**: 100% chance to teleport targets close when stuck.
- **Miner Mobs**: Mobs can mine blocks to reach you.
  - 7% chance to spawn as miners
  - Always carry a **stone pick**
  - Mine up to **Y 320**
  - Break time **1.25x slower**
  - Tool requirement: correct tool for required blocks
  - Works in **Overworld, Nether, End**

### Disabled Global Features
These exist but are **turned off**:
- Item Disruption (Endermen knocking items from hands)
- Fisher Mobs (fishing rod pulls)
- Pearler Mobs (ender pearl use)
- Throwing Webs
- Parkour Leaps
- Shielding (mob shields)
- Air Steal



## Witches
- **Thirsty Witches**: heal more often
  - Healing chance **5%**, healing threshold **70%**, strong heal below **40%**
  - Always drink water breathing/fire resistance when needed
  - Milk cleanse chance **10%**
  - Drinks regen/swiftness if ≥ 6 blocks away
- **Smarter Potion Throwing**:
  - Lingering chance **15%**
  - Throws slow falling when falling far
  - Bad potions include weakness, slowness, hunger, mining fatigue, poison, blindness, harming
  - Good potions include regen, swiftness, strength, healing
  - Apprentice chance **50%** (can throw wrong potion)
  - Attack range **16–24**, cooldown **70–90**
- **Allied Monsters**: can throw potions at allies in raids
- **Dark Art**: 33% chance to summon a villager + lightning at ≤10 blocks



## Warden
- Darkness range: **50 blocks**
- Vibration listen range: **32 blocks**
- Sonic boom range: **50 blocks**



## Villagers
- **Villager attacking enabled**, but **fight back is off** by default.
- **Alert protectors**: villagers alert guards/golems within **40 blocks**.



## Spiders
- **Stuck fix**: spiders detach from walls and leap after ~2s stuck.



## Slimes & Magma Cubes
- **Magma surf speed**: **3x faster in lava**
- **Attack fix**: damage only on jump/land
- **Jump delay**: 5–15 ticks
- **Max spawn size**: **5**



## Skeletons
- **Better shooting**: range **24–32**, cooldown **35–40**, charge **15–30**
- **Higher accuracy**: inaccuracy 6/5/3 (easy/normal/hard)
- **Fleeing**: 50% chance to avoid, distances 8–16, speed up to 1.25x
- **Wither Skeletons**: shoot wither arrows instead of fire arrows



## Shulkers
- Faster and less predictable firing
- Levitation duration **100/100/160 ticks** (easy/normal/hard)
- Levitation amplifier **5**
- Armor scaling:
  - Closed: **30**
  - Peeking: **20**
  - Open: **10**



## Illagers (Pillagers)
- **Better shooting**:
  - Range **24–32**
  - Cooldown **20–40**
  - Inaccuracy 5/3/1 (easy/normal/hard)



## Creepers
- **Smarter swell**:
  - 65% chance to ignore walls
  - Charged creepers can explode on death
  - Breach chance **7.5%**, range **24**
- **Angry creepers**:
  - 3% chance, named, particles, explode on death, power **4**
- **Walking fuse**: 10% chance to move while swelling
- **Beta strafe**: 35% chance
- **Launch creepers**:
  - 5% chance to leap at targets
  - Explosion radius **2**
- **TNT‑like creepers**: 25% ignite on explosion damage



## Silverfish (Bugs)
- Wake allies after hurt in **10 ticks**
- Larger swarm search radius
- Merge into stone at vanilla frequency



## Blazes
- Faster, heavier fireball volleys:
  - Fireball delay **4–10 ticks**
  - 2–6 fireballs per burst
  - Recharge **60–120 ticks**
  - Charge time **30–80 ticks**
  - Inaccuracy **2–14**



## Animals
- **Panic** spreads to nearby animals (16–32 block range)
- **Scared attack** behavior:
  - 35% fight back chance
  - 10% hostile chance
  - 25% chance to flee from players
  - Flee distances 7–12
- **Not tempted by food**: 5% chance



## Drowned
- **Sun resistant** for **300 ticks**
- Better swim‑up AI
- Can attack during daytime



## Ghasts
- 30% chance to fire even without line‑of‑sight
- Cooldown **40–50 ticks**
- Up to **3 fireballs** in a burst



## Snow Golems
- **Healed by snowballs** (+1 HP)
- Snowballs do **0.5 damage**
- Snowballs can **freeze for 30 ticks** (stacking allowed)



## Notes for Players
- Many behaviors are **tag‑gated** (only certain mobs are affected).
- This system is designed to **punish passive combat** and reduce safe‑spot abuse.
- Expect mobs to **adapt**, close distance, and force movement.

