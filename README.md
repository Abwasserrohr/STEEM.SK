# STEEM.SK
STEEM.SK is a script for Bukkit/Spigot, which allows players to interact with the STEEM Blockchain within Minecraft.
Server owners can create custom transactions with the Steem Blockchain and get data from Steem Nodes.

## Setup
1. Build SteemJ from [here](https://github.com/muksihs/steem-java-api-wrapper) and move the `SteemJ with dependencies.jar` file to the `plugins/skript-mirror/` folder.
2. Load the latest files to your `plugins/Skript/scripts/` folder.
3. Restart the server.
4. To use STEEM.SK, a Steem wallet is needed.
5. Insert your private postig key and dedicated minecraft server steem wallet name to the config.sk file.
6. You can also create transactions for your players, they have to authorize your server account for this: `https://steemconnect.com/authorize/@<your dedicated minecraft server steem wallet name>`
7. If you players should have transactions created, they have to add themself using `/steem sync <steem name>`
8. You're done, feel free to visit the wiki for detailed information what you can do with **STEEM.SK**.
