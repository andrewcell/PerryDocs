---
title: getWarpToMap
---
//[Perry](../../../index.html)/[tools](../index.html)/[MaplePacketCreator](index.html)/[getWarpToMap](get-warp-to-map.html)



# getWarpToMap



[jvm]\
open fun [getWarpToMap](get-warp-to-map.html)(to: [GameMap](../../server.maps/-game-map/index.html), spawnPoint: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), chr: [Character](../../client/-character/index.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)>



Gets a packet telling the client to change maps.



#### Return



The map change packet.



## Parameters


jvm

| | |
|---|---|
| to | The GameMap to warp to. |
| spawnPoint | The spawn portal number to spawn at. |
| chr | The character warping to to |




