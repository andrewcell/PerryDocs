---
title: MoveSummonHandler
---
//[Perry](../../../index.html)/[net.server.channel.handlers](../index.html)/[MoveSummonHandler](index.html)



# MoveSummonHandler



[jvm]\
class [MoveSummonHandler](index.html) : [AbstractMovementPacketHandler](../-abstract-movement-packet-handler/index.html)



## Functions


| Name | Summary |
|---|---|
| [handlePacket](handle-packet.html) | [jvm]<br>open override fun [handlePacket](handle-packet.html)(slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html), c: [Client](../../client/-client/index.html)) |
| [parseMovement](index.html#-907942053%2FFunctions%2F863300109) | [jvm]<br>open fun [parseMovement](index.html#-907942053%2FFunctions%2F863300109)(lea: [LittleEndianAccessor](../../tools.data.input/-little-endian-accessor/index.html)): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[LifeMovementFragment](../../server.movement/-life-movement-fragment/index.html)&gt; |
| [updatePosition](index.html#1958887339%2FFunctions%2F863300109) | [jvm]<br>open fun [updatePosition](index.html#1958887339%2FFunctions%2F863300109)(movement: [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[LifeMovementFragment](../../server.movement/-life-movement-fragment/index.html)&gt;, target: [AnimatedMapObject](../../server.maps/-animated-map-object/index.html), yoffset: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [validateState](../../net/-abstract-packet-handler/validate-state.html) | [jvm]<br>open override fun [validateState](../../net/-abstract-packet-handler/validate-state.html)(c: [Client](../../client/-client/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

