---
title: RangedAttackHandler
---
//[Perry](../../../index.html)/[net.server.channel.handlers](../index.html)/[RangedAttackHandler](index.html)



# RangedAttackHandler



[jvm]\
class [RangedAttackHandler](index.html) : [AbstractDealDamageHandler](../-abstract-deal-damage-handler/index.html)



## Functions


| Name | Summary |
|---|---|
| [applyAttack](../-touch-monster-damage-handler/index.html#993597111%2FFunctions%2F863300109) | [jvm]<br>open fun [applyAttack](../-touch-monster-damage-handler/index.html#993597111%2FFunctions%2F863300109)(attack: [AbstractDealDamageHandler.AttackInfo](../-abstract-deal-damage-handler/-attack-info/index.html), player: [Character](../../client/-character/index.html), attackCount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [handlePacket](handle-packet.html) | [jvm]<br>open override fun [handlePacket](handle-packet.html)(slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html), c: [Client](../../client/-client/index.html)) |
| [parseDamage](../-touch-monster-damage-handler/index.html#-816360318%2FFunctions%2F863300109) | [jvm]<br>open fun [parseDamage](../-touch-monster-damage-handler/index.html#-816360318%2FFunctions%2F863300109)(lea: [LittleEndianAccessor](../../tools.data.input/-little-endian-accessor/index.html), chr: [Character](../../client/-character/index.html), ranged: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [AbstractDealDamageHandler.AttackInfo](../-abstract-deal-damage-handler/-attack-info/index.html) |
| [validateState](../../net/-abstract-packet-handler/validate-state.html) | [jvm]<br>open override fun [validateState](../../net/-abstract-packet-handler/validate-state.html)(c: [Client](../../client/-client/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

