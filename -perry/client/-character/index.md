---
title: Character
---
//[Perry](../../../index.html)/[client](../index.html)/[Character](index.html)



# Character



[jvm]\
class [Character](index.html)(**world**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **accountId**: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), **map**: [GameMap](../../server.maps/-game-map/index.html), **client**: [Client](../-client/index.html)) : [AbstractAnimatedMapObject](../../server.maps/-abstract-animated-map-object/index.html)



## Types


| Name | Summary |
|---|---|
| [Companion](-companion/index.html) | [jvm]<br>object [Companion](-companion/index.html) |
| [FameStats](-fame-stats/index.html) | [jvm]<br>enum [FameStats](-fame-stats/index.html) : [Enum](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-enum/index.html)<[Character.FameStats](-fame-stats/index.html)> |


## Functions


| Name | Summary |
|---|---|
| [addCooldown](add-cooldown.html) | [jvm]<br>fun [addCooldown](add-cooldown.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), length: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), timer: [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>?) |
| [addCrushRing](add-crush-ring.html) | [jvm]<br>fun [addCrushRing](add-crush-ring.html)(r: [Ring](../-ring/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addDoor](add-door.html) | [jvm]<br>fun [addDoor](add-door.html)(door: [Door](../../server.maps/-door/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addExcluded](add-excluded.html) | [jvm]<br>fun [addExcluded](add-excluded.html)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [addFame](add-fame.html) | [jvm]<br>fun [addFame](add-fame.html)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addHp](add-hp.html) | [jvm]<br>fun [addHp](add-hp.html)(delta: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addMerchantMesos](add-merchant-mesos.html) | [jvm]<br>fun [addMerchantMesos](add-merchant-mesos.html)(add: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addMesosTraded](add-mesos-traded.html) | [jvm]<br>fun [addMesosTraded](add-mesos-traded.html)(gain: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addMp](add-mp.html) | [jvm]<br>fun [addMp](add-mp.html)(delta: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addMpHp](add-mp-hp.html) | [jvm]<br>fun [addMpHp](add-mp-hp.html)(hpDiff: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), mpDiff: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addStat](add-stat.html) | [jvm]<br>fun [addStat](add-stat.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), up: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [addSummon](add-summon.html) | [jvm]<br>fun [addSummon](add-summon.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), summon: [Summon](../../server.maps/-summon/index.html)): [Summon](../../server.maps/-summon/index.html)? |
| [addTrockMap](add-trock-map.html) | [jvm]<br>fun [addTrockMap](add-trock-map.html)() |
| [addVipTrockMap](add-vip-trock-map.html) | [jvm]<br>fun [addVipTrockMap](add-vip-trock-map.html)() |
| [addVisibleMapObject](add-visible-map-object.html) | [jvm]<br>fun [addVisibleMapObject](add-visible-map-object.html)(mo: [MapObject](../../server.maps/-map-object/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [announce](announce.html) | [jvm]<br>fun [announce](announce.html)(packet: [ByteArray](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)) |
| [autoban](autoban.html) | [jvm]<br>fun [autoban](autoban.html)(reason: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), gReason: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [ban](ban.html) | [jvm]<br>fun [ban](ban.html)(reason: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [block](block.html) | [jvm]<br>fun [block](block.html)(reason: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), days: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), desc: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [blockPortal](block-portal.html) | [jvm]<br>fun [blockPortal](block-portal.html)(scriptName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [calculateMaxBaseDamage](calculate-max-base-damage.html) | [jvm]<br>fun [calculateMaxBaseDamage](calculate-max-base-damage.html)(watk: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [calculateMaxBaseDamageMagic](calculate-max-base-damage-magic.html) | [jvm]<br>fun [calculateMaxBaseDamageMagic](calculate-max-base-damage-magic.html)(matk: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [cancelAllBuffs](cancel-all-buffs.html) | [jvm]<br>fun [cancelAllBuffs](cancel-all-buffs.html)(disconnect: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [cancelAllDebuffs](cancel-all-debuffs.html) | [jvm]<br>fun [cancelAllDebuffs](cancel-all-debuffs.html)() |
| [cancelBuffEffects](cancel-buff-effects.html) | [jvm]<br>fun [cancelBuffEffects](cancel-buff-effects.html)() |
| [cancelBuffStats](cancel-buff-stats.html) | [jvm]<br>fun [cancelBuffStats](cancel-buff-stats.html)(stat: [BuffStat](../-buff-stat/index.html)) |
| [cancelEffect](cancel-effect.html) | [jvm]<br>fun [cancelEffect](cancel-effect.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>fun [cancelEffect](cancel-effect.html)(effect: [StatEffect](../../server/-stat-effect/index.html)?, overwrite: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [cancelEffectFromBuffStat](cancel-effect-from-buff-stat.html) | [jvm]<br>fun [cancelEffectFromBuffStat](cancel-effect-from-buff-stat.html)(stat: [BuffStat](../-buff-stat/index.html)) |
| [cancelExpirationTask](cancel-expiration-task.html) | [jvm]<br>fun [cancelExpirationTask](cancel-expiration-task.html)() |
| [cancelMagicDoor](cancel-magic-door.html) | [jvm]<br>fun [cancelMagicDoor](cancel-magic-door.html)() |
| [cancelMapTimeLimitTask](cancel-map-time-limit-task.html) | [jvm]<br>fun [cancelMapTimeLimitTask](cancel-map-time-limit-task.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? |
| [cancelPlayerBuffs](cancel-player-buffs.html) | [jvm]<br>fun [cancelPlayerBuffs](cancel-player-buffs.html)(buffStats: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[BuffStat](../-buff-stat/index.html)>) |
| [canGiveFame](can-give-fame.html) | [jvm]<br>fun [canGiveFame](can-give-fame.html)(from: [Character](index.html)): [Character.FameStats](-fame-stats/index.html) |
| [changeJob](change-job.html) | [jvm]<br>fun [changeJob](change-job.html)(job: [Job](../-job/index.html)) |
| [changeKeyBinding](change-key-binding.html) | [jvm]<br>fun [changeKeyBinding](change-key-binding.html)(key: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), binding: [KeyBinding](../-key-binding/index.html)) |
| [changeMap](change-map.html) | [jvm]<br>fun [changeMap](change-map.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), portal: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0)<br>fun [changeMap](change-map.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), portal: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html))<br>fun [changeMap](change-map.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), portal: [Portal](../../server/-portal/index.html))<br>fun [changeMap](change-map.html)(to: [GameMap](../../server.maps/-game-map/index.html), pos: [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html))<br>fun [changeMap](change-map.html)(to: [GameMap](../../server.maps/-game-map/index.html), pto: [Portal](../../server/-portal/index.html)? = to.getPortal(0)) |
| [changeMapBanish](change-map-banish.html) | [jvm]<br>fun [changeMapBanish](change-map-banish.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), portal: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [changeSkillLevel](change-skill-level.html) | [jvm]<br>fun [changeSkillLevel](change-skill-level.html)(skill: [Skill](../-skill/index.html), newLevel: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), newMasterLevel: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), expiration: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [checkBerserk](check-berserk.html) | [jvm]<br>fun [checkBerserk](check-berserk.html)() |
| [checkMessenger](check-messenger.html) | [jvm]<br>fun [checkMessenger](check-messenger.html)() |
| [checkMobPosition](check-mob-position.html) | [jvm]<br>fun [checkMobPosition](check-mob-position.html)() |
| [checkMonsterAggro](check-monster-aggro.html) | [jvm]<br>fun [checkMonsterAggro](check-monster-aggro.html)(monster: [Monster](../../server.life/-monster/index.html)) |
| [clearDoors](clear-doors.html) | [jvm]<br>fun [clearDoors](clear-doors.html)() |
| [clearSavedLocation](clear-saved-location.html) | [jvm]<br>fun [clearSavedLocation](clear-saved-location.html)(type: [SavedLocationType](../../server.maps/-saved-location-type/index.html)) |
| [clockDelay](clock-delay.html) | [jvm]<br>fun [clockDelay](clock-delay.html)(time: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [containsAreaInfo](contains-area-info.html) | [jvm]<br>fun [containsAreaInfo](contains-area-info.html)(area: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), info: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [controlMonster](control-monster.html) | [jvm]<br>fun [controlMonster](control-monster.html)(monster: [Monster](../../server.life/-monster/index.html), aggro: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [countItem](count-item.html) | [jvm]<br>fun [countItem](count-item.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [decreaseBattleshipHp](decrease-battleship-hp.html) | [jvm]<br>fun [decreaseBattleshipHp](decrease-battleship-hp.html)(d: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [decreaseReports](decrease-reports.html) | [jvm]<br>fun [decreaseReports](decrease-reports.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [deleteFromTrockMaps](delete-from-trock-maps.html) | [jvm]<br>fun [deleteFromTrockMaps](delete-from-trock-maps.html)(map: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [deleteFromVipTrockMaps](delete-from-vip-trock-maps.html) | [jvm]<br>fun [deleteFromVipTrockMaps](delete-from-vip-trock-maps.html)(map: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [deleteGuild](delete-guild.html) | [jvm]<br>fun [deleteGuild](delete-guild.html)(guildId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [deleteWhereCharacterId](delete-where-character-id.html) | [jvm]<br>fun [deleteWhereCharacterId](delete-where-character-id.html)(con: [Connection](https://docs.oracle.com/javase/8/docs/api/java/sql/Connection.html), sql: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [disableDoor](disable-door.html) | [jvm]<br>fun [disableDoor](disable-door.html)() |
| [disconnected](disconnected.html) | [jvm]<br>fun [disconnected](disconnected.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)? |
| [dispel](dispel.html) | [jvm]<br>fun [dispel](dispel.html)() |
| [dispelDebuff](dispel-debuff.html) | [jvm]<br>fun [dispelDebuff](dispel-debuff.html)(debuff: [Disease](../-disease/index.html)) |
| [dispelDebuffs](dispel-debuffs.html) | [jvm]<br>fun [dispelDebuffs](dispel-debuffs.html)() |
| [dispelSkill](dispel-skill.html) | [jvm]<br>fun [dispelSkill](dispel-skill.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [dispelSkills](dispel-skills.html) | [jvm]<br>fun [dispelSkills](dispel-skills.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [doHurtHp](do-hurt-hp.html) | [jvm]<br>fun [doHurtHp](do-hurt-hp.html)() |
| [dropMessage](drop-message.html) | [jvm]<br>fun [dropMessage](drop-message.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0, message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [empty](empty.html) | [jvm]<br>fun [empty](empty.html)(remove: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [enteredScript](entered-script.html) | [jvm]<br>fun [enteredScript](entered-script.html)(script: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [equipChanged](equip-changed.html) | [jvm]<br>fun [equipChanged](equip-changed.html)() |
| [equipPendantOfSpirit](equip-pendant-of-spirit.html) | [jvm]<br>fun [equipPendantOfSpirit](equip-pendant-of-spirit.html)() |
| [expirationTask](expiration-task.html) | [jvm]<br>fun [expirationTask](expiration-task.html)() |
| [forceUpdateItem](force-update-item.html) | [jvm]<br>fun [forceUpdateItem](force-update-item.html)(item: [Item](../../client.inventory/-item/index.html)) |
| [gainExp](gain-exp.html) | [jvm]<br>fun [gainExp](gain-exp.html)(gain: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), show: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), inChat: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), white: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true) |
| [gainFame](gain-fame.html) | [jvm]<br>fun [gainFame](gain-fame.html)(delta: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [gainGachaExp](gain-gacha-exp.html) | [jvm]<br>fun [gainGachaExp](gain-gacha-exp.html)(gain: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [gainMeso](gain-meso.html) | [jvm]<br>fun [gainMeso](gain-meso.html)(gain: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), show: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), enableActions: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false, inChat: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false) |
| [gainMPoint](gain-m-point.html) | [jvm]<br>fun [gainMPoint](gain-m-point.html)(quantity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [gainSlots](gain-slots.html) | [jvm]<br>fun [gainSlots](gain-slots.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), slots: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), update: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getAllBuffs](get-all-buffs.html) | [jvm]<br>fun [getAllBuffs](get-all-buffs.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[PlayerBuffValueHolder](../../net.server/-player-buff-value-holder/index.html)> |
| [getAllCoolDowns](get-all-cool-downs.html) | [jvm]<br>fun [getAllCoolDowns](get-all-cool-downs.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[PlayerCoolDownValueHolder](../../net.server/-player-cool-down-value-holder/index.html)> |
| [getAndRemoveCp](get-and-remove-cp.html) | [jvm]<br>fun [getAndRemoveCp](get-and-remove-cp.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getAreaInfo](get-area-info.html) | [jvm]<br>fun [getAreaInfo](get-area-info.html)(area: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [getBuffedStartTime](get-buffed-start-time.html) | [jvm]<br>fun [getBuffedStartTime](get-buffed-start-time.html)(effect: [BuffStat](../-buff-stat/index.html)): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)? |
| [getBuffedValue](get-buffed-value.html) | [jvm]<br>fun [getBuffedValue](get-buffed-value.html)(effect: [BuffStat](../-buff-stat/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |
| [getBuffSource](get-buff-source.html) | [jvm]<br>fun [getBuffSource](get-buff-source.html)(stat: [BuffStat](../-buff-stat/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getBuffStats](get-buff-stats.html) | [jvm]<br>fun [getBuffStats](get-buff-stats.html)(effect: [StatEffect](../../server/-stat-effect/index.html), startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[BuffStat](../-buff-stat/index.html)> |
| [getCompletedQuests](get-completed-quests.html) | [jvm]<br>fun [getCompletedQuests](get-completed-quests.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[QuestStatus](../-quest-status/index.html)> |
| [getCrushRingsSorted](get-crush-rings-sorted.html) | [jvm]<br>fun [getCrushRingsSorted](get-crush-rings-sorted.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Ring](../-ring/index.html)> |
| [getCustomStatus](get-custom-status.html) | [jvm]<br>fun [getCustomStatus](get-custom-status.html)(questId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getFh](get-fh.html) | [jvm]<br>fun [getFh](get-fh.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getGuild](get-guild.html) | [jvm]<br>fun [getGuild](get-guild.html)(): [Guild](../../net.server.guild/-guild/index.html)? |
| [getInventory](get-inventory.html) | [jvm]<br>fun [getInventory](get-inventory.html)(type: [InventoryType](../../client.inventory/-inventory-type/index.html)): [Inventory](../../client.inventory/-inventory/index.html)? |
| [getItemQuantity](get-item-quantity.html) | [jvm]<br>fun [getItemQuantity](get-item-quantity.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), checkEquipped: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getJobType](get-job-type.html) | [jvm]<br>fun [getJobType](get-job-type.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getKeyValue](get-key-value.html) | [jvm]<br>fun [getKeyValue](get-key-value.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [getMasterLevel](get-master-level.html) | [jvm]<br>fun [getMasterLevel](get-master-level.html)(skill: [Skill](../-skill/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMedalText](get-medal-text.html) | [jvm]<br>fun [getMedalText](get-medal-text.html)(): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getMiniGamePoints](get-mini-game-points.html) | [jvm]<br>fun [getMiniGamePoints](get-mini-game-points.html)(type: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), omok: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getPartyId](get-party-id.html) | [jvm]<br>fun [getPartyId](get-party-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getQuest](get-quest.html) | [jvm]<br>fun [getQuest](get-quest.html)(quest: [Quest](../../server.quest/-quest/index.html)): [QuestStatus](../-quest-status/index.html) |
| [getQuestStatus](get-quest-status.html) | [jvm]<br>fun [getQuestStatus](get-quest-status.html)(quest: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getSkillExpiration](get-skill-expiration.html) | [jvm]<br>fun [getSkillExpiration](get-skill-expiration.html)(skill: [Skill](../-skill/index.html)): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>fun [getSkillExpiration](get-skill-expiration.html)(skill: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getSkillLevel](get-skill-level.html) | [jvm]<br>fun [getSkillLevel](get-skill-level.html)(skill: [Skill](../-skill/index.html)): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)<br>fun [getSkillLevel](get-skill-level.html)(skill: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html) |
| [getSlots](get-slots.html) | [jvm]<br>fun [getSlots](get-slots.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)? |
| [getStartedQuests](get-started-quests.html) | [jvm]<br>fun [getStartedQuests](get-started-quests.html)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[QuestStatus](../-quest-status/index.html)> |
| [getStartedQuestsSize](get-started-quests-size.html) | [jvm]<br>fun [getStartedQuestsSize](get-started-quests-size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getStatForBuff](get-stat-for-buff.html) | [jvm]<br>fun [getStatForBuff](get-stat-for-buff.html)(effect: [BuffStat](../-buff-stat/index.html)): [StatEffect](../../server/-stat-effect/index.html)? |
| [getTrockSize](get-trock-size.html) | [jvm]<br>fun [getTrockSize](get-trock-size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getVipTrockSize](get-vip-trock-size.html) | [jvm]<br>fun [getVipTrockSize](get-vip-trock-size.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [giveCoolDowns](give-cool-downs.html) | [jvm]<br>fun [giveCoolDowns](give-cool-downs.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), length: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)) |
| [giveDebuff](give-debuff.html) | [jvm]<br>fun [giveDebuff](give-debuff.html)(disease: [Disease](../-disease/index.html), skill: [MobSkill](../../server.life/-mob-skill/index.html)) |
| [handleEnergyChargeGain](handle-energy-charge-gain.html) | [jvm]<br>fun [handleEnergyChargeGain](handle-energy-charge-gain.html)() |
| [handleOrbconsume](handle-orbconsume.html) | [jvm]<br>fun [handleOrbconsume](handle-orbconsume.html)() |
| [hasDisease](has-disease.html) | [jvm]<br>fun [hasDisease](has-disease.html)(dis: [Disease](../-disease/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasEntered](has-entered.html) | [jvm]<br>fun [hasEntered](has-entered.html)(script: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasGivenFame](has-given-fame.html) | [jvm]<br>fun [hasGivenFame](has-given-fame.html)(to: [Character](index.html)) |
| [haveItem](have-item.html) | [jvm]<br>fun [haveItem](have-item.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [haveItem](have-item.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), qw: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hide](hide.html) | [jvm]<br>fun [hide](hide.html)(hide: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), login: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false) |
| [insertNewChar](insert-new-char.html) | [jvm]<br>fun [insertNewChar](insert-new-char.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isActiveBuffedValue](is-active-buffed-value.html) | [jvm]<br>fun [isActiveBuffedValue](is-active-buffed-value.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isAlive](is-alive.html) | [jvm]<br>fun [isAlive](is-alive.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isBeginnerJob](is-beginner-job.html) | [jvm]<br>fun [isBeginnerJob](is-beginner-job.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isBuffFrom](is-buff-from.html) | [jvm]<br>fun [isBuffFrom](is-buff-from.html)(stat: [BuffStat](../-buff-stat/index.html), skill: [Skill](../-skill/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isFacingLeft](../../server.maps/-abstract-animated-map-object/is-facing-left.html) | [jvm]<br>open override fun [isFacingLeft](../../server.maps/-abstract-animated-map-object/is-facing-left.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isGM](is-g-m.html) | [jvm]<br>fun [isGM](is-g-m.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isMapObjectVisible](is-map-object-visible.html) | [jvm]<br>fun [isMapObjectVisible](is-map-object-visible.html)(mo: [MapObject](../../server.maps/-map-object/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [leaveMap](leave-map.html) | [jvm]<br>fun [leaveMap](leave-map.html)() |
| [levelUp](level-up.html) | [jvm]<br>fun [levelUp](level-up.html)(takeExp: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [logOff](log-off.html) | [jvm]<br>fun [logOff](log-off.html)() |
| [message](message.html) | [jvm]<br>fun [message](message.html)(m: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [mobKilled](mob-killed.html) | [jvm]<br>fun [mobKilled](mob-killed.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [mount](mount.html) | [jvm]<br>fun [mount](mount.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [needQuestItem](need-quest-item.html) | [jvm]<br>fun [needQuestItem](need-quest-item.html)(questId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [newClient](new-client.html) | [jvm]<br>fun [newClient](new-client.html)(c: [Client](../-client/index.html)) |
| [playerNpc](player-npc.html) | [jvm]<br>fun [playerNpc](player-npc.html)(v: [Character](index.html), scriptId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [portalDelay](portal-delay.html) | [jvm]<br>fun [portalDelay](portal-delay.html)(delay: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [questTimeLimit](quest-time-limit.html) | [jvm]<br>fun [questTimeLimit](quest-time-limit.html)(quest: [Quest](../../server.quest/-quest/index.html), time: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [recalcLocalStats](recalc-local-stats.html) | [jvm]<br>fun [recalcLocalStats](recalc-local-stats.html)() |
| [receivePartyMemberHp](receive-party-member-hp.html) | [jvm]<br>fun [receivePartyMemberHp](receive-party-member-hp.html)() |
| [registerEffect](register-effect.html) | [jvm]<br>fun [registerEffect](register-effect.html)(effect: [StatEffect](../../server/-stat-effect/index.html), startTime: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html), schedule: [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>) |
| [removeAllCoolDownsExcept](remove-all-cool-downs-except.html) | [jvm]<br>fun [removeAllCoolDownsExcept](remove-all-cool-downs-except.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [removeCoolDown](remove-cool-down.html) | [jvm]<br>fun [removeCoolDown](remove-cool-down.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Character.Companion.CoolDownValueHolder](-companion/-cool-down-value-holder/index.html)? |
| [removeVisibleMapObject](remove-visible-map-object.html) | [jvm]<br>fun [removeVisibleMapObject](remove-visible-map-object.html)(mo: [MapObject](../../server.maps/-map-object/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [resetBattleshipHp](reset-battleship-hp.html) | [jvm]<br>fun [resetBattleshipHp](reset-battleship-hp.html)() |
| [resetStats](reset-stats.html) | [jvm]<br>fun [resetStats](reset-stats.html)() |
| [saveCoolDowns](save-cool-downs.html) | [jvm]<br>fun [saveCoolDowns](save-cool-downs.html)() |
| [saveGuildStatus](save-guild-status.html) | [jvm]<br>fun [saveGuildStatus](save-guild-status.html)() |
| [saveKeyValues](save-key-values.html) | [jvm]<br>fun [saveKeyValues](save-key-values.html)() |
| [saveToDatabase](save-to-database.html) | [jvm]<br>fun [saveToDatabase](save-to-database.html)() |
| [sendDestroyData](send-destroy-data.html) | [jvm]<br>open override fun [sendDestroyData](send-destroy-data.html)(client: [Client](../-client/index.html)) |
| [sendKeymap](send-keymap.html) | [jvm]<br>fun [sendKeymap](send-keymap.html)() |
| [sendNote](send-note.html) | [jvm]<br>fun [sendNote](send-note.html)(to: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), fame: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [sendSpawnData](send-spawn-data.html) | [jvm]<br>open override fun [sendSpawnData](send-spawn-data.html)(client: [Client](../-client/index.html)) |
| [setBuffedValue](set-buffed-value.html) | [jvm]<br>fun [setBuffedValue](set-buffed-value.html)(effect: [BuffStat](../-buff-stat/index.html), value: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setCustomStatus](set-custom-status.html) | [jvm]<br>fun [setCustomStatus](set-custom-status.html)(questId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setHpMp](set-hp-mp.html) | [jvm]<br>fun [setHpMp](set-hp-mp.html)(x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setHpSilent](set-hp-silent.html) | [jvm]<br>fun [setHpSilent](set-hp-silent.html)(delta: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [setInventory](set-inventory.html) | [jvm]<br>fun [setInventory](set-inventory.html)(type: [InventoryType](../../client.inventory/-inventory-type/index.html), inv: [Inventory](../../client.inventory/-inventory/index.html)) |
| [setKeyValue](set-key-value.html) | [jvm]<br>fun [setKeyValue](set-key-value.html)(key: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), values: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [setMiniGamePoints](set-mini-game-points.html) | [jvm]<br>fun [setMiniGamePoints](set-mini-game-points.html)(visitor: [Character](index.html), winnerSlot: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), omok: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [setRates](set-rates.html) | [jvm]<br>fun [setRates](set-rates.html)() |
| [showNote](show-note.html) | [jvm]<br>fun [showNote](show-note.html)() |
| [silentGiveBuffs](silent-give-buffs.html) | [jvm]<br>fun [silentGiveBuffs](silent-give-buffs.html)(buffs: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[PlayerBuffValueHolder](../../net.server/-player-buff-value-holder/index.html)>) |
| [silentPartyUpdate](silent-party-update.html) | [jvm]<br>fun [silentPartyUpdate](silent-party-update.html)(): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [skillIsCooling](skill-is-cooling.html) | [jvm]<br>fun [skillIsCooling](skill-is-cooling.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [startFullnessSchedule](start-fullness-schedule.html) | [jvm]<br>fun [startFullnessSchedule](start-fullness-schedule.html)(decrease: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), pet: [Pet](../../client.inventory/-pet/index.html)) |
| [startMapEffect](start-map-effect.html) | [jvm]<br>fun [startMapEffect](start-map-effect.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), duration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 30000) |
| [startMobHackParser](start-mob-hack-parser.html) | [jvm]<br>fun [startMobHackParser](start-mob-hack-parser.html)() |
| [stopControllingMonster](stop-controlling-monster.html) | [jvm]<br>fun [stopControllingMonster](stop-controlling-monster.html)(monster: [Monster](../../server.life/-monster/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [timeLimit](time-limit.html) | [jvm]<br>fun [timeLimit](time-limit.html)(second: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [toggleHidden](toggle-hidden.html) | [jvm]<br>fun [toggleHidden](toggle-hidden.html)() |
| [unblockPortal](unblock-portal.html) | [jvm]<br>fun [unblockPortal](unblock-portal.html)(scriptName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [unequipPendantOfSpirit](unequip-pendant-of-spirit.html) | [jvm]<br>fun [unequipPendantOfSpirit](unequip-pendant-of-spirit.html)() |
| [unequipPet](unequip-pet.html) | [jvm]<br>fun [unequipPet](unequip-pet.html)(hunger: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false) |
| [updateAreaInfo](update-area-info.html) | [jvm]<br>fun [updateAreaInfo](update-area-info.html)(area: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), info: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [updatePartyMemberHp](update-party-member-hp.html) | [jvm]<br>fun [updatePartyMemberHp](update-party-member-hp.html)() |
| [updateQuest](update-quest.html) | [jvm]<br>fun [updateQuest](update-quest.html)(quest: [QuestStatus](../-quest-status/index.html)) |
| [updateSingleStat](update-single-stat.html) | [jvm]<br>fun [updateSingleStat](update-single-stat.html)(stat: [CharacterStat](../-character-stat/index.html), newVal: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>fun [updateSingleStat](update-single-stat.html)(stat: [CharacterStat](../-character-stat/index.html), newVal: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), itemReaction: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [yellowMessage](yellow-message.html) | [jvm]<br>fun [yellowMessage](yellow-message.html)(m: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [accountId](account-id.html) | [jvm]<br>val [accountId](account-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [allDiseases](all-diseases.html) | [jvm]<br>val [allDiseases](all-diseases.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Disease](../-disease/index.html), [AllDiseaseValueHolder](../-all-disease-value-holder/index.html)> |
| [allianceId](alliance-id.html) | [jvm]<br>var [allianceId](alliance-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [allianceRank](alliance-rank.html) | [jvm]<br>var [allianceRank](alliance-rank.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [areaInfos](area-infos.html) | [jvm]<br>val [areaInfos](area-infos.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [attackTick](attack-tick.html) | [jvm]<br>var [attackTick](attack-tick.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [autoban](autoban.html) | [jvm]<br>var [autoban](autoban.html): [AutobanManager](../../client.autoban/-autoban-manager/index.html) |
| [banned](banned.html) | [jvm]<br>var [banned](banned.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [battleshipHp](battleship-hp.html) | [jvm]<br>var [battleshipHp](battleship-hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [beholderBuffSchedule](beholder-buff-schedule.html) | [jvm]<br>var [beholderBuffSchedule](beholder-buff-schedule.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [beholderHealingSchedule](beholder-healing-schedule.html) | [jvm]<br>var [beholderHealingSchedule](beholder-healing-schedule.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [berserkSchedule](berserk-schedule.html) | [jvm]<br>var [berserkSchedule](berserk-schedule.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [blockedPortals](blocked-portals.html) | [jvm]<br>val [blockedPortals](blocked-portals.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [bookCover](book-cover.html) | [jvm]<br>var [bookCover](book-cover.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [buddyList](buddy-list.html) | [jvm]<br>var [buddyList](buddy-list.html): [BuddyList](../-buddy-list/index.html) |
| [canDoor](can-door.html) | [jvm]<br>var [canDoor](can-door.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true |
| [cashShop](cash-shop.html) | [jvm]<br>var [cashShop](cash-shop.html): [Cashshop](../../server/-cashshop/index.html)? = null |
| [chair](chair.html) | [jvm]<br>var [chair](chair.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [chalkBoard](chalk-board.html) | [jvm]<br>var [chalkBoard](chalk-board.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [channelCheck](channel-check.html) | [jvm]<br>var [channelCheck](channel-check.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [ci](ci.html) | [jvm]<br>var [ci](ci.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [client](client.html) | [jvm]<br>var [client](client.html): [Client](../-client/index.html) |
| [clone](clone.html) | [jvm]<br>var [clone](clone.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [controlledMonsters](controlled-monsters.html) | [jvm]<br>val [controlledMonsters](controlled-monsters.html): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[Monster](../../server.life/-monster/index.html)> |
| [conversation](conversation.html) | [jvm]<br>var [conversation](conversation.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [coolDowns](cool-downs.html) | [jvm]<br>val [coolDowns](cool-downs.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Character.Companion.CoolDownValueHolder](-companion/-cool-down-value-holder/index.html)> |
| [cp](cp.html) | [jvm]<br>var [cp](cp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [crushRings](crush-rings.html) | [jvm]<br>val [crushRings](crush-rings.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Ring](../-ring/index.html)> |
| [currentPage](current-page.html) | [jvm]<br>var [currentPage](current-page.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [currentTab](current-tab.html) | [jvm]<br>var [currentTab](current-tab.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1 |
| [currentType](current-type.html) | [jvm]<br>var [currentType](current-type.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [curse](curse.html) | [jvm]<br>var [curse](curse.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [customValues](custom-values.html) | [jvm]<br>val [customValues](custom-values.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [dex](dex.html) | [jvm]<br>var [dex](dex.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 4 |
| [diseases](diseases.html) | [jvm]<br>val [diseases](diseases.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Disease](../-disease/index.html), [DiseaseValueHolder](../-disease-value-holder/index.html)> |
| [doors](doors.html) | [jvm]<br>val [doors](doors.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Door](../../server.maps/-door/index.html)> |
| [dragonBloodSchedule](dragon-blood-schedule.html) | [jvm]<br>var [dragonBloodSchedule](dragon-blood-schedule.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [dropRate](drop-rate.html) | [jvm]<br>var [dropRate](drop-rate.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1 |
| [effects](effects.html) | [jvm]<br>val [effects](effects.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[BuffStat](../-buff-stat/index.html), [Character.Companion.BuffStatValueHolder](-companion/-buff-stat-value-holder/index.html)> |
| [energybar](energybar.html) | [jvm]<br>var [energybar](energybar.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [entered](entered.html) | [jvm]<br>val [entered](entered.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)> |
| [eventInstance](event-instance.html) | [jvm]<br>var [eventInstance](event-instance.html): [EventInstanceManager](../../scripting.event/-event-instance-manager/index.html)? = null |
| [events](events.html) | [jvm]<br>var [events](events.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), [Events](../../server.events/-events/index.html)> |
| [eventTeam](event-team.html) | [jvm]<br>var [eventTeam](event-team.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [excluded](excluded.html) | [jvm]<br>val [excluded](excluded.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [exp](exp.html) | [jvm]<br>var [exp](exp.html): [AtomicInteger](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicInteger.html) |
| [expireTask](expire-task.html) | [jvm]<br>var [expireTask](expire-task.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [expRate](exp-rate.html) | [jvm]<br>var [expRate](exp-rate.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 2 |
| [face](face.html) | [jvm]<br>var [face](face.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [fame](fame.html) | [jvm]<br>var [fame](fame.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [fitness](fitness.html) | [jvm]<br>var [fitness](fitness.html): [Fitness](../../server.events.gm/-fitness/index.html)? = null |
| [friendshipRings](friendship-rings.html) | [jvm]<br>val [friendshipRings](friendship-rings.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Ring](../-ring/index.html)> |
| [fullnessSchedule](fullness-schedule.html) | [jvm]<br>var [fullnessSchedule](fullness-schedule.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [gachaExp](gacha-exp.html) | [jvm]<br>var [gachaExp](gacha-exp.html): [AtomicInteger](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicInteger.html) |
| [gender](gender.html) | [jvm]<br>var [gender](gender.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [gmLevel](gm-level.html) | [jvm]<br>var [gmLevel](gm-level.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [guildId](guild-id.html) | [jvm]<br>var [guildId](guild-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [guildRank](guild-rank.html) | [jvm]<br>var [guildRank](guild-rank.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [hair](hair.html) | [jvm]<br>var [hair](hair.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [hasMerchant](has-merchant.html) | [jvm]<br>var [hasMerchant](has-merchant.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [headTitle](head-title.html) | [jvm]<br>var [headTitle](head-title.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [hidden](hidden.html) | [jvm]<br>var [hidden](hidden.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [hiredMerchant](hired-merchant.html) | [jvm]<br>var [hiredMerchant](hired-merchant.html): [HiredMerchant](../../server.maps/-hired-merchant/index.html)? = null |
| [hp](hp.html) | [jvm]<br>var [hp](hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 50 |
| [hpDecreaseTask](hp-decrease-task.html) | [jvm]<br>var [hpDecreaseTask](hp-decrease-task.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [hpMpApUsed](hp-mp-ap-used.html) | [jvm]<br>var [hpMpApUsed](hp-mp-ap-used.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [id](id.html) | [jvm]<br>var [id](id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [initialSpawnPoint](initial-spawn-point.html) | [jvm]<br>var [initialSpawnPoint](initial-spawn-point.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [int](int.html) | [jvm]<br>var [int](int.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 4 |
| [inventories](inventories.html) | [jvm]<br>val [inventories](inventories.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Inventory](../../client.inventory/-inventory/index.html)?> |
| [itemEffect](item-effect.html) | [jvm]<br>var [itemEffect](item-effect.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [job](job.html) | [jvm]<br>var [job](job.html): [Job](../-job/index.html) |
| [jobRank](job-rank.html) | [jvm]<br>var [jobRank](job-rank.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1 |
| [jobRankMove](job-rank-move.html) | [jvm]<br>var [jobRankMove](job-rank-move.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [keymap](keymap.html) | [jvm]<br>val [keymap](keymap.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [KeyBinding](../-key-binding/index.html)> |
| [keyValueChanged](key-value-changed.html) | [jvm]<br>var [keyValueChanged](key-value-changed.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [lastFameTime](last-fame-time.html) | [jvm]<br>var [lastFameTime](last-fame-time.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [lastMonthFameIds](last-month-fame-ids.html) | [jvm]<br>var [lastMonthFameIds](last-month-fame-ids.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [lastUsedCashItem](last-used-cash-item.html) | [jvm]<br>var [lastUsedCashItem](last-used-cash-item.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0L |
| [level](level.html) | [jvm]<br>var [level](level.html): [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) = 1 |
| [linkedLevel](linked-level.html) | [jvm]<br>var [linkedLevel](linked-level.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [linkedName](linked-name.html) | [jvm]<br>var [linkedName](linked-name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [localDex](local-dex.html) | [jvm]<br>var [localDex](local-dex.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [localInt](local-int.html) | [jvm]<br>var [localInt](local-int.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [localLuk](local-luk.html) | [jvm]<br>var [localLuk](local-luk.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [localMaxHp](local-max-hp.html) | [jvm]<br>var [localMaxHp](local-max-hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [localMaxMp](local-max-mp.html) | [jvm]<br>var [localMaxMp](local-max-mp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [localStr](local-str.html) | [jvm]<br>var [localStr](local-str.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [loggedIn](logged-in.html) | [jvm]<br>var [loggedIn](logged-in.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [luk](luk.html) | [jvm]<br>var [luk](luk.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 4 |
| [magic](magic.html) | [jvm]<br>var [magic](magic.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [map](map.html) | [jvm]<br>var [map](map.html): [GameMap](../../server.maps/-game-map/index.html) |
| [mapId](map-id.html) | [jvm]<br>var [mapId](map-id.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [mapTimeLimitTask](map-time-limit-task.html) | [jvm]<br>var [mapTimeLimitTask](map-time-limit-task.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [markedMonster](marked-monster.html) | [jvm]<br>var [markedMonster](marked-monster.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [matchCardLosses](match-card-losses.html) | [jvm]<br>var [matchCardLosses](match-card-losses.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [matchCardTies](match-card-ties.html) | [jvm]<br>var [matchCardTies](match-card-ties.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [matchCardWins](match-card-wins.html) | [jvm]<br>var [matchCardWins](match-card-wins.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [maxHp](max-hp.html) | [jvm]<br>var [maxHp](max-hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 50 |
| [maxMp](max-mp.html) | [jvm]<br>var [maxMp](max-mp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 5 |
| [merchantMeso](merchant-meso.html) | [jvm]<br>var [merchantMeso](merchant-meso.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [meso](meso.html) | [jvm]<br>var [meso](meso.html): [AtomicInteger](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/atomic/AtomicInteger.html) |
| [mesoRate](meso-rate.html) | [jvm]<br>var [mesoRate](meso-rate.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1 |
| [mesosTraded](mesos-traded.html) | [jvm]<br>var [mesosTraded](mesos-traded.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [messenger](messenger.html) | [jvm]<br>var [messenger](messenger.html): [Messenger](../../net.server.world/-messenger/index.html)? = null |
| [messengerPosition](messenger-position.html) | [jvm]<br>var [messengerPosition](messenger-position.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 4 |
| [mgc](mgc.html) | [jvm]<br>var [mgc](mgc.html): [GuildCharacter](../../net.server.guild/-guild-character/index.html)? = null |
| [miniGame](mini-game.html) | [jvm]<br>var [miniGame](mini-game.html): [MiniGame](../../server/-mini-game/index.html)? = null |
| [mobHackParser](mob-hack-parser.html) | [jvm]<br>var [mobHackParser](mob-hack-parser.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [monsterBook](monster-book.html) | [jvm]<br>var [monsterBook](monster-book.html): [MonsterBook](../-monster-book/index.html) |
| [mount](mount.html) | [jvm]<br>var [mount](mount.html): [Mount](../-mount/index.html)? = null |
| [mp](mp.html) | [jvm]<br>var [mp](mp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 5 |
| [mpc](mpc.html) | [jvm]<br>var [mpc](mpc.html): [PartyCharacter](../../net.server.world/-party-character/index.html)? = null |
| [mPoints](m-points.html) | [jvm]<br>var [mPoints](m-points.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [name](name.html) | [jvm]<br>var [name](name.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [nf](nf.html) | [jvm]<br>val [nf](nf.html): [DecimalFormat](https://docs.oracle.com/javase/8/docs/api/java/text/DecimalFormat.html) |
| [notMovePlayer](not-move-player.html) | [jvm]<br>var [notMovePlayer](not-move-player.html): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false |
| [objectId](index.html#-1300557191%2FProperties%2F863300109) | [jvm]<br>open override var [objectId](index.html#-1300557191%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [objectType](object-type.html) | [jvm]<br>open override val [objectType](object-type.html): [MapObjectType](../../server.maps/-map-object-type/index.html) |
| [obtainedCp](obtained-cp.html) | [jvm]<br>var [obtainedCp](obtained-cp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [ola](ola.html) | [jvm]<br>var [ola](ola.html): [Ola](../../server.events.gm/-ola/index.html)? = null |
| [omokLooses](omok-looses.html) | [jvm]<br>var [omokLooses](omok-looses.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [omokTies](omok-ties.html) | [jvm]<br>var [omokTies](omok-ties.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [omokWins](omok-wins.html) | [jvm]<br>var [omokWins](omok-wins.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [party](party.html) | [jvm]<br>var [party](party.html): [Party](../../net.server.world/-party/index.html)? = null |
| [partyQuest](party-quest.html) | [jvm]<br>var [partyQuest](party-quest.html): [PartyQuest](../../server.partyquest/-party-quest/index.html)? = null |
| [pendantExp](pendant-exp.html) | [jvm]<br>var [pendantExp](pendant-exp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [pendantOfSpirit](pendant-of-spirit.html) | [jvm]<br>var [pendantOfSpirit](pendant-of-spirit.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [pet](pet.html) | [jvm]<br>var [pet](pet.html): [Pet](../../client.inventory/-pet/index.html)? = null |
| [petAutoHp](pet-auto-hp.html) | [jvm]<br>var [petAutoHp](pet-auto-hp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [petAutoMp](pet-auto-mp.html) | [jvm]<br>var [petAutoMp](pet-auto-mp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [playerShop](player-shop.html) | [jvm]<br>var [playerShop](player-shop.html): [PlayerShop](../../server/-player-shop/index.html)? = null |
| [portalDelay](portal-delay.html) | [jvm]<br>var [portalDelay](portal-delay.html): [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) = 0L |
| [position](index.html#-746562326%2FProperties%2F863300109) | [jvm]<br>open override var [position](index.html#-746562326%2FProperties%2F863300109): [Point](https://docs.oracle.com/javase/8/docs/api/java/awt/Point.html) |
| [possibleReports](possible-reports.html) | [jvm]<br>var [possibleReports](possible-reports.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 10 |
| [quests](quests.html) | [jvm]<br>val [quests](quests.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Quest](../../server.quest/-quest/index.html), [QuestStatus](../-quest-status/index.html)> |
| [rank](rank.html) | [jvm]<br>var [rank](rank.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 1 |
| [rankMove](rank-move.html) | [jvm]<br>var [rankMove](rank-move.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [recoveryTask](recovery-task.html) | [jvm]<br>var [recoveryTask](recovery-task.html): [ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>? = null |
| [remainingAp](remaining-ap.html) | [jvm]<br>var [remainingAp](remaining-ap.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [remainingSp](remaining-sp.html) | [jvm]<br>var [remainingSp](remaining-sp.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [savedLocations](saved-locations.html) | [jvm]<br>val [savedLocations](saved-locations.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[SavedLocation](../../server.maps/-saved-location/index.html)?> |
| [search](search.html) | [jvm]<br>var [search](search.html): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? = null |
| [shop](shop.html) | [jvm]<br>var [shop](shop.html): [Shop](../../server/-shop/index.html)? = null |
| [skills](skills.html) | [jvm]<br>val [skills](skills.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Skill](../-skill/index.html), [Character.Companion.SkillEntry](-companion/-skill-entry/index.html)> |
| [skinColor](skin-color.html) | [jvm]<br>var [skinColor](skin-color.html): [SkinColor](../../client.inventory/-skin-color/index.html) |
| [slots](slots.html) | [jvm]<br>var [slots](slots.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [stance](index.html#-235709885%2FProperties%2F863300109) | [jvm]<br>open override var [stance](index.html#-235709885%2FProperties%2F863300109): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [storage](storage.html) | [jvm]<br>val [storage](storage.html): [Storage](../../server/-storage/index.html)? |
| [str](str.html) | [jvm]<br>var [str](str.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 4 |
| [summons](summons.html) | [jvm]<br>val [summons](summons.html): [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), [Summon](../../server.maps/-summon/index.html)> |
| [timers](timers.html) | [jvm]<br>val [timers](timers.html): [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)<[ScheduledFuture](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ScheduledFuture.html)<*>> |
| [timeSet](time-set.html) | [jvm]<br>var [timeSet](time-set.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [trade](trade.html) | [jvm]<br>var [trade](trade.html): [Trade](../../server/-trade/index.html)? = null |
| [trockMaps](trock-maps.html) | [jvm]<br>val [trockMaps](trock-maps.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [vipTrockMaps](vip-trock-maps.html) | [jvm]<br>val [vipTrockMaps](vip-trock-maps.html): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)<[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)> |
| [visibleMapObjects](visible-map-objects.html) | [jvm]<br>val [visibleMapObjects](visible-map-objects.html): [MutableSet](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)<[MapObject](../../server.maps/-map-object/index.html)> |
| [watk](watk.html) | [jvm]<br>var [watk](watk.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) = 0 |
| [world](world.html) | [jvm]<br>var [world](world.html): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

