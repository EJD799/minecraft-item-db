
# minecraft-item-db
A database of all the item IDs, names, and icon sources in Minecraft, in JSON format.

**Format:**

    {
	    "minecraft:item_id": {
		    name: "Item Name",
		    texture: "url/to/texture",
			filter: "bedrock, java, or undefined"
	    }
	}

**Usage (JavaScript):**

    let itemID = "minecraft:diamond";
    let item = itemDefinitions[itemID];
    console.log(itemID); // minecraft:diamond
    console.log(item.name); // Diamond
    console.log(item.texture); // https://raw.githubusercontent.com/InventivetalentDev/minecraft-assets/1.21.10/assets/minecraft/textures/item/diamond.png
	console.log(item.filter); // undefined
