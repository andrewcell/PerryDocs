---
title: AbstractPlayerInteraction
---
//[Perry](../../../index.html)/[scripting](../index.html)/[AbstractPlayerInteraction](index.html)



# AbstractPlayerInteraction



[jvm]\
open class [AbstractPlayerInteraction](index.html)(**c**: [Client](../../client/-client/index.html))



## Functions


| Name | Summary |
|---|---|
| [canHold](can-hold.html) | [jvm]<br>fun [canHold](can-hold.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [changeMusic](change-music.html) | [jvm]<br>fun [changeMusic](change-music.html)(songName: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [containsAreaInfo](contains-area-info.html) | [jvm]<br>fun [containsAreaInfo](contains-area-info.html)(area: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), info: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [disableMiniMap](disable-mini-map.html) | [jvm]<br>fun [disableMiniMap](disable-mini-map.html)() |
| [displayGuide](display-guide.html) | [jvm]<br>fun [displayGuide](display-guide.html)(num: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [earnTitle](earn-title.html) | [jvm]<br>fun [earnTitle](earn-title.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [environmentChange](environment-change.html) | [jvm]<br>fun [environmentChange](environment-change.html)(env: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), mode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [gainAndEquip](gain-and-equip.html) | [jvm]<br>fun [gainAndEquip](gain-and-equip.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [gainItem](gain-item.html) | [jvm]<br>open fun [gainItem](gain-item.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>open fun [gainItem](gain-item.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), show: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>open fun [gainItem](gain-item.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html))<br>open fun [gainItem](gain-item.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), show: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html))<br>fun [gainItem](gain-item.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), randomStats: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html), showMessage: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)) |
| [getEventManager](get-event-manager.html) | [jvm]<br>fun [getEventManager](get-event-manager.html)(event: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [EventManager](../../scripting.event/-event-manager/index.html)? |
| [getGuild](get-guild.html) | [jvm]<br>fun [getGuild](get-guild.html)(): [Guild](../../net.server.guild/-guild/index.html)? |
| [getMap](get-map.html) | [jvm]<br>fun [getMap](get-map.html)(map: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [GameMap](../../server.maps/-game-map/index.html) |
| [getMapId](get-map-id.html) | [jvm]<br>fun [getMapId](get-map-id.html)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)? |
| [getMobSkill](get-mob-skill.html) | [jvm]<br>fun [getMobSkill](get-mob-skill.html)(skill: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), level: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [MobSkill](../../server.life/-mob-skill/index.html) |
| [getParty](get-party.html) | [jvm]<br>open fun [getParty](get-party.html)(): [Party](../../net.server.world/-party/index.html)? |
| [getPlayer](get-player.html) | [jvm]<br>fun [getPlayer](get-player.html)(): [Character](../../client/-character/index.html)? |
| [getPlayerCount](get-player-count.html) | [jvm]<br>fun [getPlayerCount](get-player-count.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getQuestProgress](get-quest-progress.html) | [jvm]<br>fun [getQuestProgress](get-quest-progress.html)(qid: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)? |
| [getQuestStatus](get-quest-status.html) | [jvm]<br>fun [getQuestStatus](get-quest-status.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [QuestStatus.Status](../../client/-quest-status/-status/index.html) |
| [getWarpMap](get-warp-map.html) | [jvm]<br>fun [getWarpMap](get-warp-map.html)(map: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [GameMap](../../server.maps/-game-map/index.html) |
| [givePartyExp](give-party-exp.html) | [jvm]<br>fun [givePartyExp](give-party-exp.html)(amount: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), party: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Character](../../client/-character/index.html)>) |
| [givePartyItems](give-party-items.html) | [jvm]<br>fun [givePartyItems](give-party-items.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), party: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Character](../../client/-character/index.html)>) |
| [guideHint](guide-hint.html) | [jvm]<br>fun [guideHint](guide-hint.html)(hint: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [guildMessage](guild-message.html) | [jvm]<br>fun [guildMessage](guild-message.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [haveItem](have-item.html) | [jvm]<br>open fun [haveItem](have-item.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [haveItem](have-item.html)(itemId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), quantity: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isLeader](is-leader.html) | [jvm]<br>fun [isLeader](is-leader.html)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isQuestCompleted](is-quest-completed.html) | [jvm]<br>fun [isQuestCompleted](is-quest-completed.html)(quest: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isQuestStarted](is-quest-started.html) | [jvm]<br>fun [isQuestStarted](is-quest-started.html)(quest: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [lockUI](lock-u-i.html) | [jvm]<br>fun [lockUI](lock-u-i.html)() |
| [mapEffect](map-effect.html) | [jvm]<br>fun [mapEffect](map-effect.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [mapMessage](map-message.html) | [jvm]<br>fun [mapMessage](map-message.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [mapSound](map-sound.html) | [jvm]<br>fun [mapSound](map-sound.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [message](message.html) | [jvm]<br>fun [message](message.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [openNpc](open-npc.html) | [jvm]<br>fun [openNpc](open-npc.html)(npcId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [openUI](open-u-i.html) | [jvm]<br>fun [openUI](open-u-i.html)(ui: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [playerMessage](player-message.html) | [jvm]<br>fun [playerMessage](player-message.html)(type: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [playSound](play-sound.html) | [jvm]<br>fun [playSound](play-sound.html)(sound: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [removeAll](remove-all.html) | [jvm]<br>fun [removeAll](remove-all.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html))<br>fun [removeAll](remove-all.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), c: [Client](../../client/-client/index.html)) |
| [removeEquipFromSlot](remove-equip-from-slot.html) | [jvm]<br>fun [removeEquipFromSlot](remove-equip-from-slot.html)(slot: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html)) |
| [removeFromParty](remove-from-party.html) | [jvm]<br>fun [removeFromParty](remove-from-party.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), party: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)<[Character](../../client/-character/index.html)>) |
| [removeGuide](remove-guide.html) | [jvm]<br>fun [removeGuide](remove-guide.html)() |
| [resetMap](reset-map.html) | [jvm]<br>open fun [resetMap](reset-map.html)(mapId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [sendClock](send-clock.html) | [jvm]<br>fun [sendClock](send-clock.html)(c: [Client](../../client/-client/index.html), time: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [showInfo](show-info.html) | [jvm]<br>fun [showInfo](show-info.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [showInfoText](show-info-text.html) | [jvm]<br>fun [showInfoText](show-info-text.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [showInstruction](show-instruction.html) | [jvm]<br>fun [showInstruction](show-instruction.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [showIntro](show-intro.html) | [jvm]<br>fun [showIntro](show-intro.html)(path: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [spawnGuide](spawn-guide.html) | [jvm]<br>fun [spawnGuide](spawn-guide.html)() |
| [spawnMonster](spawn-monster.html) | [jvm]<br>fun [spawnMonster](spawn-monster.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), x: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), y: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [talkGuide](talk-guide.html) | [jvm]<br>fun [talkGuide](talk-guide.html)(message: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [teachSkill](teach-skill.html) | [jvm]<br>fun [teachSkill](teach-skill.html)(skillId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), level: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), masterLevel: [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte/index.html), expiration: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [timeLimit](time-limit.html) | [jvm]<br>fun [timeLimit](time-limit.html)(s: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [unlockUI](unlock-u-i.html) | [jvm]<br>fun [unlockUI](unlock-u-i.html)() |
| [updateAreaInfo](update-area-info.html) | [jvm]<br>fun [updateAreaInfo](update-area-info.html)(area: [Short](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html), info: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [updateQuest](update-quest.html) | [jvm]<br>fun [updateQuest](update-quest.html)(questId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), data: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)) |
| [useItem](use-item.html) | [jvm]<br>fun [useItem](use-item.html)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |
| [warp](warp.html) | [jvm]<br>fun [warp](warp.html)(map: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?<br>fun [warp](warp.html)(map: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), portal: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)?<br>fun [warp](warp.html)(map: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), portal: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Unit](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)? |
| [warpMap](warp-map.html) | [jvm]<br>fun [warpMap](warp-map.html)(map: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)) |


## Properties


| Name | Summary |
|---|---|
| [c](c.html) | [jvm]<br>open val [c](c.html): [Client](../../client/-client/index.html) |


## Inheritors


| Name |
|---|
| [ItemScriptMethods](../../scripting.item/-item-script-methods/index.html) |
| [MapScriptMethods](../../scripting.map/-map-script-methods/index.html) |
| [NPCConversationManager](../../scripting.npc/-n-p-c-conversation-manager/index.html) |
| [PortalPlayerInteraction](../../scripting.portal/-portal-player-interaction/index.html) |
| [ReactorActionManager](../../scripting.reactor/-reactor-action-manager/index.html) |

