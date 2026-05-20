# Craftable Spawn Eggs

This datapack makes every spawn egg in Minecraft craftable using items related to each specific mob.

---

## 🛠️ How to Craft

Place **8 Eggs** around a mob-specific item in a crafting table.

|     |          |     |
| :-: | :------: | :-: |
| Egg |   Egg    | Egg |
| Egg | **Item** | Egg |
| Egg |   Egg    | Egg |

_Example: Use a piece of Beef in the center to craft a Cow Spawn Egg._

---

## 💾 Installation Guide

Because Minecraft handles datapacks differently depending on the version, please follow the specific guide below:

<a id="manual-guide"></a>

### 🔹 Minecraft 1.20.x & Vanilla Installations

If you are playing on 1.20 to 1.20.6 versions, or if you play pure Vanilla on any version, global mods might not inject into existing worlds. You **must** follow these manual steps:

1. Download the correct file for your version.
2. Go to your Minecraft folder, open `saves`, find your world folder, and open the `datapacks` directory: `.minecraft/saves/[YourWorldName]/datapacks/`
3. Drop the datapack folder or `.zip` file inside it.
4. Open your world in-game and run the command: `/datapack list` to verify if the game detected it.
5. If it is disabled, run: `/datapack enable "pack_name"` _(Pro-tip: Just type `/datapack enable` and press `Tab` to autocomplete the name!)_

### 🔸 Modded Global Loading (Minecraft 1.21+)

If you want to load the pack automatically across multiple worlds on newer modded setups, you can use a data loader mod:

- **For 1.21 to 1.21.1:** You can use popular global data loader mods like **Paxi**, **Open Loader**, **Global Packs**, or **FTB Obsidian**. **Remember to download the version that matches your modloader.**
- **For 1.21.2+:** Since the classic mods might not be available for the newest versions yet, [**Simple Datapacks**](https://www.curseforge.com/minecraft/mc-mods/simple-datapacks) is the perfect substitute. Drop the datapack into your instance's global folder, but **remember:** you still need to run `/datapack enable "pack_name"` inside the world to actually activate it!

⚠️ **NOTE:** If the datapack still doesn't show up after using a mod, follow the [manual Vanilla process detailed above](#manual-guide).

---

## ⚠️ Which file should I download?

**Important:** Because Minecraft significantly changed internal data structures (like Data Components, folder structures, and Item Tags) between updates, you **must download ONLY the file that matches your exact Minecraft version:**

| Minecraft Version   | Download File         |
| :------------------ | :-------------------- |
| **1.20 - 1.20.4**   | Version 1.20-1.20.4   |
| **1.20.5 - 1.20.6** | Version 1.20.5-1.20.6 |
| **1.21 - 1.21.1**   | Version 1.21-1.21.1   |
| **1.21.2 - 1.21.4** | Version 1.21.2-1.21.4 |
| **1.21.5+**         | Version 1.21.5+       |

_Note: Only install one of these files at a time per world to prevent recipe conflicts._

---

## 💡 Recommendations

- [**JEI (Just Enough Items):**](https://www.curseforge.com/minecraft/mc-mods/jei) Highly recommended to view the specific ingredients for every spawn egg directly in-game.
- [**Polymorph:**](https://www.curseforge.com/minecraft/mc-mods/polymorph) If you find that recipes conflict with vanilla crafting or other mods, this mod adds a button allowing you to select the desired result when multiple recipes share ingredients.

---

## 🔍 Recipes List (Spoilers!)

Since recipes are hidden by default in vanilla Minecraft until discovered, you can expand the section below to check the exact item required in the center of the grid for each mob egg:

<details>
<summary><b>Click here to expand the Recipes List 📝</b></summary>

| Mob Spawn Egg        | Center Item Required     |
| :------------------- | :----------------------- |
| **Allay**            | Amethyst Shard           |
| **Armadillo**        | Armadillo Scute          |
| **Axolotl**          | Axolotl Bucket           |
| **Bee**              | Honeycomb                |
| **Blaze**            | Blaze Rod                |
| **Bogged**           | Moss Block               |
| **Breeze**           | Breeze Rod               |
| **Camel**            | Cactus                   |
| **Cat**              | Cod                      |
| **Cave Spider**      | Fermented Spider Eye     |
| **Chicken**          | Egg                      |
| **Cod**              | Cod Bucket               |
| **Copper Golem**     | Copper Ingot             |
| **Cow**              | Beef                     |
| **Creaking**         | Resin Clump              |
| **Creeper**          | Gunpowder                |
| **Dolphin**          | Heart of the Sea         |
| **Donkey**           | Chest                    |
| **Drowned**          | Nautilus Shell           |
| **Elder Guardian**   | Wet Sponge               |
| **Enderman**         | Ender Pearl              |
| **Endermite**        | Chorus Fruit             |
| **Evoker**           | Totem of Undying         |
| **Fox**              | Sweet Berries            |
| **Frog**             | Pearlescent Froglight    |
| **Ghast**            | Ghast Tear               |
| **Glow Squid**       | Glow Ink Sac             |
| **Goat**             | Goat Horn                |
| **Guardian**         | Prismarine Crystals      |
| **Happy Ghast**      | Cake                     |
| **Hoglin**           | Crimson Fungus           |
| **Horse**            | Saddle                   |
| **Husk**             | Sand                     |
| **Iron Golem**       | Carved Pumpkin           |
| **Llama**            | Wool Carpets             |
| **Magma Cube**       | Magma Cream              |
| **Mooshroom**        | Red Mushroom             |
| **Mule**             | Golden Carrot            |
| **Nautilus**         | Conduit                  |
| **Ocelot**           | Jungle Leaves            |
| **Panda**            | Bamboo                   |
| **Parrot**           | Cookie                   |
| **Phantom**          | Phantom Membrane         |
| **Pig**              | Porkchop                 |
| **Piglin Brute**     | Golden Axe               |
| **Piglin**           | Gold Block               |
| **Pillager**         | Crossbow                 |
| **Polar Bear**       | Salmon                   |
| **Pufferfish**       | Pufferfish Bucket        |
| **Rabbit**           | Rabbit Foot              |
| **Ravager**          | Ominous Bottle           |
| **Salmon**           | Salmon Bucket            |
| **Sheep**            | Wool                     |
| **Shulker**          | Shulker Shell            |
| **Silverfish**       | Stone Bricks             |
| **Skeleton Horse**   | Bone Block               |
| **Skeleton**         | Bow                      |
| **Slime**            | Slime Block              |
| **Sniffer**          | Torchflower Seeds        |
| **Snow Golem**       | Snow Block               |
| **Spider**           | Cobweb                   |
| **Squid**            | Ink Sac                  |
| **Stray**            | Powder Snow Bucket       |
| **Strider**          | Warped Fungus on a Stick |
| **Tadpole**          | Lily Pad                 |
| **Trader Llama**     | Lead                     |
| **Tropical Fish**    | Tropical Fish Bucket     |
| **Turtle**           | Turtle Scute             |
| **Vex**              | Iron Sword               |
| **Villager**         | Emerald                  |
| **Vindicator**       | Iron Axe                 |
| **Wandering Trader** | Packed Ice               |
| **Warden**           | Sculk Shrieker           |
| **Witch**            | Brewing Stand            |
| **Wither Skeleton**  | Wither Skeleton Skull    |
| **Wolf**             | Bone                     |
| **Zoglin**           | Crimson Roots            |
| **Zombie Horse**     | Zombie Head              |
| **Zombie Nautilus**  | Dried Kelp               |
| **Zombie Villager**  | Golden Apple             |
| **Zombie**           | Rotten Flesh             |
| **Zombified Piglin** | Gold Nugget              |

</details>
