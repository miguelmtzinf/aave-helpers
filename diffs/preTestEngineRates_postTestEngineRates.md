```diff
diff --git a/./reports/preTestEngineRates.json b/./reports/postTestEngineRates.json
index 8b927d6..92f017d 100644
--- a/./reports/preTestEngineRates.json
+++ b/./reports/postTestEngineRates.json
@@ -1,408 +1,408 @@
 {
   "reserves": {
     "0x4200000000000000000000000000000000000006": {
       "borrowCap": 19745,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "usageAsCollateralEnabled": true,
       "oracle": {
         "address": "0x13e3Ee699D1909E989722E753853AE30b17e08c5",
         "latestAnswer": 157141000000
       },
       "eModeCategory": 0,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "decimals": 18,
       "isActive": true,
       "symbol": "WETH",
       "stableDebtToken": "0xD8Ad37849950903571df17049516a5CD4cbE55F6",
       "isBorrowableInIsolation": false,
       "isFrozen": false,
       "isFlashloanable": false,
       "debtCeiling": 0,
       "underlying": "0x4200000000000000000000000000000000000006",
       "liquidationProtocolFee": 1000,
       "liquidationThreshold": 8250,
       "borrowingEnabled": true,
       "aToken": "0xe50fA9b3c56FfB159cB0FCA61F5c9D750e8128c8",
       "ltv": 8000,
       "liquidationBonus": 10500,
       "stableBorrowRateEnabled": false,
       "reserveFactor": 1000,
       "supplyCap": 35900,
       "interestRateStrategy": "0xeE1BAc9355EaAfCD1B68d272d640d870bC9b4b5C",
       "variableDebtToken": "0x0c84331e39d6658Cd6e6b9ba04736cC4c4734351",
       "isSiloed": false,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e"
     },
     "0x76FB31fb4af56892A25e32cFC43De717950c9278": {
       "debtCeiling": 0,
       "stableDebtToken": "0xfAeF6A702D15428E588d4C0614AEFb4348D83D48",
       "underlying": "0x76FB31fb4af56892A25e32cFC43De717950c9278",
       "variableDebtToken": "0xE80761Ea617F66F96274eA5e8c37f03960ecC679",
       "borrowingEnabled": false,
       "isActive": true,
       "isSiloed": false,
       "borrowCap": 0,
       "aToken": "0xf329e36C7bF6E5E86ce2150875a84Ce77f477375",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "symbol": "AAVE",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "isFrozen": false,
       "oracle": {
         "address": "0x338ed6787f463394D24813b297401B9F05a8C9d1",
         "latestAnswer": 7665000000
       },
       "liquidationProtocolFee": 1000,
       "liquidationThreshold": 6500,
       "decimals": 18,
       "supplyCap": 100000,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "reserveFactor": 0,
       "liquidationBonus": 11000,
       "eModeCategory": 0,
       "usageAsCollateralEnabled": true,
       "stableBorrowRateEnabled": false,
       "isFlashloanable": false,
       "ltv": 5000,
       "isBorrowableInIsolation": false,
       "interestRateStrategy": "0xeE1BAc9355EaAfCD1B68d272d640d870bC9b4b5C"
     },
     "0x4200000000000000000000000000000000000042": {
       "decimals": 18,
       "eModeCategory": 0,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "ltv": 3000,
       "isBorrowableInIsolation": false,
       "isActive": true,
       "usageAsCollateralEnabled": true,
       "symbol": "OP",
       "liquidationThreshold": 4000,
       "interestRateStrategy": "0xeE1BAc9355EaAfCD1B68d272d640d870bC9b4b5C",
       "reserveFactor": 2000,
       "aToken": "0x513c7E3a9c69cA3e22550eF58AC1C0088e918FFf",
       "debtCeiling": 200000000,
       "stableDebtToken": "0x08Cb71192985E936C7Cd166A8b268035e400c3c3",
       "borrowingEnabled": false,
       "isFrozen": false,
       "borrowCap": 0,
       "underlying": "0x4200000000000000000000000000000000000042",
       "liquidationBonus": 11000,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "oracle": {
         "address": "0x0D276FC14719f9292D5C1eA2198673d1f4269246",
         "latestAnswer": 254511663
       },
       "stableBorrowRateEnabled": false,
       "supplyCap": 20000000,
       "isFlashloanable": false,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "liquidationProtocolFee": 1000,
       "isSiloed": false,
       "variableDebtToken": "0x77CA01483f379E58174739308945f044e1a764dc"
     },
     "0x7F5c764cBc14f9669B88837ca1490cCa17c31607": {
       "ltv": 8000,
       "borrowCap": 0,
       "eModeCategory": 1,
       "liquidationProtocolFee": 1000,
       "stableBorrowRateEnabled": true,
       "liquidationBonus": 10500,
       "borrowingEnabled": true,
       "aToken": "0x625E7708f30cA75bfd92586e17077590C60eb4cD",
       "isSiloed": false,
       "reserveFactor": 1000,
       "variableDebtToken": "0xFCCf3cAbbe80101232d343252614b6A3eE81C989",
       "isBorrowableInIsolation": true,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "interestRateStrategy": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
       "isActive": true,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "usageAsCollateralEnabled": true,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "oracle": {
         "address": "0x16a9FA2FDa030272Ce99B29CF780dFA30361E0f3",
         "latestAnswer": 100000000
       },
       "liquidationThreshold": 8500,
       "debtCeiling": 0,
       "isFlashloanable": false,
       "underlying": "0x7F5c764cBc14f9669B88837ca1490cCa17c31607",
       "isFrozen": false,
       "supplyCap": 2000000000,
       "stableDebtToken": "0x307ffe186F84a3bc2613D1eA417A5737D69A7007",
       "symbol": "USDC",
       "decimals": 6
     },
     "0x1F32b1c2345538c0c6f582fCB022739c4A194Ebb": {
       "isFrozen": false,
       "borrowingEnabled": true,
       "debtCeiling": 0,
       "symbol": "wstETH",
       "liquidationBonus": 10720,
       "borrowCap": 940,
       "supplyCap": 6000,
       "isBorrowableInIsolation": false,
       "liquidationThreshold": 7900,
       "interestRateStrategy": "0x6BA97468e2e6a3711a6DD05F0075d48E878c910e",
       "aToken": "0xc45A479877e1e9Dfe9FcD4056c699575a1045dAA",
       "variableDebtToken": "0x34e2eD44EF7466D5f9E0b782B5c08b57475e7907",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "reserveFactor": 1500,
       "oracle": {
         "address": "0x698B585CbC4407e2D54aa898B2600B53C68958f7",
         "latestAnswer": 174300712435
       },
       "eModeCategory": 0,
       "stableDebtToken": "0x78246294a4c6fBf614Ed73CcC9F8b875ca8eE841",
       "underlying": "0x1F32b1c2345538c0c6f582fCB022739c4A194Ebb",
       "isSiloed": false,
       "decimals": 18,
       "liquidationProtocolFee": 1000,
       "ltv": 7000,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "stableBorrowRateEnabled": false,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "isFlashloanable": false,
       "usageAsCollateralEnabled": true,
       "isActive": true
     },
     "0xDA10009cBd5D07dd0CeCc66161FC93D7c9000da1": {
       "isBorrowableInIsolation": true,
       "supplyCap": 2000000000,
       "stableDebtToken": "0xd94112B5B62d53C9402e7A60289c6810dEF1dC9B",
       "reserveFactor": 1000,
       "interestRateStrategy": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "borrowCap": 0,
       "underlying": "0xDA10009cBd5D07dd0CeCc66161FC93D7c9000da1",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "liquidationBonus": 10500,
       "aToken": "0x82E64f49Ed5EC1bC6e43DAD4FC8Af9bb3A2312EE",
       "decimals": 18,
       "liquidationThreshold": 8000,
       "isSiloed": false,
       "ltv": 7500,
       "symbol": "DAI",
       "isFrozen": false,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "isFlashloanable": false,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "debtCeiling": 0,
       "usageAsCollateralEnabled": true,
       "stableBorrowRateEnabled": true,
       "liquidationProtocolFee": 1000,
       "eModeCategory": 1,
       "isActive": true,
       "variableDebtToken": "0x8619d80FB0141ba7F184CbF22fd724116D9f7ffC",
       "oracle": {
         "address": "0x8dBa75e83DA73cc766A7e5a0ee71F656BAb470d6",
         "latestAnswer": 99979000
       },
       "borrowingEnabled": true
     },
     "0x94b008aA00579c1307B0EF2c499aD98a8ce58e58": {
       "liquidationProtocolFee": 1000,
       "reserveFactor": 1000,
       "variableDebtToken": "0xfb00AC187a8Eb5AFAE4eACE434F493Eb62672df7",
       "oracle": {
         "address": "0xECef79E109e997bCA29c1c0897ec9d7b03647F5E",
         "latestAnswer": 99995128
       },
       "isActive": true,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "underlying": "0x94b008aA00579c1307B0EF2c499aD98a8ce58e58",
-      "interestRateStrategy": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
+      "interestRateStrategy": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "stableBorrowRateEnabled": true,
       "isFrozen": false,
       "isBorrowableInIsolation": true,
       "borrowCap": 0,
       "decimals": 6,
       "aToken": "0x6ab707Aca953eDAeFBc4fD23bA73294241490620",
       "liquidationBonus": 10500,
       "debtCeiling": 500000000,
       "eModeCategory": 1,
       "symbol": "USDT",
       "isSiloed": false,
       "liquidationThreshold": 8000,
       "isFlashloanable": false,
       "stableDebtToken": "0x70eFfc565DB6EEf7B927610155602d31b670e802",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "borrowingEnabled": true,
       "usageAsCollateralEnabled": true,
       "supplyCap": 2000000000,
       "ltv": 7500
     },
     "0x68f180fcCe6836688e9084f035309E29Bf0A2095": {
       "isActive": true,
       "usageAsCollateralEnabled": true,
       "isSiloed": false,
       "ltv": 7000,
       "liquidationBonus": 10940,
       "supplyCap": 1100,
       "borrowingEnabled": true,
       "isFrozen": false,
       "symbol": "WBTC",
       "eModeCategory": 0,
       "liquidationThreshold": 7500,
       "borrowCap": 605,
       "isBorrowableInIsolation": false,
       "isFlashloanable": false,
       "underlying": "0x68f180fcCe6836688e9084f035309E29Bf0A2095",
       "aToken": "0x078f358208685046a11C85e8ad32895DED33A249",
       "stableDebtToken": "0x633b207Dd676331c413D4C013a6294B0FE47cD0e",
       "stableBorrowRateEnabled": false,
       "variableDebtToken": "0x92b42c66840C7AD907b4BF74879FF3eF7c529473",
       "decimals": 8,
       "interestRateStrategy": "0xeE1BAc9355EaAfCD1B68d272d640d870bC9b4b5C",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "debtCeiling": 0,
       "reserveFactor": 2000,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "oracle": {
         "address": "0xD702DD976Fb76Fffc2D3963D037dfDae5b04E593",
         "latestAnswer": 2245475153319
       },
       "liquidationProtocolFee": 1000
     },
     "0x350a791Bfc2C21F9Ed5d10980Dad2e2638ffa7f6": {
       "isFlashloanable": false,
       "eModeCategory": 0,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtToken": "0x953A573793604aF8d41F306FEb8274190dB4aE0e",
       "oracle": {
         "address": "0xCc232dcFAAE6354cE191Bd574108c1aD03f86450",
         "latestAnswer": 691711677
       },
       "isActive": true,
       "reserveFactor": 2000,
       "stableBorrowRateEnabled": false,
       "isFrozen": false,
       "borrowCap": 141900,
       "liquidationProtocolFee": 1000,
       "liquidationThreshold": 7500,
       "isSiloed": false,
       "underlying": "0x350a791Bfc2C21F9Ed5d10980Dad2e2638ffa7f6",
       "decimals": 18,
       "isBorrowableInIsolation": false,
       "symbol": "LINK",
       "ltv": 7000,
       "usageAsCollateralEnabled": true,
       "stableDebtToken": "0x89D976629b7055ff1ca02b927BA3e020F22A44e4",
       "liquidationBonus": 11000,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "interestRateStrategy": "0xeE1BAc9355EaAfCD1B68d272d640d870bC9b4b5C",
       "supplyCap": 258000,
       "debtCeiling": 0,
       "aToken": "0x191c10Aa4AF7C30e871E70C95dB0E4eb77237530",
       "borrowingEnabled": true,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3"
     },
     "0x8c6f28f2F1A3C87F0f938b96d27520d9751ec8d9": {
       "underlying": "0x8c6f28f2F1A3C87F0f938b96d27520d9751ec8d9",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "stableBorrowRateEnabled": false,
       "variableDebtToken": "0x4a1c3aD6Ed28a636ee1751C69071f6be75DEb8B8",
       "debtCeiling": 0,
       "borrowCap": 0,
       "isFrozen": false,
       "liquidationThreshold": 7500,
       "liquidationProtocolFee": 1000,
       "usageAsCollateralEnabled": true,
       "eModeCategory": 1,
       "interestRateStrategy": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "decimals": 18,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "liquidationBonus": 10540,
       "ltv": 6000,
       "isBorrowableInIsolation": false,
       "oracle": {
         "address": "0x7f99817d87baD03ea21E05112Ca799d715730efe",
         "latestAnswer": 100164737
       },
       "supplyCap": 20000000,
       "isFlashloanable": false,
       "isActive": true,
       "aToken": "0x6d80113e533a2C0fe82EaBD35f1875DcEA89Ea97",
       "stableDebtToken": "0xF15F26710c827DDe8ACBA678682F3Ce24f2Fb56E",
       "borrowingEnabled": true,
       "symbol": "sUSD",
       "reserveFactor": 1000,
       "isSiloed": false
     }
   },
   "poolConfig": {
     "oracle": "0xD81eb3728a631871a7eBBaD631b5f424909f0c77",
     "protocolDataProvider": "0x69FA688f1Dc47d4B5d8029D5a35FB7a548310654",
     "poolImpl": "0x270d4C1b6F0bB172A9fd628E29530Ca484190013",
     "pool": "0x794a61358D6845594F94dc1DB02A252b5b4814aD",
     "poolConfiguratorImpl": "0xD6FA681E22306b0F4E605B979b7c9a1dFa865ade",
     "poolConfigurator": "0x8145eddDf43f50276641b55bd3AD95944510021E",
     "poolAddressesProvider": "0xa97684ead0e402dC232d5A977953DF7ECBaB3CDb"
   },
   "chainId": 10,
   "strategies": {
     "0xA9F3C3caE095527061e6d270DBE163693e6fda9D": {
       "variableRateSlope2": 750000000000000000000000000,
       "optimalStableToTotalDebtRatio": 200000000000000000000000000,
       "maxExcessStableToTotalDebtRatio": 800000000000000000000000000,
       "baseVariableBorrowRate": 0,
       "maxExcessUsageRatio": 200000000000000000000000000,
       "address": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "optimalUsageRatio": 800000000000000000000000000,
       "baseStableBorrowRate": 50000000000000000000000000,
       "stableRateSlope1": 5000000000000000000000000,
       "stableRateSlope2": 750000000000000000000000000,
       "variableRateSlope1": 40000000000000000000000000
     },
     "0x6BA97468e2e6a3711a6DD05F0075d48E878c910e": {
       "variableRateSlope2": 800000000000000000000000000,
       "address": "0x6BA97468e2e6a3711a6DD05F0075d48E878c910e",
       "stableRateSlope2": 800000000000000000000000000,
       "variableRateSlope1": 45000000000000000000000000,
       "stableRateSlope1": 45000000000000000000000000,
       "optimalStableToTotalDebtRatio": 200000000000000000000000000,
       "maxExcessStableToTotalDebtRatio": 800000000000000000000000000,
       "optimalUsageRatio": 450000000000000000000000000,
       "baseStableBorrowRate": 55000000000000000000000000,
       "baseVariableBorrowRate": 2500000000000000000000000,
       "maxExcessUsageRatio": 550000000000000000000000000
     },
     "0xeE1BAc9355EaAfCD1B68d272d640d870bC9b4b5C": {
       "variableRateSlope2": 3000000000000000000000000000,
       "address": "0xeE1BAc9355EaAfCD1B68d272d640d870bC9b4b5C",
       "optimalStableToTotalDebtRatio": 200000000000000000000000000,
       "maxExcessStableToTotalDebtRatio": 800000000000000000000000000,
       "baseStableBorrowRate": 90000000000000000000000000,
       "variableRateSlope1": 70000000000000000000000000,
       "maxExcessUsageRatio": 550000000000000000000000000,
       "stableRateSlope2": 0,
       "stableRateSlope1": 0,
       "optimalUsageRatio": 450000000000000000000000000,
       "baseVariableBorrowRate": 0
     },
     "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4": {
       "stableRateSlope1": 5000000000000000000000000,
       "maxExcessUsageRatio": 100000000000000000000000000,
       "address": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
       "maxExcessStableToTotalDebtRatio": 800000000000000000000000000,
       "variableRateSlope1": 40000000000000000000000000,
       "variableRateSlope2": 600000000000000000000000000,
       "baseStableBorrowRate": 50000000000000000000000000,
       "optimalUsageRatio": 900000000000000000000000000,
       "optimalStableToTotalDebtRatio": 200000000000000000000000000,
       "baseVariableBorrowRate": 0,
       "stableRateSlope2": 600000000000000000000000000
     }
   },
   "eModes": {
     "1": {
       "eModeCategory": 1,
       "label": "Stablecoins",
       "priceSource": "0x0000000000000000000000000000000000000000",
       "ltv": 9700,
       "liquidationThreshold": 9750,
       "liquidationBonus": 10100
     }
   }
 }
\ No newline at end of file```