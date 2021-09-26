---
title: Monster
---
//[Perry](../../../index.html)/[server.life](../index.html)/[Monster](index.html)



# Monster



[jvm]\
class [Monster](index.html) : [AbstractLoadedLife](../../server.maps/-abstract-loaded-life/index.html)



## Constructors


| | |
|---|---|
| [Monster](-monster.html) | [jvm]<br>fun [Monster](-monster.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), stats: [MonsterStats](../-monster-stats/index.html)) |
| [Monster](-monster.html) | [jvm]<br>fun [Monster](-monster.html)(monster: [Monster](index.html)) |


## Types


| Name | Summary |
|---|---|
| [AttackerEntry](-attacker-entry/index.html) | [jvm]<br>interface [AttackerEntry](-attacker-entry/index.html) |
| [AttackingCharacter](-attacking-character/index.html) | [jvm]<br>data class [AttackingCharacter](-attacking-character/index.html)(**attacker**: [Character](../../client/-character/index.html), **lastAttackTime**: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |
| [DamageTask](-damage-task/index.html) | [jvm]<br>inner class [DamageTask](-damage-task/index.html)(**dealDamage**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **chr**: [Character](../../client/-character/index.html), **status**: [MonsterStatusEffect](../../client.status/-monster-status-effect/index.html), **cancelTask**: [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html), **type**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) : [Runnable](https://docs.oracle.com/javase/8/docs/api/java/lang/Runnable.html) |
| [PartyAttackerEntry](-party-attacker-entry/index.html) | [jvm]<br>inner class [PartyAttackerEntry](-party-attacker-entry/index.html)(**partyId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **channelServer**: [Channel](../../net.server.channel/-channel/index.html)) : [Monster.AttackerEntry](-attacker-entry/index.html) |
| [SingleAttackerEntry](-single-attacker-entry/index.html) | [jvm]<br>inner class [SingleAttackerEntry](-single-attacker-entry/index.html)(**from**: [Character](../../client/-character/index.html), **chServ**: [Channel](../../net.server.channel/-channel/index.html)) : [Monster.AttackerEntry](-attacker-entry/index.html) |


## Functions


| Name | Summary |
|---|---|
| [addListener](add-listener.html) | [jvm]<br>fun [addListener](add-listener.html)(l: [MonsterListener](../-monster-listener/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addStolen](add-stolen.html) | [jvm]<br>fun [addStolen](add-stolen.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [applyMonsterBuff](apply-monster-buff.html) | [jvm]<br>fun [applyMonsterBuff](apply-monster-buff.html)(stats: [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[MonsterStatus](../../client.status/-monster-status/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?>, x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), duration: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), skill: [MobSkill](../-mob-skill/index.html), reflection: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)?>) |
| [applyStatus](apply-status.html) | [jvm]<br>fun [applyStatus](apply-status.html)(from: [Character](../../client/-character/index.html), status: [MonsterStatusEffect](../../client.status/-monster-status-effect/index.html), poison: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), duration: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), venom: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [canUseSkill](can-use-skill.html) | [jvm]<br>fun [canUseSkill](can-use-skill.html)(toUse: [MobSkill](../-mob-skill/index.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [clearSkill](clear-skill.html) | [jvm]<br>fun [clearSkill](clear-skill.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [damage](damage.html) | [jvm]<br>fun [damage](damage.html)(from: [Character](../../client/-character/index.html), damage: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), updateAttackTime: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [getEffectiveness](get-effectiveness.html) | [jvm]<br>fun [getEffectiveness](get-effectiveness.html)(e: [Element](../-element/index.html)): [ElementalEffectiveness](../-elemental-effectiveness/index.html) |
| [getMaxHp](get-max-hp.html) | [jvm]<br>fun [getMaxHp](get-max-hp.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMaxMp](get-max-mp.html) | [jvm]<br>fun [getMaxMp](get-max-mp.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [giveExpToCharacter](give-exp-to-character.html) | [jvm]<br>fun [giveExpToCharacter](give-exp-to-character.html)(attacker: [Character](../../client/-character/index.html), exp: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), highestDamage: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), numExpSharers: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [hasBossHpBar](has-boss-hp-bar.html) | [jvm]<br>fun [hasBossHpBar](has-boss-hp-bar.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasSkill](has-skill.html) | [jvm]<br>fun [hasSkill](has-skill.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [heal](heal.html) | [jvm]<br>fun [heal](heal.html)(hpValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mpValue: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [isAlive](is-alive.html) | [jvm]<br>fun [isAlive](is-alive.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isAttackedBy](is-attacked-by.html) | [jvm]<br>fun [isAttackedBy](is-attacked-by.html)(chr: [Character](../../client/-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isBoss](is-boss.html) | [jvm]<br>fun [isBoss](is-boss.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isBuffed](is-buffed.html) | [jvm]<br>fun [isBuffed](is-buffed.html)(status: [MonsterStatus](../../client.status/-monster-status/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isControllerKnowsAboutAggro](is-controller-knows-about-aggro.html) | [jvm]<br>fun [isControllerKnowsAboutAggro](is-controller-knows-about-aggro.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isFacingLeft](../../server.maps/-abstract-animated-map-object/is-facing-left.html) | [jvm]<br>open override fun [isFacingLeft](../../server.maps/-abstract-animated-map-object/is-facing-left.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [killBy](kill-by.html) | [jvm]<br>fun [killBy](kill-by.html)(killer: [Character](../../client/-character/index.html)): [Character](../../client/-character/index.html)? |
| [makeBossHpBarPacket](make-boss-hp-bar-packet.html) | [jvm]<br>fun [makeBossHpBarPacket](make-boss-hp-bar-packet.html)(): [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html) |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../../client/-client/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../../client/-client/index.html)) |
| [setTempEffectiveness](set-temp-effectiveness.html) | [jvm]<br>fun [setTempEffectiveness](set-temp-effectiveness.html)(e: [Element](../-element/index.html), ee: [ElementalEffectiveness](../-elemental-effectiveness/index.html), milli: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [switchController](switch-controller.html) | [jvm]<br>fun [switchController](switch-controller.html)(newController: [Character](../../client/-character/index.html), immediateAggro: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [usedSkill](used-skill.html) | [jvm]<br>fun [usedSkill](used-skill.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), coolTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [attackers](attackers.html) | [jvm]<br>val [attackers](attackers.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Monster.AttackerEntry](-attacker-entry/index.html)> |
| [controller](controller.html) | [jvm]<br>var [controller](controller.html): [WeakReference](https://docs.oracle.com/javase/8/docs/api/java/lang/ref/WeakReference.html)<[Character](../../client/-character/index.html)>? |
| [controllerHasAggro](controller-has-aggro.html) | [jvm]<br>var [controllerHasAggro](controller-has-aggro.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [controllerKnowsAboutAggro](controller-knows-about-aggro.html) | [jvm]<br>var [controllerKnowsAboutAggro](controller-knows-about-aggro.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [cType](index.html#-102130339%2FProperties%2F863300109) | [jvm]<br>var [cType](index.html#-102130339%2FProperties%2F863300109): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [cy](index.html#819311594%2FProperties%2F863300109) | [jvm]<br>var [cy](index.html#819311594%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [dropsDisabled](drops-disabled.html) | [jvm]<br>var [dropsDisabled](drops-disabled.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [eventInstance](event-instance.html) | [jvm]<br>var [eventInstance](event-instance.html): [EventInstanceManager](../../scripting.event/-event-instance-manager/index.html)? = null |
| [f](index.html#-1599607340%2FProperties%2F863300109) | [jvm]<br>var [f](index.html#-1599607340%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [fake](fake.html) | [jvm]<br>var [fake](fake.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [fh](index.html#-1118150370%2FProperties%2F863300109) | [jvm]<br>var [fh](index.html#-1118150370%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [hidden](index.html#1623358390%2FProperties%2F863300109) | [jvm]<br>var [hidden](index.html#1623358390%2FProperties%2F863300109): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [highestDamageChar](highest-damage-char.html) | [jvm]<br>var [highestDamageChar](highest-damage-char.html): [Character](../../client/-character/index.html)? = null |
| [hp](hp.html) | [jvm]<br>var [hp](hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [id](index.html#1642612453%2FProperties%2F863300109) | [jvm]<br>val [id](index.html#1642612453%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [listeners](listeners.html) | [jvm]<br>val [listeners](listeners.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[MonsterListener](../-monster-listener/index.html)> |
| [map](map.html) | [jvm]<br>var [map](map.html): [GameMap](../../server.maps/-game-map/index.html)? = null |
| [monsterLock](monster-lock.html) | [jvm]<br>val [monsterLock](monster-lock.html): [ReentrantLock](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/locks/ReentrantLock.html) |
| [mp](mp.html) | [jvm]<br>var [mp](mp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mTime](index.html#1201973600%2FProperties%2F863300109) | [jvm]<br>var [mTime](index.html#1201973600%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [objectId](index.html#-362101274%2FProperties%2F863300109) | [jvm]<br>open override var [objectId](index.html#-362101274%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../../server.maps/-map-object-type/index.html) |
| [position](index.html#191893591%2FProperties%2F863300109) | [jvm]<br>open override var [position](index.html#191893591%2FProperties%2F863300109): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [rx0](index.html#-1370911536%2FProperties%2F863300109) | [jvm]<br>var [rx0](index.html#-1370911536%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [rx1](index.html#-1339891729%2FProperties%2F863300109) | [jvm]<br>var [rx1](index.html#-1339891729%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [skillsUsed](skills-used.html) | [jvm]<br>val [skillsUsed](skills-used.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>, [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [stance](index.html#-1222441744%2FProperties%2F863300109) | [jvm]<br>open override var [stance](index.html#-1222441744%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [startFh](index.html#680670582%2FProperties%2F863300109) | [jvm]<br>var [startFh](index.html#680670582%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? = null |
| [stats](stats.html) | [jvm]<br>lateinit var [stats](stats.html): [MonsterStats](../-monster-stats/index.html) |
| [stolenItems](stolen-items.html) | [jvm]<br>val [stolenItems](stolen-items.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [team](team.html) | [jvm]<br>var [team](team.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [usedSkills](used-skills.html) | [jvm]<br>val [usedSkills](used-skills.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>> |
| [venumMultiplier](venum-multiplier.html) | [jvm]<br>var [venumMultiplier](venum-multiplier.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |

