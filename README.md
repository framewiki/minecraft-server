# Framework Minecraft Server
Bug/Suggestion tracker and documentation for the Unofficial Community-Driven Framework Minecraft Server.

More info: https://link.morpheus636.com/fwmc

# Documentation
Join on the version 1.20.1 with hostname mc.framewiki.net

In-game chat is bridged with a channel in the official Framework Discord. A live world map can be found at https://fwmc.morpheus636.com

## Contact Methods
- Feel free to ask any questions in this thread or via [Discord](https://discord.gg/framework). 
- Player reports should be handled via Discord DMs to @morpheus636 or the ModMail bot (please specify it's related to the Minecraft server).
- Feature requests and bug reports should be submitted via the [GitHub Issue Tracker](https://github.com/framewiki/minecraft-server/issues).

## Server Rules
1. Respect all users. Meaning no harassment, arguing, trolling, spamming, or hate speech. 
2. NSFW, offensive content and spam are prohibited.
3. At this time, please keep all chat messages in English.
4. Follow all rules of the official Discord server, as chat is bridged to it.
5. Do not use client modifications, resource packs, auto-clickers, or other non-vanilla tools that give you an unfair advantage. This rule is very open to interpretation by the moderation team.
6. Do not attempt to dupe items or otherwise exploit the server. This includes seed cracking. 
7. No Griefing. Ensure you are using the available anti-griefing measures to protect your builds as the moderation team is unable to reverse changes made by griefers.
8. No Toxic PvP. Act in good faith when engaging in PvP. Do not camp ambush other players.

Basically, be kind to one another, and don't abuse the server. If abuse or moderation become an issue, the server will need to be shut down. Don't ruin it for everyone.

# Features
## Anti-Grief Measures
#### Spawn
A small area around spawn is claimed to prevent people from griefing the spawn point. Wander for a couple minutes and you should reach open areas to build in.
#### Claims
Claiming your land will prevent users you didn't authorize from changing anything within the claimed space. The first chest you place will create a 9x9 claim centered around it automatically. To create new claims or modify the existing one, you'll need to find or make a gold shovel.

To claim an area, simply right-click two opposite corners with a golden shovel in Basic Claims Mode (see commands below - this is the default). Your golden shovel will also allow you to modify claims. There is a limit to how many blocks you can claim. You can increase this limit by playing more.

**Creating and Modifying Claims**
- `/BasicClaims` - Puts your shovel back in basic claims mode if you had it in a different mode.
- `/SubdivideClaims` - Switches your gold shovel to subdivision mode, so you can subdivide your claims.
- `/RestrictSubclaim` - Restricts a subclaim, so that it inherits no permissions from the parent claim.
- `/AbandonClaim` - Deletes the claim you’re standing in.
- `/ClaimExplosions` - Toggles if explosions are allowed in the claim.

**Managing Permissions in Claims**
- `/Trust <user>` - Gives another player permission to edit in your claim.
- `/UnTrust <user>` - Revokes any permissions granted to a player in your claim.
- `/AccessTrust <user>` - Gives a player permission to use your buttons, levers, and beds.
- `/ContainerTrust <user>` - Gives a player permission to use your buttons, levers, beds, crafting gear, containers, and animals.
- `/PermissionTrust <user>` - Grants a player permission to share his permission level with others.
- `/Untrust All` - Removes all permissions for all players in your claim.
- `/TrustList` - Lists the permissions for the claim you’re standing in.

#### Pets
Tamed animals are protected inside and outside of claims such that only their owner can interact with them. By default, the user who tamed them is their owner. Ownership can be transferred using `/GivePet <user>`

#### Item Drops
When you die, only you can pick up your items unless you manually unlock them.
- `/UnlockDrops` - Allows other users to pick up your drops.

## Teleportation
There are two types of teleportation: Homes and Teleport Requests.

**Teleport Requests**
- `/tpa <user>` - Request to teleport to a user.
- `/tpahere <user>` - Request that a user teleport to you.

**Home**
You have a limited number of home points that you can set. These are the related commands:

- `/sethome <homename>` - Set a home that you can teleport to later.
- `/home <homename>` - Teleport to a previously set home.
- `/delhome <homename>` - Delete a previously set home.
- `/back` - Teleport to your last location before you used `/home` or a teleport request.
