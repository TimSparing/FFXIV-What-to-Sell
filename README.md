# FFXIV-What-to-Sell
This code is meant to help players make Gil by looking at data from the universalis market board.
On first time use the homeworld has to be set (this can be changed later), this is the server where you character is located in.
Users can select various pre-defined item lists or create their own, current pre-defined item lists include:
- Carpenter Craftables
- Blacksmith Craftables
- Armorer Craftables
- Goldsmith Craftables
- Leatherworker Craftables
- Weaver Craftables
- Alchemist Craftables
- Culinarian Craftables
- Miner Gatherables
- Botanist Gatherables
- Fisher Gatherables
- Tradeable Mounts
- Tradeable Minions
- Tradeable Dyes
- Tradeable Furniture

## Crafting
Looks at the craftable selected items and their recipes, returns a list that includes the amount for which each craftable item sells, and how much it would costs to purchase the ingredients for it. The highest selling server is selected for the sale price if additional servers besides the homeworld were selected, and the lowest price for ingredients in servers reachable from the homeworld is chosen. Furthermore the user has the option to exlcude following items from the ingredients price calculations:
- Gatherable items
- Huntable items
- Shards/Crystals/Clusters
- NPC Purchaseable items
- Tomestone items

## Flipping
Checks the prices at which all selected items are being traded in all reachable datacentres from the homeworld and compares them to their sale prices in the homeworld or additoinal servers depending on settings and returns a list of the largest price differentials between items trading prices, showing the ideal world to buy and sell (if additional servers besides the homeworld were selected).

## Buying
Checks the prices at which all selected items are selling in all servers in all datacentres reachable from the homeworld or additional servers depending on settings and returns a list showing where each item is cheapest to purchase.

## Selling
Checks the selling prices for all selected items in the homeworld or additional servers depending on settings and returns a list with the most profitable items to sell, weighted on sale price, competition and sale frequency.

# Disclaimer
This code is just written for fun to solidify some knowledge and improve my coding
I can't guarantee that it is well written, the science checks out or that it is competent in any other way
Please let me know if you find any issues though
