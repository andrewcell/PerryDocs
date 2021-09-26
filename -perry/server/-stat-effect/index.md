---
title: StatEffect
---
//[Perry](../../../index.html)/[server](../index.html)/[StatEffect](index.html)



# StatEffect



[jvm]\
class [StatEffect](index.html)(**duration**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **hp**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **hpR**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **mp**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **mpR**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **hpCon**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **mpCon**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **prop**: [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html), **mobCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **cooldown**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **morphId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **ghost**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **fatigue**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **repeatEffect**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **sourceId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **skill**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **watk**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **wdef**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **matk**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **mdef**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **acc**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **avoid**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **speed**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **jump**: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), **berserk**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **booster**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **overTime**: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), **x**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **y**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **damage**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **fixDamage**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **attackCount**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **bulletCount**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **bulletConsume**: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), **moneyCon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **itemCon**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **itemConNo**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **moveTo**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |


## Functions


| Name | Summary |
|---|---|
| [applyBuff](apply-buff.html) | [jvm]<br>fun [applyBuff](apply-buff.html)(applyFrom: [Character](../../client/-character/index.html)) |
| [applyBuffEffect](apply-buff-effect.html) | [jvm]<br>fun [applyBuffEffect](apply-buff-effect.html)(applyFrom: [Character](../../client/-character/index.html), applyTo: [Character](../../client/-character/index.html), primary: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [applyMonsterBuff](apply-monster-buff.html) | [jvm]<br>fun [applyMonsterBuff](apply-monster-buff.html)(applyFrom: [Character](../../client/-character/index.html)) |
| [applyPassive](apply-passive.html) | [jvm]<br>fun [applyPassive](apply-passive.html)(applyTo: [Character](../../client/-character/index.html), obj: [MapObject](../../server.maps/-map-object/index.html), attack: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [applyTo](apply-to.html) | [jvm]<br>fun [applyTo](apply-to.html)(chr: [Character](../../client/-character/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [applyTo](apply-to.html)(chr: [Character](../../client/-character/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [applyTo](apply-to.html)(applyFrom: [Character](../../client/-character/index.html), applyTo: [Character](../../client/-character/index.html), primary: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), buff: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)?): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [calcMpChange](calc-mp-change.html) | [jvm]<br>fun [calcMpChange](calc-mp-change.html)(applyFrom: [Character](../../client/-character/index.html), primary: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), buff: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isBeholder](is-beholder.html) | [jvm]<br>fun [isBeholder](is-beholder.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isBerserk](is-berserk.html) | [jvm]<br>fun [isBerserk](is-berserk.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isDragonBlood](is-dragon-blood.html) | [jvm]<br>fun [isDragonBlood](is-dragon-blood.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isMagicDoor](is-magic-door.html) | [jvm]<br>fun [isMagicDoor](is-magic-door.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isMonsterRiding](is-monster-riding.html) | [jvm]<br>fun [isMonsterRiding](is-monster-riding.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isPoison](is-poison.html) | [jvm]<br>fun [isPoison](is-poison.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isRecovery](is-recovery.html) | [jvm]<br>fun [isRecovery](is-recovery.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [makeChanceResult](make-chance-result.html) | [jvm]<br>fun [makeChanceResult](make-chance-result.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [sameSource](same-source.html) | [jvm]<br>fun [sameSource](same-source.html)(effect: [StatEffect](index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [silentApplyBuff](silent-apply-buff.html) | [jvm]<br>fun [silentApplyBuff](silent-apply-buff.html)(chr: [Character](../../client/-character/index.html), startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [acc](acc.html) | [jvm]<br>val [acc](acc.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [attackCount](attack-count.html) | [jvm]<br>val [attackCount](attack-count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [avoid](avoid.html) | [jvm]<br>val [avoid](avoid.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [berserk](berserk.html) | [jvm]<br>val [berserk](berserk.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [booster](booster.html) | [jvm]<br>val [booster](booster.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [bulletConsume](bullet-consume.html) | [jvm]<br>val [bulletConsume](bullet-consume.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [bulletCount](bullet-count.html) | [jvm]<br>val [bulletCount](bullet-count.html): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [cooldown](cooldown.html) | [jvm]<br>val [cooldown](cooldown.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [damage](damage.html) | [jvm]<br>val [damage](damage.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [duration](duration.html) | [jvm]<br>var [duration](duration.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [fatigue](fatigue.html) | [jvm]<br>val [fatigue](fatigue.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [fixDamage](fix-damage.html) | [jvm]<br>val [fixDamage](fix-damage.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [ghost](ghost.html) | [jvm]<br>val [ghost](ghost.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hp](hp.html) | [jvm]<br>val [hp](hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hpCon](hp-con.html) | [jvm]<br>val [hpCon](hp-con.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [hpR](hp-r.html) | [jvm]<br>var [hpR](hp-r.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [itemCon](item-con.html) | [jvm]<br>val [itemCon](item-con.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [itemConNo](item-con-no.html) | [jvm]<br>val [itemConNo](item-con-no.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [jump](jump.html) | [jvm]<br>val [jump](jump.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [lt](lt.html) | [jvm]<br>var [lt](lt.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)? = null |
| [matk](matk.html) | [jvm]<br>val [matk](matk.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [mdef](mdef.html) | [jvm]<br>val [mdef](mdef.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [mobCount](mob-count.html) | [jvm]<br>val [mobCount](mob-count.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [moneyCon](money-con.html) | [jvm]<br>val [moneyCon](money-con.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [monsterStatus](monster-status.html) | [jvm]<br>var [monsterStatus](monster-status.html): [Map](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)<[MonsterStatus](../../client.status/-monster-status/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>? = null |
| [morphId](morph-id.html) | [jvm]<br>val [morphId](morph-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [moveTo](move-to.html) | [jvm]<br>val [moveTo](move-to.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mp](mp.html) | [jvm]<br>val [mp](mp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mpCon](mp-con.html) | [jvm]<br>val [mpCon](mp-con.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [mpR](mp-r.html) | [jvm]<br>val [mpR](mp-r.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [overTime](over-time.html) | [jvm]<br>val [overTime](over-time.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [prop](prop.html) | [jvm]<br>val [prop](prop.html): [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [rb](rb.html) | [jvm]<br>var [rb](rb.html): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html)? = null |
| [repeatEffect](repeat-effect.html) | [jvm]<br>val [repeatEffect](repeat-effect.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [skill](skill.html) | [jvm]<br>val [skill](skill.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [sourceId](source-id.html) | [jvm]<br>val [sourceId](source-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [speed](speed.html) | [jvm]<br>val [speed](speed.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [statups](statups.html) | [jvm]<br>var [statups](statups.html): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Pair](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)<[BuffStat](../../client/-buff-stat/index.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)>>? = null |
| [watk](watk.html) | [jvm]<br>val [watk](watk.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [wdef](wdef.html) | [jvm]<br>val [wdef](wdef.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [x](x.html) | [jvm]<br>val [x](x.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [y](y.html) | [jvm]<br>val [y](y.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

