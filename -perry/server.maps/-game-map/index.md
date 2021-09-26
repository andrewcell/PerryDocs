---
title: GameMap
---
//[Perry](../../../index.html)/[server.maps](../index.html)/[GameMap](index.html)



# GameMap



[jvm]\
class [GameMap](index.html)(**mapId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **world**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **channel**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **returnMapId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **monsterRateFloat**: [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html))



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |
| [DelayedPacketCreation](-delayed-packet-creation/index.html) | [jvm]<br>interface [DelayedPacketCreation](-delayed-packet-creation/index.html) |
| [SpawnCondition](-spawn-condition/index.html) | [jvm]<br>interface [SpawnCondition](-spawn-condition/index.html) |


## Functions


| Name | Summary |
|---|---|
| [activateItemReactors](activate-item-reactors.html) | [jvm]<br>fun [activateItemReactors](activate-item-reactors.html)(drop: [MapItem](../-map-item/index.html), c: [Client](../../client/-client/index.html)) |
| [addArea](add-area.html) | [jvm]<br>fun [addArea](add-area.html)(rec: [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addMapObject](add-map-object.html) | [jvm]<br>fun [addMapObject](add-map-object.html)(mapObject: [MapObject](../-map-object/index.html)) |
| [addMapTimer](add-map-timer.html) | [jvm]<br>fun [addMapTimer](add-map-timer.html)(time: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addMonsterSpawn](add-monster-spawn.html) | [jvm]<br>fun [addMonsterSpawn](add-monster-spawn.html)(monster: [Monster](../../server.life/-monster/index.html), mobTime: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), team: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addPlayer](add-player.html) | [jvm]<br>fun [addPlayer](add-player.html)(chr: [Character](../../client/-character/index.html)) |
| [addPortal](add-portal.html) | [jvm]<br>fun [addPortal](add-portal.html)(p: [Portal](../../server/-portal/index.html)): [Portal](../../server/-portal/index.html)? |
| [allDropItem](all-drop-item.html) | [jvm]<br>fun [allDropItem](all-drop-item.html)(chr: [Character](../../client/-character/index.html)) |
| [allMonster](all-monster.html) | [jvm]<br>fun [allMonster](all-monster.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Monster](../../server.life/-monster/index.html)> |
| [broadcastGMMessage](broadcast-g-m-message.html) | [jvm]<br>fun [broadcastGMMessage](broadcast-g-m-message.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>fun [broadcastGMMessage](broadcast-g-m-message.html)(source: [Character](../../client/-character/index.html), packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>fun [broadcastGMMessage](broadcast-g-m-message.html)(source: [Character](../../client/-character/index.html), packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), repeatToSource: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>fun [broadcastGMMessage](broadcast-g-m-message.html)(source: [Character](../../client/-character/index.html)?, packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), rangeSq: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), rangedFrom: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)?) |
| [broadcastMessage](broadcast-message.html) | [jvm]<br>fun [broadcastMessage](broadcast-message.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>fun [broadcastMessage](broadcast-message.html)(source: [Character](../../client/-character/index.html), packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html))<br>fun [broadcastMessage](broadcast-message.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), rangedFrom: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>fun [broadcastMessage](broadcast-message.html)(source: [Character](../../client/-character/index.html), packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), repeatToSource: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>fun [broadcastMessage](broadcast-message.html)(source: [Character](../../client/-character/index.html)? = null, packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), rangedFrom: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)?)<br>fun [broadcastMessage](broadcast-message.html)(source: [Character](../../client/-character/index.html), packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), repeatToSource: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), ranged: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>fun [broadcastMessage](broadcast-message.html)(source: [Character](../../client/-character/index.html)?, packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html), rangeSq: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), rangedFrom: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)?) |
| [calcDropPos](calc-drop-pos.html) | [jvm]<br>fun [calcDropPos](calc-drop-pos.html)(initial: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), fallback: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [calcPointBelow](calc-point-below.html) | [jvm]<br>fun [calcPointBelow](calc-point-below.html)(initial: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)? |
| [clearDrops](clear-drops.html) | [jvm]<br>fun [clearDrops](clear-drops.html)()<br>fun [clearDrops](clear-drops.html)(chr: [Character](../../client/-character/index.html)) |
| [containsNpc](contains-npc.html) | [jvm]<br>fun [containsNpc](contains-npc.html)(npcId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [countMonster](count-monster.html) | [jvm]<br>fun [countMonster](count-monster.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [damageMonster](damage-monster.html) | [jvm]<br>fun [damageMonster](damage-monster.html)(chr: [Character](../../client/-character/index.html), monster: [Monster](../../server.life/-monster/index.html), damage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [destroyReactor](destroy-reactor.html) | [jvm]<br>fun [destroyReactor](destroy-reactor.html)(oid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [disappearingItemDrop](disappearing-item-drop.html) | [jvm]<br>fun [disappearingItemDrop](disappearing-item-drop.html)(dropper: [MapObject](../-map-object/index.html), owner: [Character](../../client/-character/index.html), item: [Item](../../client.inventory/-item/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [dropFromMonster](drop-from-monster.html) | [jvm]<br>fun [dropFromMonster](drop-from-monster.html)(chr: [Character](../../client/-character/index.html), mob: [Monster](../../server.life/-monster/index.html)) |
| [findClosestPortal](find-closest-portal.html) | [jvm]<br>fun [findClosestPortal](find-closest-portal.html)(from: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Portal](../../server/-portal/index.html)? |
| [findClosestSpawnPoint](find-closest-spawn-point.html) | [jvm]<br>fun [findClosestSpawnPoint](find-closest-spawn-point.html)(from: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Portal](../../server/-portal/index.html)? |
| [fired](fired.html) | [jvm]<br>fun [fired](fired.html)() |
| [getAllPlayer](get-all-player.html) | [jvm]<br>fun [getAllPlayer](get-all-player.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[MapObject](../-map-object/index.html)> |
| [getAllReactor](get-all-reactor.html) | [jvm]<br>fun [getAllReactor](get-all-reactor.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[MapObject](../-map-object/index.html)> |
| [getCharacterById](get-character-by-id.html) | [jvm]<br>fun [getCharacterById](get-character-by-id.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Character](../../client/-character/index.html)? |
| [getCharacterByName](get-character-by-name.html) | [jvm]<br>fun [getCharacterByName](get-character-by-name.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Character](../../client/-character/index.html)? |
| [getCharactersSize](get-characters-size.html) | [jvm]<br>fun [getCharactersSize](get-characters-size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getCharactersThreadSafe](get-characters-thread-safe.html) | [jvm]<br>fun [getCharactersThreadSafe](get-characters-thread-safe.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Character](../../client/-character/index.html)> |
| [getCurrentPartyId](get-current-party-id.html) | [jvm]<br>fun [getCurrentPartyId](get-current-party-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getEventNpc](get-event-npc.html) | [jvm]<br>fun [getEventNpc](get-event-npc.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [getForcedReturnMapAsMap](get-forced-return-map-as-map.html) | [jvm]<br>fun [getForcedReturnMapAsMap](get-forced-return-map-as-map.html)(): [GameMap](index.html) |
| [getGroundBelow](get-ground-below.html) | [jvm]<br>fun [getGroundBelow](get-ground-below.html)(pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [getMapObjectsInBox](get-map-objects-in-box.html) | [jvm]<br>fun [getMapObjectsInBox](get-map-objects-in-box.html)(box: [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html), types: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[MapObjectType](../-map-object-type/index.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[MapObject](../-map-object/index.html)> |
| [getMapObjectsInRange](get-map-objects-in-range.html) | [jvm]<br>fun [getMapObjectsInRange](get-map-objects-in-range.html)(from: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), rangeSq: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), types: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[MapObjectType](../-map-object-type/index.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[MapObject](../-map-object/index.html)> |
| [getMapObjectsInRect](get-map-objects-in-rect.html) | [jvm]<br>fun [getMapObjectsInRect](get-map-objects-in-rect.html)(box: [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html), types: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[MapObjectType](../-map-object-type/index.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[MapObject](../-map-object/index.html)> |
| [getMonsterById](get-monster-by-id.html) | [jvm]<br>fun [getMonsterById](get-monster-by-id.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Monster](../../server.life/-monster/index.html)? |
| [getMonsterByOid](get-monster-by-oid.html) | [jvm]<br>fun [getMonsterByOid](get-monster-by-oid.html)(oid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Monster](../../server.life/-monster/index.html)? |
| [getPlayersInRange](get-players-in-range.html) | [jvm]<br>fun [getPlayersInRange](get-players-in-range.html)(box: [Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html), chr: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Character](../../client/-character/index.html)>): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Character](../../client/-character/index.html)> |
| [getPortal](get-portal.html) | [jvm]<br>fun [getPortal](get-portal.html)(portalId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Portal](../../server/-portal/index.html)?<br>fun [getPortal](get-portal.html)(portalName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Portal](../../server/-portal/index.html)? |
| [getRandomSpawnPoint](get-random-spawn-point.html) | [jvm]<br>fun [getRandomSpawnPoint](get-random-spawn-point.html)(): [Portal](../../server/-portal/index.html) |
| [getReactorById](get-reactor-by-id.html) | [jvm]<br>fun [getReactorById](get-reactor-by-id.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Reactor](../-reactor/index.html)? |
| [getReactorByName](get-reactor-by-name.html) | [jvm]<br>fun [getReactorByName](get-reactor-by-name.html)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Reactor](../-reactor/index.html)? |
| [getReactorByOid](get-reactor-by-oid.html) | [jvm]<br>fun [getReactorByOid](get-reactor-by-oid.html)(oid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Reactor](../-reactor/index.html)? |
| [getReturnMap](get-return-map.html) | [jvm]<br>fun [getReturnMap](get-return-map.html)(): [GameMap](index.html) |
| [getSnowball](get-snowball.html) | [jvm]<br>fun [getSnowball](get-snowball.html)(team: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Snowball](../../server.events.gm/-snowball/index.html)? |
| [hasEventNpc](has-event-npc.html) | [jvm]<br>fun [hasEventNpc](has-event-npc.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isEventMap](is-event-map.html) | [jvm]<br>fun [isEventMap](is-event-map.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isStartingEventMap](is-starting-event-map.html) | [jvm]<br>fun [isStartingEventMap](is-starting-event-map.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [killAllMonsters](kill-all-monsters.html) | [jvm]<br>fun [killAllMonsters](kill-all-monsters.html)() |
| [killMonster](kill-monster.html) | [jvm]<br>fun [killMonster](kill-monster.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>fun [killMonster](kill-monster.html)(monster: [Monster](../../server.life/-monster/index.html), chr: [Character](../../client/-character/index.html)?, withDrops: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), secondTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, animation: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1) |
| [makeMonsterReal](make-monster-real.html) | [jvm]<br>fun [makeMonsterReal](make-monster-real.html)(monster: [Monster](../../server.life/-monster/index.html)) |
| [monsterItemDrop](monster-item-drop.html) | [jvm]<br>fun [monsterItemDrop](monster-item-drop.html)(m: [Monster](../../server.life/-monster/index.html), item: [Item](../../client.inventory/-item/index.html), delay: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [moveMonster](move-monster.html) | [jvm]<br>fun [moveMonster](move-monster.html)(monster: [Monster](../../server.life/-monster/index.html), reportedPos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [movePlayer](move-player.html) | [jvm]<br>fun [movePlayer](move-player.html)(chr: [Character](../../client/-character/index.html), newPosition: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [removeMapObject](remove-map-object.html) | [jvm]<br>fun [removeMapObject](remove-map-object.html)(obj: [MapObject](../-map-object/index.html)) |
| [removePlayer](remove-player.html) | [jvm]<br>fun [removePlayer](remove-player.html)(chr: [Character](../../client/-character/index.html)) |
| [resetReactors](reset-reactors.html) | [jvm]<br>fun [resetReactors](reset-reactors.html)() |
| [respawn](respawn.html) | [jvm]<br>fun [respawn](respawn.html)() |
| [respawnReactor](respawn-reactor.html) | [jvm]<br>fun [respawnReactor](respawn-reactor.html)(reactor: [Reactor](../-reactor/index.html)) |
| [setReactorState](set-reactor-state.html) | [jvm]<br>fun [setReactorState](set-reactor-state.html)() |
| [setSnowball](set-snowball.html) | [jvm]<br>fun [setSnowball](set-snowball.html)(team: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), ball: [Snowball](../../server.events.gm/-snowball/index.html)?) |
| [shuffleReactors](shuffle-reactors.html) | [jvm]<br>fun [shuffleReactors](shuffle-reactors.html)() |
| [spawnAndAddRangedMapObject](spawn-and-add-ranged-map-object.html) | [jvm]<br>fun [spawnAndAddRangedMapObject](spawn-and-add-ranged-map-object.html)(mapObject: [MapObject](../-map-object/index.html), packetBakery: [GameMap.DelayedPacketCreation](-delayed-packet-creation/index.html), condition: [GameMap.SpawnCondition](-spawn-condition/index.html)? = null) |
| [spawnDoor](spawn-door.html) | [jvm]<br>fun [spawnDoor](spawn-door.html)(door: [Door](../-door/index.html)) |
| [spawnDrop](spawn-drop.html) | [jvm]<br>fun [spawnDrop](spawn-drop.html)(drop1: [Item](../../client.inventory/-item/index.html), dropFrom: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), position: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), mob: [Monster](../../server.life/-monster/index.html), chr: [Character](../../client/-character/index.html), dropType: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), questId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [spawnFakeMonster](spawn-fake-monster.html) | [jvm]<br>fun [spawnFakeMonster](spawn-fake-monster.html)(monster: [Monster](../../server.life/-monster/index.html)) |
| [spawnFakeMonsterOnGroundBelow](spawn-fake-monster-on-ground-below.html) | [jvm]<br>fun [spawnFakeMonsterOnGroundBelow](spawn-fake-monster-on-ground-below.html)(mob: [Monster](../../server.life/-monster/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [spawnItemDrop](spawn-item-drop.html) | [jvm]<br>fun [spawnItemDrop](spawn-item-drop.html)(dropper: [MapObject](../-map-object/index.html), owner: [Character](../../client/-character/index.html)?, item: [Item](../../client.inventory/-item/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), ffaDrop: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), playerDrop: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [spawnMesoDrop](spawn-meso-drop.html) | [jvm]<br>fun [spawnMesoDrop](spawn-meso-drop.html)(meso: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), position: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), dropper: [MapObject](../-map-object/index.html), owner: [Character](../../client/-character/index.html)?, playerDrop: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), dropType: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html))<br>fun [spawnMesoDrop](spawn-meso-drop.html)(meso: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), dropFrom: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), position: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), mob: [Monster](../../server.life/-monster/index.html), owner: [Character](../../client/-character/index.html), playerDrop: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), dropType: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [spawnMist](spawn-mist.html) | [jvm]<br>fun [spawnMist](spawn-mist.html)(mist: [Mist](../-mist/index.html), duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), poison: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), fake: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [spawnMonster](spawn-monster.html) | [jvm]<br>fun [spawnMonster](spawn-monster.html)(monster: [Monster](../../server.life/-monster/index.html), newSpawn: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [spawnMonsterOnGroundBelow](spawn-monster-on-ground-below.html) | [jvm]<br>fun [spawnMonsterOnGroundBelow](spawn-monster-on-ground-below.html)(mob: [Monster](../../server.life/-monster/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [spawnMonsterWithEffect](spawn-monster-with-effect.html) | [jvm]<br>fun [spawnMonsterWithEffect](spawn-monster-with-effect.html)(monster: [Monster](../../server.life/-monster/index.html), effect: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)) |
| [spawnQuestItemDrop](spawn-quest-item-drop.html) | [jvm]<br>fun [spawnQuestItemDrop](spawn-quest-item-drop.html)(dropper: [MapObject](../-map-object/index.html), owner: [Character](../../client/-character/index.html), item: [Item](../../client.inventory/-item/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html), ffaDrop: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), playerDrop: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), questId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [spawnReactor](spawn-reactor.html) | [jvm]<br>fun [spawnReactor](spawn-reactor.html)(reactor: [Reactor](../-reactor/index.html)) |
| [spawnRevives](spawn-revives.html) | [jvm]<br>fun [spawnRevives](spawn-revives.html)(monster: [Monster](../../server.life/-monster/index.html)) |
| [spawnSummon](spawn-summon.html) | [jvm]<br>fun [spawnSummon](spawn-summon.html)(summon: [Summon](../-summon/index.html)) |
| [startEvent](start-event.html) | [jvm]<br>fun [startEvent](start-event.html)(chr: [Character](../../client/-character/index.html)) |
| [startMapEffect](start-map-effect.html) | [jvm]<br>fun [startMapEffect](start-map-effect.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), time: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 30000) |
| [toggleDrops](toggle-drops.html) | [jvm]<br>fun [toggleDrops](toggle-drops.html)() |
| [toggleHiddenNpc](toggle-hidden-npc.html) | [jvm]<br>fun [toggleHiddenNpc](toggle-hidden-npc.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [updateMapObjectVisibility](update-map-object-visibility.html) | [jvm]<br>fun [updateMapObjectVisibility](update-map-object-visibility.html)(chr: [Character](../../client/-character/index.html), mo: [MapObject](../-map-object/index.html)) |
| [updateMonsterController](update-monster-controller.html) | [jvm]<br>fun [updateMonsterController](update-monster-controller.html)(monster: [Monster](../../server.life/-monster/index.html)) |
| [warpEveryone](warp-everyone.html) | [jvm]<br>fun [warpEveryone](warp-everyone.html)(to: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [warpOutByTeam](warp-out-by-team.html) | [jvm]<br>fun [warpOutByTeam](warp-out-by-team.html)(team: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [allowHPQSummon](allow-h-p-q-summon.html) | [jvm]<br>var [allowHPQSummon](allow-h-p-q-summon.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [areas](areas.html) | [jvm]<br>val [areas](areas.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Rectangle](https://docs.oracle.com/javase/8/docs/api/java/awt/Rectangle.html)> |
| [boat](boat.html) | [jvm]<br>var [boat](boat.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [channel](channel.html) | [jvm]<br>val [channel](channel.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [characters](characters.html) | [jvm]<br>val [characters](characters.html): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[Character](../../client/-character/index.html)> |
| [charactersLock](characters-lock.html) | [jvm]<br>val [charactersLock](characters-lock.html): [ReentrantReadWriteLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.html) |
| [chrLock](chr-lock.html) | [jvm]<br>val [chrLock](chr-lock.html): [ReentrantReadWriteLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.html) |
| [chrRLock](chr-r-lock.html) | [jvm]<br>val [chrRLock](chr-r-lock.html): [ReentrantReadWriteLock.ReadLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.ReadLock.html) |
| [chrWLock](chr-w-lock.html) | [jvm]<br>val [chrWLock](chr-w-lock.html): [ReentrantReadWriteLock.WriteLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.WriteLock.html) |
| [clock](clock.html) | [jvm]<br>var [clock](clock.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [coconut](coconut.html) | [jvm]<br>var [coconut](coconut.html): [Coconut](../../server.events.gm/-coconut/index.html)? = null |
| [docked](docked.html) | [jvm]<br>var [docked](docked.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [dropsOn](drops-on.html) | [jvm]<br>var [dropsOn](drops-on.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [eventStarted](event-started.html) | [jvm]<br>var [eventStarted](event-started.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [everLast](ever-last.html) | [jvm]<br>var [everLast](ever-last.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [fieldLimit](field-limit.html) | [jvm]<br>var [fieldLimit](field-limit.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [fieldType](field-type.html) | [jvm]<br>var [fieldType](field-type.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [fitness](fitness.html) | [jvm]<br>var [fitness](fitness.html): [Fitness](../../server.events.gm/-fitness/index.html)? = null |
| [footholds](footholds.html) | [jvm]<br>var [footholds](footholds.html): [FootholdTree](../-foothold-tree/index.html)? = null |
| [forcedReturnMap](forced-return-map.html) | [jvm]<br>var [forcedReturnMap](forced-return-map.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 999999999 |
| [hpDec](hp-dec.html) | [jvm]<br>var [hpDec](hp-dec.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [hpDecProtect](hp-dec-protect.html) | [jvm]<br>var [hpDecProtect](hp-dec-protect.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [isOxQuiz](is-ox-quiz.html) | [jvm]<br>var [isOxQuiz](is-ox-quiz.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [mapEffect](map-effect.html) | [jvm]<br>var [mapEffect](map-effect.html): [MapEffect](../-map-effect/index.html)? = null |
| [mapId](map-id.html) | [jvm]<br>val [mapId](map-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mapMonitor](map-monitor.html) | [jvm]<br>var [mapMonitor](map-monitor.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [mapName](map-name.html) | [jvm]<br>var [mapName](map-name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [mapObjects](map-objects.html) | [jvm]<br>val [mapObjects](map-objects.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [MapObject](../-map-object/index.html)> |
| [mobCapacity](mob-capacity.html) | [jvm]<br>var [mobCapacity](mob-capacity.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mobInterval](mob-interval.html) | [jvm]<br>var [mobInterval](mob-interval.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 8000 |
| [monsterRate](monster-rate.html) | [jvm]<br>var [monsterRate](monster-rate.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [monsterRateFloat](monster-rate-float.html) | [jvm]<br>var [monsterRateFloat](monster-rate-float.html): [Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [monsterSpawn](monster-spawn.html) | [jvm]<br>val [monsterSpawn](monster-spawn.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[SpawnPoint](../../server.life/-spawn-point/index.html)> |
| [objectLock](object-lock.html) | [jvm]<br>val [objectLock](object-lock.html): [ReentrantReadWriteLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.html) |
| [objectRLock](object-r-lock.html) | [jvm]<br>val [objectRLock](object-r-lock.html): [ReentrantReadWriteLock.ReadLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.ReadLock.html) |
| [objectWLock](object-w-lock.html) | [jvm]<br>val [objectWLock](object-w-lock.html): [ReentrantReadWriteLock.WriteLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantReadWriteLock.WriteLock.html) |
| [onFirstUserEnter](on-first-user-enter.html) | [jvm]<br>var [onFirstUserEnter](on-first-user-enter.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [onUserEnter](on-user-enter.html) | [jvm]<br>var [onUserEnter](on-user-enter.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ox](ox.html) | [jvm]<br>var [ox](ox.html): [OxQuiz](../../server.events.gm/-ox-quiz/index.html)? = null |
| [portals](portals.html) | [jvm]<br>val [portals](portals.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Portal](../../server/-portal/index.html)> |
| [returnMapId](return-map-id.html) | [jvm]<br>val [returnMapId](return-map-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [riceCakeNum](rice-cake-num.html) | [jvm]<br>var [riceCakeNum](rice-cake-num.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [runningOid](running-oid.html) | [jvm]<br>var [runningOid](running-oid.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 100 |
| [snowball0](snowball0.html) | [jvm]<br>var [snowball0](snowball0.html): [Snowball](../../server.events.gm/-snowball/index.html)? = null |
| [snowball1](snowball1.html) | [jvm]<br>var [snowball1](snowball1.html): [Snowball](../../server.events.gm/-snowball/index.html)? = null |
| [snowballAttack](snowball-attack.html) | [jvm]<br>var [snowballAttack](snowball-attack.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null |
| [spawnedMonsterOnMap](spawned-monster-on-map.html) | [jvm]<br>val [spawnedMonsterOnMap](spawned-monster-on-map.html): [AtomicInteger](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicInteger.html) |
| [streetName](street-name.html) | [jvm]<br>var [streetName](street-name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [team](team.html) | [jvm]<br>var [team](team.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [timeLimit](time-limit.html) | [jvm]<br>var [timeLimit](time-limit.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? = null |
| [timeMob](time-mob.html) | [jvm]<br>var [timeMob](time-mob.html): [Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?, [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)?>? = null |
| [town](town.html) | [jvm]<br>var [town](town.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [world](world.html) | [jvm]<br>val [world](world.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

