- **Title APIs**

  Controls text displayed on the screen and the visibility of a HUD element.

  - [ScreenDisplay](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScreenDisplay.html)
  - [Player.onScreenDisplay](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#onscreendisplay)
  - [ScreenDisplay.updateSubtitle](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScreenDisplay.html#updatesubtitle)
  - [TitleDisplayOptions.subtitle](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.TitleDisplayOptions.html#subtitle)
  - [ScreenDisplay.setTitle](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScreenDisplay.html#settitle)
  - [TitleDisplayOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.TitleDisplayOptions.html)

- **HUD APIs**

  Controls text displayed on the screen and the visibility of a HUD element.

  - [ScreenDisplay](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScreenDisplay.html)
  - [Player.onScreenDisplay](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#onscreendisplay)
  - [HudElement](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.HudElement.html)
  - [ScreenDisplay.setHudVisibility](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScreenDisplay.html#sethudvisibility)
  - [ScreenDisplay.resetHudElementsVisibility](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScreenDisplay.html#resethudelementsvisibility)
  - [ScreenDisplay.getHiddenHudElements](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScreenDisplay.html#gethiddenhudelements)
  - [HudVisibility](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.HudVisibility.html)
  - [HudElementsCount](https://jaylydev.github.io/scriptapi-docs/latest/variables/_minecraft_server.HudElementsCount.html)
  - [HudVisibilityCount](https://jaylydev.github.io/scriptapi-docs/latest/variables/_minecraft_server.HudVisibilityCount.html)

- **Place Feature APIs**:

  Places predefined features in the world, such as trees, structures, or other world generation elements.

  - [Dimension.placeFeature](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Dimension.html#placefeature)
  - [Dimension.placeFeatureRule](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Dimension.html#placefeaturerule)

- **Entity Properties APIs**

  Manages are extra pieces of data that further define an entity, such as how it appears or behaves. Entity Property values are always persisted through saving and loading.

  - [Entity.getProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#getproperty)
  - [Entity.setProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#setproperty)
  - [Entity.resetProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#resetproperty)
  - [Player.getProperty](https://ja[ylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#getproperty)
  - [Player.setProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#setproperty)
  - [Player.resetProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#resetproperty)
  - [Player.setPropertyOverrideForEntity](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#setpropertyoverrideforentity)
  - [Player.removePropertyOverrideForEntity](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#removepropertyoverrideforentity)
  - [Player.clearPropertyOverridesForEntity](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#clearpropertyoverridesforentity)
  - [EntityQueryPropertyOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.EntityQueryPropertyOptions.html) (Target Selector for Entity Properties APIs)

- **Game Difficulty APIs**

  Sets or queries the difficulty level (peaceful, easy, etc.).

  - [World.getDifficulty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#getdifficulty)
  - [World.setDifficulty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#setdifficulty)

- **Jigsaw Structure APIs**

  Construct large structures from smaller sections using jigsaws.

  - [StructureManager.placeJigsaw](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.StructureManager.html#placejigsaw)
  - [StructureManager.placeJigsawStructure](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.StructureManager.html#placejigsawstructure)
  - [JigsawPlaceOptions.keepJigsaws](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.JigsawPlaceOptions.html#keepjigsaws)
  - [JigsawStructurePlaceOptions.keepJigsaws](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.JigsawStructurePlaceOptions.html#keepjigsaws)
  - [JigsawPlaceOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.JigsawPlaceOptions.html)
  - [JigsawStructurePlaceOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.JigsawStructurePlaceOptions.html)

- **Structure APIs**

  Save and load structures without having to use structure blocks.

  - [Structure](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Structure.html)
  - [StructureManager](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.StructureManager.html)
  - [World.structureManager](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#structuremanager)
  - [StructureManager.getWorldStructureIds](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.StructureManager.html#getworldstructureids)

- **Dynamic Property APIs**

  Save and load persist data within a Minecraft world, accessible only by scripts for each behaviour pack.

  - [ContainerSlot.setDynamicProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ContainerSlot.html#setdynamicproperty)
  - [Entity.setDynamicProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#setdynamicproperty)
  - [ItemStack.setDynamicProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemStack.html#setdynamicproperty)
  - [World.setDynamicProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#setdynamicproperty)
  - [ContainerSlot.setDynamicProperties](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ContainerSlot.html#setdynamicproperties)
  - [Entity.setDynamicProperties](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#setdynamicproperties)
  - [ItemStack.setDynamicProperties](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemStack.html#setdynamicproperties)
  - [World.setDynamicProperties](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#setdynamicproperties)
  - [ContainerSlot.getDynamicProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ContainerSlot.html#getdynamicproperty)
  - [Entity.getDynamicProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#getdynamicproperty)
  - [ItemStack.getDynamicProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemStack.html#getdynamicproperty)
  - [World.getDynamicProperty](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#getdynamicproperty)
  - [ContainerSlot.getDynamicPropertyTotalByteCount](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ContainerSlot.html#getdynamicpropertytotalbytecount)
  - [Entity.getDynamicPropertyTotalByteCount](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#getdynamicpropertytotalbytecount)
  - [ItemStack.getDynamicPropertyTotalByteCount](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemStack.html#getdynamicpropertytotalbytecount)
  - [World.getDynamicPropertyTotalByteCount](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#getdynamicpropertytotalbytecount)
  - [ContainerSlot.getDynamicPropertyIds](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ContainerSlot.html#getdynamicpropertyids)
  - [Entity.getDynamicPropertyIds](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#getdynamicpropertyids)
  - [ItemStack.getDynamicPropertyIds](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemStack.html#getdynamicpropertyids)
  - [World.getDynamicPropertyIds](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#getdynamicpropertyids)
  - [ContainerSlot.clearDynamicProperties](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ContainerSlot.html#cleardynamicproperties)
  - [Entity.clearDynamicProperties](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#cleardynamicproperties)
  - [ItemStack.clearDynamicProperties](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemStack.html#cleardynamicproperties)
  - [World.clearDynamicProperties](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#cleardynamicproperties)

- **Scoreboard APIs**

  Manages and displays scoreboard objectives and their scores.

  - [Scoreboard](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Scoreboard.html)
  - [World.scoreboard](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#scoreboard)
  - [ScoreboardScoreInfo](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScoreboardScoreInfo.html)
  - [ScoreboardObjective](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScoreboardObjective.html)
  - [Entity.scoreboardIdentity](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Entity.html#scoreboardidentity)
  - [ScoreboardIdentity](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ScoreboardIdentity.html)

- **Custom Command APIs**

  Implements custom commands in script.

  - [CustomCommand](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CustomCommand.html)
  - [CustomCommandResult](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CustomCommandResult.html)
  - [CustomCommandOrigin](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.CustomCommandOrigin.html)
  - [CustomCommandRegistry](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.CustomCommandRegistry.html)
  - [StartupEvent.customCommandRegistry](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.StartupEvent.html#customcommandregistry)
  - [CustomCommandParameter](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CustomCommandParameter.html)

- **Custom Components APIs**

  Define and store various properties in JSON to functionality using scripting across blocks and items.

  - [ItemCustomComponent](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.ItemCustomComponent.html)
  - [ItemCustomComponentInstance](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemCustomComponentInstance.html)
  - [BlockCustomComponent](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.BlockCustomComponent.html)
  - [BlockCustomComponentInstance](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockCustomComponentInstance.html)
  - [BlockComponentRegistry.registerCustomComponent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockComponentRegistry.html#registercustomcomponent)
  - [ItemComponentRegistry.registerCustomComponent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemComponentRegistry.html#registercustomcomponent)
  - [BlockCustomComponentInstance.customComponentParameters](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockCustomComponentInstance.html#customcomponentparameters)
  - [CustomComponentParameters](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.CustomComponentParameters.html)
  - [ItemCustomComponentInstance.customComponentParameters](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemCustomComponentInstance.html#customcomponentparameters)

- **Camera APIs**

  - [Camera](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Camera.html)
  - [Player.camera](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#camera)
  - [Camera.setDefaultCamera](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Camera.html#setdefaultcamera)
  - [Camera.setCamera](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Camera.html#setcamera)
  - [CameraFadeOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CameraFadeOptions.html)
  - [CameraEaseOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CameraEaseOptions.html)
  - [CameraTargetOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CameraTargetOptions.html)
  - [CameraSetRotOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CameraSetRotOptions.html)
  - [CameraSetPosOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CameraSetPosOptions.html)
  - [CameraFadeTimeOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CameraFadeTimeOptions.html)
  - [CameraSetFacingOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CameraSetFacingOptions.html)
  - [CameraFixedBoomOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CameraFixedBoomOptions.html)
  - [CameraSetLocationOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.CameraSetLocationOptions.html)

- **Input Permission APIs**

  - [Player.inputPermissions](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#inputpermissions)
  - [PlayerInputPermissions](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerInputPermissions.html)
  - [WorldAfterEvents.playerInputPermissionCategoryChange](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#playerinputpermissioncategorychange)
  - [PlayerInputPermissionCategoryChangeAfterEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerInputPermissionCategoryChangeAfterEvent.html)

- **Performance Watchdog APIs**

  - [SystemBeforeEvents.watchdogTerminate](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.SystemBeforeEvents.html#watchdogterminate)
  - [@minecraft/debug-utilities.disableWatchdogTimingWarnings](https://jaylydev.github.io/scriptapi-docs/latest/functions/_minecraft_debug-utilities.disableWatchdogTimingWarnings.html)
  - [WatchdogTerminateBeforeEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WatchdogTerminateBeforeEvent.html)

- **Enchantment APIs**

  - [Enchantment](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.Enchantment.html)
  - [EnchantmentType](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.EnchantmentType.html)
  - [EnchantmentTypes](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.EnchantmentTypes.html)
  - [ItemEnchantableComponent.removeEnchantment](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemEnchantableComponent.html#removeenchantment)
  - [ItemEnchantableComponent.removeAllEnchantments](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemEnchantableComponent.html#removeallenchantments)
  - [ItemEnchantableComponent.hasEnchantment](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemEnchantableComponent.html#hasenchantment)
  - [ItemEnchantableComponent.getEnchantment](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemEnchantableComponent.html#getenchantment)
  - [ItemEnchantableComponent.getEnchantments](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemEnchantableComponent.html#getenchantments)
  - [ItemEnchantableComponent.canAddEnchantment](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemEnchantableComponent.html#canaddenchantment)
  - [ItemEnchantableComponent.addEnchantment](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemEnchantableComponent.html#addenchantment)
  - [ItemEnchantableComponent.addEnchantments](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemEnchantableComponent.html#addenchantments)

- **Input APIs**

  Script APIs to detect player input & modes.

  - [InputInfo](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.InputInfo.html)
  - [Player.inputInfo](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#inputinfo)
  - [PlayerInputModeChangeAfterEvent.previousInputModeUsed](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerInputModeChangeAfterEvent.html#previousinputmodeused)
  - [PlayerInputPermissions](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerInputPermissions.html)
  - [WorldAfterEvents.playerInputPermissionCategoryChange](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#playerinputpermissioncategorychange)
  - [PlayerInputPermissionCategoryChangeAfterEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerInputPermissionCategoryChangeAfterEvent.html)
  - [WorldAfterEvents.playerInputModeChange](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#playerinputmodechange)
  - [PlayerInputModeChangeAfterEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerInputModeChangeAfterEvent.html)
  - [WorldAfterEvents.playerButtonInput](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#playerbuttoninput)
  - [PlayerButtonInputAfterEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerButtonInputAfterEvent.html)
  - [PlayerInputModeChangeAfterEvent.newInputModeUsed](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerInputModeChangeAfterEvent.html#newinputmodeused)
  - [InputInfo.lastInputModeUsed](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.InputInfo.html#lastinputmodeused)
  - [InputEventOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.InputEventOptions.html)
  - [PlayerButtonInputAfterEvent.newButtonState](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerButtonInputAfterEvent.html#newbuttonstate)
  - [InputInfo.getButtonState](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.InputInfo.html#getbuttonstate)
  - [InputInfo.getMovementVector](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.InputInfo.html#getmovementvector)

- **Particle APIs**

  - [EntityEffectOptions.showParticles](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.EntityEffectOptions.html#showparticles)
  - [EntityProjectileComponent.hitParticle](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.EntityProjectileComponent.html#hitparticle)
  - [EntityProjectileComponent.critParticlesOnProjectileHurt](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.EntityProjectileComponent.html#critparticlesonprojectilehurt)
  - [BlockDestructionParticlesComponent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockDestructionParticlesComponent.html)
  - [Dimension.spawnParticle](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Dimension.html#spawnparticle)
  - [Player.spawnParticle](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#spawnparticle)

- **Liquid APIs**

  - [PotionOptions.liquid](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.PotionOptions.html#liquid)
  - [EntityProjectileComponent.liquidInertia](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.EntityProjectileComponent.html#liquidinertia)
  - [AimAssistPresetSettings.setLiquidTargetingItems](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.AimAssistPresetSettings.html#setliquidtargetingitems)
  - [Block.isLiquid](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Block.html#isliquid)
  - [Potions.getPotionLiquidType](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Potions.html#getpotionliquidtype)
  - [EntityFloatsInLiquidComponent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.EntityFloatsInLiquidComponent.html)
  - [JigsawPlaceOptions.liquidSettings](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.JigsawPlaceOptions.html#liquidsettings)
  - [JigsawStructurePlaceOptions.liquidSettings](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.JigsawStructurePlaceOptions.html#liquidsettings)
  - [ItemPotionComponent.potionLiquidType](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemPotionComponent.html#potionliquidtype)
  - [PotionLiquidType](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PotionLiquidType.html)
  - [Block.isLiquidBlocking](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Block.html#isliquidblocking)
  - [BlockPermutation.isLiquidBlocking](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockPermutation.html#isliquidblocking)
  - [BlockRaycastOptions.includeLiquidBlocks](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.BlockRaycastOptions.html#includeliquidblocks)
  - [EntityRaycastOptions.includeLiquidBlocks](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.EntityRaycastOptions.html#includeliquidblocks)
  - [AimAssistPreset.getLiquidTargetingItems](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.AimAssistPreset.html#getliquidtargetingitems)
  - [AimAssistPresetSettings.getLiquidTargetingItems](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.AimAssistPresetSettings.html#getliquidtargetingitems)
  - [Block.canContainLiquid](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Block.html#cancontainliquid)
  - [BlockPermutation.canContainLiquid](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockPermutation.html#cancontainliquid)
  - [Block.canBeDestroyedByLiquidSpread](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Block.html#canbedestroyedbyliquidspread)
  - [BlockPermutation.canBeDestroyedByLiquidSpread](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockPermutation.html#canbedestroyedbyliquidspread)
  - [Block.liquidSpreadCausesSpawn](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Block.html#liquidspreadcausesspawn)
  - [BlockPermutation.liquidSpreadCausesSpawn](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockPermutation.html#liquidspreadcausesspawn)
  - [Block.liquidCanFlowFromDirection](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Block.html#liquidcanflowfromdirection)

- **Device Info APIs**

  - [SystemInfo](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.SystemInfo.html)
  - [System.serverSystemInfo](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.System.html#serversysteminfo)
  - [ClientSystemInfo](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ClientSystemInfo.html)
  - [Player.clientSystemInfo](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#clientsysteminfo)
  - [SystemInfo.memoryTier](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.SystemInfo.html#memorytier)
  - [ClientSystemInfo.platformType](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ClientSystemInfo.html#platformtype)

- **Hardcore Mode APIs**

  - [World.isHardcore](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#ishardcore)

- **Player Interact APIs**

  - [BlockCustomComponent.onPlayerInteract](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.BlockCustomComponent.html#onplayerinteract)
  - [EntityRideableComponent.crouchingSkipInteract](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.EntityRideableComponent.html#crouchingskipinteract)
  - [BlockComponentPlayerInteractEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockComponentPlayerInteractEvent.html)
  - [WorldAfterEvents.playerInteractWithEntity](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#playerinteractwithentity)
  - [WorldBeforeEvents.playerInteractWithEntity](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldBeforeEvents.html#playerinteractwithentity)
  - [WorldAfterEvents.playerInteractWithBlock](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#playerinteractwithblock)
  - [WorldBeforeEvents.playerInteractWithBlock](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldBeforeEvents.html#playerinteractwithblock)

- **Redstone APIs**

  - [PressurePlatePopAfterEvent.redstonePower](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PressurePlatePopAfterEvent.html#redstonepower)
  - [PressurePlatePushAfterEvent.redstonePower](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PressurePlatePushAfterEvent.html#redstonepower)
  - [TargetBlockHitAfterEvent.redstonePower](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.TargetBlockHitAfterEvent.html#redstonepower)
  - [Block.getRedstonePower](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Block.html#getredstonepower)
  - [PressurePlatePopAfterEvent.previousRedstonePower](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PressurePlatePopAfterEvent.html#previousredstonepower)
  - [PressurePlatePushAfterEvent.previousRedstonePower](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PressurePlatePushAfterEvent.html#previousredstonepower)
  - [TargetBlockHitAfterEvent.previousRedstonePower](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.TargetBlockHitAfterEvent.html#previousredstonepower)

- **Block / Item / Player Inventory APIs**

  - [BlockComponentTypes.Inventory](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.BlockComponentTypes.html#inventory)
  - [EntityComponentTypes.Inventory](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.EntityComponentTypes.html#inventory)
  - [ItemComponentTypes.Inventory](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.ItemComponentTypes.html#inventory)
  - [ItemLockMode.inventory](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.ItemLockMode.html#inventory)
  - [PlayerInventoryType.Inventory](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.PlayerInventoryType.html#inventory)
  - [EntityInventoryComponent.inventorySize](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.EntityInventoryComponent.html#inventorysize)
  - [PlayerInventoryItemChangeAfterEvent.inventoryType](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerInventoryItemChangeAfterEvent.html#inventorytype)
  - [InventoryItemEventOptions.inventoryType](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.InventoryItemEventOptions.html#inventorytype)
  - [PlayerInventoryType](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.PlayerInventoryType.html)
  - [WorldAfterEvents.playerInventoryItemChange](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#playerinventoryitemchange)
  - [PlayerInventoryItemChangeAfterEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerInventoryItemChangeAfterEvent.html)
  - [PlayerCursorInventoryComponent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerCursorInventoryComponent.html)
  - [ItemInventoryComponent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.ItemInventoryComponent.html)
  - [EntityInventoryComponent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.EntityInventoryComponent.html)
  - [EntityComponentTypes.CursorInventory](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.EntityComponentTypes.html#cursorinventory)
  - [BlockInventoryComponent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.BlockInventoryComponent.html)
  - [GameRule.KeepInventory](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.GameRule.html#keepinventory)
  - [GameRules.keepInventory](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.GameRules.html#keepinventory)
  - [InventoryItemEventOptions](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.InventoryItemEventOptions.html)

- **Player Emote APIs**

  - [WorldAfterEvents.playerEmote](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#playeremote)
  - [PlayerEmoteAfterEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerEmoteAfterEvent.html)

- **Game Rule APIs**

  - [GameRule](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.GameRule.html)
  - [GameRules](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.GameRules.html)
  - [World.gameRules](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.World.html#gamerules)
  - [WorldAfterEvents.gameRuleChange](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#gamerulechange)
  - [GameRuleChangeAfterEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.GameRuleChangeAfterEvent.html)

- **GameMode APIs**

  - [GameMode](https://jaylydev.github.io/scriptapi-docs/latest/enums/_minecraft_server.GameMode.html)
  - [EntityFilter.gameMode](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.EntityFilter.html#gamemode)
  - [Player.setGameMode](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#setgamemode)
  - [PlayerGameModeChangeBeforeEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerGameModeChangeBeforeEvent.html)
  - [PlayerGameModeChangeBeforeEventSignal](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerGameModeChangeBeforeEventSignal.html)
  - [PlayerGameModeChangeAfterEvent](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerGameModeChangeAfterEvent.html)
  - [PlayerGameModeChangeAfterEventSignal](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerGameModeChangeAfterEventSignal.html)
  - [Player.getGameMode](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.Player.html#getgamemode)
  - [PlayerGameModeChangeAfterEvent.toGameMode](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerGameModeChangeAfterEvent.html#togamemode)
  - [PlayerGameModeChangeBeforeEvent.toGameMode](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerGameModeChangeBeforeEvent.html#togamemode)
  - [WorldAfterEvents.playerGameModeChange](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldAfterEvents.html#playergamemodechange)
  - [WorldBeforeEvents.playerGameModeChange](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.WorldBeforeEvents.html#playergamemodechange)
  - [PlayerGameModeChangeAfterEvent.fromGameMode](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerGameModeChangeAfterEvent.html#fromgamemode)
  - [PlayerGameModeChangeBeforeEvent.fromGameMode](https://jaylydev.github.io/scriptapi-docs/latest/classes/_minecraft_server.PlayerGameModeChangeBeforeEvent.html#fromgamemode)
  - [EntityFilter.excludeGameModes](https://jaylydev.github.io/scriptapi-docs/latest/interfaces/_minecraft_server.EntityFilter.html#excludegamemodes)
