---
title: AbstractPacketHandler
---
//[Perry](../../../index.html)/[net](../index.html)/[AbstractPacketHandler](index.html)



# AbstractPacketHandler



[jvm]\
abstract class [AbstractPacketHandler](index.html) : [PacketHandler](../-packet-handler/index.html)



## Functions


| Name | Summary |
|---|---|
| [handlePacket](../-packet-handler/handle-packet.html) | [jvm]<br>abstract fun [handlePacket](../-packet-handler/handle-packet.html)(slea: [SeekableLittleEndianAccessor](../../tools.data.input/-seekable-little-endian-accessor/index.html), c: [Client](../../client/-client/index.html)) |
| [validateState](validate-state.html) | [jvm]<br>open override fun [validateState](validate-state.html)(c: [Client](../../client/-client/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |


## Inheritors


| Name |
|---|
| [AbstractDealDamageHandler](../../net.server.channel.handlers/-abstract-deal-damage-handler/index.html) |
| [AbstractMovementPacketHandler](../../net.server.channel.handlers/-abstract-movement-packet-handler/index.html) |
| [AdminChatHandler](../../net.server.channel.handlers/-admin-chat-handler/index.html) |
| [AdminCommandHandler](../../net.server.channel.handlers/-admin-command-handler/index.html) |
| [AdminLogHandler](../../net.server.channel.handlers/-admin-log-handler/index.html) |
| [AutoAggroHandler](../../net.server.channel.handlers/-auto-aggro-handler/index.html) |
| [AutoAssignHandler](../../net.server.channel.handlers/-auto-assign-handler/index.html) |
| [BeholderHandler](../../net.server.channel.handlers/-beholder-handler/index.html) |
| [CancelBuffHandler](../../net.server.channel.handlers/-cancel-buff-handler/index.html) |
| [CancelChairHandler](../../net.server.channel.handlers/-cancel-chair-handler/index.html) |
| [CancelDebuffHandler](../../net.server.channel.handlers/-cancel-debuff-handler/index.html) |
| [CancelItemEffectHandler](../../net.server.channel.handlers/-cancel-item-effect-handler/index.html) |
| [CashOperationHandler](../../net.server.channel.handlers/-cash-operation-handler/index.html) |
| [ChangeMapHandler](../../net.server.channel.handlers/-change-map-handler/index.html) |
| [ChangeMapSpecialHandler](../../net.server.channel.handlers/-change-map-special-handler/index.html) |
| [CharInfoRequestHandler](../../net.server.channel.handlers/-char-info-request-handler/index.html) |
| [ClickGuideHandler](../../net.server.channel.handlers/-click-guide-handler/index.html) |
| [CloseChalkboardHandler](../../net.server.channel.handlers/-close-chalkboard-handler/index.html) |
| [CoconutHandler](../../net.server.channel.handlers/-coconut-handler/index.html) |
| [DenyGuildRequestHandler](../../net.server.channel.handlers/-deny-guild-request-handler/index.html) |
| [DenyPartyRequestHandler](../../net.server.channel.handlers/-deny-party-request-handler/index.html) |
| [DistributeAPHandler](../../net.server.channel.handlers/-distribute-a-p-handler/index.html) |
| [DistributeSPHandler](../../net.server.channel.handlers/-distribute-s-p-handler/index.html) |
| [EnterCashShopHandler](../../net.server.channel.handlers/-enter-cash-shop-handler/index.html) |
| [GuildOperationHandler](../../net.server.channel.handlers/-guild-operation-handler/index.html) |
| [ItemPickupHandler](../../net.server.channel.handlers/-item-pickup-handler/index.html) |
| [BBSOperationHandler](../../net.server.channel.handlers/-b-b-s-operation-handler/index.html) |
| [BuddyListModifyHandler](../../net.server.channel.handlers/-buddy-list-modify-handler/index.html) |
| [ChangeChannelHandler](../../net.server.channel.handlers/-change-channel-handler/index.html) |
| [CouponCodeHandler](../../net.server.channel.handlers/-coupon-code-handler/index.html) |
| [DamageSummonHandler](../../net.server.channel.handlers/-damage-summon-handler/index.html) |
| [DoorHandler](../../net.server.channel.handlers/-door-handler/index.html) |
| [DueyHandler](../../net.server.channel.handlers/-duey-handler/index.html) |
| [FaceExpressionHandler](../../net.server.channel.handlers/-face-expression-handler/index.html) |
| [FredrickHandler](../../net.server.channel.handlers/-fredrick-handler/index.html) |
| [GeneralChatHandler](../../net.server.channel.handlers/-general-chat-handler/index.html) |
| [GiveFameHandler](../../net.server.channel.handlers/-give-fame-handler/index.html) |
| [HealOvertimeHandler](../../net.server.channel.handlers/-heal-overtime-handler/index.html) |
| [HiredMerchantRequest](../../net.server.channel.handlers/-hired-merchant-request/index.html) |
| [InnerPortalHandler](../../net.server.channel.handlers/-inner-portal-handler/index.html) |
| [ItemIdSortHandler](../../net.server.channel.handlers/-item-id-sort-handler/index.html) |
| [ItemMoveHandler](../../net.server.channel.handlers/-item-move-handler/index.html) |
| [ItemRewardHandler](../../net.server.channel.handlers/-item-reward-handler/index.html) |
| [ItemSortHandler](../../net.server.channel.handlers/-item-sort-handler/index.html) |
| [KeymapChangeHandler](../../net.server.channel.handlers/-keymap-change-handler/index.html) |
| [LeftKnockbackHandler](../../net.server.channel.handlers/-left-knockback-handler/index.html) |
| [MesoDropHandler](../../net.server.channel.handlers/-meso-drop-handler/index.html) |
| [MessengerHandler](../../net.server.channel.handlers/-messenger-handler/index.html) |
| [MobDamageMobFriendlyHandler](../../net.server.channel.handlers/-mob-damage-mob-friendly-handler/index.html) |
| [MobDamageMobHandler](../../net.server.channel.handlers/-mob-damage-mob-handler/index.html) |
| [MonsterBombHandler](../../net.server.channel.handlers/-monster-bomb-handler/index.html) |
| [MonsterBookCoverHandler](../../net.server.channel.handlers/-monster-book-cover-handler/index.html) |
| [NPCAnimation](../../net.server.channel.handlers/-n-p-c-animation/index.html) |
| [NPCMoreTalkHandler](../../net.server.channel.handlers/-n-p-c-more-talk-handler/index.html) |
| [NPCShopHandler](../../net.server.channel.handlers/-n-p-c-shop-handler/index.html) |
| [NPCTalkHandler](../../net.server.channel.handlers/-n-p-c-talk-handler/index.html) |
| [NoteActionHandler](../../net.server.channel.handlers/-note-action-handler/index.html) |
| [PartyChatHandler](../../net.server.channel.handlers/-party-chat-handler/index.html) |
| [PartyOperationHandler](../../net.server.channel.handlers/-party-operation-handler/index.html) |
| [PetAutoPotHandler](../../net.server.channel.handlers/-pet-auto-pot-handler/index.html) |
| [PetChatHandler](../../net.server.channel.handlers/-pet-chat-handler/index.html) |
| [PetCommandHandler](../../net.server.channel.handlers/-pet-command-handler/index.html) |
| [PetExcludeItemsHandler](../../net.server.channel.handlers/-pet-exclude-items-handler/index.html) |
| [PetFoodHandler](../../net.server.channel.handlers/-pet-food-handler/index.html) |
| [PetLootHandler](../../net.server.channel.handlers/-pet-loot-handler/index.html) |
| [PlayerInteractionHandler](../../net.server.channel.handlers/-player-interaction-handler/index.html) |
| [PlayerLoggedInHandler](../../net.server.channel.handlers/-player-logged-in-handler/index.html) |
| [QuestActionHandler](../../net.server.channel.handlers/-quest-action-handler/index.html) |
| [ReactorHitHandler](../../net.server.channel.handlers/-reactor-hit-handler/index.html) |
| [RemoteGachaponHandler](../../net.server.channel.handlers/-remote-gachapon-handler/index.html) |
| [RemoteStoreHandler](../../net.server.channel.handlers/-remote-store-handler/index.html) |
| [ReportHandler](../../net.server.channel.handlers/-report-handler/index.html) |
| [ScriptedItemHandler](../../net.server.channel.handlers/-scripted-item-handler/index.html) |
| [ScrollHandler](../../net.server.channel.handlers/-scroll-handler/index.html) |
| [SkillEffectHandler](../../net.server.channel.handlers/-skill-effect-handler/index.html) |
| [SpawnPetHandler](../../net.server.channel.handlers/-spawn-pet-handler/index.html) |
| [SpecialMoveHandler](../../net.server.channel.handlers/-special-move-handler/index.html) |
| [StorageHandler](../../net.server.channel.handlers/-storage-handler/index.html) |
| [SummonDamageHandler](../../net.server.channel.handlers/-summon-damage-handler/index.html) |
| [TakeDamageHandler](../../net.server.channel.handlers/-take-damage-handler/index.html) |
| [TouchReactorHandler](../../net.server.channel.handlers/-touch-reactor-handler/index.html) |
| [TouchingCashShopHandler](../../net.server.channel.handlers/-touching-cash-shop-handler/index.html) |
| [TrockAddMapHandler](../../net.server.channel.handlers/-trock-add-map-handler/index.html) |
| [UseCashItemHandler](../../net.server.channel.handlers/-use-cash-item-handler/index.html) |
| [UseCatchItemHandler](../../net.server.channel.handlers/-use-catch-item-handler/index.html) |
| [UseChairHandler](../../net.server.channel.handlers/-use-chair-handler/index.html) |
| [UseDeathItemHandler](../../net.server.channel.handlers/-use-death-item-handler/index.html) |
| [UseHammerHandler](../../net.server.channel.handlers/-use-hammer-handler/index.html) |
| [UseItemEffectHandler](../../net.server.channel.handlers/-use-item-effect-handler/index.html) |
| [UseItemHandler](../../net.server.channel.handlers/-use-item-handler/index.html) |
| [UseLifeHandler](../../net.server.channel.handlers/-use-life-handler/index.html) |
| [UseMountFoodHandler](../../net.server.channel.handlers/-use-mount-food-handler/index.html) |
| [UseSolomonHandler](../../net.server.channel.handlers/-use-solomon-handler/index.html) |
| [UseSummonBag](../../net.server.channel.handlers/-use-summon-bag/index.html) |
| [WeddingHandler](../../net.server.channel.handlers/-wedding-handler/index.html) |
| [WhisperHandler](../../net.server.channel.handlers/-whisper-handler/index.html) |
| [DCHandler](../../client/-d-c-handler/index.html) |
| [CharListRequestHandler](../../net.server.handlers.login/-char-list-request-handler/index.html) |
| [CharSelectedHandler](../../net.server.handlers.login/-char-selected-handler/index.html) |
| [CheckCharNameHandler](../../net.server.handlers.login/-check-char-name-handler/index.html) |
| [ClientCheckHandler](../../net.server.handlers.login/-client-check-handler/index.html) |
| [CreateCharHandler](../../net.server.handlers.login/-create-char-handler/index.html) |
| [DeleteCharHandler](../../net.server.handlers.login/-delete-char-handler/index.html) |
| [LoginSuccessHandler](../../net.server.handlers.login/-login-success-handler/index.html) |
| [ReLogRequestHandler](../../net.server.handlers.login/-re-log-request-handler/index.html) |

