```diff
diff --git a/./reports/preTestEnginePolV3.json b/./reports/postTestEnginePolV3.json
index f07cd73..a664980 100644
--- a/./reports/preTestEnginePolV3.json
+++ b/./reports/postTestEnginePolV3.json
@@ -1,726 +1,739 @@
 {
   "chainId": 137,
   "poolConfig": {
     "poolConfigurator": "0x8145eddDf43f50276641b55bd3AD95944510021E",
     "pool": "0x794a61358D6845594F94dc1DB02A252b5b4814aD",
     "poolConfiguratorImpl": "0xD6FA681E22306b0F4E605B979b7c9a1dFa865ade",
     "oracle": "0xb023e699F5a33916Ea823A16485e259257cA8Bd1",
     "poolAddressesProvider": "0xa97684ead0e402dC232d5A977953DF7ECBaB3CDb",
     "protocolDataProvider": "0x69FA688f1Dc47d4B5d8029D5a35FB7a548310654",
     "poolImpl": "0xDF9e4ABdbd94107932265319479643D3B05809dc"
   },
   "reserves": {
     "0x4e3Decbb3645551B8A19f0eA1678079FCB33fB4c": {
       "symbol": "jEUR",
       "ltv": 0,
       "isSiloed": false,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "isBorrowableInIsolation": false,
       "interestRateStrategy": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
       "supplyCap": 0,
       "stableDebtToken": "0x6B4b37618D85Db2a7b469983C888040F7F05Ea3D",
       "oracle": {
         "latestAnswer": 106759000,
         "address": "0x73366Fe0AA0Ded304479862808e02506FE556a98"
       },
       "liquidationProtocolFee": 1000,
       "borrowCap": 0,
       "usageAsCollateralEnabled": false,
       "aToken": "0x6533afac2E7BCCB20dca161449A13A32D391fb00",
       "variableDebtToken": "0x44705f578135cC5d703b4c9c122528C73Eb87145",
       "debtCeiling": 0,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "liquidationBonus": 0,
       "reserveFactor": 2000,
       "decimals": 18,
       "liquidationThreshold": 0,
       "eModeCategory": 1,
       "isActive": true,
       "isFlashloanable": false,
       "underlying": "0x4e3Decbb3645551B8A19f0eA1678079FCB33fB4c",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "stableBorrowRateEnabled": false,
       "borrowingEnabled": true,
       "isFrozen": true
     },
     "0x385Eeac5cB85A38A9a07A70c73e0a3271CfB54A7": {
       "usageAsCollateralEnabled": true,
       "isSiloed": false,
       "isFlashloanable": false,
       "debtCeiling": 0,
       "stableBorrowRateEnabled": false,
       "liquidationProtocolFee": 1000,
       "eModeCategory": 0,
       "underlying": "0x385Eeac5cB85A38A9a07A70c73e0a3271CfB54A7",
       "aToken": "0x8Eb270e296023E9D92081fdF967dDd7878724424",
       "borrowingEnabled": true,
       "stableDebtToken": "0x3EF10DFf4928279c004308EbADc4Db8B7620d6fc",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "decimals": 18,
       "isBorrowableInIsolation": false,
       "oracle": {
         "latestAnswer": 153968584,
         "address": "0xDD229Ce42f11D8Ee7fFf29bDB71C7b81352e11be"
       },
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "ltv": 2500,
       "isFrozen": false,
       "borrowCap": 3234000,
       "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "variableDebtToken": "0xCE186F6Cccb0c955445bb9d10C59caE488Fea559",
       "liquidationThreshold": 4500,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "symbol": "GHST",
       "liquidationBonus": 11500,
-      "reserveFactor": 2000,
+      "reserveFactor": 3500,
       "supplyCap": 5876000,
       "isActive": true
     },
     "0x1BFD67037B42Cf73acF2047067bd4F2C47D9BfD6": {
       "oracle": {
         "latestAnswer": 2244136000000,
         "address": "0xc907E116054Ad103354f2D350FD2514433D57F6f"
       },
       "symbol": "WBTC",
       "liquidationBonus": 10650,
       "liquidationProtocolFee": 1000,
       "liquidationThreshold": 7500,
       "eModeCategory": 0,
       "usageAsCollateralEnabled": true,
       "stableBorrowRateEnabled": false,
       "isFrozen": false,
       "isActive": true,
       "isFlashloanable": false,
       "borrowCap": 851,
       "ltv": 7000,
       "reserveFactor": 2000,
       "decimals": 8,
       "isBorrowableInIsolation": false,
       "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "stableDebtToken": "0x633b207Dd676331c413D4C013a6294B0FE47cD0e",
       "variableDebtToken": "0x92b42c66840C7AD907b4BF74879FF3eF7c529473",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "aToken": "0x078f358208685046a11C85e8ad32895DED33A249",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "borrowingEnabled": true,
       "debtCeiling": 0,
       "supplyCap": 1548,
       "isSiloed": false,
       "underlying": "0x1BFD67037B42Cf73acF2047067bd4F2C47D9BfD6",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B"
     },
     "0x9a71012B13CA4d3D0Cdc72A177DF3ef03b0E76A3": {
       "stableBorrowRateEnabled": false,
       "usageAsCollateralEnabled": true,
       "isActive": true,
       "isBorrowableInIsolation": false,
       "liquidationProtocolFee": 1000,
       "isFlashloanable": false,
       "isSiloed": false,
       "borrowingEnabled": true,
       "interestRateStrategy": "0x4b8D3277d49E114C8F2D6E0B2eD310e29226fe16",
       "aToken": "0x8ffDf2DE812095b1D19CB146E4c004587C0A0692",
       "stableDebtToken": "0xa5e408678469d23efDB7694b1B0A85BB0669e8bd",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "variableDebtToken": "0xA8669021776Bc142DfcA87c21b4A52595bCbB40a",
       "oracle": {
         "latestAnswer": 649789451,
         "address": "0xD106B538F2A868c28Ca1Ec7E298C3325E0251d66"
       },
       "reserveFactor": 2000,
       "decimals": 18,
       "borrowCap": 256140,
       "debtCeiling": 0,
       "liquidationThreshold": 4500,
       "liquidationBonus": 11000,
       "supplyCap": 361000,
       "eModeCategory": 0,
       "symbol": "BAL",
       "isFrozen": false,
       "ltv": 2000,
       "underlying": "0x9a71012B13CA4d3D0Cdc72A177DF3ef03b0E76A3"
     },
     "0xa3Fa99A148fA48D14Ed51d610c367C61876997F1": {
       "oracle": {
         "latestAnswer": 99638912,
         "address": "0xd8d483d813547CfB624b8Dc33a00F2fcbCd2D428"
       },
       "liquidationThreshold": 8000,
       "borrowCap": 600000,
       "eModeCategory": 1,
       "usageAsCollateralEnabled": true,
       "underlying": "0xa3Fa99A148fA48D14Ed51d610c367C61876997F1",
       "symbol": "miMATIC",
-      "reserveFactor": 1000,
+      "reserveFactor": 2000,
       "ltv": 7500,
       "stableBorrowRateEnabled": false,
       "isActive": true,
       "isSiloed": false,
-      "interestRateStrategy": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
+      "interestRateStrategy": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "decimals": 18,
       "liquidationBonus": 10500,
       "debtCeiling": 200000000,
       "isFrozen": false,
       "aToken": "0xeBe517846d0F36eCEd99C735cbF6131e1fEB775D",
       "borrowingEnabled": true,
       "variableDebtToken": "0x18248226C16BF76c032817854E7C83a2113B4f06",
       "stableDebtToken": "0x687871030477bf974725232F764aa04318A8b9c8",
       "liquidationProtocolFee": 1000,
       "supplyCap": 1100000,
       "isFlashloanable": false,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "isBorrowableInIsolation": false
     },
     "0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174": {
       "ltv": 8250,
       "borrowCap": 100000000,
       "decimals": 6,
       "usageAsCollateralEnabled": true,
       "underlying": "0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174",
       "oracle": {
         "latestAnswer": 99994500,
         "address": "0xfE4A8cc5b5B2366C1B58Bea3858e81843581b2F7"
       },
       "borrowingEnabled": true,
       "symbol": "USDC",
       "isActive": true,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "aToken": "0x625E7708f30cA75bfd92586e17077590C60eb4cD",
       "stableBorrowRateEnabled": true,
       "reserveFactor": 1000,
       "debtCeiling": 0,
       "isSiloed": false,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "stableDebtToken": "0x307ffe186F84a3bc2613D1eA417A5737D69A7007",
       "eModeCategory": 1,
       "liquidationProtocolFee": 1000,
       "isFlashloanable": false,
       "isBorrowableInIsolation": true,
       "interestRateStrategy": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "liquidationThreshold": 8500,
       "supplyCap": 150000000,
       "isFrozen": false,
       "variableDebtToken": "0xFCCf3cAbbe80101232d343252614b6A3eE81C989",
       "liquidationBonus": 10400
     },
     "0x8f3Cf7ad23Cd3CaDbD9735AFf958023239c6A063": {
       "debtCeiling": 0,
       "borrowingEnabled": true,
       "isFrozen": false,
       "isSiloed": false,
       "variableDebtToken": "0x8619d80FB0141ba7F184CbF22fd724116D9f7ffC",
       "reserveFactor": 1000,
       "borrowCap": 30000000,
       "isFlashloanable": false,
       "liquidationThreshold": 8000,
       "aToken": "0x82E64f49Ed5EC1bC6e43DAD4FC8Af9bb3A2312EE",
       "usageAsCollateralEnabled": true,
       "liquidationProtocolFee": 1000,
       "eModeCategory": 1,
       "stableBorrowRateEnabled": true,
       "decimals": 18,
       "ltv": 7500,
       "isBorrowableInIsolation": true,
       "underlying": "0x8f3Cf7ad23Cd3CaDbD9735AFf958023239c6A063",
       "stableDebtToken": "0xd94112B5B62d53C9402e7A60289c6810dEF1dC9B",
       "supplyCap": 45000000,
       "liquidationBonus": 10500,
       "isActive": true,
       "symbol": "DAI",
       "interestRateStrategy": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "oracle": {
         "latestAnswer": 99987213,
         "address": "0x4746DeC9e833A82EC7C2C1356372CcF2cfcD2F3D"
       }
     },
     "0xE0B52e49357Fd4DAf2c15e02058DCE6BC0057db4": {
       "reserveFactor": 2000,
       "usageAsCollateralEnabled": false,
       "liquidationBonus": 0,
       "symbol": "agEUR",
       "isSiloed": false,
       "isFlashloanable": false,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "ltv": 0,
       "isFrozen": false,
       "isActive": true,
       "stableDebtToken": "0x40B4BAEcc69B882e8804f9286b12228C27F8c9BF",
       "variableDebtToken": "0x3ca5FA07689F266e907439aFd1fBB59c44fe12f6",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "oracle": {
         "latestAnswer": 106759000,
         "address": "0x73366Fe0AA0Ded304479862808e02506FE556a98"
       },
       "isBorrowableInIsolation": false,
-      "interestRateStrategy": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
+      "interestRateStrategy": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "borrowCap": 0,
       "supplyCap": 0,
       "liquidationProtocolFee": 1000,
       "underlying": "0xE0B52e49357Fd4DAf2c15e02058DCE6BC0057db4",
       "borrowingEnabled": true,
       "stableBorrowRateEnabled": false,
       "decimals": 18,
       "aToken": "0x8437d7C167dFB82ED4Cb79CD44B7a32A1dd95c77",
       "liquidationThreshold": 0,
       "eModeCategory": 1,
       "debtCeiling": 0
     },
     "0x53E0bca35eC356BD5ddDFebbD1Fc0fD03FaBad39": {
       "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "symbol": "LINK",
       "underlying": "0x53E0bca35eC356BD5ddDFebbD1Fc0fD03FaBad39",
       "liquidationThreshold": 6500,
       "ltv": 5000,
       "isSiloed": false,
       "isBorrowableInIsolation": false,
       "reserveFactor": 2000,
       "borrowCap": 163702,
       "debtCeiling": 0,
       "aToken": "0x191c10Aa4AF7C30e871E70C95dB0E4eb77237530",
       "decimals": 18,
       "stableDebtToken": "0x89D976629b7055ff1ca02b927BA3e020F22A44e4",
       "isActive": true,
       "variableDebtToken": "0x953A573793604aF8d41F306FEb8274190dB4aE0e",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "liquidationBonus": 10750,
       "usageAsCollateralEnabled": true,
       "borrowingEnabled": true,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "oracle": {
         "latestAnswer": 691600000,
         "address": "0xd9FFdb71EbE7496cC440152d43986Aae0AB76665"
       },
       "isFlashloanable": false,
       "supplyCap": 297640,
       "eModeCategory": 0,
       "liquidationProtocolFee": 1000,
       "stableBorrowRateEnabled": false,
       "isFrozen": false
     },
     "0xD6DF932A45C0f255f85145f286eA0b292B21C90B": {
       "eModeCategory": 0,
       "liquidationProtocolFee": 1000,
       "usageAsCollateralEnabled": true,
       "isActive": true,
       "liquidationThreshold": 7000,
       "isSiloed": false,
       "aToken": "0xf329e36C7bF6E5E86ce2150875a84Ce77f477375",
       "underlying": "0xD6DF932A45C0f255f85145f286eA0b292B21C90B",
       "reserveFactor": 0,
       "borrowingEnabled": false,
       "isFrozen": false,
       "isBorrowableInIsolation": false,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "borrowCap": 0,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "isFlashloanable": false,
       "oracle": {
         "latestAnswer": 7673000000,
         "address": "0x72484B12719E23115761D5DA1646945632979bB6"
       },
       "ltv": 6000,
       "variableDebtToken": "0xE80761Ea617F66F96274eA5e8c37f03960ecC679",
       "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "stableDebtToken": "0xfAeF6A702D15428E588d4C0614AEFb4348D83D48",
       "symbol": "AAVE",
       "stableBorrowRateEnabled": false,
       "debtCeiling": 0,
       "decimals": 18,
       "supplyCap": 36820,
       "liquidationBonus": 10750
     },
     "0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619": {
       "isFrozen": false,
       "eModeCategory": 0,
       "underlying": "0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtToken": "0x0c84331e39d6658Cd6e6b9ba04736cC4c4734351",
       "oracle": {
         "latestAnswer": 156981339277,
         "address": "0xF9680D99D6C9589e2a93a78A04A279e509205945"
       },
       "liquidationThreshold": 8250,
       "isSiloed": false,
-      "reserveFactor": 1000,
-      "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
+      "reserveFactor": 1500,
+      "interestRateStrategy": "0x27eFE5db315b71753b2a38ED3d5dd7E9362ba93F",
       "stableDebtToken": "0xD8Ad37849950903571df17049516a5CD4cbE55F6",
       "borrowingEnabled": true,
       "isBorrowableInIsolation": false,
       "debtCeiling": 0,
       "usageAsCollateralEnabled": true,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "decimals": 18,
       "ltv": 8000,
       "aToken": "0xe50fA9b3c56FfB159cB0FCA61F5c9D750e8128c8",
       "liquidationProtocolFee": 1000,
       "liquidationBonus": 10500,
       "symbol": "WETH",
       "supplyCap": 26900,
       "isActive": true,
       "borrowCap": 14795,
       "isFlashloanable": false,
       "stableBorrowRateEnabled": false
     },
     "0x0d500B1d8E8eF31E21C99d1Db9A6444d3ADf1270": {
       "supplyCap": 47000000,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "stableBorrowRateEnabled": false,
       "isFrozen": false,
       "isFlashloanable": false,
       "liquidationBonus": 11000,
       "usageAsCollateralEnabled": true,
       "decimals": 18,
       "borrowingEnabled": true,
       "ltv": 6500,
       "liquidationProtocolFee": 1000,
       "isActive": true,
       "isSiloed": false,
       "borrowCap": 39950000,
       "isBorrowableInIsolation": false,
       "debtCeiling": 0,
       "stableDebtToken": "0xF15F26710c827DDe8ACBA678682F3Ce24f2Fb56E",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "oracle": {
         "latestAnswer": 113095493,
         "address": "0xAB594600376Ec9fD91F8e885dADF0CE036862dE0"
       },
       "symbol": "WMATIC",
       "interestRateStrategy": "0xFB0898dCFb69DF9E01DBE625A5988D6542e5BdC5",
       "eModeCategory": 2,
       "underlying": "0x0d500B1d8E8eF31E21C99d1Db9A6444d3ADf1270",
       "liquidationThreshold": 7000,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "aToken": "0x6d80113e533a2C0fe82EaBD35f1875DcEA89Ea97",
       "reserveFactor": 2000,
       "variableDebtToken": "0x4a1c3aD6Ed28a636ee1751C69071f6be75DEb8B8"
     },
     "0x172370d5Cd63279eFa6d502DAB29171933a610AF": {
       "reserveFactor": 1000,
       "supplyCap": 937700,
       "usageAsCollateralEnabled": true,
       "isFrozen": false,
       "variableDebtToken": "0x77CA01483f379E58174739308945f044e1a764dc",
       "decimals": 18,
       "symbol": "CRV",
       "liquidationProtocolFee": 1000,
       "borrowCap": 640437,
       "liquidationBonus": 10500,
       "borrowingEnabled": true,
       "isActive": true,
       "aToken": "0x513c7E3a9c69cA3e22550eF58AC1C0088e918FFf",
       "stableBorrowRateEnabled": false,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "oracle": {
         "latestAnswer": 95800000,
         "address": "0x336584C8E6Dc19637A5b36206B1c79923111b405"
       },
       "stableDebtToken": "0x08Cb71192985E936C7Cd166A8b268035e400c3c3",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "isFlashloanable": false,
       "liquidationThreshold": 8000,
       "ltv": 7500,
       "isBorrowableInIsolation": false,
       "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "eModeCategory": 0,
       "underlying": "0x172370d5Cd63279eFa6d502DAB29171933a610AF",
       "debtCeiling": 0,
       "isSiloed": false,
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e"
     },
     "0x85955046DF4668e1DD369D2DE9f3AEB98DD2A369": {
       "liquidationThreshold": 4500,
       "isFrozen": false,
       "underlying": "0x85955046DF4668e1DD369D2DE9f3AEB98DD2A369",
       "variableDebtToken": "0xf611aEb5013fD2c0511c9CD55c7dc5C1140741A6",
       "borrowCap": 779,
       "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "liquidationBonus": 11000,
       "isFlashloanable": false,
       "stableDebtToken": "0xDC1fad70953Bb3918592b6fCc374fe05F5811B6a",
       "debtCeiling": 0,
       "liquidationProtocolFee": 1000,
       "symbol": "DPI",
       "isActive": true,
       "ltv": 2000,
       "stableBorrowRateEnabled": false,
       "borrowingEnabled": true,
       "decimals": 18,
       "isBorrowableInIsolation": false,
       "aToken": "0x724dc807b04555b71ed48a6896b6F41593b8C637",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
-      "reserveFactor": 2000,
+      "reserveFactor": 3500,
       "supplyCap": 1417,
       "eModeCategory": 0,
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "oracle": {
         "latestAnswer": 8829621299,
         "address": "0x2e48b7924FBe04d575BA229A59b64547d9da16e9"
       },
       "isSiloed": false,
       "usageAsCollateralEnabled": true
     },
     "0x3A58a54C066FdC0f2D55FC9C89F0415C92eBf3C4": {
       "isActive": true,
       "eModeCategory": 2,
       "isFrozen": false,
       "borrowCap": 0,
       "reserveFactor": 2000,
       "liquidationProtocolFee": 2000,
       "isFlashloanable": false,
       "supplyCap": 7500000,
       "aToken": "0xEA1132120ddcDDA2F119e99Fa7A27a0d036F7Ac9",
       "variableDebtToken": "0x6b030Ff3FB9956B1B69f475B77aE0d3Cf2CC5aFa",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "oracle": {
         "latestAnswer": 120239385,
         "address": "0x97371dF4492605486e23Da797fA68e55Fc38a13f"
       },
       "stableBorrowRateEnabled": false,
       "debtCeiling": 0,
       "liquidationThreshold": 6500,
       "symbol": "stMATIC",
       "liquidationBonus": 11000,
       "usageAsCollateralEnabled": true,
       "isBorrowableInIsolation": false,
       "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "decimals": 18,
       "ltv": 5000,
       "underlying": "0x3A58a54C066FdC0f2D55FC9C89F0415C92eBf3C4",
       "stableDebtToken": "0x1fFD28689DA7d0148ff0fCB669e9f9f0Fc13a219",
       "isSiloed": false,
       "borrowingEnabled": false
     },
     "0xfa68FB4628DFF1028CFEc22b4162FCcd0d45efb6": {
       "liquidationThreshold": 6500,
       "isBorrowableInIsolation": false,
       "aToken": "0x80cA0d8C38d2e2BcbaB66aA1648Bd1C7160500FE",
       "oracle": {
         "latestAnswer": 119458629,
         "address": "0x5d37E4b374E6907de8Fc7fb33EE3b0af403C7403"
       },
       "isSiloed": false,
       "isActive": true,
       "reserveFactor": 2000,
       "liquidationBonus": 11000,
       "isFlashloanable": false,
       "underlying": "0xfa68FB4628DFF1028CFEc22b4162FCcd0d45efb6",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "stableDebtToken": "0x62fC96b27a510cF4977B59FF952Dc32378Cc221d",
       "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "variableDebtToken": "0xB5b46F918C2923fC7f26DB76e8a6A6e9C4347Cf9",
       "borrowCap": 0,
       "borrowingEnabled": false,
       "isFrozen": false,
       "decimals": 18,
       "eModeCategory": 2,
       "supplyCap": 6000000,
       "liquidationProtocolFee": 2000,
       "debtCeiling": 0,
       "symbol": "MaticX",
       "ltv": 5000,
       "usageAsCollateralEnabled": true,
       "stableBorrowRateEnabled": false
     },
     "0xE111178A87A3BFf0c8d18DECBa5798827539Ae99": {
       "isFrozen": false,
       "liquidationProtocolFee": 1000,
       "stableDebtToken": "0x8a9FdE6925a839F6B1932d16B36aC026F8d3FbdB",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "ltv": 6500,
       "variableDebtToken": "0x5D557B07776D12967914379C71a1310e917C7555",
       "usageAsCollateralEnabled": true,
       "underlying": "0xE111178A87A3BFf0c8d18DECBa5798827539Ae99",
       "isActive": true,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "supplyCap": 4000000,
       "debtCeiling": 500000000,
       "decimals": 2,
       "liquidationThreshold": 7000,
       "stableBorrowRateEnabled": true,
-      "interestRateStrategy": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
+      "interestRateStrategy": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "aToken": "0x38d693cE1dF5AaDF7bC62595A37D667aD57922e5",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "eModeCategory": 1,
       "oracle": {
         "latestAnswer": 106759000,
         "address": "0x73366Fe0AA0Ded304479862808e02506FE556a98"
       },
       "reserveFactor": 1000,
       "liquidationBonus": 10750,
       "borrowingEnabled": true,
       "symbol": "EURS",
       "borrowCap": 947000,
       "isSiloed": false,
       "isBorrowableInIsolation": false,
       "isFlashloanable": false
     },
     "0xc2132D05D31c914a87C6611C10748AEb04B58e8F": {
       "symbol": "USDT",
       "borrowingEnabled": true,
       "liquidationBonus": 10500,
       "stableBorrowRateEnabled": true,
       "isActive": true,
       "isSiloed": false,
-      "interestRateStrategy": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
+      "interestRateStrategy": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "isFrozen": false,
       "ltv": 7500,
       "isFlashloanable": false,
       "reserveFactor": 1000,
       "usageAsCollateralEnabled": true,
       "liquidationProtocolFee": 1000,
       "decimals": 6,
       "eModeCategory": 1,
       "debtCeiling": 500000000,
       "isBorrowableInIsolation": true,
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "supplyCap": 45000000,
       "oracle": {
         "latestAnswer": 100000000,
         "address": "0x0A6513e40db6EB1b165753AD52E80663aeA50545"
       },
       "borrowCap": 30000000,
       "variableDebtToken": "0xfb00AC187a8Eb5AFAE4eACE434F493Eb62672df7",
       "aToken": "0x6ab707Aca953eDAeFBc4fD23bA73294241490620",
       "stableDebtToken": "0x70eFfc565DB6EEf7B927610155602d31b670e802",
       "underlying": "0xc2132D05D31c914a87C6611C10748AEb04B58e8F",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "liquidationThreshold": 8000
     },
     "0x0b3F868E0BE5597D5DB7fEB59E1CADBb0fdDa50a": {
       "liquidationProtocolFee": 1000,
       "reserveFactor": 2000,
       "borrowCap": 102484,
       "supplyCap": 299320,
       "symbol": "SUSHI",
       "debtCeiling": 0,
       "stableBorrowRateEnabled": false,
       "isSiloed": false,
       "isFrozen": false,
       "isActive": true,
       "liquidationBonus": 11000,
       "borrowingEnabled": true,
       "ltv": 2000,
       "isBorrowableInIsolation": false,
       "aToken": "0xc45A479877e1e9Dfe9FcD4056c699575a1045dAA",
       "aTokenImpl": "0xa5ba6E5EC19a1Bf23C857991c857dB62b2Aa187B",
       "stableDebtTokenImpl": "0x52A1CeB68Ee6b7B5D13E0376A1E0E4423A8cE26e",
       "variableDebtTokenImpl": "0x81387c40EB75acB02757C1Ae55D5936E78c9dEd3",
       "interestRateStrategy": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "oracle": {
         "latestAnswer": 121170720,
         "address": "0x49B0c695039243BBfEb8EcD054EB70061fd54aa0"
       },
       "liquidationThreshold": 4500,
       "eModeCategory": 0,
       "isFlashloanable": false,
       "underlying": "0x0b3F868E0BE5597D5DB7fEB59E1CADBb0fdDa50a",
       "decimals": 18,
       "stableDebtToken": "0x78246294a4c6fBf614Ed73CcC9F8b875ca8eE841",
       "variableDebtToken": "0x34e2eD44EF7466D5f9E0b782B5c08b57475e7907",
       "usageAsCollateralEnabled": true
     }
   },
   "strategies": {
     "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F": {
       "variableRateSlope1": 70000000000000000000000000,
       "variableRateSlope2": 3000000000000000000000000000,
       "stableRateSlope2": 0,
       "baseVariableBorrowRate": 0,
       "maxExcessStableToTotalDebtRatio": 800000000000000000000000000,
       "stableRateSlope1": 0,
       "address": "0x03733F4E008d36f2e37F0080fF1c8DF756622E6F",
       "optimalStableToTotalDebtRatio": 200000000000000000000000000,
       "maxExcessUsageRatio": 550000000000000000000000000,
       "optimalUsageRatio": 450000000000000000000000000,
       "baseStableBorrowRate": 90000000000000000000000000
     },
+    "0x27eFE5db315b71753b2a38ED3d5dd7E9362ba93F": {
+      "baseStableBorrowRate": 68000000000000000000000000,
+      "variableRateSlope2": 800000000000000000000000000,
+      "optimalStableToTotalDebtRatio": 200000000000000000000000000,
+      "maxExcessStableToTotalDebtRatio": 800000000000000000000000000,
+      "optimalUsageRatio": 800000000000000000000000000,
+      "stableRateSlope1": 40000000000000000000000000,
+      "stableRateSlope2": 800000000000000000000000000,
+      "address": "0x27eFE5db315b71753b2a38ED3d5dd7E9362ba93F",
+      "variableRateSlope1": 38000000000000000000000000,
+      "maxExcessUsageRatio": 200000000000000000000000000,
+      "baseVariableBorrowRate": 10000000000000000000000000
+    },
     "0xA9F3C3caE095527061e6d270DBE163693e6fda9D": {
       "maxExcessStableToTotalDebtRatio": 800000000000000000000000000,
       "stableRateSlope1": 5000000000000000000000000,
       "optimalUsageRatio": 800000000000000000000000000,
       "baseStableBorrowRate": 50000000000000000000000000,
       "address": "0xA9F3C3caE095527061e6d270DBE163693e6fda9D",
       "stableRateSlope2": 750000000000000000000000000,
       "optimalStableToTotalDebtRatio": 200000000000000000000000000,
       "variableRateSlope2": 750000000000000000000000000,
       "baseVariableBorrowRate": 0,
       "maxExcessUsageRatio": 200000000000000000000000000,
       "variableRateSlope1": 40000000000000000000000000
     },
     "0xFB0898dCFb69DF9E01DBE625A5988D6542e5BdC5": {
       "address": "0xFB0898dCFb69DF9E01DBE625A5988D6542e5BdC5",
       "optimalUsageRatio": 750000000000000000000000000,
       "baseStableBorrowRate": 81000000000000000000000000,
       "stableRateSlope1": 0,
       "baseVariableBorrowRate": 0,
       "stableRateSlope2": 0,
       "maxExcessUsageRatio": 250000000000000000000000000,
       "variableRateSlope2": 1000000000000000000000000000,
       "maxExcessStableToTotalDebtRatio": 800000000000000000000000000,
       "variableRateSlope1": 61000000000000000000000000,
       "optimalStableToTotalDebtRatio": 200000000000000000000000000
     },
     "0x4b8D3277d49E114C8F2D6E0B2eD310e29226fe16": {
       "baseStableBorrowRate": 160000000000000000000000000,
       "variableRateSlope1": 140000000000000000000000000,
       "maxExcessUsageRatio": 200000000000000000000000000,
       "maxExcessStableToTotalDebtRatio": 800000000000000000000000000,
       "optimalStableToTotalDebtRatio": 200000000000000000000000000,
       "variableRateSlope2": 1500000000000000000000000000,
       "address": "0x4b8D3277d49E114C8F2D6E0B2eD310e29226fe16",
       "stableRateSlope1": 0,
       "baseVariableBorrowRate": 30000000000000000000000000,
       "stableRateSlope2": 0,
       "optimalUsageRatio": 800000000000000000000000000
     },
     "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4": {
       "baseVariableBorrowRate": 0,
       "variableRateSlope2": 600000000000000000000000000,
       "baseStableBorrowRate": 50000000000000000000000000,
       "optimalStableToTotalDebtRatio": 200000000000000000000000000,
       "maxExcessUsageRatio": 100000000000000000000000000,
       "optimalUsageRatio": 900000000000000000000000000,
       "address": "0x41B66b4b6b4c9dab039d96528D1b88f7BAF8C5A4",
       "stableRateSlope1": 5000000000000000000000000,
       "variableRateSlope1": 40000000000000000000000000,
       "stableRateSlope2": 600000000000000000000000000,
       "maxExcessStableToTotalDebtRatio": 800000000000000000000000000
     }
   },
   "eModes": {
     "1": {
       "priceSource": "0x0000000000000000000000000000000000000000",
       "liquidationBonus": 10100,
       "label": "Stablecoins",
       "ltv": 9700,
       "eModeCategory": 1,
       "liquidationThreshold": 9750
     },
     "2": {
       "liquidationThreshold": 9500,
       "liquidationBonus": 10100,
       "priceSource": "0x0000000000000000000000000000000000000000",
       "label": "MATIC correlated",
       "eModeCategory": 2,
       "ltv": 9250
     }
   }
 }
\ No newline at end of file```