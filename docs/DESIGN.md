# Horde design

Implement against this file, not folklore.

## Identity

- Product: **Horde**
- Repo: `computerpets-horde`
- Idea: Pet Defense Corps
- Genre: Bullet-heaven
- Engine: Godot
- Surface: `Godot editor`

## Loop

Dojo trains the numbers. Horde spends them. Weapon evolutions are trait-legal. 10-minute nightly run. Death = tired overlay, not a lost pet.

## Play beats

- Pick pet + starting trait weapon.
- Survive waves. Choose 3-of-1 upgrades.
- Chest loot = run-only until extract.
- Extract at 10:00 or die trying.

## Neighbors

- computerpets-siege
- computerpets-dojo
- computerpets-raid
- computerpets-motion

## Failure doctrine

Upgrade that changes species → illegal, filtered. Low-end CPU → spawn cap. Overlay continues if Horde is closed.

## Hard rules

1. Minigames cannot mint or burn NFTs by themselves (Minter is the write path).
2. Stats come from lived overlay care + Dojo caps, not cash shop.
3. Species kits stay inside Lore. Illegal hybrids never spawn.
4. Fail soft: the desktop overlay process is not this process.
