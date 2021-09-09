# Changelog (LiteNetLibManager)

## 1.31 (2021-08-07)
- Reduce packet size.

## 1.30c (2021-02-21)
- Update to latest LiteNetLibManager version.
- Fix networked prefabs not registered before server start.
- Add `-gameBotCount` environment configuration, use it to set bot count when start dedicated server.
- Add `-gameMatchTime` environment configuration, use it to set match time when start dedicated server.
- Add `-gameMatchKill` environment configuration, use it to set kill count to win when start dedicated server.
- Add `-gameMatchScore` environment configuration, use it to score count to win when start dedicated server.
- Kick client whom connecting while match ended.
- Restart server after match ended.
- Fix wrong player's ranking when match end.
- Fix null-reference for on-screen mobile controller when start non-mobile games.

## 1.30 (2020-07-02)
- Change networking system to `LiteNetLibManager` (You should read [how to update](../pages/104-update-to-litenetlib.md)).
- Change to move characters by changes transform's position, rigibody will be used to applies force.
- Add `ExplosionForce` and `ExplosionForceRadius` settings to `Bomb Entity` it will applies to force character when explode.

# Changelog (UNET)

## 1.24b (2020-02-12)
- Fix hide area bugs

## 1.24
- Add `HideArea`, developer can attach this component to grasses which will be used to hide characters

## 1.23d
- Avoid null exception when there is no head to select

## 1.23c
- Fix invalid execute order

## 1.23b
- Fix bought items won't be saved

## 1.23
- Add codes to support Playfab integration project (https://github.com/insthync/dot-io-playfab-client)

## 1.22
- Reduce packets size
- Add custom equipment
- Add kick bomb powerup
- Add option to bomb entity to able to explode through walls

## 1.21b
- Fix bots pickup currencies to players bugs
- Move map list and game rules from `Create game UI` to `Game instance`

## 1.21
- Add end match reward

## 1.20
- Fix codes that duplicating with Fantasy Customization Pack project

## 1.19
- Fix mobile controllers issues
- Add price option to In-Game Product

## 1.18
- Fix mobile controllers
- Add price option to In-Game Product

## 1.17
- Fix invalid mobile controller for death match mode

## 1.16
- Add kill notify messages

## 1.15
- Fix invalid score sort in Death match mode

## 1.14
- Add chat and emoticon

## 1.13
- Add reward currency when kill other characters

## 1.12
- Add deathmatch game mode

## 1.11
- Make UIGameplay instantiating by Game rules
- Add command line settings for decication
- Can set to show mobile joystick or not via GameInstance (Home scene)
- Score/Kill/Dead reset immediately when dies

## 1.38
- Fix random animation bugs
- Add network game framework to prepare future game modes
- Add more secure monetization save

## 1.1
- Make character gravity supports so characters can walks on slopes
- Add network game framework to prepare future game modes
- Add more secure monetization save

## 1.08
- Add black fade
- Add audio manager

## 1.07
- Add invincible status, will be activated when spawn

## 1.06
- Improve graphics
- Fix bugs

## 1.05
- Fix bugs
- Improve Network Discovery to show scene and player count
- Improve Ads monetize, now it's able to set random-able rewards
- Improve IAP products, now it's able to set more than 1 currencies