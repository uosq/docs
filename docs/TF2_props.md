# Entity Props

## Entities

### CTFWearableLevelableItem
```lua
m_unLevel:  Integer
```

### CTFWearableCampaignItem
```lua
m_nState:  Integer
```

### CTFBaseRocket
```lua
m_vInitialVelocity:  Vector
m_vecOrigin:  Vector
m_angRotation:  Vector
m_iDeflected:  Integer
m_hLauncher:  Integer
```

### CTFWeaponBaseGrenadeProj
```lua
m_vInitialVelocity:  Vector
m_bCritical:  Integer
m_iDeflected:  Integer
m_vecOrigin:  Vector
m_angRotation:  Vector
m_hDeflectOwner:  Integer
```

### CTFWeaponBase
```lua
m_bLowered:  Integer
m_iReloadMode:  Integer
m_bResetParity:  Integer
m_bReloadedThroughAnimEvent:  Integer
m_bDisguiseWeapon:  Integer

LocalActiveTFWeaponData
{
	m_flLastCritCheckTime: Float
	m_flReloadPriorNextFire: Float
	m_flLastFireTime: Float
	m_flEffectBarRegenTime: Float
	m_flObservedCritChance: Float
}

NonLocalTFWeaponData: DataTable
m_flEnergy: Float
m_hExtraWearable:  Integer
m_hExtraWearableViewModel:  Integer
m_bBeingRepurposedForTaunt:  Integer
m_nKillComboClass:  Integer
m_nKillComboCount:  Integer
m_flInspectAnimEndTime: Float
m_nInspectStage:  Integer
m_iConsecutiveShots:  Integer
```

### CTFWeaponRobotArm
```lua
m_hRobotArm:  Integer
```

### CTFWeaponThrowable
```lua
m_flChargeBeginTime: Float
```

### CTFWeaponKatana
```lua
m_bIsBloody:  Integer
```

### CSniperDot
```lua
m_flChargeStartTime: Float
```

### CTFSniperRifleClassic
```lua
m_bCharging:  Integer
```

### CTFSniperRifle
```lua
	SniperRifleLocalData
	{
	m_flChargedDamage: Float
	}
```

### CWeaponChargedSMG
```lua
m_flMinicritCharge: Float
```

### CTFWeaponSlap
```lua
m_bFirstHit:  Integer
m_nNumKills:  Integer
```

### CTFWeaponRocketPack
```lua
m_flInitLaunchTime: Float
m_flLaunchTime: Float
m_flToggleEndTime: Float
m_bEnabled:  Integer
```

### CCrossbow
```lua
m_flRegenerateDuration: Float
m_flLastUsedTimestamp: Float
```

### CWeaponRaygun
```lua
m_bUseNewProjectileCode:  Integer
```

### CWeaponPipebombLauncher
```lua
PipebombLauncherLocalData
{
	m_iPipebombCount:  Integer
	m_flChargeBeginTime: Float
}
```

### CParticleCannon
```lua
m_flChargeBeginTime: Float
m_iChargeEffect:  Integer
```

### CWeaponMinigun
```lua
m_iWeaponState:  Integer
m_bCritShot:  Integer
```

### CWeaponMedigun
```lua
m_hHealingTarget:  Integer
m_bHealing:  Integer
m_bAttacking:  Integer
m_bChargeRelease:  Integer
m_bHolstered:  Integer
m_nChargeResistType:  Integer
m_hLastHealingTarget:  Integer

LocalTFWeaponMedigunData
{
	m_flChargeLevel: Float
}

NonLocalTFWeaponMedigunData
{
	m_flChargeLevel: Float
}
```

### CWeaponLunchBox
```lua
m_bBroken:  Integer
```

### CTFWeaponKnife
```lua
m_bReadyToBackstab:  Integer
m_bKnifeExists:  Integer
m_flKnifeRegenerateDuration: Float
m_flKnifeMeltTimestamp: Float
```

### CWeaponGrenadeLauncher
```lua
m_flDetonateTime: Float
m_iCurrentTube:  Integer
m_iGoalTube:  Integer
```

### CTFProjectile_Pipebomb
```lua
m_bTouched:  Integer
m_iType:  Integer
m_hLauncher:  Integer
m_bDefensiveBomb:  Integer
```

### CGrapplingHook
```lua
m_hProjectile:  Integer
```

### CWeaponFlareGun_Revenge
```lua
m_fLastExtinguishTime: Float
```

### CWeaponFlareGun
```lua
m_flChargeBeginTime: Float
```

### CWeaponFlameThrower
```lua
m_iWeaponState:  Integer
m_bCritFire:  Integer
m_bHitTarget:  Integer
m_flChargeBeginTime: Float

LocalFlameThrowerData
{
	m_iActiveFlames:  Integer
	m_iDamagingFlames:  Integer
	m_hFlameManager:  Integer
	m_bHasHalloweenSpell:  Integer
}
```
### CWeaponFlameBall
```lua
m_flRechargeScale: Float
```

### CWeaponCompoundBow
```lua
m_bArrowAlight:  Integer
m_bNoFire:  Integer
```

### CTFWeaponStickBomb
```lua
m_iDetonated:  Integer
```

### CTFWeaponBreakableMelee
```lua
m_bBroken:  Integer
```

### CTFDroppedWeapon
```lua
m_Item
	{
	m_iItemDefinitionIndex:  Integer
	m_iEntityLevel:  Integer
	m_iItemIDHigh:  Integer
	m_iItemIDLow:  Integer
	m_iAccountID:  Integer
	m_iEntityQuality:  Integer
	m_bInitialized:  Integer
	m_bOnlyIterateItemViewAttributes:  Integer
	m_AttributeList
	{
		m_Attributes
		{
			lengthproxy
			{
				lengthprop20:  Integer
			}
		}
	}
	m_iTeamNumber:  Integer
	m_NetworkedDynamicAttributesForDemos
		{
		m_Attributes
			{
				lengthproxy
				{
					lengthprop20:  Integer
				}
			}
		}
	}
m_flChargeLevel: Float
```

### CTFWeaponSapper
```lua
m_flChargeBeginTime: Float
```

### CTFWeaponBuilder
```lua
m_iBuildState:  Integer
	BuilderLocalData
	{
	m_iObjectType:  Integer
	m_hObjectBeingBuilt:  Integer
	m_aBuildableObjectTypes: DataTable
	}
m_iObjectMode:  Integer
m_flWheatleyTalkingUntil: Float
```

### CTFWeaponBuilder
```lua
m_iBuildState:  Integer
	BuilderLocalData
	{
	m_iObjectType:  Integer
	m_hObjectBeingBuilt:  Integer
	m_aBuildableObjectTypes: DataTable
	}
m_iObjectMode:  Integer
m_flWheatleyTalkingUntil: Float
```

### CTFProjectile_Rocket
```lua
m_bCritical:  Integer
```

### CTFProjectile_Flare
```lua
m_bCritical:  Integer
```

### CTFProjectile_EnergyBall
```lua
m_bChargedShot:  Integer
m_vColor1:  Vector
m_vColor2:  Vector
```

### CTFProjectile_Arrow
```lua
m_bArrowAlight:  Integer
m_bCritical:  Integer
m_iProjectileType:  Integer
```

### CMannVsMachineStats
```lua
m_iCurrentWaveIdx:  Integer
m_iServerWaveID:  Integer
m_iCurrencyCollectedForRespec:  Integer
m_nRespecsAwardedInWave:  Integer

m_runningTotalWaveStats
{
	nCreditsDropped:  Integer
	nCreditsAcquired:  Integer
	nCreditsBonus:  Integer
	nPlayerDeaths:  Integer
	nBuyBacks:  Integer
}

m_previousWaveStats
{
		nCreditsDropped:  Integer
		nCreditsAcquired:  Integer
		nCreditsBonus:  Integer
		nPlayerDeaths:  Integer
		nBuyBacks:  Integer
}

m_currentWaveStats
{
	nCreditsDropped:  Integer
	nCreditsAcquired:  Integer
	nCreditsBonus:  Integer
	nPlayerDeaths:  Integer
	nBuyBacks:  Integer
}
```

### CTFBaseBoss
```lua
m_lastHealthPercentage: Float
```

### CBossAlpha
```lua
m_isNuking:  Integer
```

### CTFWeaponSpellBook
```lua
m_iSelectedSpellIndex:  Integer
m_iSpellCharges:  Integer
m_flTimeNextSpell: Float
m_bFiredAttack:  Integer
```

### CHightower_TeleportVortex
```lua
m_iState:  Integer
```

### CTeleportVortex
```lua
m_iState:  Integer
```

### CZombie
```lua
m_flHeadScale: Float
```

### CMerasmus
```lua
m_bRevealed:  Integer
m_bIsDoingAOEAttack:  Integer
m_bStunned:  Integer
```

### CEyeballBoss
```lua
m_lookAtSpot:  Vector
m_attitude:  Integer
```

### CTFBotHintEngineerNest
```lua
m_bHasActiveTeleporter:  Integer
```

### CBotNPCMinion
```lua
m_stunTarget:  Integer
```

### CBotNPC
```lua
m_laserTarget:  Integer
m_isNuking:  Integer
```

### CPasstimeGun
```lua
m_eThrowState:  Integer
m_fChargeBeginTime: Float
```

### CTFRobotDestruction_Robot
```lua
m_iHealth:  Integer
m_iMaxHealth:  Integer
m_eType:  Integer
```

### CTFReviveMarker
```lua
m_hOwner:  Integer
m_iHealth:  Integer
m_iMaxHealth:  Integer
m_nRevives:  Integer
```

### CTFProjectile_BallOfFire
```lua
m_vecInitialVelocity:  Vector
m_vecSpawnOrigin:  Vector
```

### CTFBaseProjectile
```lua
m_vInitialVelocity:  Vector
m_hLauncher:  Integer
```

### CTFPointManager
```lua
m_nRandomSeed:  Integer
m_unNextPointIndex:  Integer
m_nSpawnTime: DataTable
```

### CTFRobotDestructionLogic
```lua
m_nMaxPoints:  Integer
m_nBlueScore:  Integer
m_nRedScore:  Integer
m_nBlueTargetPoints:  Integer
m_nRedTargetPoints:  Integer
m_flBlueTeamRespawnScale: Float
m_flRedTeamRespawnScale: Float
m_flBlueFinaleEndTime: Float
m_flRedFinaleEndTime: Float
m_flFinaleLength: Float
m_szResFile: String
m_eWinningMethod: DataTable
m_flCountdownEndTime: Float
```

### CTFRobotDestruction_RobotGroup
```lua
m_pszHudIcon: String
m_iTeamNum:  Integer
m_nGroupNumber:  Integer
m_nState:  Integer
m_flRespawnStartTime: Float
m_flRespawnEndTime: Float
m_flLastAttackedTime: Float
```

### CTFPlayerDestructionLogic
```lua
m_hRedTeamLeader:  Integer
m_hBlueTeamLeader:  Integer
m_iszCountdownImage: String
m_bUsingCountdownImage:  Integer
```

### CTFMinigameLogic
```lua
m_hActiveMinigame:  Integer
```

### CTFMinigame
```lua
m_nMinigameTeamScore: DataTable
m_nMaxScoreForMiniGame:  Integer
m_pszHudResFile: String
m_eScoringType:  Integer
```

### CTFPowerupBottle
```lua
m_bActive:  Integer
m_usNumCharges:  Integer
```

### CHalloweenSoulPack
```lua
m_hTarget:  Integer
m_vecPreCurvePos:  Vector
m_vecStartCurvePos:  Vector
m_flDuration: Float
```

### CBonusRoundLogic
```lua
m_hBonusWinner:  Integer

m_aBonusPlayerRoll
{
	lengthproxy
	{
		lengthprop101:  Integer
	}
}

m_Item
{
	m_iItemDefinitionIndex:  Integer
	m_iEntityLevel:  Integer
	m_iItemIDHigh:  Integer
	m_iItemIDLow:  Integer
	m_iAccountID:  Integer
	m_iEntityQuality:  Integer
	m_bInitialized:  Integer
	m_bOnlyIterateItemViewAttributes:  Integer
	m_iTeamNumber:  Integer
	m_AttributeList
	{
		m_Attributes
		{
			lengthproxy
			{
				lengthprop20:  Integer
			}
		}
	}

	m_NetworkedDynamicAttributesForDemos
	{
		m_Attributes
		{
			lengthproxy
			{
				lengthprop20:  Integer
			}
		}
	}
}
```

### CTFGameRulesProxy
```lua
tf_gamerules_data
{
	m_nGameType:  Integer
	m_nStopWatchState:  Integer
	m_pszTeamGoalStringRed: String
	m_pszTeamGoalStringBlue: String
	m_flCapturePointEnableTime: Float
	m_nHudType:  Integer
	m_bIsInTraining:  Integer
	m_bAllowTrainingAchievements:  Integer
	m_bIsWaitingForTrainingContinue:  Integer
	m_bIsTrainingHUDVisible:  Integer
	m_bIsInItemTestingMode:  Integer
	m_hBonusLogic:  Integer
	m_bPlayingKoth:  Integer
	m_bPlayingMedieval:  Integer
	m_bPlayingHybrid_CTF_CP:  Integer
	m_bPlayingSpecialDeliveryMode:  Integer
	m_bPlayingRobotDestructionMode:  Integer
	m_hRedKothTimer:  Integer
	m_hBlueKothTimer:  Integer
	m_nMapHolidayType:  Integer
	m_itHandle:  Integer
	m_bPlayingMannVsMachine:  Integer
	m_hBirthdayPlayer:  Integer
	m_nBossHealth:  Integer
	m_nMaxBossHealth:  Integer
	m_fBossNormalizedTravelDistance:  Integer
	m_bMannVsMachineAlarmStatus:  Integer
	m_bHaveMinPlayersToEnableReady:  Integer
	m_bBountyModeEnabled:  Integer
	m_nHalloweenEffect:  Integer
	m_fHalloweenEffectStartTime: Float
	m_fHalloweenEffectDuration: Float
	m_halloweenScenario:  Integer
	m_bHelltowerPlayersInHell:  Integer
	m_bIsUsingSpells:  Integer
	m_bCompetitiveMode:  Integer
	m_nMatchGroupType:  Integer
	m_bMatchEnded:  Integer
	m_bPowerupMode:  Integer
	m_pszCustomUpgradesFile: String
	m_bTruceActive:  Integer
	m_bShowMatchSummary:  Integer
	m_bShowCompetitiveMatchSummary:  Integer
	m_bTeamsSwitched:  Integer
	m_bMapHasMatchSummaryStage:  Integer
	m_bPlayersAreOnMatchSummaryStage:  Integer
	m_bStopWatchWinner:  Integer
	m_ePlayerWantsRematch: DataTable
	m_eRematchState:  Integer
	m_nNextMapVoteOptions: DataTable
	m_nForceUpgrades:  Integer
	m_nForceEscortPushLogic:  Integer
	m_bRopesHolidayLightsAllowed:  Integer
}
```

### CTFFlameManager
```lua
m_hWeapon:  Integer
m_hAttacker:  Integer
m_flSpreadDegree: Float
m_flRedirectedFlameSizeMult: Float
m_flFlameStartSizeMult: Float
m_flFlameEndSizeMult: Float
m_flFlameIgnorePlayerVelocity: Float
m_flFlameReflectionAdditionalLifeTime: Float
m_flFlameReflectionDamageReduction: Float
m_iMaxFlameReflectionCount:  Integer
m_nShouldReflect:  Integer
m_flFlameSpeed: Float
m_flFlameLifeTime: Float
m_flRandomLifeTimeOffset: Float
m_flFlameGravity: Float
m_flFlameDrag: Float
m_flFlameUp: Float
m_bIsFiring:  Integer
```

### CCHalloweenGiftPickup
```lua
m_hTargetPlayer:  Integer
```

### CCBonusDuckPickup
```lua
m_bSpecial:  Integer
```

### CCaptureFlag
```lua
m_bDisabled:  Integer
m_bVisibleWhenDisabled:  Integer
m_nType:  Integer
m_nFlagStatus:  Integer
m_flResetTime: Float
m_flNeutralTime: Float
m_flMaxResetTime: Float
m_hPrevOwner:  Integer
m_szModel: String
m_szHudIcon: String
m_szPaperEffect: String
m_szTrailEffect: String
m_nUseTrailEffect:  Integer
m_nPointValue:  Integer
m_flAutoCapTime: Float
m_bGlowEnabled:  Integer
m_flTimeToSetPoisonous: Float
```

### CTFTeam
```lua
m_nFlagCaptures:  Integer
m_iRole:  Integer
team_object_array_element:  Integer
team_object_array: Array
m_hLeader:  Integer
```

### CTFPlayerResource
```lua
m_iTotalScore: DataTable
m_iMaxHealth: DataTable
m_iMaxBuffedHealth: DataTable
m_iPlayerClass: DataTable
m_bArenaSpectator: DataTable
m_iActiveDominations: DataTable
m_flNextRespawnTime: DataTable
m_iChargeLevel: DataTable
m_iDamage: DataTable
m_iDamageAssist: DataTable
m_iDamageBoss: DataTable
m_iHealing: DataTable
m_iHealingAssist: DataTable
m_iDamageBlocked: DataTable
m_iCurrencyCollected: DataTable
m_iBonusPoints: DataTable
m_iPlayerLevel: DataTable
m_iStreaks: DataTable
m_iUpgradeRefundCredits: DataTable
m_iBuybackCredits: DataTable
m_iPartyLeaderRedTeamIndex:  Integer
m_iPartyLeaderBlueTeamIndex:  Integer
m_iEventTeamStatus:  Integer
m_iPlayerClassWhenKilled: DataTable
m_iConnectionState: DataTable
m_flConnectTime: DataTable
```

### CTFPlayer
```lua
m_bSaveMeParity:  Integer
m_bIsMiniBoss:  Integer
m_bIsABot:  Integer
m_nBotSkill:  Integer
m_nWaterLevel:  Integer
m_hRagdoll:  Integer

m_PlayerClass
{
	m_iClass:  Integer
	m_iszClassIcon: String
	m_iszCustomModel: String
	m_vecCustomModelOffset:  Vector
	m_angCustomModelRotation:  Vector
	m_bCustomModelRotates:  Integer
	m_bCustomModelRotationSet:  Integer
	m_bCustomModelVisibleToSelf:  Integer
	m_bUseClassAnimations:  Integer
	m_iClassModelParity:  Integer
}

m_Shared
{
	m_nPlayerCond:  Integer
	m_bJumping:  Integer
	m_nNumHealers:  Integer
	m_iCritMult:  Integer
	m_iAirDash:  Integer
	m_nAirDucked:  Integer
	m_flDuckTimer: Float
	m_nPlayerState:  Integer
	m_iDesiredPlayerClass:  Integer
	m_flMovementStunTime: Float
	m_iMovementStunAmount:  Integer
	m_iMovementStunParity:  Integer
	m_hStunner:  Integer
	m_iStunFlags:  Integer
	m_nArenaNumChanges:  Integer
	m_bArenaFirstBloodBoost:  Integer
	m_iWeaponKnockbackID:  Integer
	m_bLoadoutUnavailable:  Integer
	m_iItemFindBonus:  Integer
	m_bShieldEquipped:  Integer
	m_bParachuteEquipped:  Integer
	m_iNextMeleeCrit:  Integer
	m_iDecapitations:  Integer
	m_iRevengeCrits:  Integer
	m_iDisguiseBody:  Integer
	m_hCarriedObject:  Integer
	m_bCarryingObject:  Integer
	m_flNextNoiseMakerTime: Float
	m_iSpawnRoomTouchCount:  Integer
	m_iKillCountSinceLastDeploy:  Integer
	m_flFirstPrimaryAttack: Float
	m_flEnergyDrinkMeter: Float
	m_flHypeMeter: Float
	m_flChargeMeter: Float
	m_flInvisChangeCompleteTime: Float
	m_nDisguiseTeam:  Integer
	m_nDisguiseClass:  Integer
	m_nDisguiseSkinOverride:  Integer
	m_nMaskClass:  Integer
	m_hDisguiseTarget:  Integer
	m_iDisguiseHealth:  Integer
	m_bFeignDeathReady:  Integer
	m_hDisguiseWeapon:  Integer
	m_nTeamTeleporterUsed:  Integer
	m_flCloakMeter: Float
	m_flSpyTranqBuffDuration: Float
	
	tfsharedlocaldata
	{
		m_nDesiredDisguiseTeam:  Integer
		m_nDesiredDisguiseClass:  Integer
		m_flStealthNoAttackExpire: Float
		m_flStealthNextChangeTime: Float
		m_bLastDisguisedAsOwnTeam:  Integer
		m_flRageMeter: Float
		m_bRageDraining:  Integer
		m_flNextRageEarnTime: Float
		m_bInUpgradeZone:  Integer
		m_flItemChargeMeter: DataTable
		m_bPlayerDominated: DataTable
		m_bPlayerDominatingMe: DataTable
	
		m_ScoreData
		{
			m_iCaptures:  Integer
			m_iDefenses:  Integer
			m_iKills:  Integer
			m_iDeaths:  Integer
			m_iSuicides:  Integer
			m_iDominations:  Integer
			m_iRevenge:  Integer
			m_iBuildingsBuilt:  Integer
			m_iBuildingsDestroyed:  Integer
			m_iHeadshots:  Integer
			m_iBackstabs:  Integer
			m_iHealPoints:  Integer
			m_iInvulns:  Integer
			m_iTeleports:  Integer
			m_iResupplyPoints:  Integer
			m_iKillAssists:  Integer
			m_iPoints:  Integer
			m_iBonusPoints:  Integer
			m_iDamageDone:  Integer
			m_iCrits:  Integer
		}
			
		m_RoundScoreData
		{
			m_iCaptures:  Integer
			m_iDefenses:  Integer
			m_iKills:  Integer
			m_iDeaths:  Integer
			m_iSuicides:  Integer
			m_iDominations:  Integer
			m_iRevenge:  Integer
			m_iBuildingsBuilt:  Integer
			m_iBuildingsDestroyed:  Integer
			m_iHeadshots:  Integer
			m_iBackstabs:  Integer
			m_iHealPoints:  Integer
			m_iInvulns:  Integer
			m_iTeleports:  Integer
			m_iResupplyPoints:  Integer
			m_iKillAssists:  Integer
			m_iPoints:  Integer
			m_iBonusPoints:  Integer
			m_iDamageDone:  Integer
			m_iCrits:  Integer
		}
	}

	m_ConditionList
	{
		_condition_bits:  Integer
	}

	m_iTauntIndex:  Integer
	m_iTauntConcept:  Integer
	m_nPlayerCondEx:  Integer
	m_iStunIndex:  Integer
	m_nHalloweenBombHeadStage:  Integer
	m_nPlayerCondEx2:  Integer
	m_nPlayerCondEx3:  Integer
	m_nStreaks: DataTable
	m_unTauntSourceItemID_Low:  Integer
	m_unTauntSourceItemID_High:  Integer
	m_flRuneCharge: Float
	m_bHasPasstimeBall:  Integer
	m_bIsTargetedForPasstimePass:  Integer
	m_hPasstimePassTarget:  Integer
	m_askForBallTime: Float
	m_bKingRuneBuffActive:  Integer

	m_ConditionData
	{
		lengthproxy
		{
			lengthprop131:  Integer
		}
	}

	m_nPlayerCondEx4:  Integer
	m_flHolsterAnimTime: Float
	m_hSwitchTo:  Integer
}

m_hItem:  Integer
tflocaldata
{
	m_vecOrigin: VectorXY
	m_vecOrigin[2]: Float
	player_object_array_element:  Integer
	player_object_array: Array
	m_angEyeAngles[0]: Float
	m_angEyeAngles[1]: Float
	m_bIsCoaching:  Integer
	m_hCoach:  Integer
	m_hStudent:  Integer
	m_nCurrency:  Integer
	m_nExperienceLevel:  Integer
	m_nExperienceLevelProgress:  Integer
	m_bMatchSafeToLeave:  Integer
}

tfnonlocaldata
{
	m_vecOrigin: VectorXY,
	m_vecOrigin[2]: Float
	m_angEyeAngles[0]: Float
	m_angEyeAngles[1]: Float
}

m_bAllowMoveDuringTaunt:  Integer
m_bIsReadyToHighFive:  Integer
m_hHighFivePartner:  Integer
m_nForceTauntCam:  Integer
m_flTauntYaw: Float
m_nActiveTauntSlot:  Integer
m_iTauntItemDefIndex:  Integer
m_flCurrentTauntMoveSpeed: Float
m_flVehicleReverseTime: Float
m_flMvMLastDamageTime: Float
m_flLastDamageTime: Float
m_bInPowerPlay:  Integer
m_iSpawnCounter:  Integer
m_bArenaSpectator:  Integer

m_AttributeManager
{
	m_hOuter:  Integer
	m_ProviderType:  Integer
	m_iReapplyProvisionParity:  Integer
}

m_flHeadScale: Float
m_flTorsoScale: Float
m_flHandScale: Float
m_bUseBossHealthBar:  Integer
m_bUsingVRHeadset:  Integer
m_bForcedSkin:  Integer
m_nForcedSkin:  Integer
m_bGlowEnabled:  Integer

TFSendHealersDataTable
{
	m_nActiveWpnClip:  Integer
}

m_flKartNextAvailableBoost: Float
m_iKartHealth:  Integer
m_iKartState:  Integer
m_hGrapplingHookTarget:  Integer
m_hSecondaryLastWeapon:  Integer
m_bUsingActionSlot:  Integer
m_flInspectTime: Float
m_flHelpmeButtonPressTime: Float
m_iCampaignMedals:  Integer
m_iPlayerSkinOverride:  Integer
m_bViewingCYOAPDA:  Integer
m_bRegenerating:  Integer
```

### CTFRagdoll
```lua
m_vecRagdollOrigin:  Vector
m_hPlayer:  Integer
m_vecForce:  Vector
m_vecRagdollVelocity:  Vector
m_nForceBone:  Integer
m_bGib:  Integer
m_bBurning:  Integer
m_bElectrocuted:  Integer
m_bFeignDeath:  Integer
m_bWasDisguised:  Integer
m_bOnGround:  Integer
m_bCloaked:  Integer
m_bBecomeAsh:  Integer
m_iDamageCustom:  Integer
m_iTeam:  Integer
m_iClass:  Integer

m_hRagWearables
{
	lengthproxy
	{
		lengthprop8:  Integer
	}
}

m_bGoldRagdoll:  Integer
m_bIceRagdoll:  Integer
m_bCritOnHardHit:  Integer
m_flHeadScale: Float
m_flTorsoScale: Float
m_flHandScale: Float
```

### CTFPasstimeLogic
```lua
m_hBall:  Integer
m_trackPoints[0]:  Vector
m_trackPoints: Array
m_iNumSections:  Integer
m_iCurrentSection:  Integer
m_flMaxPassRange: Float
m_iBallPower:  Integer
m_flPackSpeed: Float
m_bPlayerIsPackMember: DataTable
```

### CPasstimeBall
```lua
m_iCollisionCount:  Integer
m_hHomingTarget:  Integer
m_hCarrier:  Integer
m_hPrevCarrier:  Integer
```

### CTFObjectiveResource
```lua
m_nMannVsMachineMaxWaveCount:  Integer
m_nMannVsMachineWaveCount:  Integer
m_nMannVsMachineWaveEnemyCount:  Integer
m_nMvMWorldMoney:  Integer
m_flMannVsMachineNextWaveTime: Float
m_bMannVsMachineBetweenWaves:  Integer
m_nFlagCarrierUpgradeLevel:  Integer
m_flMvMBaseBombUpgradeTime: Float
m_flMvMNextBombUpgradeTime: Float
m_iszMvMPopfileName: String
m_iChallengeIndex:  Integer
m_nMvMEventPopfileType:  Integer
m_nMannVsMachineWaveClassCounts: DataTable
m_iszMannVsMachineWaveClassNames[0]: String
m_iszMannVsMachineWaveClassNames: Array
m_nMannVsMachineWaveClassFlags: DataTable
m_nMannVsMachineWaveClassCounts2: DataTable
m_iszMannVsMachineWaveClassNames2[0]: String
m_iszMannVsMachineWaveClassNames2: Array
m_nMannVsMachineWaveClassFlags2: DataTable
m_bMannVsMachineWaveClassActive: DataTable
m_bMannVsMachineWaveClassActive2: DataTable
```

### CTFGlow
```lua
m_iMode:  Integer
m_glowColor:  Integer
m_bDisabled:  Integer
m_hTarget:  Integer
```

### CAmmoPack
```lua
m_vecInitialVelocity:  Vector
m_angRotation[0]: Float
m_angRotation[1]: Float
m_angRotation[2]: Float
```

### CObjectTeleporter
```lua
m_iState:  Integer
m_flRechargeTime: Float
m_flCurrentRechargeDuration: Float
m_iTimesUsed:  Integer
m_flYawToExit: Float
m_bMatchBuilding:  Integer
```

### CObjectSentrygun
```lua
m_iAmmoShells:  Integer
m_iAmmoRockets:  Integer
m_iState:  Integer
m_bPlayerControlled:  Integer
m_nShieldLevel:  Integer
m_bShielded:  Integer
m_hEnemy:  Integer
m_hAutoAimTarget:  Integer
	
SentrygunLocalData
{
	m_iKills:  Integer
	m_iAssists:  Integer
}
```

### CObjectDispenser
```lua
m_iState:  Integer
m_iAmmoMetal:  Integer
m_iMiniBombCounter:  Integer
healing_array_element:  Integer
healing_array: Array
```

### CMonsterResource
```lua
m_iBossHealthPercentageByte:  Integer
m_iBossStunPercentageByte:  Integer
m_iSkillShotCompleteCount:  Integer
m_fSkillShotComboEndTime: Float
m_iBossState:  Integer
```

### CFuncPasstimeGoal
```lua
m_bTriggerDisabled:  Integer
m_iGoalType:  Integer
```

### CCaptureZone
```lua
m_bDisabled:  Integer
```

### CCurrencyPack
```lua
m_bDistributed:  Integer
```

### CBaseObject
```lua
m_iHealth:  Integer
m_iMaxHealth:  Integer
m_bHasSapper:  Integer
m_iObjectType:  Integer
m_bBuilding:  Integer
m_bPlacing:  Integer
m_bCarried:  Integer
m_bCarryDeploy:  Integer
m_bMiniBuilding:  Integer
m_flPercentageConstructed: Float
m_fObjectFlags:  Integer
m_hBuiltOnEntity:  Integer
m_bDisabled:  Integer
m_hBuilder:  Integer
m_vecBuildMaxs:  Vector
m_vecBuildMins:  Vector
m_iDesiredBuildRotations:  Integer
m_bServerOverridePlacement:  Integer
m_iUpgradeLevel:  Integer
m_iUpgradeMetal:  Integer
m_iUpgradeMetalRequired:  Integer
m_iHighestUpgradeLevel:  Integer
m_iObjectMode:  Integer
m_bDisposableBuilding:  Integer
m_bWasMapPlaced:  Integer
m_bPlasmaDisable:  Integer
```

### CTestTraceline
```lua
m_clrRender:  Integer
m_vecOrigin:  Vector
m_angRotation[0]: Float
m_angRotation[1]: Float
m_angRotation[2]: Float
moveparent:  Integer
```

### CBaseBeam
```lua
m_nModelIndex:  Integer
m_nHaloIndex:  Integer
m_nStartFrame:  Integer
m_nFrameRate:  Integer
m_fLife: Float
m_fWidth: Float
m_fEndWidth: Float
m_nFadeLength:  Integer
m_fAmplitude: Float
m_nSpeed:  Integer
r:  Integer
g:  Integer
B:  Integer
a:  Integer
m_nFlags:  Integer
```

### CSteamJet
```lua
m_SpreadSpeed: Float
m_Speed: Float
m_StartSize: Float
m_EndSize: Float
m_Rate: Float
m_JetLength: Float
m_bEmit:  Integer
m_bFaceLeft:  Integer
m_nType:  Integer
m_spawnflags:  Integer
m_flRollSpeed: Float
```

### CSmokeStack
```lua
m_SpreadSpeed: Float
m_Speed: Float
m_StartSize: Float
m_EndSize: Float
m_Rate: Float
m_JetLength: Float
m_bEmit:  Integer
m_flBaseSpread: Float
m_flTwist: Float
m_flRollSpeed: Float
m_iMaterialModel:  Integer
m_AmbientLight.m_vPos:  Vector
m_AmbientLight.m_vColor:  Vector
m_AmbientLight.m_flIntensity: Float
m_DirLight.m_vPos:  Vector
m_DirLight.m_vColor:  Vector
m_DirLight.m_flIntensity: Float
m_vWind:  Vector
```

### CDustTrail
```lua
m_SpawnRate: Float
m_Color:  Vector
m_ParticleLifetime: Float
m_StopEmitTime: Float
m_MinSpeed: Float
m_MaxSpeed: Float
m_MinDirectedSpeed: Float
m_MaxDirectedSpeed: Float
m_StartSize: Float
m_EndSize: Float
m_SpawnRadius: Float
m_bEmit:  Integer
m_Opacity: Float
```

### CFireTrail
```lua
m_nAttachment:  Integer
m_flLifetime: Float
```

### CSporeTrail
```lua
m_flSpawnRate: Float
m_vecEndColor:  Vector
m_flParticleLifetime: Float
m_flStartSize: Float
m_flEndSize: Float
m_flSpawnRadius: Float
m_bEmit:  Integer
```

### CSporeExplosion
```lua
m_flSpawnRate: Float
m_flParticleLifetime: Float
m_flStartSize: Float
m_flEndSize: Float
m_flSpawnRadius: Float
m_bEmit:  Integer
m_bDontRemove:  Integer
```

### CRocketTrail
```lua
m_SpawnRate: Float
m_StartColor:  Vector
m_EndColor:  Vector
m_ParticleLifetime: Float
m_StopEmitTime: Float
m_MinSpeed: Float
m_MaxSpeed: Float
m_StartSize: Float
m_EndSize: Float
m_SpawnRadius: Float
m_bEmit:  Integer
m_nAttachment:  Integer
m_Opacity: Float
m_bDamaged:  Integer
m_flFlareScale: Float
```

### CSmokeTrail
```lua
m_SpawnRate: Float
m_StartColor:  Vector
m_EndColor:  Vector
m_ParticleLifetime: Float
m_StopEmitTime: Float
m_MinSpeed: Float
m_MaxSpeed: Float
m_MinDirectedSpeed: Float
m_MaxDirectedSpeed: Float
m_StartSize: Float
m_EndSize: Float
m_SpawnRadius: Float
m_bEmit:  Integer
m_nAttachment:  Integer
m_Opacity: Float
```

### CPropVehicleDriveable
```lua
m_hPlayer:  Integer
m_nSpeed:  Integer
m_nRPM:  Integer
m_flThrottle: Float
m_nBoostTimeLeft:  Integer
m_nHasBoost:  Integer
m_nScannerDisabledWeapons:  Integer
m_nScannerDisabledVehicle:  Integer
m_bEnterAnimOn:  Integer
m_bExitAnimOn:  Integer
m_bUnableToFire:  Integer
m_vecEyeExitEndpoint:  Vector
m_bHasGun:  Integer
m_vecGunCrosshair:  Vector
```

### CParticleSmokeGrenade
```lua
m_flSpawnTime: Float
m_FadeStartTime: Float
m_FadeEndTime: Float
m_CurrentStage:  Integer
```

### CParticleFire
```lua
m_vOrigin:  Vector
m_vDirection:  Vector
```

### CQuadraticBeam
```lua
m_targetPosition:  Vector
m_controlPosition:  Vector
m_scrollRate: Float
m_flWidth: Float
```

### CEmbers
```lua
m_nDensity:  Integer
m_nLifeTime:  Integer
m_nSpeed:  Integer
m_bEmit:  Integer
```

### CEnvWind
```lua
m_EnvWindShared
{
	m_iMinWind:  Integer
	m_iMaxWind:  Integer
	m_iMinGust:  Integer
	m_iMaxGust:  Integer
	m_flMinGustDelay: Float
	m_flMaxGustDelay: Float
	m_iGustDirChange:  Integer
	m_iWindSeed:  Integer
	m_iInitialWindDir:  Integer
	m_flInitialWindSpeed: Float
	m_flStartTime: Float
	m_flGustDuration: Float
}
```

### CPrecipitation
```lua
m_nPrecipType:  Integer
```

### CWeaponIFMBaseCamera
```lua
m_flRenderAspectRatio: Float
m_flRenderFOV: Float
m_flRenderArmLength: Float
m_vecRenderPosition:  Vector
m_angRenderAngles:  Vector
```

### CTFWearable
```lua
m_bDisguiseWearable:  Integer
m_hWeaponAssociatedWith:  Integer
```

### CBaseAttributableItem
```lua
m_AttributeManager
{
	m_hOuter:  Integer
	m_ProviderType:  Integer
	m_iReapplyProvisionParity:  Integer
	m_Item
	{
		m_iItemDefinitionIndex:  Integer
		m_iEntityLevel:  Integer
		m_iItemIDHigh:  Integer
		m_iItemIDLow:  Integer
		m_iAccountID:  Integer
		m_iEntityQuality:  Integer
		m_bInitialized:  Integer
		m_bOnlyIterateItemViewAttributes:  Integer
		m_iTeamNumber:  Integer
		m_AttributeList
		{
			m_Attributes
			{
				lengthproxy:
				{
					lengthprop20:  Integer
				}
			}
		}

		m_NetworkedDynamicAttributesForDemos
		{
			m_Attributes
			{
				lengthproxy:
				{
					lengthprop20:  Integer
				}
			}
		}
	}
}
```

### CEconEntity
```lua
m_AttributeManager
{
	m_hOuter:  Integer
	m_ProviderType:  Integer
	m_iReapplyProvisionParity:  Integer
	m_Item
	{
		m_iItemDefinitionIndex:  Integer
		m_iEntityLevel:  Integer
		m_iItemIDHigh:  Integer
		m_iItemIDLow:  Integer
		m_iAccountID:  Integer
		m_iEntityQuality:  Integer
		m_bInitialized:  Integer
		m_bOnlyIterateItemViewAttributes:  Integer
		m_iTeamNumber:  Integer

		m_AttributeList
		{
			m_Attributes
			{
				lengthproxy:
				{
					lengthprop20:  Integer
				}
			}
		}

		m_NetworkedDynamicAttributesForDemos
		{
			m_Attributes
			{
				lengthproxy:
				{
					lengthprop20:  Integer
				}
			}
		}
	}
}
m_bValidatedAttachedEntity:  Integer
```

### CHandleTest
```lua
m_Handle:  Integer
m_bSendHandle:  Integer
```

### CTeamplayRoundBasedRulesProxy
```lua
teamplayroundbased_gamerules_data
{
	m_iRoundState:  Integer
	m_bInWaitingForPlayers:  Integer
	m_iWinningTeam:  Integer
	m_bInOvertime:  Integer
	m_bInSetup:  Integer
	m_bSwitchedTeamsThisRound:  Integer
	m_bAwaitingReadyRestart:  Integer
	m_flRestartRoundTime: Float
	m_flMapResetTime: Float
	m_nRoundsPlayed:  Integer
	m_flNextRespawnWave: DataTable
	m_TeamRespawnWaveTimes: DataTable
	m_bTeamReady: DataTable
	m_bStopWatch:  Integer
	m_bMultipleTrains:  Integer
	m_bPlayerReady: DataTable
	m_bCheatsEnabledDuringLevel:  Integer
	m_flCountdownTime: Float
	m_flStateTransitionTime: Float
}
```

### CTeamRoundTimer
```lua
m_bTimerPaused:  Integer
m_flTimeRemaining: Float
m_flTimerEndTime: Float
m_nTimerMaxLength:  Integer
m_bIsDisabled:  Integer
m_bShowInHUD:  Integer
m_nTimerLength:  Integer
m_nTimerInitialLength:  Integer
m_bAutoCountdown:  Integer
m_nSetupTimeLength:  Integer
m_nState:  Integer
m_bStartPaused:  Integer
m_bShowTimeRemaining:  Integer
m_bInCaptureWatchState:  Integer
m_bStopWatchTimer:  Integer
m_flTotalTime: Float
```

### CSpriteTrail
```lua
m_flLifetime: Float
m_flStartWidth: Float
m_flEndWidth: Float
m_flStartWidthVariance: Float
m_flTextureRes: Float
m_flMinFadeLength: Float
m_vecSkyboxOrigin:  Vector
m_flSkyboxScale: Float
```

### CSprite
```lua
m_hAttachedToEntity:  Integer
m_nAttachment:  Integer
m_flScaleTime: Float
m_flSpriteScale: Float
m_flSpriteFramerate: Float
m_flGlowProxySize: Float
m_flHDRColorScale: Float
m_flFrame: Float
m_flBrightnessTime: Float
m_nBrightness:  Integer
m_bWorldSpaceScale:  Integer
```

### CRagdoll_Attached
```lua
m_boneIndexAttached:  Integer
m_ragdollAttachedObjectIndex:  Integer
m_attachmentPointBoneSpace:  Vector
m_attachmentPointRagdollSpace:  Vector
```

### CRagdoll
```lua
m_ragAngles[0]:  Vector
m_ragAngles: Array
m_ragPos[0]:  Vector
m_ragPos: Array
m_hUnragdoll:  Integer
m_flBlendWeight: Float
m_nOverlaySequence:  Integer
```

### CPoseController
```lua
m_hProps: DataTable
m_chPoseIndex: DataTable
m_bPoseValueParity:  Integer
m_fPoseValue: Float
m_fInterpolationTime: Float
m_bInterpolationWrap:  Integer
m_fCycleFrequency: Float
m_nFModType:  Integer
m_fFModTimeOffset: Float
m_fFModRate: Float
m_fFModAmplitude: Float
```

### CFuncLadder
```lua
m_vecPlayerMountPositionTop:  Vector
m_vecPlayerMountPositionBottom:  Vector
m_vecLadderDir:  Vector
m_bFakeLadder:  Integer
```

### CDetailController
```lua
m_flFadeStartDist: Float
m_flFadeEndDist: Float
```

### CWorld
```lua
m_flWaveHeight: Float
m_WorldMins:  Vector
m_WorldMaxs:  Vector
m_bStartDark:  Integer
m_flMaxOccludeeArea: Float
m_flMinOccluderArea: Float
m_flMaxPropScreenSpaceWidth: Float
m_flMinPropScreenSpaceWidth: Float
m_iszDetailSpriteMaterial: String
m_bColdWorld:  Integer
```

### CWaterLODControl
```lua
m_flCheapWaterStartDistance: Float
m_flCheapWaterEndDistance: Float
```

### CVoteController
```lua
m_iActiveIssueIndex:  Integer
m_nVoteIdx:  Integer
m_iOnlyTeamToVote:  Integer
m_nVoteOptionCount: DataTable
m_nPotentialVotes:  Integer
m_bIsYesNoVote:  Integer
```

### CVGuiScreen
```lua
m_flWidth: Float
m_flHeight: Float
m_fScreenFlags:  Integer
m_nPanelName:  Integer
m_nAttachmentIndex:  Integer
m_nOverlayMaterial:  Integer
m_hPlayerOwner:  Integer
```

### CPropJeep
```lua
m_bHeadlightIsOn:  Integer
```

### CPropVehicleChoreoGeneric
```lua
m_hPlayer:  Integer
m_bEnterAnimOn:  Integer
m_bExitAnimOn:  Integer
m_vecEyeExitEndpoint:  Vector
m_vehicleView.bClampEyeAngles:  Integer
m_vehicleView.flPitchCurveZero: Float
m_vehicleView.flPitchCurveLinear: Float
m_vehicleView.flRollCurveZero: Float
m_vehicleView.flRollCurveLinear: Float
m_vehicleView.flFOV: Float
m_vehicleView.flYawMin: Float
m_vehicleView.flYawMax: Float
m_vehicleView.flPitchMin: Float
m_vehicleView.flPitchMax: Float
```

### CProxyToggle
```lua
blah
{
	m_WithProxy:  Integer
}
```

### CTesla
```lua
m_SoundName: String
m_iszSpriteName: String
```

### CTeamTrainWatcher
```lua
m_flTotalProgress: Float
m_iTrainSpeedLevel:  Integer
m_flRecedeTime: Float
m_nNumCappers:  Integer
m_hGlowEnt:  Integer
```

### CBaseTeamObjectiveResource
```lua
m_iTimerToShowInHUD:  Integer
m_iStopWatchTimer:  Integer
m_iNumControlPoints:  Integer
m_bPlayingMiniRounds:  Integer
m_bControlPointsReset:  Integer
m_iUpdateCapHudParity:  Integer
m_vCPPositions[0]:  Vector
m_vCPPositions: Array
m_bCPIsVisible: DataTable
m_flLazyCapPerc: DataTable
m_iTeamIcons: DataTable
m_iTeamOverlays: DataTable
m_iTeamReqCappers: DataTable
m_flTeamCapTime: DataTable
m_iPreviousPoints: DataTable
m_bTeamCanCap: DataTable
m_iTeamBaseIcons: DataTable
m_iBaseControlPoints: DataTable
m_bInMiniRound: DataTable
m_iWarnOnCap: DataTable
m_iszWarnSound[0]: String
m_iszWarnSound: Array
m_flPathDistance: DataTable
m_iCPGroup: DataTable
m_bCPLocked: DataTable
m_nNumNodeHillData: DataTable
m_flNodeHillData: DataTable
m_bTrackAlarm: DataTable
m_flUnlockTimes: DataTable
m_bHillIsDownhill: DataTable
m_flCPTimerTimes: DataTable
m_iNumTeamMembers: DataTable
m_iCappingTeam: DataTable
m_iTeamInZone: DataTable
m_bBlocked: DataTable
m_iOwner: DataTable
m_bCPCapRateScalesWithPlayers: DataTable
m_pszCapLayoutInHUD: String
m_flCustomPositionX: Float
m_flCustomPositionY: Float
```

### CTeam
```lua
m_iTeamNum:  Integer
m_iScore:  Integer
m_iRoundsWon:  Integer
m_szTeamname: String
player_array_element:  Integer
player_array: Array
```

### CSun
```lua
m_clrRender:  Integer
m_clrOverlay:  Integer
m_vDirection:  Vector
m_bOn:  Integer
m_nSize:  Integer
m_nOverlaySize:  Integer
m_nMaterial:  Integer
m_nOverlayMaterial:  Integer
	HDRColorScale: Float
```

### CParticlePerformanceMonitor
```lua
m_bMeasurePerf:  Integer
m_bDisplayPerf:  Integer
```

### CSpotlightEnd
```lua
m_flLightScale: Float
m_Radius: Float
```

### CSlideshowDisplay
```lua
m_bEnabled:  Integer
m_szDisplayText: String
m_szSlideshowDirectory: String
m_chCurrentSlideLists: DataTable
m_fMinSlideTime: Float
m_fMaxSlideTime: Float
m_iCycleType:  Integer
m_bNoListRepeats:  Integer
```

### CShadowControl
```lua
m_shadowDirection:  Vector
m_shadowColor:  Integer
m_flShadowMaxDist: Float
m_bDisableShadows:  Integer
```

### CSceneEntity
```lua
m_nSceneStringIndex:  Integer
m_bIsPlayingBack:  Integer
m_bPaused:  Integer
m_bMultiplayer:  Integer
m_flForceClientTime: Float

m_hActorList
{
	lengthproxy
	{
		lengthprop16:  Integer
	}
}
```

### CRopeKeyframe
```lua
m_iRopeMaterialModelIndex:  Integer
m_hStartPoint:  Integer
m_hEndPoint:  Integer
m_iStartAttachment:  Integer
m_iEndAttachment:  Integer
m_fLockedPoints:  Integer
m_Slack:  Integer
m_RopeLength:  Integer
m_RopeFlags:  Integer
m_TextureScale: Float
m_nSegments:  Integer
m_bConstrainBetweenEndpoints:  Integer
m_Subdiv:  Integer
m_Width: Float
m_flScrollSpeed: Float
m_vecOrigin:  Vector
moveparent:  Integer
m_iParentAttachment:  Integer
```

### CRagdollManager
```lua
m_iCurrentMaxRagdollCount:  Integer
```

### CPhysicsPropMultiplayer
```lua
m_iPhysicsMode:  Integer
m_fMass: Float
m_collisionMins:  Vector
m_collisionMaxs:  Vector
```

### CPhysBoxMultiplayer
```lua
m_iPhysicsMode:  Integer
m_fMass: Float
```

### CDynamicProp
```lua
m_bUseHitboxesForRenderBox:  Integer
```

### CPointWorldText
```lua
m_szText: String
m_flTextSize: Float
m_flTextSpacingX: Float
m_flTextSpacingY: Float
m_colTextColor:  Integer
m_nOrientation:  Integer
m_nFont:  Integer
m_bRainbow:  Integer
```

### CPointCommentaryNode
```lua
m_bActive:  Integer
m_flStartTime: Float
m_iszCommentaryFile: String
m_iszCommentaryFileNoHDR: String
m_iszSpeakers: String
m_iNodeNumber:  Integer
m_iNodeNumberMax:  Integer
m_hViewPosition:  Integer
```

### CPointCamera
```lua
m_FOV: Float
m_Resolution: Float
m_bFogEnable:  Integer
m_FogColor:  Integer
m_flFogStart: Float
m_flFogEnd: Float
m_flFogMaxDensity: Float
m_bActive:  Integer
m_bUseScreenAspectRatio:  Integer
```

### CPlayerResource
```lua
m_iPing: DataTable
m_iScore: DataTable
m_iDeaths: DataTable
m_bConnected: DataTable
m_iTeam: DataTable
m_bAlive: DataTable
m_iHealth: DataTable
m_iAccountID: DataTable
m_bValid: DataTable
m_iUserID: DataTable
```

### CPlasma
```lua
m_flStartScale: Float
m_flScale: Float
m_flScaleTime: Float
m_nFlags:  Integer
m_nPlasmaModelIndex:  Integer
m_nPlasmaModelIndex2:  Integer
m_nGlowModelIndex:  Integer
```

### CPhysicsProp
```lua
m_bAwake:  Integer
```

### CPhysBox
```lua
m_mass: Float
```

### CParticleSystem
```lua
m_vecOrigin:  Vector
m_hOwnerEntity:  Integer
moveparent:  Integer
m_iParentAttachment:  Integer
m_angRotation:  Vector
m_iEffectIndex:  Integer
m_bActive:  Integer
m_flStartTime: Float
m_hControlPointEnts: DataTable
m_iControlPointParents: DataTable
m_bWeatherEffect:  Integer
```

### CMaterialModifyControl
```lua
m_szMaterialName: String
m_szMaterialVar: String
m_szMaterialVarValue: String
m_iFrameStart:  Integer
m_iFrameEnd:  Integer
m_bWrap:  Integer
m_flFramerate: Float
m_bNewAnimCommandsSemaphore:  Integer
m_flFloatLerpStartValue: Float
m_flFloatLerpEndValue: Float
m_flFloatLerpTransitionTime: Float
m_bFloatLerpWrap:  Integer
m_nModifyMode:  Integer
```

### CLightGlow
```lua
m_clrRender:  Integer
m_nHorizontalSize:  Integer
m_nVerticalSize:  Integer
m_nMinDist:  Integer
m_nMaxDist:  Integer
m_nOuterMaxDist:  Integer
m_spawnflags:  Integer
m_vecOrigin:  Vector
m_angRotation:  Vector
moveparent:  Integer
m_flGlowProxySize: Float
HDRColorScale: Float
```

### CInfoOverlayAccessor
```lua
m_iTextureFrameIndex:  Integer
m_iOverlayID:  Integer
```

### CFuncSmokeVolume
```lua
m_Color1:  Integer
m_Color2:  Integer
m_MaterialName: String
m_ParticleDrawWidth: Float
m_ParticleSpacingDistance: Float
m_DensityRampSpeed: Float
m_RotationSpeed: Float
m_MovementSpeed: Float
m_Density: Float
m_spawnflags:  Integer

m_Collision
{
	m_vecMinsPreScaled:  Vector
	m_vecMaxsPreScaled:  Vector
	m_vecMins:  Vector
	m_vecMaxs:  Vector
	m_nSolidType:  Integer
	m_usSolidFlags:  Integer
	m_nSurroundType:  Integer
	m_triggerBloat:  Integer
	m_bUniformTriggerBloat:  Integer
	m_vecSpecifiedSurroundingMinsPreScaled:  Vector
	m_vecSpecifiedSurroundingMaxsPreScaled:  Vector
	m_vecSpecifiedSurroundingMins:  Vector
	m_vecSpecifiedSurroundingMaxs:  Vector
}
```

### CFuncRotating
```lua
m_vecOrigin:  Vector
m_angRotation[0]: Float
m_angRotation[1]: Float
m_angRotation[2]: Float
m_flSimulationTime:  Integer
```

### CFuncOccluder
```lua
m_bActive:  Integer
m_nOccluderIndex:  Integer
```

### CFunc_LOD
```lua
m_fDisappearDist: Float
```

### CFunc_Dust
```lua
m_Color:  Integer
m_SpawnRate:  Integer
m_flSizeMin: Float
m_flSizeMax: Float
m_LifetimeMin:  Integer
m_LifetimeMax:  Integer
m_DustFlags:  Integer
m_SpeedMax:  Integer
m_DistMax:  Integer
m_nModelIndex:  Integer
m_FallSpeed: Float

m_Collision
{
	m_vecMinsPreScaled:  Vector
	m_vecMaxsPreScaled:  Vector
	m_vecMins:  Vector
	m_vecMaxs:  Vector
	m_nSolidType:  Integer
	m_usSolidFlags:  Integer
	m_nSurroundType:  Integer
	m_triggerBloat:  Integer
	m_bUniformTriggerBloat:  Integer
	m_vecSpecifiedSurroundingMinsPreScaled:  Vector
	m_vecSpecifiedSurroundingMaxsPreScaled:  Vector
	m_vecSpecifiedSurroundingMins:  Vector
	m_vecSpecifiedSurroundingMaxs:  Vector
}
```

### CFuncConveyor
```lua
m_flConveyorSpeed: Float
```

### CBreakableSurface
```lua
m_nNumWide:  Integer
m_nNumHigh:  Integer
m_flPanelWidth: Float
m_flPanelHeight: Float
m_vNormal:  Vector
m_vCorner:  Vector
m_bIsBroken:  Integer
m_nSurfaceType:  Integer
m_RawPanelBitVec: DataTable
```

### CFuncAreaPortalWindow
```lua
m_flFadeStartDist: Float
m_flFadeDist: Float
m_flTranslucencyLimit: Float
m_iBackgroundModelIndex:  Integer
```

### CCFish
```lua
m_poolOrigin:  Vector
m_x: Float
m_y: Float
m_z: Float
m_angle: Float
m_nModelIndex:  Integer
m_lifeState:  Integer
m_waterLevel: Float
```

### CEntityFlame
```lua
m_hEntAttached:  Integer
```

### CFireSmoke
```lua
m_flStartScale: Float
m_flScale: Float
m_flScaleTime: Float
m_nFlags:  Integer
m_nFlameModelIndex:  Integer
m_nFlameFromAboveModelIndex:  Integer
```

### CEnvTonemapController
```lua
m_bUseCustomAutoExposureMin:  Integer
m_bUseCustomAutoExposureMax:  Integer
m_bUseCustomBloomScale:  Integer
m_flCustomAutoExposureMin: Float
m_flCustomAutoExposureMax: Float
m_flCustomBloomScale: Float
m_flCustomBloomScaleMinimum: Float
```

### CEnvScreenEffect
```lua
m_flDuration: Float
m_nType:  Integer
```

### CEnvScreenOverlay
```lua
m_iszOverlayNames[0]: String
m_iszOverlayNames: Array
m_flOverlayTimes[0]: Float
m_flOverlayTimes: Array
m_flStartTime: Float
m_iDesiredOverlay:  Integer
m_bIsActive:  Integer
```

### CEnvProjectedTexture
```lua
m_hTargetEntity:  Integer
m_bState:  Integer
m_flLightFOV: Float
m_bEnableShadows:  Integer
m_bLightOnlyTarget:  Integer
m_bLightWorld:  Integer
m_bCameraSpace:  Integer
m_LinearFloatLightColor:  Vector
m_flAmbient: Float
m_SpotlightTextureName: String
m_nSpotlightTextureFrame:  Integer
m_flNearZ: Float
m_flFarZ: Float
m_nShadowQuality:  Integer
```

### CEnvParticleScript
```lua
m_flSequenceScale: Float
```

### CFogController
```lua
m_fog.enable:  Integer
m_fog.blend:  Integer
m_fog.dirPrimary:  Vector
m_fog.colorPrimary:  Integer
m_fog.colorSecondary:  Integer
m_fog.start: Float
m_fog.end: Float
m_fog.farz: Float
m_fog.maxdensity: Float
m_fog.colorPrimaryLerpTo:  Integer
m_fog.colorSecondaryLerpTo:  Integer
m_fog.startLerpTo: Float
m_fog.endLerpTo: Float
m_fog.lerptime: Float
m_fog.duration: Float
```

### CEntityParticleTrail
```lua
m_iMaterialName:  Integer
m_hConstraintEntity:  Integer

m_Info
{
	m_flLifetime: Float
	m_flStartSize: Float
	m_flEndSize: Float
}
```

### CEntityDissolve
```lua
m_flStartTime: Float
m_flFadeOutStart: Float
m_flFadeOutLength: Float
m_flFadeOutModelStart: Float
m_flFadeOutModelLength: Float
m_flFadeInStart: Float
m_flFadeInLength: Float
m_nDissolveType:  Integer
m_vDissolverOrigin:  Vector
m_nMagnitude:  Integer
```

### CDynamicLight
```lua
m_Flags:  Integer
m_LightStyle:  Integer
m_Radius: Float
m_Exponent:  Integer
m_InnerAngle: Float
m_OuterAngle: Float
m_SpotRadius: Float
```

### CColorCorrectionVolume
```lua
m_Weight: Float
m_lookupFilename: String
```

### CColorCorrection
```lua
m_vecOrigin:  Vector
m_minFalloff: Float
m_maxFalloff: Float
m_flCurWeight: Float
m_netLookupFilename: String
m_bEnabled:  Integer
```

### CBasePlayer
```lua
m_iFOV:  Integer
m_iFOVStart:  Integer
m_flFOVTime: Float
m_iDefaultFOV:  Integer
m_hZoomOwner:  Integer
m_hVehicle:  Integer
m_hUseEntity:  Integer
m_iHealth:  Integer
m_lifeState:  Integer
m_iBonusProgress:  Integer
m_iBonusChallenge:  Integer
m_flMaxspeed: Float
m_fFlags:  Integer
m_iObserverMode:  Integer
m_hObserverTarget:  Integer
m_hViewModel[0]:  Integer
m_hViewModel: Array
m_szLastPlaceName: String

localdata
{
	m_vecViewOffset[0]: Float
	m_vecViewOffset[1]: Float
	m_vecViewOffset[2]: Float
	m_flFriction: Float
	m_iAmmo: DataTable
	m_fOnTarget:  Integer
	m_nTickBase:  Integer
	m_nNextThinkTick:  Integer
	m_hLastWeapon:  Integer
	m_hGroundEntity:  Integer
	m_vecVelocity[0]: Float
	m_vecVelocity[1]: Float
	m_vecVelocity[2]: Float
	m_vecBaseVelocity:  Vector
	m_hConstraintEntity:  Integer
	m_vecConstraintCenter:  Vector
	m_flConstraintRadius: Float
	m_flConstraintWidth: Float
	m_flConstraintSpeedFactor: Float
	m_flDeathTime: Float
	m_nWaterLevel:  Integer
	m_flLaggedMovementValue: Float

	m_Local
	{
		m_chAreaBits: DataTable
		m_chAreaPortalBits: DataTable
		m_iHideHUD:  Integer
		m_flFOVRate: Float
		m_bDucked:  Integer
		m_bDucking:  Integer
		m_bInDuckJump:  Integer
		m_flDucktime: Float
		m_flDuckJumpTime: Float
		m_flJumpTime: Float
		m_flFallVelocity: Float
		m_vecPunchAngle:  Vector
		m_vecPunchAngleVel:  Vector
		m_bDrawViewmodel:  Integer
		m_bWearingSuit:  Integer
		m_bPoisoned:  Integer
		m_bForceLocalPlayerDraw:  Integer
		m_flStepSize: Float
		m_bAllowAutoMovement:  Integer
		m_skybox3d.scale:  Integer
		m_skybox3d.origin:  Vector
		m_skybox3d.area:  Integer
		m_skybox3d.fog.enable:  Integer
		m_skybox3d.fog.blend:  Integer
		m_skybox3d.fog.dirPrimary:  Vector
		m_skybox3d.fog.colorPrimary:  Integer
		m_skybox3d.fog.colorSecondary:  Integer
		m_skybox3d.fog.start: Float
		m_skybox3d.fog.end: Float
		m_skybox3d.fog.maxdensity: Float
		m_PlayerFog.m_hCtrl:  Integer
		m_audio.localSound[0]:  Vector
		m_audio.localSound[1]:  Vector
		m_audio.localSound[2]:  Vector
		m_audio.localSound[3]:  Vector
		m_audio.localSound[4]:  Vector
		m_audio.localSound[5]:  Vector
		m_audio.localSound[6]:  Vector
		m_audio.localSound[7]:  Vector
		m_audio.soundscapeIndex:  Integer
		m_audio.localBits:  Integer
		m_audio.entIndex:  Integer
		m_szScriptOverlayMaterial: String
	}
}

m_AttributeList
{
	m_Attributes
	{
		lengthproxy
		{
			lengthprop20:  Integer
		}
	}
}

pl
{
	deadflag:  Integer
}

m_hMyWearables
{
	lengthproxy
	{
		lengthprop8:  Integer
	}
}
```

### CBaseFlex
```lua
m_flexWeight: DataTable
m_blinktoggle:  Integer
m_viewtarget:  Vector
```

### CBaseEntity
```lua
AnimTimeMustBeFirst
{
	m_flAnimTime:  Integer
}
m_flSimulationTime:  Integer
m_ubInterpolationFrame:  Integer
m_vecOrigin:  Vector
m_angRotation:  Vector
m_nModelIndex:  Integer
m_fEffects:  Integer
m_nRenderMode:  Integer
m_nRenderFX:  Integer
m_clrRender:  Integer
m_iTeamNum:  Integer
m_CollisionGroup:  Integer
m_flElasticity: Float
m_flShadowCastDistance: Float
m_hOwnerEntity:  Integer
m_hEffectEntity:  Integer
moveparent:  Integer
m_iParentAttachment:  Integer
movetype:  Integer
movecollide:  Integer

m_iTextureFrameIndex:  Integer
m_bSimulatedEveryTick:  Integer
m_bAnimatedEveryTick:  Integer
m_bAlternateSorting:  Integer
m_nModelIndexOverrides: DataTable

m_Collision
{
	m_vecMinsPreScaled:  Vector
	m_vecMaxsPreScaled:  Vector
	m_vecMins:  Vector
	m_vecMaxs:  Vector
	m_nSolidType:  Integer
	m_usSolidFlags:  Integer
	m_nSurroundType:  Integer
	m_triggerBloat:  Integer
	m_bUniformTriggerBloat:  Integer
	m_vecSpecifiedSurroundingMinsPreScaled:  Vector
	m_vecSpecifiedSurroundingMaxsPreScaled:  Vector
	m_vecSpecifiedSurroundingMins:  Vector
	m_vecSpecifiedSurroundingMaxs:  Vector
}

predictable_id
{
	m_PredictableID:  Integer
	m_bIsPlayerSimulated:  Integer
}
```

### CBaseDoor
```lua
m_flWaveHeight: Float
```

### CBaseCombatCharacter
```lua
bcc_localdata
{
	m_flNextAttack: Float
}

m_hActiveWeapon:  Integer
m_hMyWeapons: DataTable
m_bGlowEnabled:  Integer
```

### CBaseAnimatingOverlay
```lua
overlay_vars
{
	m_AnimOverlay
	{
		lengthproxy
		{
			lengthprop15:  Integer
		}
	}
}
```

### CBoneFollower
```lua
m_modelIndex:  Integer
m_solidIndex:  Integer
```

### CBaseAnimating
```lua
m_nSequence:  Integer
m_nForceBone:  Integer
m_vecForce:  Vector
m_nSkin:  Integer
m_nBody:  Integer
m_nHitboxSet:  Integer
m_flModelScale: Float
m_flModelWidthScale: Float
m_flPoseParameter: DataTable
m_flPlaybackRate: Float
m_flEncodedController: DataTable
m_bClientSideAnimation:  Integer
m_bClientSideFrameReset:  Integer
m_nNewSequenceParity:  Integer
m_nResetEventsParity:  Integer
m_nMuzzleFlashParity:  Integer
m_hLightingOrigin:  Integer
m_hLightingOriginRelative:  Integer

m_fadeMinDist: Float
m_fadeMaxDist: Float
m_flFadeScale: Float

serveranimdata
{
	m_flCycle: Float
}
```

### CInfoLightingRelative
```lua
m_hLightingLandmark:  Integer
```

### CAI_BaseNPC
```lua
m_lifeState:  Integer
m_bPerformAvoidance:  Integer
m_bIsMoving:  Integer
m_bFadeCorpse:  Integer
m_iDeathPose:  Integer
m_iDeathFrame:  Integer
m_iSpeedModRadius:  Integer
m_iSpeedModSpeed:  Integer
m_bSpeedModActive:  Integer
m_bImportanRagdoll:  Integer
m_flTimePingEffect: Float
```

### CBeam
```lua
m_nBeamType:  Integer
m_nBeamFlags:  Integer
m_nNumBeamEnts:  Integer
m_hAttachEntity: DataTable
m_nAttachIndex: DataTable
m_nHaloIndex:  Integer
m_fHaloScale: Float
m_fWidth: Float
m_fEndWidth: Float
m_fFadeLength: Float
m_fAmplitude: Float
m_fStartFrame: Float
m_fSpeed: Float
m_flFramerate: Float
m_flHDRColorScale: Float
m_clrRender:  Integer
m_nRenderFX:  Integer
m_nRenderMode:  Integer
m_flFrame: Float
m_vecEndPos:  Vector
m_nModelIndex:  Integer
m_nMinDXLevel:  Integer
m_vecOrigin:  Vector
moveparent:  Integer

beampredictable_id
{
	m_PredictableID:  Integer
	m_bIsPlayerSimulated:  Integer
}
```

### CBaseViewModel
```lua
m_nModelIndex:  Integer
m_nSkin:  Integer
m_nBody:  Integer
m_nSequence:  Integer
m_nViewModelIndex:  Integer
m_flPlaybackRate: Float
m_fEffects:  Integer
m_nAnimationParity:  Integer
m_hWeapon:  Integer
m_hOwner:  Integer
m_nNewSequenceParity:  Integer
m_nResetEventsParity:  Integer
m_nMuzzleFlashParity:  Integer
m_flPoseParameter[0]: Float
m_flPoseParameter: Array
```

### CBaseProjectile
```lua
m_hOriginalLauncher:  Integer
```

### CBaseGrenade
```lua
m_flDamage: Float
m_DmgRadius: Float
m_bIsLive:  Integer
m_hThrower:  Integer
m_vecVelocity:  Vector
m_fFlags:  Integer
```

### CBaseCombatWeapon
```lua
m_iViewModelIndex:  Integer
m_iWorldModelIndex:  Integer
m_iState:  Integer
m_hOwner:  Integer

LocalWeaponData
{
	m_iClip1:  Integer
	m_iClip2:  Integer
	m_iPrimaryAmmoType:  Integer
	m_iSecondaryAmmoType:  Integer
	m_nViewModelIndex:  Integer
	m_nCustomViewmodelModelIndex:  Integer
	m_bFlipViewModel:  Integer
}

LocalActiveWeaponData
{
	m_flNextPrimaryAttack: Float
	m_flNextSecondaryAttack: Float
	m_nNextThinkTick:  Integer
	m_flTimeWeaponIdle: Float
}
```

## Temp Entities

### CTETFParticleEffect
```lua
m_vecOrigin[0]: Float
m_vecOrigin[1]: Float
m_vecOrigin[2]: Float
m_vecStart[0]: Float
m_vecStart[1]: Float
m_vecStart[2]: Float
m_vecAngles:  Vector
m_iParticleSystemIndex:  Integer
entindex:  Integer
m_iAttachType:  Integer
m_iAttachmentPointIndex:  Integer
m_bResetParticles:  Integer
m_bCustomColors:  Integer
m_CustomColors.m_vecColor1:  Vector
m_CustomColors.m_vecColor2:  Vector
m_bControlPoint1:  Integer
m_ControlPoint1.m_eParticleAttachment:  Integer
m_ControlPoint1.m_vecOffset[0]: Float
m_ControlPoint1.m_vecOffset[1]: Float
m_ControlPoint1.m_vecOffset[2]: Float
```

### CTETFExplosion
```lua
m_vecOrigin[0]: Float
m_vecOrigin[1]: Float
m_vecOrigin[2]: Float
m_vecNormal:  Vector
m_iWeaponID:  Integer
entindex:  Integer
m_nDefID:  Integer
m_nSound:  Integer
m_iCustomParticleIndex:  Integer
```

### CTETFBlood
```lua
m_vecOrigin[0]: Float
m_vecOrigin[1]: Float
m_vecOrigin[2]: Float
m_vecNormal:  Vector
entindex:  Integer
```

### CTEPlayerAnimEvent
```lua
m_hPlayer:  Integer
m_iEvent:  Integer
m_nData:  Integer
```

### CTEFireBullets
```lua
m_vecOrigin:  Vector
m_vecAngles[0]: Float
m_vecAngles[1]: Float
m_iWeaponID:  Integer
m_iMode:  Integer
m_iSeed:  Integer
m_iPlayer:  Integer
m_flSpread: Float
m_bCritical:  Integer
```

### CTEWorldDecal
```lua
m_vecOrigin:  Vector
m_nIndex:  Integer
```

### CTESpriteSpray
```lua
m_vecOrigin:  Vector
m_vecDirection:  Vector
m_nModelIndex:  Integer
m_fNoise: Float
m_nCount:  Integer
m_nSpeed:  Integer
```

### CTESprite
```lua
m_vecOrigin:  Vector
m_nModelIndex:  Integer
m_fScale: Float
m_nBrightness:  Integer
```

### CTESparks
```lua
m_nMagnitude:  Integer
m_nTrailLength:  Integer
m_vecDir:  Vector
```

### CTESmoke
```lua
m_vecOrigin:  Vector
m_nModelIndex:  Integer
m_fScale: Float
m_nFrameRate:  Integer
```

### CTEShowLine
```lua
m_vecEnd:  Vector
```

### CTEProjectedDecal
```lua
m_vecOrigin:  Vector
m_angRotation:  Vector
m_flDistance: Float
m_nIndex:  Integer
```

### CTEPlayerDecal
```lua
m_vecOrigin:  Vector
m_nEntity:  Integer
m_nPlayer:  Integer
```

### CTEPhysicsProp
```lua
m_vecOrigin:  Vector
m_angRotation[0]: Float
m_angRotation[1]: Float
m_angRotation[2]: Float
m_vecVelocity:  Vector
m_nModelIndex:  Integer
m_nFlags:  Integer
m_nSkin:  Integer
m_nEffects:  Integer
```

### CTEParticleSystem
```lua
m_vecOrigin[0]: Float
m_vecOrigin[1]: Float
m_vecOrigin[2]: Float
```

### CTEMuzzleFlash
```lua
m_vecOrigin:  Vector
m_vecAngles:  Vector
m_flScale: Float
m_nType:  Integer
```

### CTELargeFunnel
```lua
m_nModelIndex:  Integer
m_nReversed:  Integer
```

### CTEKillPlayerAttachments
```lua
m_nPlayer:  Integer
```

### CTEImpact
```lua
m_vecOrigin:  Vector
m_vecNormal:  Vector
m_iType:  Integer
m_ucFlags:  Integer
```

### CTEGlowSprite
```lua
m_vecOrigin:  Vector
m_nModelIndex:  Integer
m_fScale: Float
m_fLife: Float
m_nBrightness:  Integer
```

### CTEShatterSurface
```lua
m_vecOrigin:  Vector
m_vecAngles:  Vector
m_vecForce:  Vector
m_vecForcePos:  Vector
m_flWidth: Float
m_flHeight: Float
m_flShardSize: Float
m_nSurfaceType:  Integer
m_uchFrontColor[0]:  Integer
m_uchFrontColor[1]:  Integer
m_uchFrontColor[2]:  Integer
m_uchBackColor[0]:  Integer
m_uchBackColor[1]:  Integer
m_uchBackColor[2]:  Integer
```

### CTEFootprintDecal
```lua
m_vecOrigin:  Vector
m_vecDirection:  Vector
m_nEntity:  Integer
m_nIndex:  Integer
m_chMaterialType:  Integer
```

### CTEFizz
```lua
m_nEntity:  Integer
m_nModelIndex:  Integer
m_nDensity:  Integer
m_nCurrent:  Integer
```

### CTEExplosion
```lua
m_nModelIndex:  Integer
m_fScale: Float
m_nFrameRate:  Integer
m_nFlags:  Integer
m_vecNormal:  Vector
m_chMaterialType:  Integer
m_nRadius:  Integer
m_nMagnitude:  Integer
```

### CTEEnergySplash
```lua
m_vecPos:  Vector
m_vecDir:  Vector
m_bExplosive:  Integer
```

### CTEEffectDispatch
```lua
m_EffectData
{
	m_vOrigin[0]: Float
	m_vOrigin[1]: Float
	m_vOrigin[2]: Float
	m_vStart[0]: Float
	m_vStart[1]: Float
	m_vStart[2]: Float
	m_vAngles:  Vector
	m_vNormal:  Vector
	m_fFlags:  Integer
	m_flMagnitude: Float
	m_flScale: Float
	m_nAttachmentIndex:  Integer
	m_nSurfaceProp:  Integer
	m_iEffectName:  Integer
	m_nMaterial:  Integer
	m_nDamageType:  Integer
	m_nHitBox:  Integer
	entindex:  Integer
	m_nColor:  Integer
	m_flRadius: Float
	m_bCustomColors:  Integer
	m_CustomColors.m_vecColor1:  Vector
	m_CustomColors.m_vecColor2:  Vector
	m_bControlPoint1:  Integer
	m_ControlPoint1.m_eParticleAttachment:  Integer
	m_ControlPoint1.m_vecOffset[0]: Float
	m_ControlPoint1.m_vecOffset[1]: Float
	m_ControlPoint1.m_vecOffset[2]: Float
}
```

### CTEDynamicLight
```lua
m_vecOrigin:  Vector
r:  Integer
g:  Integer
B:  Integer
exponent:  Integer
m_fRadius: Float
m_fTime: Float
m_fDecay: Float
```

### CTEDecal
```lua
m_vecOrigin:  Vector
m_vecStart:  Vector
m_nEntity:  Integer
m_nHitBox:  Integer
m_nIndex:  Integer
```

### CTEClientProjectile
```lua
m_vecOrigin:  Vector
m_vecVelocity:  Vector
m_nModelIndex:  Integer
m_nLifeTime:  Integer
m_hOwner:  Integer
```

### CTEBubbleTrail
```lua
m_vecMins:  Vector
m_vecMaxs:  Vector
m_nModelIndex:  Integer
m_flWaterZ: Float
m_nCount:  Integer
m_fSpeed: Float
```

### CTEBubbles
```lua
m_vecMins:  Vector
m_vecMaxs:  Vector
m_nModelIndex:  Integer
m_fHeight: Float
m_nCount:  Integer
m_fSpeed: Float
```

### CTEBSPDecal
```lua
m_vecOrigin:  Vector
m_nEntity:  Integer
m_nIndex:  Integer
```

### CTEBreakModel
```lua
m_vecOrigin:  Vector
m_angRotation[0]: Float
m_angRotation[1]: Float
m_angRotation[2]: Float
m_vecSize:  Vector
m_vecVelocity:  Vector
m_nModelIndex:  Integer
m_nRandomization:  Integer
m_nCount:  Integer
m_fTime: Float
m_nFlags:  Integer
```

### CTEBloodStream
```lua
m_vecDirection:  Vector
r:  Integer
g:  Integer
B:  Integer
a:  Integer
m_nAmount:  Integer
```

### CTEBloodSprite
```lua
m_vecOrigin:  Vector
m_vecDirection:  Vector
r:  Integer
g:  Integer
B:  Integer
a:  Integer
m_nSprayModel:  Integer
m_nDropModel:  Integer
m_nSize:  Integer
```

### CTEBeamSpline
```lua
m_nPoints:  Integer
m_vecPoints[0]:  Vector
m_vecPoints: Array
```

### CTEBeamRingPoint
```lua
m_vecCenter:  Vector
m_flStartRadius: Float
m_flEndRadius: Float
```

### CTEBeamRing
```lua
m_nStartEntity:  Integer
m_nEndEntity:  Integer
```

### CTEBeamPoints
```lua
m_vecStartPoint:  Vector
m_vecEndPoint:  Vector
```

### CTEBeamLaser
```lua
m_nStartEntity:  Integer
m_nEndEntity:  Integer
```

### CTEBeamFollow
```lua
m_iEntIndex:  Integer
```

### CTEBeamEnts
```lua
m_nStartEntity:  Integer
m_nEndEntity:  Integer
```

### CTEBeamEntPoint
```lua
m_nStartEntity:  Integer
m_nEndEntity:  Integer
m_vecStartPoint:  Vector
m_vecEndPoint:  Vector
```

### CTEMetalSparks
```lua
m_vecPos:  Vector
m_vecDir:  Vector
```

### CTEGaussExplosion
```lua
m_nType:  Integer
m_vecDirection:  Vector
```

### CTEDust
```lua
m_flSize: Float
m_flSpeed: Float
m_vecDirection:  Vector
```
