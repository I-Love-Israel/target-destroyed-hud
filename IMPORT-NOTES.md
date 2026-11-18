# target-destroyed-hud

Source snapshot: source.zip (extract to work on the project). File hashes are in source-manifest.json. AGENTS.md records the required commit-and-push workflow.

target-destroyed-hud-1.1.0+26.2.jar was built from this source snapshot on 2026-11-18 with build.ps1 (Java 25, Minecraft 26.2). Version 1.1.0 adds the loot guard: after you kill an enemy player and no other enemy is within 30 blocks of the body, world clicks lock for 1.5 seconds, and a friend's death always locks them for 2 seconds. It is on by default. `/targethud lootguard true|false` turns it on or off, and `/targethud friend add|remove|list <name>` manages the friends list, whose players are never counted as enemies.

Compiled files are preserved existing builds, not rebuilt or tested during this backup. Desktop installers are in GitHub Releases. Build caches and personal runtime data are excluded.
