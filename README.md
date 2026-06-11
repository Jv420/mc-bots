# DynathiAI Minecraft Bots

Welkom bij de DynathiAI bot collectie.

## Eerste bot: HouseBot

HouseBot is een Mineflayer bot die automatisch huizen kan bouwen.

## Installatie

1. Installeer Node.js 22+
2. Clone de repository
3. Voer uit:

```bash
npm install
```

## .env

Maak een .env bestand:

```env
BOT_HOST=dynathiv2.duckdns.org
BOT_PORT=25565
BOT_USERNAME=HouseBot
BOT_VERSION=false
```

## Starten

```bash
npm run housebot
```

## Commands

In Minecraft:

```text
!buildhouse
```

Start een huisbouw-opdracht.

## Geplande bots

- HouseBot
- BobBuilder
- MinerBot
- FarmBot
- GuardBot
- ShopBot
- VillageBot
- CastleBot

## LuckPerms voorbeeld

```bash
/lp creategroup housebot
/lp group housebot meta setprefix 85 "&8[&6🏗 HOUSEBOT&8] &6"
/lp user HouseBot parent set housebot
```
