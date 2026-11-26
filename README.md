# NOVA shared mod list

The mod list every copy of [NOVA](https://github.com/UrFavOperator/nova-mod-hub) (a Nuclear Option mod manager)
downloads, so it doesn't have to search GitHub itself. It's rebuilt automatically every 6 hours.

- `catalog.json` — every mod NOVA lists (GitHub, Nexus Mods and popular Steam Workshop items), plus a permanent
  number for each GitHub/Nexus mod and the versions it has published. Pack codes like `NOVA-XXXX-XXXX-XXXX` refer to
  mods by these numbers, so numbers are never reused or changed.
- `packs.json` — published mod packs, opened in NOVA with codes like `PACK-K7QX`.
- `extras.json` — mods posted from the developer's NOVA so they can go in pack codes even when the scan doesn't find them.
- `overrides.json` — category corrections.

Everything here is public information from GitHub, Nexus Mods and the Steam Workshop. All mods belong to their
authors.
