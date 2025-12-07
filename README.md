
# minecraft-item-db
⚠️ This is not complete! The JSON file will be added soon. ⚠️
A database of all the item IDs, names, and icon sources in Minecraft, in JSON format.

**Format:**

    {
	    "minecraft:item_id": {
		    name: "Item Name",
		    texture: "url/to/texture"
	    }
	}

**Usage (JavaScript):**

    let itemID = "minecraft:diamond";
    let item = itemDefinitions[itemID];
    console.log(itemID); // minecraft:diamond
    console.log(item.name); // Diamond
    console.log(item.texture); // https://raw.githubusercontent.com/InventivetalentDev/minecraft-assets/1.21.10/assets/minecraft/textures/item/diamond.png
