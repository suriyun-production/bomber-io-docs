# Changelog (PUN2)

1.20 (2020-11-07)
- Change RPC function usages from `photonView.RPC("function", player, param1, param2, param3)` to `photonView.TargetRPC(function, player, param1, param2, param3)`.
- Change RPC function usages from `photonView.RPC("function", RpcTarget.All, param1, param2, param3)` to `photonView.AllRPC(function, param1, param2, param3)`.
- Change RPC function usages from `photonView.RPC("function", RpcTarget.Others, param1, param2, param3)` to `photonView.OthersRPC(function, player, param1, param2, param3)`.
- Change RPC function usages from `photonView.RPC("function", RpcTarget.MasterClient, param1, param2, param3)` to `photonView.MasterRPC(function, player, param1, param2, param3)`.
- Fix teams are not spawning in designated team spawn areas.
- Fix teams are not spawning the correct amount for each team. If its 6 players, sometimes one team has 4, the other 2.
- Fix bug when the master leaves then rejoins a room, more bots are spawned than the limit.

1.19 (2020-07-02)
- Change to move characters by changes transform's position, rigibody will be used to applies force.
- Add `ExplosionForce` and `ExplosionForceRadius` settings to `Bomb Entity` it will applies to force character when explode.

1.18 (2020-05-08)
- Fix black fade not fade out when start game sometime
- Reduce character stats update packet size.

1.17b (2020-04-16)
- Add `NO_IAP` and `NO_ADS` predefined to disable IAP or ADS

1.17 (2020-04-15)
- Update PUN2

1.16c (2020-02-16)
- Fix invalid adjusting BOTs amount when players enter or exit the game

1.16b (2020-02-12)
- Fix hide area bugs
- Fix cannot start game in offline mode
- Fix invalid bot count

1.16
- Add `HideArea`, developer can attach this component to grasses which will be used to hide characters
- Fix invalid add bot state when switch master client

1.15d
- Remove transforms from Photon View → Observe List
- Avoid null exception when there is no head to select

1.15c
- Fix invalid GameInstance and UIMainMenu execute order

1.15b
- Fix bought items won't be saved

1.15
- Add Playfab integration demo

1.14
- Fix home scene loading while application quit
- Add codes to support Playfab integration project (https://github.com/insthync/dot-io-playfab-client)

1.13
- Upgrade to PUN2, Please read (https://suriyun-production.github.io/bomber-io-docs/#/pages/101-update-to-pun2.md)

1.12
- Reduce packets size
- Add custom equipment
- Add kick bomb powerup
- Add option to bomb entity to able to explode through walls

1.11
- Add spawn position settings for specific team setting to `GameplayManager`

1.10
- Add password for room creation
- Fix invalid map name in waiting room UI
- Switch master client when watch Ads

1.09e
- Fix bots pickup currencies to players bugs
- Move map list and game rules from `Create game UI` to `Game instance`

1.09d
- Fix invalid asmdef locations

1.09c
- Fix clients play as spectator mode when host start game after created room

1.09b
- Fix missing button events
- Fix cannot play in offline mode
- Fix no bot in offline mode

1.09
- Add lobby system
- Add team death match mode

1.08
- Add end match reward

1.07
- Fix codes that duplicating with Fantasy Customization Pack project

1.06
- Add sendRate and sendRateOnSerialize options to SimplePhotonNetworkManager
- Fix empty bot player name

1.05
- Fix mobile controllers issues
- Add price option to In-Game Product

1.04
- Fix mobile controllers
- Add price option to In-Game Product

1.03
- Fix invalid mobile controller for death match mode

1.02
- Fix missing room info in lobby list

1.01
- Add offline mode
- Fix bugs