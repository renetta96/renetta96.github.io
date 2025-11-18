> I generated speech lines using OpenAI GPT. If you find any weird dialogue, please report in the comment.

> I also added a skill tree. It's a work in progress. Will gradually add more skills, refine FX, balance, etc.

# Table of Contents
- [Introduction](#introduction)
- [Hives](#hives)
- [Metapises](#metapises)
- [Tokens](#tokens)
- [Items](#items)
- [Skill Tree](#skilltree)
- [Others](#others)

# **Introduction** <a name="introduction"></a>

*Wuzzy is the bee master, with his own family of bees. The bees are called Metapis (apis is bee in Latin, so Metapis means Metabee, just like Metahuman).*

**Stats**
- Health: 175
- Sanity: 100
- Hunger: 150
- Damage modifier: 0.75

**Perks**
- Has chance to summon bees on attack, maximum of 4. Initially he has a pool of maximum 6 bees.
- Refilling the pool costs both hunger and time, scaled to his current hunger. Refilling stops below 20% hunger.
- Gains 25% bonus from [honeyed and sweet foods](https://dontstarve.fandom.com/wiki/Sweetener). Only get 50% from non-honeyed foods. His favorite food is Honey Ham.
- Runs faster in spring, slower in winter.
- Has coldness resistance based on number of symbiotic bees he currently has.
- Can gather pollen from flowers. Produce 1 honey after eating 10 pollen.
- Won't trigger wasp hives and bee box when harvesting.


# **Hives** <a name="hives"></a>

## **Metapis Mother Hive**
![Metapis Mother Hive](https://i.imgur.com/1zfmgxb.png)
- At most one can be built at a time per world.
- Provides sanity when stand nearby.
- Can be upgraded to level 3.
- Repairs itself and nearby child hives slowly.
- Releases bees to protect Wuzzy players.
- Level 2 & 3 each adds 1 extra to Wuzzy's bees pool.
- Level 3 has a lamp that lights on at night.


## **Metapis Container**
![Metapis Container](https://i.imgur.com/ULxlGL6.png)
- Limit to 1 per Mother Hive.
- Can contain honey and pollen. Honey stops perishing when put into the container.
- Can refresh Honey Armor using honey if put inside.
- Produces honey from pollen periodically. 


## **Metapis Teleportal**
![Metapis Teleportal](https://i.imgur.com/rlj8EYM.png)

**Tier:** ![Tier](https://i.imgur.com/l03Rzrl.png)

- Teleports bees from Mother Hive to fight for Wuzzy.
- May cost honey every time a bee is summoned.

## **Child Hives**
- Allows Mother Hive / Teleportal and Wuzzy to spawn/summon more types of Metapis to fight.
- Each hive adds 1 max bee to Mother Hive. Each 2 hives adds 1 bee to Wuzzy's pool.
- Can only be built near a Mother Hive.
- Extra bees from Child Hives consume honey in Container periodically. Without enough honey, they gradually die.
- Regenerating extra bees cost honey. Without enough honey, they stop regenerating.

### **Metapis Moonguard Hive**
![Metapis Moonguard Hive](https://i.imgur.com/zI5m1RN.png)

**Tier:** ![Tier](https://i.imgur.com/bKTYiQp.png)

Recipe: 2 Beefalo Horn, 1 Honeycomb, 10 Moonrock

### **Metapis Voltwing Hive**
![Metapis Voltwing Hive](https://i.imgur.com/gVnINaD.png)

**Tier:** ![Tier](https://i.imgur.com/gCSTnmA.png), sold by ![Crabby Hermit](https://i.imgur.com/xbwpw3U.png) lv.6

Recipe: 2 Volt Goat Horn, 1 Honeycomb, 8 Cookie Cutter Shell

### **Metapis Mutant Hive**
![Metapis Mutant Hive](https://i.imgur.com/U3UH707.png)

**Tier:** ![Tier](https://i.imgur.com/IXiuiaI.png)

Recipe: 8 Moon Moth Wings, 1 Honeycomb, 10 Moon Shard

### **Metapis Shadow Hive**
![Metapis Shadow Hive](https://i.imgur.com/lyiuEVG.png)

**Tier:** ![Tier](https://i.imgur.com/Zl7jKJd.png)

Recipe: 10 Nightmare Fuel, 1 Honeycomb, 6 Thulecite

### **Metapis Alchemist Hive**
![Metapis Alchemist Hive](https://i.imgur.com/nIszzPl.png)

**Unlock after defeating Bee Queen 2 times (non-retroactively).**

Recipe: 8 Butterfly, 1 Honeycomb, 6 Papyrus.

### **Metapis Barrack**
![Metapis Barrack](https://i.imgur.com/5ETpbz4.png)

**Tier:** ![Tier](https://i.imgur.com/ldR9iTj.png)

Recipe: 40 Honey, 1 Honeycomb, 4 Killerbee
- Adds 2 bees to Mother Hive.
- Adds 1 bee to Wuzzy.
- Makes Mother Hive regen bees faster.
- Boost bees' health and damage by this multiplier: 1 + log_base_1.5(num_barracks)

# **Metapises** <a name="metapises"></a>

## **Metapis Worker**
![Metapis Worker](https://i.imgur.com/02GVD42.png)
- Pollinates flowers and stores pollen in the Metapis Container.
- Will not fight, instead go back home or run away.
- Brings more pollen home as Mother Hive's stage advances.

## **Metapis Soldier**
![Metapis Soldier](https://i.imgur.com/T01zomk.png)
- Can be spawned/summoned by default.
- Mother Hive stage 2: +25% damage absorption.
- Mother Hive stage 3: has chance to immediately reset attack cooldown on attacked.

## **Metapis Moonguard**
![Metapis Moonguard](https://i.imgur.com/lpDqOAP.png)
- Tanky.
- Taunts nearby enemies every second.
- Mother Hive stage 2: +50% damage absorption.
- Mother Hive stage 3: on hit, apply Frostbite debuffs that reduce attacker's movement speed and damage, stack up to 5 times (50% reduced movement speed, 10% reduced damage). Also may add coldness, that eventually freeze attackers if stacks enough (like Chilled Amulet).

## **Metapis Voltwing**
![Metapis Voltwing](https://i.imgur.com/hihMnda.png)
- Slow & long ranged electric attack.
- Mother Hive stage 2: has 30% chance to double strike.
- Mother Hive stage 3: has 35% chance to double strike, 20% to tripple strike.

## **Metapis Mutant**
![Metapis Mutant](https://i.imgur.com/reEZHi5.png)
- Moves fast.
- Mother Hive stage 2: deal backstab damage. Combo well with Moonguard's Taunt.
- Mother Hive stage 3: poison attack.

## **Metapis Shadow**
![Metapis Shadow](https://i.imgur.com/nkenvEZ.png)
- Medium ranged AOE attack. Each attack summons AOE spikes to strike the enemy, enemies closer to the middle take more damage.
- Mother Hive stage 2: teleport away to avoid when attacked.
- Mother Hive stage 3: increase damage area.

## **Metapis Mimic**
![Metapis Mimic](https://i.imgur.com/bfHIAo2.png)
- Evolves from Metapis Soldier via Skill Tree. Randomly changes attacks based on nearby Metapises: 
  + Metapis Mutant: Deals poison attacks and causes poison ticks to have a chance to deal increased damage.
  + Metapis Shadow: Has a chance to cause a spike area attack. May shred damage absorption from enemies, causing them to take more damage, stack up to 20 times (20% more damage taken).
  + Metapis Moonguard: Add coldness to the target and deals extra % health damage when the target unfreezes.
  + Metapis Voltwing: Has a chance to trigger an immediate attack from a nearby Voltwing.
  + Metapis Alchemist: Has a chance to heal a nearby ally. 

## **Metapis Alchemist**
![Metapis Alchemist](https://i.imgur.com/mkCEPdR.png)
- Periodically heal another bee. Amount increases per attack between healings.
- Mother Hive stage 2: heals 2 more bees.
- Mother Hive stage 3: heals 3 more bees. Also periodically throws a healing orb for Wuzzy nearby. Consecutive orbs within 10 seconds heal less, to a minimum of 30% effectiveness.

# **Tokens** <a name="tokens"></a>

![](https://i.imgur.com/0iWltIZ.png) ![](https://i.imgur.com/K2QWMui.png) ![](https://i.imgur.com/XRT2qlJ.png) ![](https://i.imgur.com/z25xjsL.png) ![](https://i.imgur.com/roEIMIv.png) ![](https://i.imgur.com/vug3xtj.png)

**In short, they are used to control how many minions of each type you want to summon.**

There are 6 types of Tokens, each tied to a Metapis:

- **Soldier/Mimic Token**: unlocked from the start.  
- **Moonguard Token**: unlocked with Moonguard Hive.  
- **Voltwing Token**: unlocked with Voltwing Hive.  
- **Mutant Token**: unlocked with Mutant Hive.  
- **Shadow Token**: unlocked with Shadow Hive.  
- **Alchemist Token**: unlocked with Alchemist Hive.

When the **Mother Hive** reaches **Level 3**, it unlocks a container with **6 slots**.  
You can insert Tokens to control the types of Metapises you summon:

- One token = 1 out of 6 minions will be that type.  
- One empty slot = 1 out of 6 minions will be randomized among available types.

**Examples:**

1. Built Moonguard, Shadow, and Alchemist Hives. Slots: Moonguard x2, Shadow x2, empty x2.  
   - For every 6 minions: 2 Moonguards, 2 Shadows, 2 random (Moonguard/Shadow/Alchemist).

2. Built Moonguard, Shadow, and Alchemist Hives. Slots: Shadow x6.  
   - All summoned minions are Shadows.

3. Built Moonguard, Shadow, and Alchemist Hives. Slots: Shadow x3, Moonguard x3.  
   - 3 Shadows and 3 Moonguards per 6 minions.

# **Items** <a name="items"></a>

## **Honey Suit**
![Honey Suit](https://i.imgur.com/KScIwLf.png)
- Indestructible, but perish over time like Ham Bat.
- Damage absorption from 50-70% based on spoilage.
- When hit, recovers health per 3 seconds for 3 times based on spoilage and lost health.
- Adds 1 to Wuzzy's bee pool, and helps refill the pool up to 33% faster based on spoilage.
- Can be put in Mother Hive to stop perishing and refresh spoilage by consuming honey.

## **Melissa**
![Melissa](https://i.imgur.com/36uY5Fp.png)
- 40 damage, 150 uses
- Minions summoned on attack using Melissa will be a bit stronger.

## **Pollen**
![Pollen](https://i.imgur.com/aatBqPp.png)
- Can be picked from flowers. Regrows after 2 days in game.
- Is edible, but very minor benefit.
- Perishes in 10 days, but 5 times faster if it gets wet.
- Stops perishing when put in the hive.
- In winter, flowers stop producing pollen, only resume in spring. In spring, there is 50% chance to pick 2 pollen from a flower.

# **Skill Tree** <a name="skilltree"></a>

## **Metapimancer**


| **Skill** | **Description** | **Prerequisites** |
| :----------------: | :------ | :---- |
| ![](https://i.imgur.com/Bzcj5pE.png) <br> Tyrant I | Halve all Metapises' health and damage. Boost Wuzzy’s stats and set damage multiplier to 1.05x - 1.5x based on Mother Hive upgrades. | Shepherd skills are not unlocked. |
| ![](https://i.imgur.com/RFeicHP.png) <br> Tyrant II | When attacked, Wuzzy may redirect 10x damage to 3 nearby Metapises, guaranteed at 30% HP. If too few Metapises are nearby, Wuzzy takes the hit. | Tyrant I |
| ![](https://i.imgur.com/jt487z6.png) <br> Shepherd I | Reduce Wuzzy's stats, set damage multipler to 0.6x. Boost all Metapises' health and damage by 25%. Metapises are able to attack shadow creatures. | Tyrant skills are not unlocked. |
| ![](https://i.imgur.com/CNgbuzj.png) <br> Shepherd II | Attacking or being attacked may enrage nearby Metapises, boosting their damage and speed. Chance and number affected scale with Wuzzy’s missing health. | Shepherd I |


## **Metapis**

### **Metapis Mutant**

| **Skill** | **Description** | **Prerequisites** |
| :----------------: | :------ | :---- |
| ![](https://i.imgur.com/RBJYHEM.png) <br> Metapis Mutant I | Less poison base damage but it becomes stackable. Maximum 20 stacks. | Cannot activate more than 4 Metapis skill trees. |
| ![](https://i.imgur.com/cCUfpks.png) <br> Metapis Mutant II | Directly summoned Metapis Mutants have a chance to coat Wuzzy’s attacks in poison for 10 seconds. This coating also gives poison ticks on the target a chance to deal increased damage. | Metapis Mutant I |

### **Metapis Shadow**

| **Skill** | **Description** | **Prerequisites** |
| :----------------: | :------ | :---- |
| ![](https://i.imgur.com/OWlybvW.png) <br> Metapis Shadow I | Metapis Shadows can summon Shadowlings to attack enemies. These melee minions have health decay over time and any damage received is capped at 15% max health. | Cannot activate more than 4 Metapis skill trees. |
| ![](https://i.imgur.com/2G7UMRd.png) <br> Metapis Shadow II | When a Metapis dies, it has a chance to spawn Shadowlings. On death, Shadowlings may release damaging spikes at nearby enemies. If Metapis Alchemist II is activated and the dying Metapis is frenzied, it will always spawn frenzied Shadowlings instead. | Metapis Shadow I |

### **Metapis Moonguard**

| **Skill** | **Description** | **Prerequisites** |
| :----------------: | :------ | :---- |
| ![](https://i.imgur.com/TzUZcpD.png) <br> Metapis Moonguard I | Metapis Moonguards now reduce incoming damage by 30% to 80%, depending on their missing health, reaching maximum reduction at 30% health. Additionally, they possess a chance to shield nearby ally Metapises from any incoming damage. Activates only at Mother Hive level 2. | Cannot activate more than 4 Metapis skill trees. |
| ![](https://i.imgur.com/EMyZX2C.png) <br> Metapis Moonguard II | Metapis Moonguards have a chance to retaliate with an ice nova upon receiving any damage. This also applies to damage received from shielding allies. Activates only at Mother Hive level 3. | Metapis Moonguard I |

### **Metapis Voltwing**

| **Skill** | **Description** | **Prerequisites** |
| :----------------: | :------ | :---- |
| ![](https://i.imgur.com/XsXNFX5.png) <br> Metapis Voltwing I | Metapis Voltwings orbit around their target, periodically firing electric orbs. Each attack builds up their charge, and at full power, they unleash an electric wisp that accelerates toward the target, dealing damage on impact. | Cannot activate more than 4 Metapis skill trees. |
| ![](https://i.imgur.com/55LEHJV.png) <br> Metapis Voltwing II | Metapis Voltwings' attacks apply a debuff to their target. When the target thaws, electric wisps erupts from them and circles back to strike again. Additionally, Wuzzy's attacks have a chance to charge some nearby Voltwings. | Metapis Voltwing I |

### **Metapis Mimic**

| **Skill** | **Description** | **Prerequisites** |
| :----------------: | :------ | :---- |
| ![](https://i.imgur.com/iqvUQKq.png) <br> Metapis Mimic I | Evolve Metapis Soldiers into Metapis Mimics, which periodically adapt their abilities based on nearby Metapises. They can only hold 1 ability mostly, but sometimes can hold up to 2 abilities. | Cannot activate more than 4 Metapis skill trees. |
| ![](https://i.imgur.com/FhMrzP6.png) <br> Metapis Mimic II | Metapis Mimics can now retain up to 2 abilities, and sometimes can hold up to 3. | Metapis Mimic I |


### **Metapis Alchemist**

| **Skill** | **Description** | **Prerequisites** |
| :----------------: | :------ | :---- |
| ![](https://i.imgur.com/5oV6MKk.png) <br> Metapis Alchemist I | Metapis Alchemists periodically release pheromones, briefly frenzying nearby allies to boost attack speed but increase damage taken. Their heal orbs also gain Wuzzy’s bonus movement speed for a short time, stacking up to 3 times. | Cannot activate more than 4 Metapis skill trees. |
| ![](https://i.imgur.com/i1gg3OJ.png) <br> Metapis Alchemist II | When a Metapis dies while frenzied, it explodes, dealing double damage in a small area. If Metapis Shadow II is active, it always spawns Shadowlings on death and sends them into a frenzy. | Metapis Alchemist I |


## **Honeysmith** 


| **Skill** | **Description** | **Prerequisites** |
| :----------------: | :------ | :---- |
| ![](https://i.imgur.com/avtK6QQ.png) <br> Melissa I | Every 4th attack with Melissa, Wuzzy slams the target for 3x damage. Also double Melissa's max uses. | Available from the start. |
| ![](https://i.imgur.com/sEuzkkR.png) <br> Melissa II | Wuzzy uses Melissa to swap with another Metapis, consuming durability. The swapped Metapis becomes frenzied and enraged. Melissa now deals 52 damage. | Melissa I |

## **Affinity**

*WIP*
  
# **Others** <a name="others"></a>
- Wuzzy has a widget to show the current number of symbiotic bees inside him and the regeneration progress.

![Widget 1](https://i.imgur.com/fpW3Zyr.png)![Widget 2](https://i.imgur.com/Q73cwy7.png)![Widget 3](https://i.imgur.com/Uc8bcq8.png)![Widget 4](https://i.imgur.com/We79Y0w.png)
