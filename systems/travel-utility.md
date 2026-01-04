# Travel & Utility

Travel in **Ashen Legacy** is tuned to feel *earned*, not instant. We want exploration to matter early and networks to matter later. The pack gives you strong tools once you’ve put in the work, but doesn’t skip the journey.

## Waystones: earned convenience, not free teleportation

Waystones are your mid‑to‑late game travel backbone. They are **world‑generated** and meant to be discovered, named, and linked into a network.

- **Worldgen frequency:** about **1 every 25 chunks** (`frequency = 25`).
- **Dimensions:** Overworld, Nether, and End are all eligible (`dimensionAllowList` includes all three).
- **Village placement:** waystones **do spawn in villages**, and are **forced near the center** (`spawnInVillages = true`, `forceSpawnInVillages = true`).
- **Naming:** worldgen uses the custom Ashen‑themed name list (`nameGenerationMode = PRESET_FIRST`).

### Teleport costs and cooldowns
Teleportation exists to reduce repetitive backtracking once you’ve explored.

- **Distance cost:** **1 XP level per 1000 blocks** (`blocksPerXpLevel = 1000`).
- **Max base cost:** **3 levels** (`maximumBaseXpCost = 3.0`).  
  That means even very long jumps won’t exceed a base cost of 3 levels.
- **Dimensional travel:** **3 XP levels flat** (`dimensionalWarpXpCost = 3`).
- **Warp Stone & inventory button:** **0 XP** (their multipliers are `0.0`).
- **Cooldowns:** **300s** (5 minutes) for **Warp Stone** and **Inventory button** (`warpStoneCooldown = 300`, `inventoryButtonCooldown = 300`).
- **Charge time:** Warp Stone and scrolls take **32 ticks** (1.6s) to use; warp plates take **20 ticks** (1s).

### Restrictions & behavior
- **Rename locked:** only the placer can rename (`restrictRenameToOwner = true`).
- **Generated waystones are unbreakable** (`generatedWaystonesUnbreakable = true`).
- **Leashed mobs come with you**, even across dimensions, except **Withers** (`transportLeashed = true`, denylist includes `minecraft:wither`).

**Design intent:** early on, waystones are landmarks; later, they’re infrastructure. XP costs are deliberately low but **cooldowns are real**, so you still make choices about when to “spend” a teleport.

---

## Small Ships: faster travel, not instant travel

Ships are meant to make ocean and river travel feel fast *if you invest in them*. They’re not meant to delete travel time; they’re meant to make it feel rewarding.

### Ship combat and durability
- **Collision damage:** **7.5** (ships hurt when they hit things at speed).
- **Knockback on collision:** enabled.
- **Sunken ships despawn:** **15 minutes**.
- **Cannon damage:** **25** per hit.
- **Cannon terrain damage:** **1.0** (low, so combat is risky but not world‑destroying).

### Speed modifiers (global)
- **Container penalty:** up to **10%** speed loss when full.
- **Cannon penalty:** **2.5%** speed loss per cannon.
- **Paddling bonus:** **+35%** for paddle ships while paddling.
- **Biome bonus/penalty:** up to **±20%** depending on biome type.
- **Shield damage reduction:** **3% per shield**.

### Ship classes (base stats)
- **Cog**  
  - **Health:** 300  
  - **Speed:** 30 km/h  
  - **Rotation speed:** 4.5  
  - **Container:** 108 slots (12 rows)  
  - **Biome preference:** Cold
- **Brigg**  
  - **Health:** 450  
  - **Speed:** 35 km/h  
  - **Rotation speed:** 4.0  
  - **Container:** 162 slots (18 rows)  
  - **Biome preference:** Cold
- **Galley**  
  - **Health:** 200  
  - **Speed:** 30 km/h  
  - **Rotation speed:** 5.0  
  - **Container:** 54 slots (6 rows)  
  - **Biome preference:** Warm
- **Drakkar**  
  - **Health:** 200  
  - **Speed:** 30 km/h  
  - **Rotation speed:** 5.0  
  - **Container:** 54 slots (6 rows)  
  - **Biome preference:** Cold

### Practical implications
- Bigger ships are **faster and tougher**, but trade turn speed and require investment.
- Cargo and armament **slow you down**, so travel vs combat is a real choice.
## Spyglass Utility

Scouting is an underrated part of travel. Spyglass Improvements is tuned for clarity, not gimmicks:

- **Zoom step size:** **0.1** per tick.
- **Crosshair hidden while scoping** (clean visuals).
- **Overlay:** default (keeps vanilla readability).

**Design intent:** scouting is a tool, not a power spike. You get information, not speed.

## In Summary

Travel tools in **Ashen Legacy** are meant to **reward planning** rather than erase distance. Waystones are your late‑game network with real cooldowns. Ships reward investment and smart loadouts. Utility features help you *see* and *move* better without bypassing the world.
