# TechProgression

A lightweight progression plugin for Minecraft 1.21.1 that locks crafting recipes, workstations and technologies behind research purchased with an economy or special item requirements.

Designed for survival servers that want a long-term progression system without requiring mods.

---

## Features

- Technology research system
- Economy integration (Vault)
- Item requirement research (End Research)
- Recipe locking
- Workstation locking
- LuckPerms integration
- PlaceholderAPI support
- DeluxeMenus compatible
- Fully configurable
- No client-side mods required

---

## Requirements

- Minecraft 1.21.1
- Java 21
- Vault
- LuckPerms
- Economy plugin compatible with Vault

Optional

- PlaceholderAPI
- DeluxeMenus

---

## Technologies

Current default technologies include

### Tools

- Stone & Gold Equipment
- Iron Tools
- Diamond Tools
- Netherite Tools

### Armor

- Leather Armor
- Iron Armor
- Diamond Armor
- Netherite Armor

### Utility

- Shield
- Buckets
- Shears

### Magic

- Enchanting
- Smithing
- Advanced Enchanting

### Brewing

- Brewing

### Redstone

- Redstone Engineering
- Advanced Redstone

### Storage

- Barrels
- Ender Chest
- Shulker Boxes

### End Game

- End Research

End Research unlocks Eye of Ender crafting by sacrificing rare items instead of paying money.

---

## Commands

| Command | Description |
|----------|-------------|
| /techshop | Opens the technology menu |
| /techbuy <technology> | Purchase a technology |
| /techstatus [technology] | View progression |
| /techunlock <player> <technology> | Admin unlock |
| /techreset <player> <technology> | Admin reset |
| /techreload | Reload configuration |

---

## Permissions

```
techprogression.admin
techprogression.bypass
tech.<technology>
```

Example

```
tech.iron_tools
tech.diamond_tools
tech.enchanting
tech.end_research
```

---

## Configuration

Everything is configured inside

```
plugins/TechProgression/config.yml
```

Each technology supports

- Display name
- Cost
- Item requirements
- Required technologies
- Permission
- Locked items

Example

```yaml
diamond_tools:
  cost: 15000
  requires: iron_tools
  permission: tech.diamond_tools
```

---

## Compatible Plugins

- Vault
- LuckPerms
- PlaceholderAPI
- DeluxeMenus
- TAB

---

## License

Personal project.
Feel free to modify for your own server.
