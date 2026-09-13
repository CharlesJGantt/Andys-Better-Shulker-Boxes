# Changelog

## 1.1.7 — Persistent, recoverable labels on the face you choose

- Item labels no longer disappear when their chunk unloads. A label remains attached unless a player removes it, replaces it, or the labeled shulker is destroyed.
- Labels now appear on the shulker-box face the player clicks, including the outward-facing lid and four side faces of floor-, wall-, and ceiling-placed shulkers.
- Removing, replacing, or destroying a label safely returns the original item, dropping it nearby when necessary.
- Mining a shulker keeps its label attached to the shulker item and restores the same face and rotation when placed again.
- Names, lore, enchantments, durability damage, and other stored item data remain intact.
- Restored labels remain hidden until the correct icon is ready, preventing the paper fallback from briefly appearing.
