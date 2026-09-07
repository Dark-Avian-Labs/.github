# Dark Avian Labs

Tools we reach for ourselves. Warframe loadouts and collection trackers. Watcher of Realms gear. A Discord bot for Ark of War. A Windows snippet manager, a homelab diagram editor, a household budget you can share.

Hosted apps sign in with [Clerk](https://clerk.com). Desktop and local tools stay off the server. Source is on GitHub.

## Projects

### [Codex](https://codex.darkavianlabs.com)

Collection tracker for Warframe, Epic Seven, and Watcher of Realms. Tables and worksheets per game, not a generic form. Warframe catalog data syncs from Armory.

### [Armory](https://armory.darkavianlabs.com)

Warframe mod builder and item catalog. Helminth, Archon shards, Incarnon, named builds and loadouts. Codex reads the same catalog.

### [Outfitter](https://outfitter.darkavianlabs.com)

Watcher of Realms gear inventory and loadout optimizer. Mythic pieces, one loadout per hero, search the stash for sets that hit stat floors. Hero catalog and combat stats come from Codex.

### [TC-Bot](https://github.com/Dark-Avian-Labs/TC-Bot)

Discord bot for Ark of War, built for Diplomacy of War. Slash commands for healing, gear, and iTS. Mopup timing posted into channels.

### [Poltergeist](https://github.com/Dark-Avian-Labs/Poltergeist)

Portable Windows snippet manager. Global hotkey, nested picker at the cursor, tokens, conditionals, DeepL. Successor to GhostWriter.

### [InfoGraphic](https://github.com/Dark-Avian-Labs/InfoGraphic)

Local-first homelab topology editor. Drag devices, wire ports, export SVG or PNG. No account, no server.

### [BudgetPlanner](https://budget.darkavianlabs.com)

Shared household budget for recurring expenses, income, and credits. Invite by email. English and German.

### AerieDrive

Portable dev-environment sync for gitignored config and an age-encrypted vault. In development. Not public yet.

## What we value

- Software we use ourselves, then publish
- Worksheets, loadouts, and diagrams before the chrome
- InfoGraphic and Poltergeist run locally. TC-Bot is self-hosted
- The same glass UI across Codex, Armory, Outfitter, BudgetPlanner, and [darkavianlabs.com](https://darkavianlabs.com)

## Tech focus

- TypeScript on the web, Rust on the Windows desktop
- React, Vite, and Tailwind for the hosted apps
- Clerk for sign-in on Codex, Armory, Outfitter, and BudgetPlanner
- GitHub for source, GitHub Actions for validate and deploy
