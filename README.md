# ARPGE-Unity
A framework-in-progress for making Action-RPG (ARPG), or "Diablo clones", on Unity. They may also be known as "hack-and-slash" games. Diablo, released in 1996, was a rogue-like dungeon crawler, and its successor, Diablo II, released in 2000, are heavy influences to the genre, that inspired many ARPGs developed in the following years.

The key features of an ARPG are defined by the following:
- Isometric view
- Point & click (Mouse click to move & interact)
- Fighting against lots of mobs
- Character customisation
- Item/loot system, usually with mods & rarity levels
- Crafting system, such as adding quality or rolling mods onto it
- Quests to progress storyline but generally “optional”


Common Tropes (i.e. common traits shared by ARPGs, due to large references to the Diablo series)
- Grid-like inventory, stash
- Multiple acts
- Multiple difficulty levels, usually requiring you to play through multiple times (albeit most modern ARPGs do not follow this anymore)
- Usually offer a hardcore mode (some form of permadeath)
- Typically dark fantasy setting

The 7 Features of ARPGE Framework:
1. Game World Interaction
- Movement
- Camera
- World Interaction (including Dialogue)

2. Terrain
- Generate terrain
- Placement of objects & enemy spawn points
- Explore possibilities of randomisation
- Minimap
- Spatial Partitioning

3. Inventory
- Grids (pick up & fill up inventory smartly with sorting)
- Equipment slots
- Item base class & types
- Read item information from a database (can be local)
- Stash

4. Skills
- Skill Binding
- Skill Tree
> Node (name, icon (image)
> Unlock conditiosn (a generic Condition class that can be level, node connection?)
> Parent node (reference to Node))

5. Player Stats
- Basic stats (e.g. HP, MP, atk, atk spd)
- Inaccessible stats that affect gameplay (e.g. movement speed)
- Easy-to-create formula for damage algorithms (e.g. choose from presets of algorithms like quadratic, exponential, log, etc)

6. Enemies
- Standard enemies:
> Skeletons
> Zombies/undead
> Some potentially rabid animal

7. User Interface
- Easy-to-create UI
- Create HP/MP bars, Skill Bindings, etc
