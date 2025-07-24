# pasco-results

This repository contains the generated abstractions produced by the tool PASCo. The folders are structured based on the parameters used during the generation process.

## Folder Structure

- **k_n**: Indicates the `k_bound` parameter used to set up PASCo.
- **t_600**: Indicates the timeout used in seconds.

## File Types

Each generated abstraction contains the following files:

- `.epa` or `.states`: The abstraction in EPA mode or states (for enum).
- `.csv`: The query times for that abstraction.
- `.txt`: Extra information.

## Summary of Results

Final abstraction build times were measured on a system equipped with an Intel Core i7-4790 processor (4 cores), 16GB of RAM, running Windows 10.

| Config                                      | k_bound | Mode    | Time     |
|----------------------------------------------|---------|---------|----------|
| AssetTransferConfig                          | 8       | states  | 0:08:44  |
| BasicProvenanceConfig                        | 8       | states  | 0:00:13  |
| DefectiveComponentCounterConfig              | 8       | states  | 0:00:05  |
| DigitalLockerConfig                          | 8       | states  | 0:03:09  |
| FrequentFlyerRewardsCalculatorConfig         | 8       | states  | 0:00:05  |
| HelloBlockchainConfig                        | 8       | states  | 0:00:07  |
| RefrigeratedTransportationConfig             | 8       | states  | 0:00:28  |
| RoomThermostatConfig                         | 8       | states  | 0:00:09  |
| SimpleMarketplaceConfig                      | 8       | states  | 0:00:16  |
| AssetTransferFixedConfig                     | 8       | states  | 0:08:47  |
| BasicProvenanceFixedConfig                   | 8       | states  | 0:00:13  |
| DefectiveComponentCounterFixedConfig         | 8       | states  | 0:00:06  |
| DigitalLockerFixedConfig                     | 8       | states  | 0:03:03  |
| HelloBlockchainFixedConfig                   | 8       | states  | 0:00:07  |
| RefrigeratedTransportationFixedConfig        | 8       | states  | 0:00:27  |
| SimpleMarketplaceFixedConfig                 | 8       | states  | 0:00:16  |
| RefundEscrowConfig                          | 8       | states  | 0:00:31  |
| RefundEscrowConfig                          | 8       | epa     | 0:00:30  |
| RefundEscrowWithdrawConfig                   | 8       | epa     | 0:01:04  |
| EscrowVaultConfig                            | 8       | states  | 0:01:09  |
| EscrowVaultConfig                            | 8       | epa     | 0:00:40  |
| EPXCrowdsaleConfig                           | 8       | states  | 0:07:22  |
| EPXCrowdsaleConfig                           | 8       | epa     | 0:01:49  |
| EPXCrowdsaleIsCrowdsaleClosedConfig          | 8       | epa     | 0:02:54  |
| ValidatorAuctionConfig                       | 8       | states  | 0:01:45  |
| ValidatorAuctionConfig                       | 8       | epa     | 0:01:37  |
| ValidatorAuction_withdrawConfig              | 8       | epa     | 0:03:18  |
| SimpleAuctionConfig                          | 8       | epa     | 0:01:02  |
| SimpleAuctionTimeConfig                      | 8       | epa     | 0:01:32  |
| SimpleAuctionEndedConfig                     | 8       | epa     | 0:01:06  |
| SimpleAuctionHBConfig                        | 8       | states  | 0:01:22  |
| AuctionConfig                                | 8       | epa     | 0:00:18  |
| AuctionEndedConfig                           | 8       | epa     | 0:00:23  |
| AuctionWithdrawConfig                        | 8       | epa     | 0:00:41  |
| RockPaperScissorsConfig                      | 8       | states  | 0:00:56  |
| RockPaperScissorsConfig                      | 8       | epa     | 0:00:19  |
| CrowdfundingTime_BaseConfig                  | 8       | epa     | 0:00:24  |
| CrowdfundingTime_BaseBalanceConfig           | 8       | epa     | 0:01:14  |
| CrowdfundingTime_BaseBalanceFixConfig        | 8       | epa     | 0:00:59  |
| EtherstoreOriginalReentrancyConfig           | 8       | epa     | 0:05:07  |
| ReentranceOriginalReentrancyConfig           | 8       | epa     | 0:10:11  |
| Reentrancy_daoOriginalReentrancyConfig       | 8       | epa     | 0:03:13  |
| Reentrancy_simpleOriginalReentrancyConfig    | 8       | epa     | 0:08:08  |
| Simple_daoOriginalReentrancyConfig           | 8       | epa     | 0:10:11  |
| EtherstoreReentrancyConfig                   | 16      | epa     | 0:12:16  |
| ReentranceReentrancyConfig                   | 16      | epa     | 0:22:00  |
| Reentrancy_daoReentrancyConfig               | 16      | epa     | 0:20:48  |
| Reentrancy_simpleReentrancyConfig            | 16      | epa     | 0:20:52  |
| Simple_daoReentrancyConfig                   | 16      | epa     | 0:22:01  |
| EtherstoreReentrancyFixedConfig              | 16      | epa     | 0:20:55  |
| ReentranceReentrancyFixedConfig              | 16      | epa     | 0:20:43  |
| Reentrancy_daoReentrancyFixedConfig          | 16      | epa     | 0:20:43  |
| Reentrancy_simpleReentrancyFixedConfig       | 16      | epa     | 0:20:42  |
| Simple_daoReentrancyFixedConfig              | 16      | epa     | 0:20:43  |
| EtherstoreReentrancyFixed_lockConfig         | 16      | epa     | 0:40:50  |
| ReentranceReentrancyFixed_lockConfig         | 16      | epa     | 0:40:48  |
| Reentrancy_daoReentrancyFixed_lockConfig     | 16      | epa     | 0:20:10  |
| Reentrancy_simpleReentrancyFixed_lockConfig  | 16      | epa     | 0:31:25  |
| Simple_daoReentrancyFixed_lockConfig         | 16      | epa     | 0:40:48  |
