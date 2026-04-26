# ItemLocks-Issues
This repository is intended for issues tracking for ItemLocks, a Minecraft mod for Minecraft. You can download it on [Modrinth](https://modrinth.com/mod/itemlocks/versions) and [CurseForge](https://www.curseforge.com/minecraft/mc-mods/itemlocks/files). You can also find the FAQ over on [itemlocks.com/faq](https://itemlocks.com/faq/).

### Links
- Download on [Modrinth](https://modrinth.com/mod/itemlocks/versions)
- Download on [CurseForge](https://www.curseforge.com/minecraft/mc-mods/itemlocks/files)
- Read the [FAQ](https://itemlocks.com/faq/)
- Visit the [Website](https://itemlocks.com/)

# What is ItemLocks? (This section is copied from the mod pages on CurseForge and Modrinth)
ItemLocks allows you to lock item slots in your inventory, preventing you from moving items unwillingly.  
Ever been in a tight PvP situation, or just minding your own business, and suddenly that one guy shows up?  
Well luckily you used this mod, locked the sword slot, and kept your weapon steady despite pressing Q in full panic.

**Main Features:**
- Toggle lock on individual slots by holding **LOCK** (Default: C) and left clicking a slot.
- Bypass a lock by holding **BYPASS** (Default: B) and interacting with a slot.
- Separate locks are saved per world/server without the need of the user's intervention.
- Fully configurable to your own liking, either through Mod List or by pressing **OPTIONS** (Default: N).
- Locks cannot be placed on an empty slot (will be configurable in the future).
- Making a slot empty while bypassing a lock does not remove the lock.
- Empty slots with a lock are unlocked until it's occupied.

ItemLocks does not grant immunity to item loss during death nor prevents server from manipulating the inventory. The mod is fully client side and only does what the client is capable of.

# Bug Reports, Feedback and Suggestions.
First make sure you've read the [FAQ](https://itemlocks.com/faq/) and that no other issues mention your specific issue. If you still need to open an issue, do so by following one of the templates.

# Contributions?
ItemLocks is currently closed source. Partially due to my confusing use of branches and patching, working with a public repository would honestly slow down the process of implementing anything in a reasonable amount of time. That being said, ItemLocks itself is not obfuscated, so if you are curious what it does, feel free to decompile it instead.

### Why not do source available without a license?
Because that's honestly more confusing than having it closed source, especially for users not too used with open source and source available and how that stuff works. And this also ties in directly to how I do branches for ItemLocks.

Since I support a range of versions, not just the latest versions, the idea of one singular master/main branch doesn't make sense for me. Instead each supported version has its own branch which I then apply using patches. This is not ideal for an open source project, nor is it ideal for GitHub's UI itself, but it works for my current workflow and I've managed to optimize the development in a way where keeping track of these branches isn't too difficult.

With this in mind, the idea of having users interact with a lot of individual branches rather than one singular branch, it wouldn't work in the long run, and would be quite difficult for me to handle.
