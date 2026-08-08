# TechSell

A lightweight sell shop plugin designed for progression servers.

Players earn money by gathering resources and selling them through an easy-to-use GUI.

Built as a replacement for EconomyShopGUI when only selling is needed.

---

## Features

- /techsell GUI
- Live total value
- Stack value preview
- Shift-click support
- Vault economy
- Configurable prices
- Sell-only economy
- Safe item return
- Unsellable items automatically rejected

---

## Requirements

Minecraft 1.21.1

Java 21

Vault

Compatible Vault Economy

---

## Commands

| Command | Description |
|----------|-------------|
| /techsell | Opens sell GUI |
| /techsellreload | Reload configuration |

---

## Configuration

```
plugins/TechSell/config.yml
```

Example

```yaml
sell-prices:
  COBBLESTONE: 0.5
  COAL: 3
  IRON_INGOT: 8
  DIAMOND: 75
```

Only configured materials are accepted inside the sell GUI.

---

## GUI

- 45 sell slots
- Live running total
- Confirm button
- Cancel button
- Automatic item return

Items can never be lost.

---

## Economy

Uses Vault for deposits.

No economy is stored inside the plugin.

---

## Designed for

Progression servers

Survival

RPG

Economy servers

---

## Future Ideas

- Categories
- Price browser
- Statistics
- Sell history
- Daily challenges

---

## License

Personal project.
Feel free to modify for your own server.
